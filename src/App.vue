<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'
import '..node_modules/bootstrap/dist/css/bootstrap.min.css'

 export default{
    data() {
      return {
        message: "Hello Vite"
      }
      
    },
    components: {
        AppTitle,
        AppHero,
        jumbotron
    },
  }
</script>

<template>
  <h1>{{message}}</h1>
  <AppTitle />
  <jumbotron />
  
  
</template>

<style>
</style>
