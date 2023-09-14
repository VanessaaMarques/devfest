<template>
    <v-footer
      class="bg-indigo-lighten-1 text-center d-flex flex-column"
      color="grey"
    >
      <div>
        <a href="https://www.instagram.com/gdgrioverde/ " target="_blank"><v-btn
            icon="mdi-instagram"
            color="white"
            class="mx-4"
            variant="text"
            
        ></v-btn></a>
        <a href="https://www.google.com.br/maps/" target="_blank"><v-btn
            label = "Localização"
            color="white"
            class="mx-4"
            variant="text"
            
        ></v-btn></a>
      </div>
  
      <div class="pt-2">
       Realização: <strong>GDG Rio Verde</strong> - {{ new Date().getFullYear() }}
      </div>
  
      <v-divider></v-divider>
  

    </v-footer>
  </template>

<script lang="ts">

</script>