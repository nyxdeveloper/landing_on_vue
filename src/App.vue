<template>
  <div id="app">
  <Header/> 
  <Top/>
  <Services/>
  <Projects/>
  <Advantages/>
  <Location/>
  <Footer/>
  </div>
</template>

<script>
import Header from '@/components/Header'
import Top from '@/components/Top'
import Services from '@/components/Services'
import Projects from '@/components/Projects'
import Advantages from '@/components/Advantages'
import Location from '@/components/Location'
import Footer from '@/components/Footer'

export default {
  name: 'App',
  components: {
    Header,
    Top,
    Services,
    Projects,
    Advantages,
    Location,
    Footer
  }
}
</script>

<style>
body{
  overflow-x: hidden;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
button, input, textarea, a, button:active, input:active, textarea:active, a:active, button:focus, input:focus, textarea:focus, a:focus{
  outline: none;
}
</style>
