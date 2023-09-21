<script>

// import HelloWorld from './components/HelloWorld.vue'
import AppTitle from './components/AppTitle.vue'

export default {
  data() {
    return {
      text: "Hello Vite",
      count: 0
    }
  },
  components: {
    AppTitle
  },

}

</script>

<template>
  <h1>{{ text }}</h1>
  <!--   <HelloWorld msg="MessaggioTest" /> -->
  <AppTitle title="La mia prima app con Vite!" />
</template>

<style></style>
