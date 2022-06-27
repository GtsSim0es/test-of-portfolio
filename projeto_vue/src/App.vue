<template>
  <div>
    <div class="bar"></div>
    <div class="menu">
      <profileVue/>
      <menuVue/>
    </div>
    <HomeVue/>
  </div>
</template>

<script>
import menuVue from './components/menu.vue'
import profileVue from './components/profile.vue'
import HomeVue from './components/home.vue'

export default {
  name: 'App',
  components: {
    menuVue,
    profileVue,
    HomeVue
}
}
</script>

<style>
  *{
    font-family: 'Source Sans Pro', sans-serif;
    margin: 0;
    padding: 0;
    border: 0;
    list-style: none;
  }

  body {
    
  }

  .menu{
    margin-left: 3vh;
    width: 20%;
    height: 100vh;
    background-color: rgb(59, 59, 59);
    box-shadow: 5px -3px 10px rgb(92, 92, 92);
    position: fixed;
  }

  div:empty {
    background: rgb(31, 31, 31);
    height: 100vh;
    width: 3vh;
    float: left;
    position: fixed;
  }
</style>