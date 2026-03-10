<style>
  /* --- CONTENEDOR DE TARJETAS --- */
  .grid-visual {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    gap: 25px;
    margin: 30px 0;
  }

  /* --- ESTILO DE LAS TARJETAS --- */
  .card-premium {
    background: #ffffff;
    border: 1px solid #e1e4e8;
    border-radius: 15px;
    padding: 25px;
    box-shadow: 0 10px 20px rgba(0,0,0,0.05);
    transition: all 0.3s ease;
  }

  .card-premium:hover {
    transform: translateY(-8px);
    box-shadow: 0 15px 30px rgba(0,0,0,0.12);
  }

  .border-green { border-top: 8px solid #2ea44f; }
  .border-blue { border-top: 8px solid #0366d6; }
  .border-orange { border-top: 8px solid #f66a0a; }
  .border-purple { border-top: 8px solid #6f42c1; }

  /* --- ESTILO DE LA TABLA --- */
  .tabla-bonita {
    width: 100%;
    border-collapse: collapse;
    margin: 25px 0;
    font-size: 0.95em;
    border-radius: 10px;
    overflow: hidden; 
    box-shadow: 0 4px 15px rgba(0,0,0,0.05);
  }

  .tabla-bonita thead tr {
    background-color: #2ea44f;
    color: #ffffff;
    text-align: left;
    font-weight: bold;
  }

  .tabla-bonita th, .tabla-bonita td {
    padding: 15px 20px;
    border-bottom: 1px solid #edf2f7;
  }

  .tabla-bonita tbody tr:nth-of-type(even) {
    background-color: #f8f9fa;
  }

  .tabla-bonita tbody tr:last-of-type {
    border-bottom: 3px solid #2ea44f;
  }

  .card-title {
    font-size: 1.25em;
    font-weight: bold;
    color: #1a1a1a;
    margin-bottom: 12px;
    display: flex;
    align-items: center;
    gap: 10px;
  }
  
  /* --- ESTILO DE LA IMAGEN DE LA CARICATURA --- */
  .img-cartoon {
    max-width: 100%;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.15);
    margin: 30px auto;
    display: block;
  }
</style>

<div markdown="1">

<div style="
  text-align: center;
  padding: 20px;
  border-radius: 10px;
  background: linear-gradient(90deg, #2ea44f, #6f42c1);
  color: white;
  margin: 20px auto;
">
  <h1 style="margin: 0; font-size: 2.2em;">Obsolescencia Programada</h1>
</div>
> **"Un producto que no se desgasta es una tragedia para los negocios."**

---

## 1. ¿Qué es exactamente?

<div class="card-premium border-green">
  <div class="card-title">Definición Técnica</div>
  <p class="card-text">
    Es el diseño de un producto con una <strong>vida útil limitada artificialmente</strong>. Los fabricantes calculan el momento exacto en el que el dispositivo debe fallar o volverse incompatible para forzar al consumidor a comprar la siguiente versión. No es un error de ingeniería, es una decisión de negocio.
  </p>
</div>


---

## 2. Un poco de historia: El Cartel Phoebus

En 1924, los principales fabricantes de bombillas del mundo formaron el **Cartel Phoebus**. Su objetivo: reducir la duración de las bombillas de **2.500 horas a solo 1.000**. Este fue el nacimiento oficial de la obsolescencia programada para asegurar ventas recurrentes.

<div class="tarjeta-sergio" style="text-align: center; border: none; box-shadow: none;">
  <img src="obsolescencia.jpg" class="img-cartoon" alt="Documental sobre obsolescencia programada">
  <p style="font-style: italic; color: #666; font-size: 0.9em; margin-top: 10px;">
    <strong>Cartel Phoebus.</strong>
  </p>
</div>

---

## 3. Tipos y Funcionamiento

<div class="grid-visual">

  <div class="card-premium border-blue">
    <div class="card-title">Obsolescencia de Software</div>
    <p>Actualizaciones que vuelven lentos los dispositivos o apps que dejan de ser compatibles con hardware que aún funciona perfectamente.</p>
  </div>

  <div class="card-premium border-orange">
    <div class="card-title">Obsolescencia Técnica</div>
    <p>Uso de materiales frágiles o componentes (como condensadores) diseñados para fallar tras un número determinado de ciclos de uso.</p>
  </div>

  <div class="card-premium border-purple">
    <div class="card-title">Barreras de Reparación</div>
    <p>Piezas pegadas y falta de repuestos oficiales. El objetivo es que reparar sea <strong>más caro</strong> que comprar un producto nuevo.</p>
  </div>

</div>

<div class="tarjeta-sergio" style="text-align: center; border: none; box-shadow: none;">
  <img src="4.webp" class="img-cartoon" alt="Ilustración del Derecho a Reparar frente al Consumo Forzado">
  <p style="font-style: italic; color: #666; font-size: 0.9em; margin-top: 10px;"><strong>Consumo más barato que arreglar.</strong></p>
</div>

---

## 4. El Impacto en nuestro Planeta

<div class="tarjeta-sergio" style="text-align: center; border: none; box-shadow: none;">
  <img src="consecuencias-1.png" class="img-cartoon" alt="Consecuencias de la obsolescencia programada">
  <p style="font-style: italic; color: #666; font-size: 0.9em; margin-top: 10px;">
    <strong>Consecuencias de la obsolescencia programada: producción, consumo, gastos y residuos.</strong>
  </p>
</div>



Cada vez que renovamos un dispositivo prematuramente, el medio ambiente sufre las consecuencias:

<table class="tabla-bonita">
  <thead>
    <tr>
      <th> Recurso</th>
      <th> Impacto de la Renovación</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Minerales Raros</strong></td>
      <td>Extracción intensiva de litio, coltán y tierras raras en zonas críticas.</td>
    </tr>
    <tr>
      <td><strong>Energía</strong></td>
      <td>Fabricar un móvil consume el 80% de toda la energía que usará en su vida.</td>
    </tr>
    <tr>
      <td><strong>Residuos</strong></td>
      <td>Millones de toneladas de metales pesados contaminan suelos y aguas anualmente.</td>
    </tr>
  </tbody>
</table>


---

## 5. ¿Hay soluciones?

Existen movimientos como el **"Right to Repair"** (Derecho a Reparar) y empresas que diseñan hardware modular para combatir esta tendencia. La informática ecológica es la clave para un futuro sostenible.

<div class="tarjeta-sergio" style="text-align: center; border: none; box-shadow: none;">
  <img src="derecho_a_reparar.jpg" class="img-cartoon" alt="Reparación de un smartphone">
  <p style="font-style: italic; color: #666; font-size: 0.9em; margin-top: 10px;">
    <strong>Derecho a reparar.</strong>
  </p>
</div>

---


<div style="display: flex; justify-content: space-between; margin-top: 40px; padding-top: 20px; border-top: 1px solid #eee;">
  <a href="index.html" style="text-decoration:none; color:#2ea44f; font-weight:bold;">🏠 Volver al Inicio</a>
  <a href="Sergio_informatica.html" style="text-decoration:none; color:#2ea44f; font-weight:bold;">Informática Ecológica ➜</a>
</div>

</div>
