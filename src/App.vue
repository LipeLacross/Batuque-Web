<template>
  <div id="app">
    <Header />
    <Hero />
    <About />
    <ProjectOverview />
    <Services />
    <Resources />
    <BugReport />
    <Contact />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Hero from './components/Hero.vue';
import About from './components/About.vue';
import Services from './components/Services.vue';
import Resources from './components/Resources.vue';
import BugReport from './components/BugReport.vue';
import Contact from './components/Contact.vue';
import Footer from './components/Footer.vue';
import ProjectOverview from './components/ProjectOverview.vue';

export default {
  components: {
    Header,
    Hero,
    About,
    ProjectOverview,
    Services,
    Resources,
    BugReport,
    Contact,
    Footer,
  }
};
</script>

<style src="./assets/main.css"></style>
