<template>
  <v-app>
    <v-app-bar
      flat
      class="animate__animated animate__fadeIn animate__slower"
      color="#1A1E27"
      dark
      
    >
      <div class="d-flex align-center">
        
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="https://github.com/backendpapa"
        target="_blank"
        text
        plain
        icon
      >
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
<style>
::-webkit-scrollbar {
  display: none;
}
.nana{
  /* background-color: ; */
}
</style>
