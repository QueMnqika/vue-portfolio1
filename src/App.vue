<template>
    <Navbar />
    <router-view/>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import HomeView from "./views/HomeView.vue";
  
  export default{
    name: 'App',
    components:{
    Navbar,
    HomeView,
    // Footer
    },
    data(){
      return {

      }
    }
  }
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Oswald&display=swap');

body{
  font-family: 'Oswald', sans-serif;
  padding: 0;
  margin: 0;
  height: 100vh;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}



/* nav {
  padding: 30px;
}*/

nav a {
  font-size: 18px;
  color: #2c3e50;
  padding: 0 15px;
  text-decoration: none;
} 

nav a:hover {
  font-size: 18px;
  font-weight: bold;
  color: #d50505;
  text-decoration: underline;
} 
</style>
