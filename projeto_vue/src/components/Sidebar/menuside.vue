<template>
    <div class="bar">
        <label for=""><img class="imgmenu" src="img/menu.png" alt=""></label>
        <div class="menu1">
            <a href=""><img class="imgp" src="img/home.png"></a>
        </div>
    </div>
</template>

<script>
  export default {
    name: 'menuside-vue'
  }
</script>

<style scoped>
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

.menu1{
    margin-top: 15vh;
}

</style>


