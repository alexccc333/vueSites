<template>
  <div id="app">
    <MainHeader/>
    <SectionWatch/>
    <SectionProgress/>
    <SectionLets/>
    <SectionDesign/>
    <Footer/>
  </div>
</template>

<script>
import MainHeader from './components/MainHeader.vue'
import SectionWatch from './components/SectionWatch'
import SectionProgress from './components/SectionProgress'
import SectionLets from './components/SectionLets'
import SectionDesign from './components/SectionDesign'
import Footer from './components/Footer'
import Copyright from './components/Copyright'
import MainLogin from './components/Login'
export default {
  name: 'app',
  components: {
    MainHeader,
    SectionWatch,
    SectionProgress,
    SectionLets,
    SectionDesign,
    Footer,
    Copyright,
    MainLogin,
  },
  data(){
    return
    {
      //status:false,
    }
  },
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
