<template>
  <div class="container-fluid">
    <!-- Hero Section -->
    <section class="bg-light text-center py-5">
      <h1 class="display-4">⚡ Sparen Sie Energie mit Little Energy</h1>
      <p class="lead">Optimieren Sie Ihre Energiekosten für eine bessere Zukunft!</p>
      <a href="#" class="btn btn-success btn-lg">Mehr erfahren</a>
    </section>

    <!-- Dienstleistungen -->
    <section class="row text-center my-5">
      <div class="col-md-4">
        <div class="card h-100">
          <img src="https://via.placeholder.com/300" class="card-img-top" alt="Anbieterwechsel">
          <div class="card-body">
            <h5 class="card-title">Anbieterwechsel</h5>
            <p class="card-text">Sparen Sie jährlich durch einen Anbieterwechsel bei Strom und Gas.</p>
            <a href="#" class="btn btn-primary">Mehr erfahren</a>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card h-100">
          <img src="https://via.placeholder.com/300" class="card-img-top" alt="LED-Umrüstung">
          <div class="card-body">
            <h5 class="card-title">LED-Umrüstung</h5>
            <p class="card-text">Senken Sie Ihre Energiekosten durch energieeffiziente Beleuchtungslösungen.</p>
            <a href="#" class="btn btn-primary">Mehr erfahren</a>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card h-100">
          <img src="https://via.placeholder.com/300" class="card-img-top" alt="Photovoltaik">
          <div class="card-body">
            <h5 class="card-title">Photovoltaik</h5>
            <p class="card-text">Erzeugen Sie Ihre eigene Energie durch maßgeschneiderte PV-Anlagen.</p>
            <a href="#" class="btn btn-primary">Mehr erfahren</a>
          </div>
        </div>
      </div>
    </section>

  </div>
</template>

<script setup>
// Keine zusätzliche Logik nötig
</script>

<style scoped>
.card-img-top {
  height: 200px;
  object-fit: cover;
}
.bg-light {
  background-color: #f8f9fa !important;
}
.btn-success {
  background-color: #11673c;
  border: none;
}
</style>
