<template>
  <v-app-bar color="grey">
    <v-app-bar-title>
      <v-icon />
      DevFest Rio Verde 2023
    </v-app-bar-title>
    <v-row  no-gutters>
      <v-btn
        v-for="link in links"
        :key="link"
        color="white"
        variant="text"
        class="mx-2"
        rounded="xl"
      >
        {{ link }}
      </v-btn>
    </v-row>
    <v-btn value="favorites">
    <v-icon>mdi-account-edit</v-icon>

    <span>Inscrições</span>
  </v-btn>
  </v-app-bar>
</template>

<script lang="ts">
  export default {
    data: () => ({
      links: [
        'Home',
        'Sobre',
        'Patrocinadores',
        'Palestrantes',
        'Contatos',
      ],
    }),
  }
</script>