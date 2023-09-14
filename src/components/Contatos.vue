<template>
    <v-footer
      class="bg-indigo-lighten-1 text-center d-flex flex-column"
      color="grey"
    >
      <div>
        <a href="https://www.instagram.com/gdgrioverde/ " target="_blank"><v-btn
          v-for="icon in icons"
          :key="icon"
          class="mx-4"
          :icon="icon"
          variant="text"
          color="white"
        ></v-btn></a>
      </div>
  
      <div class="pt-2">
       Realização: <strong>GDG Rio Verde</strong> - {{ new Date().getFullYear() }}
      </div>
  
      <v-divider></v-divider>
  

    </v-footer>
  </template>

<script lang="ts">
  export default {
    data: () => ({
      icons: [

        'mdi-instagram',
      ],
    }),
  }
</script>