---
layout: default
title: Residuos Informáticos
---


<style>
  /* --- PALETA DE COLORES LUX --- */
  :root {
    --bg-soft: #f0f2f5;
    --accent-purple: #6c5ce7;
    --accent-gold: #ffb8b8; /* Tono coral suave */
    --text-main: #2d3436;
    --shadow: 20px 20px 60px #bebebe, -20px -20px 60px #ffffff;
  }

  .contenedor-premium {
    background-color: var(--bg-soft);
    padding: 50px;
    border-radius: 40px;
    color: var(--text-main);
    font-family: 'Segoe UI', Roboto, sans-serif;
  }

  /* --- CABECERA ESTILO REVISTA --- */
  .header-residuos {
    text-align: center;
    margin-bottom: 60px;
  }

  .header-residuos h1 {
    font-size: 3.5em;
    font-weight: 900;
    color: var(--accent-purple);
    margin: 0;
    letter-spacing: -2px;
  }

  .subtitulo-badge {
    display: inline-block;
    background: var(--accent-purple);
    color: white;
    padding: 5px 20px;
    border-radius: 50px;
    font-size: 0.9em;
    margin-top: 10px;
    text-transform: uppercase;
    letter-spacing: 2px;
  }

  /* --- SECCIONES NEUMÓRFICAS --- */
  .seccion-card {
    background: var(--bg-soft);
    border-radius: 30px;
    padding: 40px;
    margin-bottom: 40px;
    box-shadow: var(--shadow);
    border: 1px solid rgba(255,255,255,0.2);
  }

  /* --- GRID DE CATEGORÍAS TIPO APP --- */
  .app-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 20px;
    margin-top: 30px;
  }

  .app-item {
    background: #f0f2f5;
    padding: 20px;
    border-radius: 25px;
    text-align: center;
    box-shadow: 6px 6px 12px #d1d9e6, -6px -6px 12px #ffffff;
    transition: 0.3s;
    border: 1px solid transparent;
  }

  .app-item:hover {
    box-shadow: inset 6px 6px 12px #d1d9e6, inset -6px -6px 12px #ffffff;
    transform: scale(0.98);
  }

  .app-item i {
    font-size: 2em;
    display: block;
    margin-bottom: 10px;
  }

  /* --- LISTA DE TOXICIDAD CON INDICADORES --- */
  .tox-list {
    list-style: none;
    padding: 0;
  }

  .tox-item {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 0;
    border-bottom: 1px dashed #b2bec3;
  }

  .nivel-alerta {
    height: 8px;
    width: 100px;
    background: #dfe6e9;
    border-radius: 10px;
    overflow: hidden;
  }

  .alerta-fill {
    height: 100%;
    background: var(--accent-purple);
  }

  /* --- BANNER DE MINERÍA (ESTILO DARK MODE) --- */
  .banner-mineria {
    background: #2d3436;
    color: white;
    border-radius: 30px;
    padding: 40px;
    display: flex;
    align-items: center;
    gap: 30px;
    margin: 60px 0;
  }

  .circle-stat {
    width: 120px;
    height: 120px;
    border: 8px solid var(--accent-purple);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.5em;
    font-weight: bold;
    flex-shrink: 0;
  }

  /* --- NAVEGACIÓN MINIMALISTA --- */
  .nav-minimal {
    display: flex;
    justify-content: space-between;
    margin-top: 80px;
  }

  .btn-flat {
    text-decoration: none;
    color: var(--accent-purple);
    font-weight: bold;
    padding: 15px 30px;
    border-radius: 15px;
    box-shadow: 4px 4px 10px #bebebe, -4px -4px 10px #ffffff;
    transition: 0.2s;
  }

  .btn-flat:active {
    box-shadow: inset 4px 4px 10px #bebebe, inset -4px -4px 10px #ffffff;
  }

  .btn-primary {
    background: var(--accent-purple);
    color: white;
  }
</style>

<div class="contenedor-premium">

  <header class="header-residuos retraso-1">
    <h1>E-Waste Crisis</h1>
    <span class="subtitulo-badge">Informe de Sostenibilidad 2024</span>
    <p style="margin-top: 25px; font-size: 1.1em; max-width: 600px; margin-left: auto; margin-right: auto;">
      La tecnología avanza, pero los materiales permanecen. Estamos ante el residuo sólido urbano que más rápido crece en la historia de la humanidad.
    </p>
  </header>

  <div class="seccion-card retraso-2">
    <h2 style="color: var(--accent-purple);">01. Clasificación RAEE</h2>
    <p>Identificamos cuatro ecosistemas críticos de desecho informático que requieren tratamiento diferenciado:</p>
    
    <div class="app-grid">
      <div class="app-item">
        <span>💻</span>
        <strong>Sistemas</strong>
        <small>CPUs y Laptops</small>
      </div>
      <div class="app-item">
        <span>📱</span>
        <strong>Mobile</strong>
        <small>Smartphones</small>
      </div>
      <div class="app-item">
        <span>🔋</span>
        <strong>Celdas</strong>
        <small>Baterías Li-ion</small>
      </div>
      <div class="app-item">
        <span>📡</span>
        <strong>Nodos</strong>
        <small>Routers y Redes</small>
      </div>
    </div>
  </div>

  <div class="seccion-card retraso-3">
    <h2 style="color: var(--accent-purple);">02. Componentes Críticos</h2>
    <p>Análisis de los elementos químicos presentes en el hardware convencional y su impacto biológico:</p>
    
    

    <div class="tox-list">
      <div class="tox-item">
        <span><strong>Mercurio</strong> (Pantallas LCD)</span>
        <div class="nivel-alerta"><div class="alerta-fill" style="width: 90%;"></div></div>
      </div>
      <div class="tox-item">
        <span><strong>Plomo</strong> (Soldaduras)</span>
        <div class="nivel-alerta"><div class="alerta-fill" style="width: 75%;"></div></div>
      </div>
      <div class="tox-item">
        <span><strong>Cadmio</strong> (Circuitos)</span>
        <div class="nivel-alerta"><div class="alerta-fill" style="width: 85%;"></div></div>
      </div>
    </div>
  </div>

  <div class="banner-mineria">
    <div class="circle-stat">80%</div>
    <div>
      <h3 style="margin: 0; color: var(--accent-purple);">Minería Urbana</h3>
      <p style="margin: 5px 0 0; opacity: 0.8;">
        El 80% de un ordenador es reciclable. Recuperar metales preciosos de placas base reduce la necesidad de excavaciones mineras en un 60%.
      </p>
    </div>
  </div>

  <div class="seccion-card">
    <h2 style="color: var(--accent-purple);">03. Hoja de Ruta Ética</h2>
    <ul style="line-height: 2;">
      <li><strong>Reparación:</strong> Priorizar el mantenimiento sobre la sustitución.</li>
      <li><strong>Software:</strong> Usar SO eficientes para hardware de baja potencia.</li>
      <li><strong>Gestión:</strong> Disposición final en centros RAEE certificados.</li>
    </ul>
  </div>

  <footer class="nav-minimal">
    <a href="contaminacion.html" class="btn-flat">← Anterior</a>
    <a href="obsolescencia.html" class="btn-flat btn-primary">Siguiente Capítulo →</a>
  </footer>

</div>
