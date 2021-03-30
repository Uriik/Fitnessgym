<template>
  <div id="app">
    <Header/>
    <SectionWho/>
    <SectionThree/>
    <SectionExac/>
    <SectionArtc/>
    <Article/>
    <Footer/>
    <Style./>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import SectionWho from './components/SectionWho.vue'
import SectionThree from './components/SectionThree.vue'
import SectionExac from './components/SectionExac.vue'
import SectionArtc from './components/SectionArtc.vue'
import Article from './components/Article.vue'
import Footer from './components/Footer.vue'
import Style from './components/Style.css'

export default {
  name: 'App',
  components: {
    Header,
    SectionWho,
    SectionThree,
    SectionExac,
    SectionArtc,
    Article,
    Footer,
    Style
  }
}
</script>

<style>

</style>
