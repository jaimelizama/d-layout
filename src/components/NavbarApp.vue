<template>
  <v-app-bar dense>
    <v-app-bar-nav-icon></v-app-bar-nav-icon>
    <v-toolbar-title>Mi App</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-toolbar-items>
      <v-btn flat elevation="0">INICIO</v-btn>
      <v-btn flat elevation="0">BUSCAR</v-btn>
      <v-btn flat elevation="0">ACERCA DE</v-btn>
    </v-toolbar-items>
  </v-app-bar>
</template>

<script>
export default {
  name: 'NavbarApp'
}
</script>

<style></style>
