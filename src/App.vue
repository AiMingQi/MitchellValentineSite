<template>
  <v-app>
    <v-app-bar
      app
      color="#c00000"
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="./assets/logo.png"
          transition="scale-transition"
          width="40"
        />
        <h2 class="ml-2"> Mitchell Valentine</h2>
        
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="https://github.com/aimingqi"
        target="_blank"
        text
      >
        <span class="mr-2">My Github</span>
        <v-icon>mdi-github</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
