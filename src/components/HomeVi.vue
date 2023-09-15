<template>
  <v-window
    v-model="onboarding"
    show-arrows="hover"
    height="100%"
    width="100%"
  >
    <v-window-item
      v-for="n in length"
      :key="`card-${n}`"
      height="100%"
      width="100%"
    >
      <v-card
        elevation="2"
        height="100%"
        class="d-flex align-center justify-center ma-2"
        width="100%"
        
      >
      <img
        src="@/assets/devfest.jpg"
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

