<template>
  <v-app-bar app color="#ffffff" elevate-on-scroll height="120" class="header-bar">
    <v-toolbar-title class="d-flex flex-column align-start">
      <div class="d-flex align-center">
        <img src="../bin/img/Logo.png" alt="Logo" height="105" class="mr-2">
        <div class="text-content">
          <span class="text-title">Instituto Americano</span>
          <div class="text-subtitle">Forma parte de Nuestros Alumnos</div>
        </div>
        <v-btn icon href="https://www.facebook.com/AMERICANO2017?locale=es_LA" target="_blank" class="ml-2">
          <v-icon color="#007AFF">mdi-facebook</v-icon>
        </v-btn>
      </div>
    </v-toolbar-title>

    <v-spacer></v-spacer>

    <!-- Botones de navegación -->
    <div class="nav-buttons">
      <v-btn text color="#007AFF" @click="$emit('scroll-to-section', 'hero')">Inicio</v-btn>
      <v-btn text color="#007AFF" @click="$emit('scroll-to-section', 'quienesSomos')">Quiénes Somos</v-btn>
      <v-btn text color="#007AFF" @click="$emit('scroll-to-section', 'ofertaAcademica')">Oferta Académica</v-btn>
      <v-btn text color="#007AFF" @click="$emit('scroll-to-section', 'contactSection')">Contáctanos</v-btn>
    </div>
  </v-app-bar>
</template>

<script>
export default {}
</script>

<style scoped>
.text-title {
  font-family: 'Arial', sans-serif;
  font-size: 1.8rem; /* Ajusta según sea necesario */
  font-weight: bold; 
  color: #1a1a1a;
  line-height: 1.2; 
  white-space: nowrap; /* Evita el salto de línea */
  overflow: hidden;
  text-overflow: ellipsis; /* Muestra puntos suspensivos si el texto es muy largo */
}

.text-subtitle {
  font-family: 'Arial', sans-serif;
  font-size: 0.8rem; /* Ajusta según sea necesario */
  color: #808080; 
  margin-top: 4px; 
  white-space: nowrap; /* Evita el salto de línea */
  overflow: hidden;
  text-overflow: ellipsis; /* Muestra puntos suspensivos si el texto es muy largo */
}

.header-bar {
  box-shadow: 0px 4px 2px -2px gray; 
  border-bottom: 4px solid #FF0000; 
  padding-left: 20px; 
  padding-right: 20px;
}

.nav-buttons {
  display: flex;
}

.nav-buttons v-btn {
  font-family: 'Arial', sans-serif;
  font-size: 1rem;
  font-weight: bold;
}

/* Media query para ocultar los botones cuando el viewport es pequeño, ajustado para simular el zoom */
@media (max-width: 1100px) {
  .nav-buttons {
    display: none;
  }
}
</style>
