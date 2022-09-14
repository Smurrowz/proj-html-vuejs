<template>
  <div id="app">
    <HeaderComponent/>
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';


export default {
  name: 'App',
  components: {
    HeaderComponent
}
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=DM+Sans:ital,wght@0,400;0,500;0,700;1,400;1,500;1,700&display=swap');
*{
  font-family: 'DM Sans', sans-serif;
  }
</style>
