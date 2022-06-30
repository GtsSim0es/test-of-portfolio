<template>
    <div class="bar">
        <div class="menu1">
            <img class="imgp" src="img/home.png">
            <img class="imgp" id="imgP" src="img/project.png">
            <img class="imgp" id="imgC" src="img/contact.png">
        </div>
        </div>

<div class="menu">
  <div class="back">
        <div class="logo">
            <a href="https://github.com/GtsSim0es"><img class="imgG" src="img/GitHub.png"></a> 
            <a href="https://www.linkedin.com/in/gabriel-sim0es"><img class="imgG" src="img/linkedin.png"></a> 
            <a href="mailto:gabi.tsimoes@hotmail.com"><img class="imgG" src="img/mail.png"></a> 
        </div>
        <div class="align">
        <h1>{{name}}</h1> <br>
        <h2>{{graduacao}}</h2> 
        </div>
    </div>  

    <ul>
    <a href="#"><li>Home</li></a>
    <a href="#"><li>Projetos</li></a>
    <a href="#"><li>Contato</li></a>
  </ul>

</div>

</template>

<script>
  export default {
    name: 'menuside-vue',
    data(){
        return{
            name:'Gabriel Simões',
            dev: 'Front-End',
            graduacao: 'Computer Engineering'
        }
    },
    methods: {
        showmenu()
        {
            var btn = document.querySelector('#menunav')
            var container = document.querySelector('.menu')

            btn.addEventListener('click', function(){
                if(container.style.display === "block"){
                    container.style.display = "none"
                } else {
                    container.style.display = "block"
                }
            })

            this.$emit('menushow')  
        }
    }
    }
  
</script>


<style scoped>

label:hover{
    cursor: pointer;
    transform: scale(1.1);
}
.bar{
    background: #222;
    height: 100vh;
    width: 5vh;
    float: left;
    position: fixed;
  }

.imgmenu {
    width: 70%;
    margin-left: 0.6vh;
    margin-top: 3.5vh;
}

.imgp{
    width: 70%;
    margin-left: 0.6vh;
}

#imgP{
    margin-top: 0.2vh;
}

#imgC{
    margin-top: -0.3vh;
}


.menu1{
    margin-top: 23.5vh;
}

@media (max-width: 999px) {
    .menu1{
        margin-top: 2vh;
    }
}

@keyframes menu1 {
  from {
    margin-top: 23.5vh;
  }
  to {
    margin-top: 2vh;
  }
}

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

*{
    font-weight: 800;
    text-shadow: 2px 2px 3px rgba(255,255,255,0.1);
}

.logo {
    margin-left: 5.5vh;
}

h1 {
    color: rgba(0,0,0,0.6);
    font-size: 25px;
    float: right;
}

h2 {
    color: rgba(0,0,0,0.6);
    float: right;
    font-size: 17px;
}
.back{
    background-color:#222;
    height: 25vh;
}
.align{
    margin-top: 2vh;
    float: right;
    margin-right: 3vh;
}

.photo{
    width: 60%;
    height: 6vh;
    float: right;
}

img{
    width: 10%;
    margin: 3vh;
    float: left;
}

img:hover{
    transform: scale(1.1);
}

.menu{

    margin-left: 5vh;
    width: 20vw;
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

@media (max-width: 1300px){
.imgG{
    margin-right: -0.2vh;
    width: 15%; 
}
.logo {
    margin-left: 4vh;
}
}

</style>


