<template>
  <div id="app">
    <MainHeader v-show="this.$store.state.main"/>
    <SectionWatch v-show="this.$store.state.main"/>
    <SectionProgress v-show="this.$store.state.main"/>
    <SectionLets v-show="this.$store.state.main"/>
    <SectionDesign v-show="this.$store.state.main"/>
    <Footer v-show="this.$store.state.main"/>
    <registr v-show="this.$store.state.registr"/>
    <MainLogin v-show="this.$store.state.login"></MainLogin>

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
import registr from './components/registr'
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
    registr
  },
  data: function () {
    return {

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
