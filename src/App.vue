<template>

  <nav>
  <img src="https://i.postimg.cc/XNcHD2rs/lojjjj.png" width="200" height="110" >
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>|
     <router-link to="/resume">Resume</router-link>|
      <router-link to="/contact">Contact</router-link>|
       <router-link to="/testimonial">Testimonials</router-link>|
        <router-link to="/projects">Projects</router-link>
  </nav>
  <router-view/>
  
  
  <Footer />
  
</template>

<script>
import Footer from './components/Footer.vue'
export default {
 components: {Footer}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {

  position:relative;
  height:100%;
  width:100%
}

nav a {
  font-weight: bold;
  color: white;
}

nav a.router-link-exact-active {
  color: #A865C9;
}
nav .router-link{
  float:right;
}
nav img{
  justify-content:left;
}



</style>
