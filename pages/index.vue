<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="10">
      <div class="text-center">
        <vuetify-logo />
      </div>
      <v-card>
        <v-card-title class="headline">
          Welcome to my music room by Itunes .If you ready you can push botton
          continue.
        </v-card-title>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" nuxt to="/inspire"> Continue </v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>
<script>
import VuetifyLogo from '~/components/VuetifyLogo.vue'
export default {
  components: {
    VuetifyLogo,
  },
}
</script>
