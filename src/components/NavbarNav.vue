<script setup lang="ts">

</script>

<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-custom fixed-top">
    <div class="container-fluid d-flex justify-content-center">
      <router-link class="navbar-brand me-auto" to="/">⚡ Little Energy</router-link>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <!-- Navigationslinks -->
      <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <router-link class="nav-link" to="/">Home</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="/about">About</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="/contact">Contact</router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>




<style scoped>
/* Grüner Hintergrund der Navbar */
.bg-custom {
  background-color: #308737;
}

/* Vergrößerte Navbar */
.navbar {
  padding: 1.5rem 2rem; /* Erhöhtes Padding oben/unten und links/rechts */
  border-bottom: 1px solid #d1d1d1;
}

/* Größere Links */
.nav-link {
  color: #fff; /* Links weiß */
  font-weight: bold;
  font-size: 1.3rem; /* Größere Schriftgröße der Links */
  padding: 0.75rem 1.5rem; /* Mehr Platz zwischen den Links */
}

/* Hover-Effekt für Links (nur Unterstreichung) */
.nav-link:hover {
  text-decoration: underline;
  background-color: transparent; /* Kein Hintergrundwechsel beim Hover */
}

/* Markenname fett, größer und weiß */
.navbar-brand {
  font-weight: bold;
  color: #fff;
  font-size: 2rem; /* Größeres Logo/Brand */
}

/* Für mobile Ansicht: Vergrößerter Toggler-Button */
.navbar-toggler {
  padding: 0.75rem 1rem;
}

/* Optional: Wenn die Navbar bei größeren Bildschirmen breiter wirken soll */
.container-fluid {
  max-width: 1200px; /* Maximale Breite der Navbar */
}

</style>

