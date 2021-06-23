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
section {
  position: relative;
}
button {
        padding: 1rem;
        color: white;
        background-color: #1fad96;
        border-radius: 5px;
        border: none;
    }
h2 {
        text-transform: capitalize;
        font-size: 30px;
        letter-spacing: 1.1;
        text-align: center;
        span {
            font-weight: 300;
            color: #27ab94;
        }
}
.circle {
  border-radius: 100%;
  position: absolute;
}

// .ronchi {
//   background-color: #efb056;
// }

// .royal {
//   background-color: royalblue;
// }
// .coral {
//   background-color: #a65e6d;
// }
// .green {
//   background-color: #27ab64;
// }
// .orange {
//   background-color: #febc4d;
// }
</style>
