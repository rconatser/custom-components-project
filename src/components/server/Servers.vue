<template>
  <v-container class="grey lighten-5 card-container">
      <h2 class="pb-4">Our Servers' Status</h2>

    <!-- Stack the columns on mobile by making one full-width and the other half-width -->
    <v-row>
      <v-col
        cols="12"
        md="4"
      >
        <v-card
          class="pa-8"
          :elevation="hover ? 12 : 6"
        >
          <!-- .col-12 .col-md-8 -->
          <h3 class="font-weight-light text-uppercase">Server One</h3>
          <h4 class="font-weight-normal">Status: </h4>
        </v-card>
      </v-col>
      <v-col
        cols="12"
        md="4"
        
      >
        <v-card
          class="pa-8"
          :elevation="hover ? 12 : 6"
        >
          <!-- .col-12 .col-md-8 -->
          <h3 class="font-weight-light text-uppercase">Server Two</h3>
          <h4 class="font-weight-normal">Status: </h4>
        </v-card>
      </v-col>
      <v-col
        cols="12"
        md="4"
      >
        <v-card
          class="pa-8"
          :elevation="hover ? 12 : 6"
        >
          <!-- .col-6 .col-md-4 -->
          <h3 class="font-weight-light text-uppercase">Server Three</h3>
          <h4 class="font-weight-normal">Status: </h4>
        </v-card>
      </v-col>
    </v-row>

    <!-- Columns are always 50% wide, on mobile and desktop -->
    <v-row>
      <v-col
        cols="12"
        md="6"
      >
        <v-card
          class="pa-8"
          :elevation="hover ? 12 : 6"
        >
          <h3 class="font-weight-light text-uppercase">Server Four</h3>
          <h4 class="font-weight-normal">Status: </h4>
        </v-card>
      </v-col>
      <v-col
        cols="12"
        md="6"
      >
        <v-card
          class="pa-8"
          :elevation="hover ? 12 : 6"
        >
          <!-- .col-6 -->
          <h3 class="font-weight-light text-uppercase">Server Five</h3>
          <h4 class="font-weight-normal">Status: </h4>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    .card-container {
        min-width: 360px;
        max-width: 1200px;
    }

    v-card {

    }
</style>