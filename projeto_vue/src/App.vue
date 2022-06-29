<template>
  <div>
    <menuside/>
    <div class="menu">
      <profileVue/>
      <menuVue/>
    </div>

    <HomeVue/>
    
  </div>
</template>

<script>
import menuVue from './components/Sidebar/menu.vue'
import profileVue from './components/Sidebar/profile.vue'
import HomeVue from './components/home.vue'
import menuside from './components/Sidebar/menuside.vue'



export default {
  name: 'App',
  components: {
    menuVue,
    profileVue,
    HomeVue,
    menuside,

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
  .menu{
    margin-left: 5vh;
    width: 20%;
    height: 100vh;
    background-color: #222;
    box-shadow: 5px -3px 10px rgb(92, 92, 92);
    position: fixed;
  }
@media (max-width: 999px){
  .menu{
        display: none;
    }
}

</style>