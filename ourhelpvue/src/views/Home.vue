<template>
  <v-container class="grey lighten-5">
    <v-row no-gutters>
      <v-col cols="12" sm="6" md="8" lg="4">
        <v-card class="pa-2 mx-2" style="height: 100%;">
          <h2>Our Help: Lorem Ipsum</h2>
          <br/>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem ea doloremque nobis nemo culpa perferendis voluptas! Ut nesciunt rerum tempore quod voluptate? Voluptatum omnis consectetur nulla deserunt aspernatur reprehenderit nemo.</p>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor, praesentium accusamus ab deleniti obcaecati perferendis id ipsum corporis nulla exercitationem minima sit! Quo laborum perspiciatis similique quibusdam, possimus illo alias.</p>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Exercitationem tenetur, id mollitia labore sed quaerat nihil impedit magni. Dignissimos earum temporibus, sed aliquam neque ut porro perferendis obcaecati repudiandae necessitatibus?</p>
        </v-card>
      </v-col>
      <v-col cols="12" sm="6" md="4" lg="8">
        <v-card class="pa-2  mx-2" style="height: 100%;" ><Carrousel/></v-card>
      </v-col>
    </v-row>
  
  </v-container>
</template>

<script>
// @ is an alias to /src

import Carrousel from "../components/carrousel";

export default {
  name: "Home",
  components: {
    Carrousel,
  },
};
</script>