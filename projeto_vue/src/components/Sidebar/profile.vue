<template>
    <div class="back">
        <div class="logo">
            <a href=""><img class="imgG" src="img/GitHub.png"></a> 
            <a href=""><img src="img/linkedin.png"></a> 
            <a href=""><img src="img/mail.png"></a> 
        </div>
        <div class="align">
        <h1>{{name}}</h1> <br>
        <h2>{{graduacao}}</h2> 
        </div>
    </div>  
</template>

<script>
  export default {
    name: 'profile-vue',
    data(){
        return{
            name:'Gabriel Terra Simões',
            dev: 'Front-End',
            graduacao: 'Computer Engineering'
        }
    }
  }
</script>

<style scoped>
*{
    font-weight: 800;
    color: rgba(0,0,0,0.6);
    text-shadow: 2px 2px 3px rgba(255,255,255,0.1);
}

.logo {
    margin-left: 5.5vh;
}

h1 {
    font-size: 25px;
}

h2 {
    margin-top: -2vh;
    float: right;
    font-size: 17px;
}
.back{
    background-color:#222;
    height: 20vh;
}
.align{
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


</style>
