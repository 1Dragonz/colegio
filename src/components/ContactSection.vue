<template>
  <section class="contact-section">
    <div class="section-content">
      <h2 class="section-title">C O N T A C T A N O S</h2>
      <p class="contact-email">info@institutoamericano.edu.gt</p>
      <p class="contact-info">
        <span class="contact-address">6 Av. 18-23 Zona 1. </span>
        <span class="contact-phone">Tel. 0000000</span>
      </p>
    </div>
  </section>
</template>

<script>
export default {
}
</script>

<style scoped>
.contact-section {
  padding: 20px;
}

.section-content {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}

.section-title {
  font-family: 'Arial', sans-serif;
  font-size: 2.5rem;
  font-weight: bold;
  color: #410E0B; /* Color del título */
  margin-bottom: 10px;
  text-align: left;
  letter-spacing: 0.15rem; /* Espaciado entre letras */
  text-transform: uppercase; /* Todo en mayúsculas */
}

.contact-email {
  font-family: 'Arial', sans-serif;
  font-size: 1.5rem; /* Tamaño de letra más grande */
  color: #02542D; /* Color del correo */
  margin-bottom: 15px;
}

.contact-info {
  font-family: 'Arial', sans-serif;
  font-size: 1rem;
  color: #000000;
  text-align: left;
}

.contact-address {
  color: #FF0000; /* Color de la dirección */
}

.contact-phone {
  color: #13A919; /* Color del teléfono */
}
</style>
