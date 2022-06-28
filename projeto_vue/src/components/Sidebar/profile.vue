<template>
    <div class="back">
        <div class="photo"><img src="img/profile.JPG" > <br></div>
    
        <div class="align">
        {{name}} <br>
        {{graduacao}}
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
.back{
    background-color:rgb(43, 43, 43);
    height: 30vh;
}
.align{
    float: right;
    margin-top: 15vh;
    margin-right: 3vh;
}

.photo{
    width: 60%;
    height: 6vh;
    float: right;
}

img{
    width: 50%;
    float: right;
    margin: 3vh;
}
</style>
