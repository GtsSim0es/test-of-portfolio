
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
    line-height: 6vh;
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
    font-weight: 800;
    color: rgba(0,0,0,0.7);
    text-shadow: 2px 2px 3px rgba(255,255,255,0.1);
    text-decoration: none;
  }

  a:hover 
  {
    color: white;
  }

@media (max-width: 999px){


}


</style>
