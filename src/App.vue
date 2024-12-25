<template>
  <div>
    <MainNavbar/>
    <AppHeader />
    <AboutSection />
    <ContactSection />
    <AppFooter />
  </div>
</template>

<script>
import MainNavbar from "./components/MainNavbar.vue";
import AppHeader from './components/AppHeader.vue';
import AboutSection from './components/AboutSection.vue';
import ContactSection from './components/ContactSection.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components: {
    MainNavbar,
    AppHeader,
    AboutSection,
    ContactSection,
    AppFooter,
  },
};

</script>
