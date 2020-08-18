<template>
  <v-app>
    <v-card color="grey lighten-4" flat height="200px" tile>
      <v-toolbar dense>
        <v-toolbar-title>First Nuxt App</v-toolbar-title>

        <v-spacer></v-spacer>

        <v-btn>
          <nuxt-link to="/"> Home</nuxt-link>
        </v-btn>

        <v-btn>
          <nuxt-link to="/about"> About</nuxt-link>
        </v-btn>

        <v-btn>
          <nuxt-link to="/inspire"> Inspire</nuxt-link>
        </v-btn>
      </v-toolbar>
    </v-card>
    <nuxt />
  </v-app>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped></style>
