---
layout: default
title: Residuos Informáticos
---

<style>
  /* --- ANIMACIONES EN CASCADA --- */
  @keyframes fadeInUp {
    0% { opacity: 0; transform: translateY(20px); }
    100% { opacity: 1; transform: translateY(0); }
  }
  .retraso-1 { animation: fadeInUp 0.8s ease-out forwards; }
  .retraso-2 { opacity: 0; animation: fadeInUp 0.8s ease-out 0.2s forwards; }
  .retraso-3 { opacity: 0; animation: fadeInUp 0.8s ease-out 0.4s forwards; }
  .retraso-4 { opacity: 0; animation: fadeInUp 0.8s ease-out 0.6s forwards; }

  /* --- MINI ÍNDICE INTERNO --- */
  .mini-indice {
    background: #ffffff;
    border: 1px solid #e1e4e8;
    padding: 20px;
    border-radius: 12px;
    margin-bottom: 30px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    border-left: 5px solid #0366d6;
  }
  .mini-indice h4 { margin-top: 0; color: #24292e; font-size: 1.2em; }
  .mini-indice ul { list-style: none; padding-left: 0; }
  .mini-indice li { margin: 8px 0; }
  .mini-indice a { color: #0366d6; text-decoration: none; font-weight: 500; }
  .mini-indice a:hover { text-decoration: underline; color: #586069; }

  /* --- CAJA TEMÁTICA AZUL --- */
  .caja-azul {
    background: linear-gradient(135deg, #e3f2fd 0%, #bbdefb 100%);
    border-left: 6px solid #0366d6;
    padding: 25px;
    margin: 25px 0;
    border-radius: 10px;
    color: #0c2d48;
    line-height: 1.7;
    font-size: 1.1em;
  }

  /* --- ESTILO DE IMÁGENES --- */
  .img-estilo {
    border-radius: 12px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.15);
    display: block;
    margin: 30px auto;
    max-width: 100%;
    height: auto;
  }

  /* --- GRID DE TARJETAS --- */
  .grid-detalles {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 20px;
    margin: 30px 0;
  }
  .tarjeta-detalle {
    background: #ffffff;
    border: 1px solid #d1d5da;
    padding: 20px;
    border-radius: 10px;
    border-top: 5px solid #0366d6;
    transition: all 0.3s ease;
  }
  .tarjeta-detalle:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.1);
  }

  /* --- SECCIONES DE CONTENIDO --- */
  .seccion-contenido { margin-bottom: 60px; }
  .texto-resaltado { color: #0366d6; font-weight: bold; }

  /* --- BOTONES DE NAVEGACIÓN --- */
  .nav-botones {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 15px;
    margin-top: 50px;
    border-top: 2px solid #eaecef;
    padding-top: 30px;
  }
  .btn-nav {
    flex: 1;
    min-width: 160px;
    padding: 14px 20px;
    color: white !important;
    text-decoration: none;
    border-radius: 8px;
    font-weight: bold;
    text-align: center;
    transition: all 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  }
  .btn-nav:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 15px rgba(0,0,0,0.2);
    filter: brightness(1.1);
  }
  .btn-nav.volver { background-color: #6a737d; }
  .btn-nav.siguiente { background-color: #0366d6; }
</style>

# Residuos Informáticos: El Lado Oscuro de la Era Digital

<div class="retraso-1">
La revolución tecnológica ha transformado nuestra forma de vivir, trabajar y comunicarnos. Sin embargo, este progreso tiene un precio invisible: la acumulación masiva de **residuos electrónicos** o **e-waste**. 

Se estima que el mundo genera más de **50 millones de toneladas** de desechos electrónicos al año, una cifra que crece tres veces más rápido que cualquier otro tipo de residuo sólido urbano.
</div>

<div class="mini-indice retraso-2">
  <h4>Contenido de la Guía</h4>
  <ul>
    <li><a href="#definicion">1. ¿Qué son los RAEE?</a></li>
    <li><a href="#peligros">2. El Peligro Químico</a></li>
    <li><a href="#impacto">3. Impacto Global y Ética</a></li>
    <li><a href="#mineria">4. La Minería Urbana</a></li>
    <li><a href="#soluciones">5. Mitigación y Acción</a></li>
  </ul>
</div>

---

<section id="definicion" class="seccion-contenido retraso-3">
  
## 1. ¿Qué son los Residuos Informáticos?
  
Los residuos informáticos, conocidos técnicamente como <span class="texto-resaltado">RAEE</span> (Residuos de Aparatos Eléctricos y Electrónicos), comprenden todos aquellos dispositivos de computación y telecomunicaciones que han llegado al final de su vida útil.

<div class="grid-detalles">
  <div class="tarjeta-detalle">
    <strong>Hardware de Escritorio</strong><br>
    CPUs, monitores (CRT, LCD, LED), teclados y ratones.
  </div>
  <div class="tarjeta-detalle">
    <strong>Dispositivos Portátiles</strong><br>
    Laptops, tablets y smartphones de última generación.
  </div>
  <div class="tarjeta-detalle">
    <strong>Periféricos y Redes</strong><br>
    Impresoras, escáneres, routers y módems.
  </div>
  <div class="tarjeta-detalle">
    <strong>Almacenamiento</strong><br>
    Discos duros, unidades SSD y memorias flash.
  </div>
</div>

</section>

<section id="peligros" class="seccion-contenido retraso-4">

## 2. El Peligro Químico: Componentes Tóxicos
  
Un ordenador no es solo plástico y metal; es un "cóctel" químico complejo. Cuando estos dispositivos terminan en vertederos comunes, los materiales tóxicos se filtran al suelo.

| Material | Localización común | Impacto Ambiental/Salud |
| :--- | :--- | :--- |
| **Plomo** | Soldaduras y tubos CRT. | Daños al sistema nervioso y riñones. |
| **Mercurio** | Pantallas planas. | Bioacumulativo, afecta el cerebro. |
| **Cadmio** | Baterías y placas. | Altamente cancerígeno. |
| **Bario** | Pantallas frontales. | Debilidad muscular y daños cardíacos. |
| **Retardantes** | Carcasas plásticas. | Alteraciones hormonales. |

</section>

<section id="impacto" class="seccion-contenido">

## 3. Impacto Global y Desigualdad
  
El problema tiene una dimensión ética preocupante. Gran parte de los desechos generados en países desarrollados terminan en vertederos informales como **Agbogbloshie en Ghana**. Allí, trabajadores y niños extraen metales valiosos quemando cables sin protección, liberando gases altamente tóxicos y contaminando permanentemente los ecosistemas locales.

</section>

<div class="caja-azul">

### 4. La Minería Urbana: Una Oportunidad Perdida
Aunque son peligrosos, los residuos informáticos son una mina de recursos. 

> **¿Sabías que?** Hay más oro en una tonelada de teléfonos móviles que en una tonelada de mineral extraído de una mina de oro convencional.

**Beneficios del reciclaje especializado:**
* **Recuperación de metales raros:** Litio, cobalto y neodimio.
* **Ahorro energético:** Reciclar aluminio consume un **95% menos** de energía que extraerlo.
* **Reducción de huella:** Menos minería tradicional significa proteger la biodiversidad.

</div>

<section id="soluciones" class="seccion-contenido">

## 5. ¿Cómo podemos mitigar el problema?
  
La solución no es dejar de usar tecnología, sino cambiar nuestra relación con ella:

* **Reducir:** Evitar el recambio tecnológico por moda.
* **Reutilizar:** Dar una segunda vida con sistemas ligeros (Linux) o donarlos.
* **Reciclaje Responsable:** Acudir a **Puntos Limpios** o centros RAEE.
* **Derecho a Reparar:** Apoyar marcas que permitan la reparación fácil.

<img src="https://images.unsplash.com/photo-1550009158-9ebf69173e03?auto=format&fit=crop&q=80&w=1000" alt="Reciclaje electrónico" class="img-estilo">

</section>

### Conclusión
La **Informática Ambiental** nos enseña que el ciclo de vida de un ordenador no termina cuando dejamos de usarlo. Como responsables de esta sección, Manuel y el equipo subrayamos que la gestión ética es el primer paso para una tecnología realmente "inteligente" para el planeta.

<div class="nav-botones">
  <a href="#" class="btn-nav volver">← Volver al Índice</a>
  <a href="#" class="btn-nav siguiente">Siguiente: Energía Verde →</a>
</div>
