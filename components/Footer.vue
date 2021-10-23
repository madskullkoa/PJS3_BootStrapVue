<template>
  <v-footer
    dark
    padless
  >
    <v-card
    
      flat
      tile
      class="white--text text-center dims"
    >
      <v-card-text>
        <v-btn
          v-for="icon in icons"
          :key="icon"
          class="mx-4 white--text"
          icon
        >
          <v-icon size="24px">
            {{ icon }}
          </v-icon>
        </v-btn>
      </v-card-text>

      <v-card-text class="white--text pt-0">
      Site officiel de la commune d’ïle-de-Bréhat : <br>
      Toute l’information pratique sur l’administration de la commune, les démarches administratives, les services, la vie quotidienne insulaire, les loisirs et le tourisme.
      </v-card-text>

      <v-divider></v-divider>

      <v-card-text class="white--text">
        {{ new Date().getFullYear() }} — <strong>4Zem</strong>
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<script>
  export default {
    data: () => ({
      icons: [
        'mdi-facebook',
        'mdi-youtube',
      ],
    }),
  }
</script>

<style>
.dims{
  width:100%;
  height:100%;
}
</style>