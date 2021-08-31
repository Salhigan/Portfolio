<template>
  <div id="app">
    <Header />
    <main>
      <HautPage />
      <Logo />
      <Profil />
      <Music />
      <PixelArt />
    </main>
    <Footer />
  </div>  
</template>

<script>
import Header from './components/module/Header.vue'
import Music from './components/module/Music.vue'
import Logo from './components/module/Logo.vue'
import PixelArt from './components/module/PixelArt.vue'
import Profil from './components/module/Profil.vue'
import HautPage from './components/module/HautPage.vue'
import Footer from './components/module/Footer.vue'


export default {
  name: 'App',
  components: {
    Header, Profil, Logo, Music, PixelArt, HautPage, Footer
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Righteous&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Oswald&display=swap');

html {
  scroll-behavior: smooth;
  font-size: 62.5%;
}
.container {
  margin: 0 auto;
  width: 1800px;
}
section {
  background-color:rgb(83, 83, 83);
}
#app {
  font-family: 'Oswald', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #b1b1b1;
}

body {
  margin: 0;
  padding: 0;

  background-color: #3b3b3b;
}

h2 {
    font-size: 4rem;
    padding-top: 2rem;

    color: #fff;
    font-family: 'Righteous', cursive;
}

</style>
