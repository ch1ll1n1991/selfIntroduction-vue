<template>
  <div id="app">
    <Header />
    <About />
    <Skills />
    <Experience />
    <Contact />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import About from './components/About.vue';
import Skills from './components/Skills.vue';
import Experience from './components/Experience.vue';
import Contact from './components/Contact.vue';
import Footer from './components/Footer.vue';
import './assets/styles.css';  // グローバルスタイルをインポート


export default {
  name: 'App',
  components: {
    Header,
    About,
    Skills,
    Experience,
    Contact,
    Footer
  }
}
</script>

<style>
/* グローバルスタイルをここに追加 */
</style>
