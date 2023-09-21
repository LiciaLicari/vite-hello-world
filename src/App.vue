<script>
import AppHero from './components/AppHero.vue'
import AppTitle from './components/AppTitle.vue'


export default {
  data() {
    return {
      message: "Hello Vite"
    }

  },
  components: {
    AppTitle,
    AppHero,
  },
}
</script>

<template>
  <h1>{{ message }}</h1>
  <AppTitle />
  <AppHero />
</template>

<style></style>
