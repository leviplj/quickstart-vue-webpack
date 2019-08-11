<template>
  <div id="app">
    {{message}}
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {
  },
  data() {
    return {
      message: 'Not a Hello World!'
    };
  },
};
</script>

<style>
  #app {
    font-size: 2rem;
    font-family: 'Roboto', sans-serif;
    color: blue;
  }
</style>