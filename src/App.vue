<template>
  <div id="app">    
    <HomePage/>
    
  </div>
</template>

<script>
import HomePage from './components/HomePage.vue';


export default {
  name: 'app',
  components: {
    HomePage
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Jost&display=swap');

:root{
  --font-main: 'Jost', sans-serif;
}

.font-jost{
  font-family: var(--font-main);
}

#app {
 
}
</style>
