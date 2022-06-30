<template>
  <div>
    <menuside/>
    <HomeVue/>
    
  </div>
</template>

<script>
import HomeVue from './components/home.vue'
import menuside from './components/Sidebar/menuside.vue'

export default {
  name: 'App',
  components: {
    HomeVue,
    menuside
  }
}
</script>


<style>
  *{
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
    list-style: none;
  }

  body{
    overflow-x: hidden;
  }

</style>