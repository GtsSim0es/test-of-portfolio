<template>
  <div>
    <Menu />
    <p>oiasdasdas</p> 
  </div>
</template>

<script>
import Menu from './components/menu.vue'

export default {
  name: 'App',
  components: {
    Menu,
  }
}
</script>

<style>
  *{
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    font: inherit;
    vertical-align: baseline;
  }

  body {
    background-color: #333;
    color: #FFF;
  }
</style>