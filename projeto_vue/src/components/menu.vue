
<template>
  <ul>
    <a href="#"><li>Home</li></a>
    <a href="#"><li>Projetos</li></a>
    <a href="#"><li>Contato</li></a>
    <a href="#"><li>Contato</li></a>
    <a href="#"><li>Contato</li></a>
  </ul>
</template>

<script>
  export default {
    name: 'menu-vue'
  }
</script>

<style scoped>
  ul 
  {

    background-color: rgb(26, 26, 26);
   
    margin-left: auto;
    margin-right: auto;
  }

  li 
  {
    margin-top: 3px;
    width: 100%;
    background-color: rgb(43, 43, 43);
    line-height: 8vh;
    font-size: 18px;
    float: left;
    text-align: center;
    transition: .2s;
  }

  li:hover
    {   
        background-color: rgb(37, 37, 37);
        transform: scale(1.05);
    }

  a 
  {
    color: #DDD;
    text-decoration: none;

  }

  a:hover 
  {
    color: rgb(38, 0, 255);
  }

</style>
