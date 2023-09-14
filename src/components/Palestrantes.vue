<template>
    <div>
        <h1 position="center">Palestrantes</h1>
        <v-timeline>
        <v-timeline-item
            dot-color="purple-lighten-2"
            width="80vh"
            position="center"
        >
            <v-card>
            <v-card-title class="bg-purple-lighten-2">
                <v-icon
                size="large"
                class="me-4"
                icon="mdi-magnify"
                >
                </v-icon>
               <label>Title 1</label> 
            </v-card-title>
            <v-card-text>
                Lorem ipsum dolor sit amet, no nam oblique veritus. Commune scaevola imperdiet nec ut, sed euismod convenire principes at. Est et nobis iisque percipit.
            </v-card-text>
            </v-card>
        </v-timeline-item>
    
        <v-timeline-item
            dot-color="amber-lighten-1"
            fill-dot
            width="80vh"
        >
            <v-card>
            <v-card-title class="bg-amber-lighten-1 justify-end">
                <v-icon
                size="large"
                class ="me-4"
                icon="mdi-home-outline"
                ></v-icon>
                <label>Title 2</label> 
            </v-card-title>
            <v-card-text>
                Lorem ipsum dolor sit amet, no nam oblique veritus. Commune scaevola imperdiet nec ut, sed euismod convenire principes at. Est et nobis iisque percipit.
            </v-card-text>
            </v-card>
        </v-timeline-item>
    
        <v-timeline-item
            dot-color="cyan-lighten-1"
            fill-dot
            width="80vh"
        >
            <v-card>
            <v-card-title class="bg-cyan-lighten-1">
                <v-icon
                class="me-4"
                size="large"
                icon="mdi-email-outline"
                ></v-icon>
                <label>Title 3</label>
            </v-card-title>
            <v-card-text>
                Lorem ipsum dolor sit amet, no nam oblique veritus. Commune scaevola imperdiet nec ut, sed euismod convenire principes at. Est et nobis iisque percipit.
            </v-card-text>
            </v-card>
        </v-timeline-item>
    
        <v-timeline-item
            dot-color="red-lighten-1"
            fill-dot
            width="80vh"
        >
            <v-card>
            <v-card-title class="bg-red-lighten-1 justify-end">
                <v-icon
                size="large"
                icon="mdi-account-multiple-outline"
                class="me-4"
                ></v-icon>
                <label>Title 4</label>
            </v-card-title>
            <v-card-text>
                Lorem ipsum dolor sit amet, no nam oblique veritus. Commune scaevola imperdiet nec ut, sed euismod convenire principes at. Est et nobis iisque percipit.
            </v-card-text>
            </v-card>
        </v-timeline-item>
    
        <v-timeline-item
            dot-color="green-lighten-1"
            fill-dot
            width="80vh"
        >
            <v-card>
            <v-card-title class="bg-green-lighten-1">
                <v-icon
                class="me-4"
                size="large"
                icon="mdi-phone-in-talk"
                ></v-icon>
                <label>Title 5</label>
            </v-card-title>
            <v-card-text>
                Lorem ipsum dolor sit amet, no nam oblique veritus. Commune scaevola imperdiet nec ut, sed euismod convenire principes at. Est et nobis iisque percipit.
            </v-card-text>
            </v-card>
        </v-timeline-item>
        </v-timeline>
    </div>
  </template>