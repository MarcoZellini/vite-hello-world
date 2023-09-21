<script>
import AppHero from './components/AppHero.vue'
import AppTitle from './components/AppTitle.vue'

export default {
  data() {
    return {
      text: "Hello Vite",
      title: 'My First Hero Section',
      count: 0
    }
  },
  components: {
    AppHero,
    AppTitle
  },

}

</script>

<template>
  <h1 class="text-center">{{ text }}</h1>
  <AppTitle title="La mia prima app con Vite!" />
  <AppHero title="Ho creato una Hero annidando due Vue Components" />
</template>

<style></style>
