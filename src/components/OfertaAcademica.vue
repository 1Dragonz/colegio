<template>
 <div class="xD">
 <section class="oferta-academica">
    <div class="section-content">
      <div class="text-content">
        <div class="section-line"></div>
        <h2 class="section-title">Oferta Académica</h2>
        <div class="oferta-item">
          <v-icon class="oferta-icon">mdi-school</v-icon>
          <p class="oferta-text">Preprimaria</p>
        </div>
        <div class="oferta-item">
          <v-icon class="oferta-icon">mdi-school</v-icon>
          <p class="oferta-text">Primaria Completa</p>
        </div>
        <div class="oferta-item">
          <v-icon class="oferta-icon">mdi-school</v-icon>
          <p class="oferta-text">Ciclo Básico</p>
        </div>
        <div class="oferta-item">
          <v-icon class="oferta-icon">mdi-school</v-icon>
          <p class="oferta-text">Bachillerato</p>
        </div>
        <div class="oferta-item">
          <v-icon class="oferta-icon">mdi-school</v-icon>
          <p class="oferta-text">Perito</p>
        </div>
      </div>
      <img src="../bin/img/oferta.jpg" alt="Oferta Académica" class="section-image">
    </div>
  </section>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
.xD{
  border-bottom: 2px solid #CAC4D0; 
  padding-left: 20px; 
  padding-right: 20px;
}
.oferta-academica {
  background-color: #f0f0f0; 
  display: flex;
  flex-direction: column;
  padding: 20px;
  border-radius: 8px;
}

.section-content {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
}

.section-title {
  font-family: 'Arial', sans-serif;
  font-size: 1.8rem;
  font-weight: bold;
  color: #02542D; 
  margin-bottom: 20px;
  text-align: left;
}

.text-content {
  width: 50%;
}

.oferta-item {
  display: flex;
  align-items: center;
  margin-bottom: 10px;
}

.oferta-icon {
  color: #FF2D55; 
  font-size: 1.5rem;
  margin-right: 10px;
}

.oferta-text {
  font-family: 'Arial', sans-serif;
  font-size: 1.2rem;
  font-weight: bold;
  color: #000000; 
  text-align: left;
}

.section-image {
  width: 45%;
  border-radius: 8px;
}

.section-line {
  width: 50px;
  height: 4px;
  margin-bottom: 10px;
  background-color: #FF2D55;
}
</style>
