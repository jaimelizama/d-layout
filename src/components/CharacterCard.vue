<template>
  <v-container>
    <v-row>
      <v-col
        cols="12"
        sm="6"
        md="4"
        v-for="(character, id) in $store.state.characters"
        :key="id"
      >
        <v-card class="mx-auto" max-width="auto">
          <v-img class="align-end" :src="character.imagen"> </v-img>
          <v-card-title>{{ character.nombre }}</v-card-title>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'CharacterCard'
}
</script>

<style></style>
