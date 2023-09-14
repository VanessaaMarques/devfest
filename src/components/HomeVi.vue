<template>
  <v-window
    v-model="onboarding"
    show-arrows="hover"
  >
    <v-window-item
      v-for="n in length"
      :key="`card-${n}`"
    >
      <v-card
        elevation="2"
        height="900"
        class="d-flex align-center justify-center ma-2"
        
      >
      <img
        src="@/assets/devfest.jpg"
        height="600"
        width="800"
        alt="DevFest Rio Verde 2023"

      />
      </v-card>
    </v-window-item>
  </v-window>
</template>

<script lang="ts">
  export default {
    data: () => ({
      length: 1,
      onboarding: 0,
    }),
  }
</script>

