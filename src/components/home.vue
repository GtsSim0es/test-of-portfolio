<template>
<div>
<h1>I'm Gabriel and Welcome to my Website, a place where I can show the things that I'm capable of.</h1>
<p>I was born in Brazil, 2003, in a city called Ribeirão Preto. In 2021 I started studying by myself web development, HTML, CSS and JAVASCRIPT so I created a lot of projects to learn it. Today I’m a student of computer engineering at UNAERP (2022 - 2027) and very interested in programming languages like C++ or NODEJS.</p>
<span><img src="img/homeimage.png" alt=""></span>

</div>
</template>

<script>
  export default {
    name: 'home-vue'
  }
</script>

<style scoped>
 *{
    color: grey;
    text-align: center;

 }

html{
white-space:nowrap;
}
body {
display:inline-block;
overflow-x: hidden
}

img{
  margin-top: -8vh;
}
 
div{
    float: right;
    width: 79vw;
    height: 100vh;
}

h1{
    margin: 10vh;
    font-size: 40px;
}

p{
    margin: 10vh;
    font-size: 20px;
}

@media (max-width:999px) {
  div{
    float: right;
    width: 97vw;
  }
  img{
  width: 50vh;
  overflow: hidden;
}
}



</style>
