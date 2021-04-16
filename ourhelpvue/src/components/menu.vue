<template>
  <v-card class="overflow-hidden">
      <v-container style="height: 100vh">
        <v-app-bar
          absolute
          color="#6A76AB"
          dark
          src="https://picsum.photos/1920/1080?random"
        >
          <template v-slot:img="{ props }">
            <v-img
              v-bind="props"
              gradient="to top right, rgba(100,115,201,.7), rgba(25,32,72,.7)"
            ></v-img>
          </template>

          <v-app-bar-nav-icon></v-app-bar-nav-icon>

          <v-app-bar-title>Title</v-app-bar-title>

          <v-spacer></v-spacer>

          <v-btn icon>
            <v-icon>mdi-magnify</v-icon>
          </v-btn>

          <v-btn icon>
            <v-icon>mdi-heart</v-icon>
          </v-btn>

          <v-btn icon>
            <v-icon>mdi-dots-vertical</v-icon>
          </v-btn>

          <template v-slot:extension>
            <v-tabs align-with-title>
              <v-tab>Home</v-tab>
              <v-tab>About</v-tab>
              <v-tab>Tab 3</v-tab>
              <v-tab-item><router-view to="/" /></v-tab-item>
              <v-tab-item><router-link to="/about" /></v-tab-item>
              <v-tab-item><About /></v-tab-item>
            </v-tabs>
          </template>
        </v-app-bar>
      </v-container>
      <Footer />
  </v-card>
</template>


<script>
import About from "../views/About.vue";
import Footer from "../components/footer.vue";

export default {
  components: { About, Footer },
};
</script>
