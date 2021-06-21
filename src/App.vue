<template>
    <div id="app">
      <Header />
      <Main />
    </div>
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue'

export default {
  name: 'App',
  components: {
   Header,
   Main
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;700&family=Poppins:wght@300;400;700&family=Roboto:wght@300;400;700&display=swap');

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
</style>
