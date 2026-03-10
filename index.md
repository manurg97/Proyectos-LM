---
layout: default
title: Inicio - Informática Ambiental
---

<style>
  /* --- CONTENEDOR PRINCIPAL --- */
  .main-container {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: #2c3e50;
    max-width: 900px;
    margin: auto;
  }

  /* --- HEADER ESTILO HERO --- */
  .hero-section {
    background: linear-gradient(120deg, #2e7d32 0%, #004d40 100%);
    color: white;
    padding: 60px 20px;
    border-radius: 20px;
    text-align: center;
    box-shadow: 0 10px 30px rgba(0,0,0,0.15);
    margin-bottom: 40px;
  }

  /* --- GRID DE NAVEGACIÓN --- */
  .grid-indice {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 20px;
    padding: 10px;
  }

  /* --- TARJETAS (ESTILO GLASSMORPHISM) --- */
  .card {
    background: #ffffff;
    border: 1px solid #e0e0e0;
    border-radius: 15px;
    padding: 25px;
    text-decoration: none !important;
    color: #333 !important;
    transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
  }

  .card:hover {
    transform: translateY(-10px);
    box-shadow: 0 15px 30px rgba(0,0,0,0.1);
    border-color: #2e7d32;
  }

  .card-icon {
    font-size: 40px;
    margin-bottom: 15px;
  }

  .card-title {
    font-weight: bold;
    font-size: 1.2em;
    margin-bottom: 10px;
    color: #1b5e20;
  }

  .card-desc {
    font-size: 0.9em;
    color: #666;
  }

  /* --- PIE DE PÁGINA --- */
  .footer-info {
    margin-top: 50px;
    padding: 20px;
    border-top: 2px solid #eee;
    text-align: center;
    font-style: italic;
    color: #7f8c8d;
  }
</style>

<div class="main-container">

  <div class="hero-section">
    <h1 style="color: white; margin: 0; font-size: 2.8em;">🌍 Informática y Medio Ambiente</h1>
    <p style="font-size: 1.2em; opacity: 0.9; margin-top: 15px;">Explorando el impacto tecnológico en nuestro ecosistema</p>
  </div>

  <div class="grid-indice">
    
    <a href="Pablo_contaminacion.html" class="card">
      <div class="card-icon">🌫️</div>
      <div class="card-title">Contaminación Ambiental</div>
      <div class="card-desc">Entiende qué es y cómo afecta la actividad humana al entorno global.</div>
    </a>

    <a href="Manuel_residuos.html" class="card">
      <div class="card-icon">🗑️</div>
      <div class="card-title">Residuos Informáticos</div>
      <div class="card-desc">El desafío de la basura electrónica y la gestión de componentes tóxicos.</div>
    </a>

    <a href="Sergio_obsolescencia.html" class="card">
      <div class="card-icon">⏲️</div>
      <div class="card-title">Obsolescencia Programada</div>
      <div class="card-desc">¿Por qué los dispositivos duran cada vez menos? Análisis de esta estrategia.</div>
    </a>

    <a href="Sergio_informatica.html" class="card">
      <div class="card-icon">🌱</div>
      <div class="card-title">Informática Ecológica</div>
      <div class="card-desc">Soluciones y tecnologías verdes para un desarrollo digital sostenible.</div>
    </a>

    <a href="referencias.html" class="card" style="grid-column: 1 / -1;">
      <div class="card-icon">📚</div>
      <div class="card-title">Referencias y Bibliografía</div>
      <div class="card-desc">Fuentes consultadas y autoría del proyecto colaborativo.</div>
    </a>

  </div>

  <div class="footer-info">
    "La tecnología debe ser una herramienta para sanar el planeta, no para destruirlo."
    <br><strong>Proyecto Sevilla 25 - 2026</strong>
  </div>

</div>
