<template>
    <nav class="navbar navbar-expand-lg">
        <router-link to="/">
        <img class="img-fluid w-25 m-auto" src="../assets/que-m-logo.png" alt="logo" loading="lazy">
        </router-link>
  <div class="container-fluid d-flex justify-content-end">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0 me-5 mx-auto">
        <li class="nav-item">
          <router-link to="/" class="nav-link active">
            <img src="https://i.postimg.cc/0jdS2PKq/system-solid-41-home.gif" width="30px" alt="">
            
          </router-link>
        </li>
        <li>
          <router-link to="/about" class="nav-link active">
            About
          </router-link>
        </li>
        <li>
          <router-link to="/resume" class="nav-link active">
            Resume
          </router-link>
        </li>
        <li>
          <router-link to="/projects" class="nav-link active">
           Projects
          </router-link>
        </li>
        <li>
          <router-link to="/testimonial" class="nav-link active">
            Testimonials
          </router-link>
        </li>
        <li>
          <router-link to="/contact" class="nav-link active">
            Contact
          </router-link>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>









<script>

export default {
    name: 'Navbar',
    data(){
        return{
    
        }
    }
}
</script>

<style scoped>

header, nav{
    display: flex;
    justify-content: space-between;
    background-color: #FFD700;
}

nav{
    padding: 28px 15px;
}

nav a {
    
  font-weight: bold;
  color: #2c3e50;
  padding: 0 5px;
}
</style>