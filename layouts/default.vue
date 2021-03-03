<template>
  <v-app>
    <div class="container">
      <v-toolbar flat class="align-center">
        <h3 style="font-family: 'Dancing Script'; color: #9895B6; font-size: xx-large">Diary of Sam</h3>
        <v-spacer></v-spacer>

        <v-btn to="/" plain class="mx-2" color="primary">
          Home
        </v-btn>

        <v-btn to="/projects" plain class="mx-2" color="primary">
          Blog
        </v-btn>

        <v-btn to="/about" plain class="mx-2" color="primary">
          About
        </v-btn>
      </v-toolbar>
    </div>
    <v-main>
<!--      <v-container>-->
        <nuxt />
<!--      </v-container>-->
    </v-main>
  </v-app>
</template>

<script>
export default {
  data () {
    return {

    }
  }
}
</script>

<style>
</style>
