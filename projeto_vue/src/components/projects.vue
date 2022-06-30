<template>
<div class="all">
    <h1>Projects</h1>
    <ul>
      <li>
        <h2>Jewellery Inventory</h2> 
        <a href=""><img src="img/inventory.png" id="imgje"></a>
        <p>This is a site made in Nodejs and MySQL for a Jewellery to organize your inventory</p>
      </li>
    <li>
      <h3>Digital Menu</h3> 
      <a href=""><img src="img/tecnoburgerw.png" alt="" id="imgtec"></a>
      <p>This is a site made in Nodejs and MySQL for a restaurant to show your clientes the menu </p>
    </li>
    </ul>
</div>
</template>

<script>
  export default {
    name: 'projects-vue'
  }
</script>

<style scoped>

li{
  display: inline-block;
  width: 30vw;
  margin: 6vh;
}

#imgtec{
  width: 53vh;
  margin-bottom: 2vh;
}

img{
   width: 60vh;
}

img:hover{
   transform: scale(1.1);
}
 .all{
    background-color: #495057 ;
    text-align: center;
    float: right;
    margin-top:27vh ;
    width: 78vw;
    color: white;
    text-shadow: 2px 2px 3px rgb(0, 0, 0);
 }

 @media (max-width: 999px){
  .all{
    width: 97vw;
    margin-top:85vh ;
  }
  li{
    width: 40vh;
    margin: 10vh;
  }
  #imgtec{
  width: 30vh;
}

#imgje{


}

img{
  width: 40vh;

}

 }

 h1{
  margin-top: 4vh;
    margin-bottom: 10vh;
    font-size: 60px;
    
}

h2{
  font-size: 50px;
}

h3{
  font-size: 50px;
  margin-bottom: 4.5vh;
}

p{
font-size: 28px;
}
</style>


