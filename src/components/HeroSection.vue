<template>
  <section class="hero-section">
    <div class="hero-image-1"></div>
<br><br><br>
    <div class="hero-image-2">
      <div class="hero-content">
        <h1 class="hero-title">EDUCAR ES SERVIR</h1>
        <div class="hero-line"></div>
        <p class="hero-subtitle">Estamos mejorando nuestros servicios, para brindar una educación de calidad y a la vez sustentarla con herramientas tecnológicas de primer nivel</p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
}
</script>

<style scoped>
.hero-section {
  display: flex;
  flex-direction: column;
}

.hero-image-1 {
  height: 400px; 
  background-image: url('../bin/img/Pizarron.jpg'); 
  background-size: cover;
  background-position: center;
}

.hero-image-2 {
  height: 400px;
  background-image: url('../bin/img/Educar.jpg'); 
  background-size: cover;
  background-position: center;
  display: flex;
  justify-content: center;
  align-items: center;
}

.hero-content {
  text-align: center;
  background-color: rgba(170, 170, 170, 0.8); 
  padding: 20px;
  width: 100%; 
  height: 100%; 
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  border-radius: 8px;
}

.hero-title {
  font-family: 'Arial', sans-serif;
  font-size: 2.5rem;
  color: #fff;
  margin-bottom: 0px;
}


.hero-line {
  width: 100px;
  height: 4px;
  background-color: #FF2D55;
  margin: 40px 0;
}

.hero-subtitle {
  font-family: 'Arial', sans-serif;
  font-size: 1.2rem;
  color: #fff;
  font-weight: bold;
}
</style>
