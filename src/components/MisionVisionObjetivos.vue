<template>
  <section class="mision-vision-objetivos">
    <div class="section mision">
      <div class="section-content">
        <div class="text-content">
          <div class="section-line mision-line"></div>
          <h2 class="section-title">Misión</h2>
          <p class="section-text">Nuestra misión es proporcionar una educación integral, fomentando el desarrollo académico y personal de nuestros estudiantes.</p>
        </div>
        <img src="../bin/img/Logo.png" alt="Misión" class="section-image">
      </div>
    </div>

    <div class="section vision">
      <div class="section-content">
        <img src="../bin/img/Vision.jpg" alt="Visión" class="section-image">
        <div class="text-content">
          <div class="section-line vision-line"></div>
          <h2 class="section-title">Visión</h2>
          <p class="section-text">Aspiramos a ser una institución educativa de referencia, reconocida por la calidad de nuestros programas y el compromiso con la formación integral.</p>
        </div>
      </div>
    </div>

    <div class="section objetivos">
      <div class="section-content">
        <img src="../bin/img/Objetivos.jpg" alt="Objetivos" class="section-image">

        <div class="text-content">
          <div class="section-line objetivos-line"></div>
          <h2 class="section-title">Objetivos</h2>
          <p class="section-text">Nuestros objetivos son asegurar la excelencia académica, promover valores éticos y preparar a nuestros estudiantes para los desafíos del futuro.</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
}
</script>

<style scoped>
.mision-vision-objetivos {
  display: flex;
  flex-direction: column;
  gap: 30px;
  padding: 20px;
}

.section {
  display: flex;
  align-items: center;
  padding: 20px;
  border-radius: 8px;
}

.mision {
  background-color: #f0f0f0; 
}

.vision, .objetivos {
  background-color: #ffffff;
}

.section-content {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
}

.section-image {
  width: 50%;
  border-radius: 8px;
}

.text-content {
  width: 45%;
}

.section-title {
  font-family: 'Arial', sans-serif;
  font-size: 1.8rem;
  color: #02542D; 
  margin-bottom: 10px;
  text-align: left;
}

.section-text {
  font-family: 'Arial', sans-serif;
  font-size: 1rem;
  color: #000000; 
  text-align: left;
}


.section-line {
  width: 50px;
  height: 4px;
  margin-bottom: 10px;
}

.mision-line {
  background-color: #FF2D55;
}

.vision-line {
  background-color: #FF2D55;
}

.objetivos-line {
  background-color: #FFCC00;
}
</style>
