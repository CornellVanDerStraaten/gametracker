<template>
  <div id="app">
    <Toplays v-bind:toplays="toplays"/>
  </div>
</template>

<script>
import Toplays from "./components/Toplays";

export default {
  name: 'App',
  components: {
    Toplays
  },
  data() {
    return {
      toplays: [
        {
          id: 1,
          title: "Super Mario Odyssey",
          completed: true
        },
        {
          id: 2,
          title: "Cyberpunk 2077",
          completed: false
        },
        {
          id: 2,
          title: "Borderlands 2",
          completed: false
        }
      ]
    }
  }
}
</script>

<style>
  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

  body {
    font-family: Arial, Helvetica, sans-serif;
    line-height: 1.4;
  }
</style>
