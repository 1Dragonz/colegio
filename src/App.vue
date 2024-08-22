<template>
  <v-app>
    <!-- Header -->
    <AppHeader @scroll-to-section="scrollToSection" />
    <v-main>
      <v-container>
        <!-- Secciones -->
        <HeroSection ref="hero" />
        <QuienesSomos ref="quienesSomos" />
        <MisionVisionObjetivos ref="misionVisionObjetivos" />
        <OfertaAcademica ref="ofertaAcademica" />
        <ContactSection ref="contactSection" />
      </v-container>
    </v-main>
    <!-- Footer -->
    <AppFooter />
  </v-app>
</template>

<script>
import AppHeader from './components/AppHeader.vue'
import HeroSection from './components/HeroSection.vue'
import QuienesSomos from './components/QuienesSomos.vue'
import MisionVisionObjetivos from './components/MisionVisionObjetivos.vue'
import OfertaAcademica from './components/OfertaAcademica.vue'
import ContactSection from './components/ContactSection.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  components: {
    AppHeader,
    HeroSection,
    QuienesSomos,
    MisionVisionObjetivos,
    OfertaAcademica,
    ContactSection,
    AppFooter
  },
  methods: {
    scrollToSection(section) {
      const targetSection = this.$refs[section];
      if (targetSection) {
        window.scrollTo({
          top: targetSection.$el.offsetTop - 120, // Ajusta 120 para tomar en cuenta la altura del header
          behavior: 'smooth'
        });
      }
    }
  }
}
</script>

<style>
@import url("bin/styles.css");
</style>
