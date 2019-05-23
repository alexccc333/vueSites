<template>
  <div id="app">
    <MainHeader/>
    <SectionWatch/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MainHeader from './components/MainHeader.vue'
import SectionWatch from './components/SectionWatch'
export default {
  name: 'app',
  components: {
    HelloWorld,MainHeader,SectionWatch
  }
}
</script>

<style>

body{
  font-family: 'Montserrat', sans-serif;
  min-width: 320px;
  color: #1d1d1d;
}
img{
  max-width: 100%;
  height: auto;
}
section{
  padding: 100px 0;
}
h3{
  font-style: italic;
  font-size: 42px;
  font-family: 'Palatino Linotype', 'Book Antiqua', Palatino, serif;
}
h4{
  font-weight: 600;
  font-size: 44px;
  margin-bottom: 20px;
}

</style>
