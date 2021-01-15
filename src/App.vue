<template>
  <div id="app">
    {{msg}}
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {

  },
  data() {
    return {
      toplay: [
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
