<script>
import appTitle from './components/AppTitle.vue'

 export default{
    data() {
      return {
        message: "Hello Vite"
      }
      
    },
    components: {
        appTitle
    },
  }
</script>

<template>
  <h1>{{message}}</h1>
  <appTitle />
  
</template>

<style>
</style>
