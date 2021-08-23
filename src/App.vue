<template>
  <Navbar/>
</template>

<script>
import Navbar from './components/common/Navbar/Navbar.vue';

export default {
  name: 'App',
  components: {
    Navbar
  }
}
</script>

<style lang="scss" scoped>
@import './styles/app.scss';

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-family: sans-serif;
  text-align: center;
  color: #2c3e50;

}

</style>
