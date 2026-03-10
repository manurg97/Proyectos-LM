---
layout: default
title: Análisis - Obsolescencia Programada
---

<style>
/* --- ANIMACIONES --- */
@keyframes fadeInUp {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}

.animado { animation: fadeInUp 0.8s ease-out forwards; }

/* --- HEADER PRINCIPAL --- */
.hero-obsolescencia {
  background: linear-gradient(135deg, #1b5e20 0%, #4caf50 100%);
  color: white;
  padding: 50px 20px;
  border-radius: 20px;
  text-align: center;
  box-shadow: 0 10px 20px rgba(0,0,0,0.1);
  margin-bottom: 30px;
}

/* --- CAJA DE TEXTO PRINCIPAL --- */
.bloque-texto {
  background: #f1f8e9;
  border-left: 6px solid #2e7d32;
  padding: 25px;
  border-radius: 8px;
  line-height: 1.8;
  font-size: 1.1em;
  margin: 20px 0;
}

/* --- TARJETAS DE IMPACTO --- */
.contenedor-tarjetas {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  margin-top: 30px;
}

.tarjeta-impacto {
  background: white;
  border: 1px solid #e0e0e0;
  padding: 20px;
  border-radius: 12px;
  transition: all 0.3s ease;
  text-align: center;
}

.tarjeta-impacto:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 15px rgba(0,0,0,0.1);
  border-color: #4caf50;
}

.tarjeta-impacto h3 {
  color: #2e7d32;
  margin-top: 10px;
}

/* --- BOTONES DE NAVEGACIÓN --- */
.footer-nav {
  display: flex;
  justify-content: space-between;
  margin-top: 50px;
  padding-top: 20px;
  border-top: 1px solid #eee;
}

.btn-nav {
  padding: 12px 25px;
  border-radius: 30px;
  text-decoration: none;
  font-weight: bold;
  transition: 0.3s;
}

.btn-home { background: #607d8b; color: white !important; }
.btn-next { background: #2e7d32; color: white !important; }

</style>

<div class="animado" markdown="1">

<header class="hero-obsolescencia">
  <h1 style="color: white; margin: 0; font-size: 2.8em;">🕰️ Obsolescencia Programada</h1>
  <p style="opacity: 0.9; font-size: 1.2em;">Comprendiendo el ciclo de vida de la tecnología moderna</p>
</header>

## 📖 ¿Qué es exactamente?

<div class="bloque-texto">
La <strong>obsolescencia programada</strong> es la planificación del final de la vida útil de un producto. Durante su diseño, los fabricantes establecen un tiempo aproximado tras el cual el producto dejará de funcionar o se volverá inservible. 
</div>

Esto ocurre frecuentemente por:
* 🛠️ **Falta de repuestos:** Piezas imposibles de encontrar.
* 🔋 **Componentes limitados:** Baterías o chips diseñados para degradarse.

---

## 💰 El Objetivo Económico

El motor principal de esta práctica es **aumentar las ventas**. Al obligar a los consumidores a sustituir los productos con mayor frecuencia, las empresas obtienen beneficios constantes incentivando la **compra continua**.



---

## ⚠️ Consecuencias Críticas

Esta estrategia no solo afecta a nuestro bolsillo, sino que daña gravemente al planeta:

<div class="contenedor-tarjetas">
  <div class="tarjeta-impacto">
