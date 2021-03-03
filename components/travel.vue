<template>
  <v-container >
    <h2 style="font-family: Dancing Script; color: #9895B6">Travel Diaries</h2>
    <v-row no-gutters>
      <v-col
        v-for="n in 3"
        :key="n"
        cols="12"
        sm="4"
      >
        <blogCard/>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import blogCard from "~/components/blogCard";

export default {
name: "travel",
  components:{
    blogCard
  }
}
</script>

<style scoped>

</style>
