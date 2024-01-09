<template>
  <div class="home">
    <img src="../assets/landingPhoto.jpg" width="1519px" alt="">
  </div>
  <div class="title">
    <h1>{{ title }}</h1>
  <h4>{{ titleText }}</h4>
  </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'


export default {
  name: 'Home',
  data(){
    return{
      title: 'Qaqambile Mnqika',
      titleText: 'Aspiring Software Developer'
    }
  },
  components: {
    Navbar
  }
}
</script>

<style scoped>
.home>img{
  opacity: 80%;
  position: absolute;
  right: 0;
}

.title{
  position: relative;
  top: 25vh;
  text-shadow: 0 0 8px #fff;
}
</style>
