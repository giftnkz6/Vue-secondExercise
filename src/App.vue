<template>
  <NavBar />
  <router-view/>
  <Footer></Footer>
</template>

<script>
  import NavBar from "./components/NavBar.vue"
  import Footer from "./components/Footer.vue"
  export default {
    name: "App",
    components: {
      NavBar,
      Footer
    }
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

/* body{
  background-image: url("https://imageio.forbes.com/blogs-images/yjeanmundelsalle/files/2019/06/01_A-painting-by-Dr-Esther-Mahlangu-1200x805.jpg?format=jpg&width=1200");
} */


nav {
  margin: auto;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}

li{
  list-style: none;
  margin: 1rem;
}
ul{
  display: flex;
}
</style>
