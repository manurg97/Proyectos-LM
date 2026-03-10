<style>
  /* --- ESTILO GENERAL --- */
  body {
    font-family: "Segoe UI", Arial, sans-serif;
    line-height: 1.7;
    color: #222;
  }

  /* --- NUEVO ESTILO DE TARJETAS --- */
  .eco-card {
    background: #ffffff;
    border-radius: 14px;
    padding: 25px;
    border: 1px solid #dfe3e8;
    box-shadow: 0 6px 18px rgba(0,0,0,0.06);
    transition: 0.3s ease;
  }

  .eco-card:hover {
    transform: translateY(-6px);
    box-shadow: 0 10px 25px rgba(0,0,0,0.12);
  }

  .eco-green { border-left: 8px solid #28a745; }
  .eco-blue { border-left: 8px solid #007bff; }
  .eco-yellow { border-left: 8px solid #f0ad4e; }
  .eco-red { border-left: 8px solid #d9534f; }

  .eco-title {
    font-size: 1.3em;
    font-weight: bold;
    margin-bottom: 12px;
  }

  /* --- NUEVO ESTILO DE TABLAS --- */
  .tabla-eco {
    width: 100%;
    border-collapse: collapse;
    margin: 25px 0;
    font-size: 1em;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
  }

  .tabla-eco thead tr {
    background: #28a745;
    color: white;
    text-align: left;
  }

  .tabla-eco th, .tabla-eco td {
    padding: 14px 18px;
    border-bottom: 1px solid #e9ecef;
  }

  .tabla-eco tbody tr:nth-child(even) {
    background: #f8f9fa;
  }

  /* --- IMÁGENES --- */
  .eco-img {
    max-width: 100%;
    border-radius: 12px;
    margin: 25px auto;
    display: block;
    box-shadow: 0 5px 15px rgba(0,0,0,0.15);
  }

  /* --- BOTÓN VOLVER AL INICIO --- */
  .btn-inicio {
    display: inline-block;
    padding: 12px 25px;
    background: #28a745;
    color: white;
    text-decoration: none;
    font-weight: bold;
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.15);
    transition: 0.3s ease;
  }

  .btn-inicio:hover {
    background: #218838;
  }

</style>

<div markdown="1">

<!-- TÍTULO PRINCIPAL -->
<div style="
  text-align: center;
  padding: 25px;
  border-radius: 12px;
  background: linear-gradient(90deg, #28a745, #007bff);
  color: white;
  margin: 20px auto;
">
  <h1 style="margin: 0; font-size: 2.3em;">Informática Ecológica</h1>
</div>

---

## 1. ¿Qué es la informática ecológica?

<div class="eco-card eco-green">
  <div class="eco-title">Definición General</div>
  <p>
    La informática ecológica consiste en diseñar, fabricar, utilizar y desechar dispositivos tecnológicos de forma que se reduzca su impacto ambiental. 
    Su objetivo es disminuir el consumo energético, reducir emisiones, usar materiales sostenibles y minimizar los residuos electrónicos.
  </p>
</div>

<div class="eco-card eco-blue" style="margin-top: 20px;">
  <div class="eco-title">Importancia Actual</div>
  <p>
    El sector TIC genera entre el 1,8 % y el 3,9 % de las emisiones globales de gases de efecto invernadero. 
    Por ello, adoptar prácticas ecológicas es fundamental para combatir el cambio climático.
  </p>
</div>

---

## 2. Qué pueden hacer los fabricantes

<div class="eco-card eco-yellow">
  <div class="eco-title">Medidas principales</div>
  <p>Los fabricantes pueden reducir el impacto ambiental desde el diseño hasta la fabricación:</p>
</div>

<table class="tabla-eco">
  <thead>
    <tr>
      <th>Área</th>
      <th>Acciones ecológicas</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Diseño eficiente</td>
      <td>Reducir el consumo energético y el calor generado por los dispositivos.</td>
    </tr>
    <tr>
      <td>Arquitecturas avanzadas</td>
      <td>Uso de CPU + GPU para mejorar la eficiencia, como el superordenador AiMOS.</td>
    </tr>
    <tr>
      <td>Materiales sostenibles</td>
      <td>Evitar sustancias tóxicas y reducir residuos en la fabricación.</td>
    </tr>
    <tr>
      <td>Durabilidad</td>
      <td>Aumentar la vida útil y evitar la obsolescencia programada.</td>
    </tr>
    <tr>
      <td>Reutilización y reciclaje</td>
      <td>Facilitar la reparación y el reciclaje de componentes.</td>
    </tr>
  </tbody>
</table>

---

## 3. Qué pueden hacer las organizaciones

<div class="eco-card eco-blue">
  <div class="eco-title">Acciones recomendadas</div>
  <p>Las empresas y gobiernos pueden reducir enormemente el impacto ambiental de la tecnología.</p>
</div>

<table class="tabla-eco">
  <thead>
    <tr>
      <th>Área</th>
      <th>Acción sostenible</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Centros de datos</td>
      <td>Implementar pasillos fríos y calientes para optimizar la refrigeración.</td>
    </tr>
    <tr>
      <td>Automatización</td>
      <td>Usar sistemas que regulen temperatura y ventilación.</td>
    </tr>
    <tr>
      <td>Gestión energética</td>
      <td>Apagar equipos cuando no se usan y programar tareas.</td>
    </tr>
    <tr>
      <td>Ahorro económico</td>
      <td>La eficiencia energética reduce costes a largo plazo.</td>
    </tr>
  </tbody>
</table>

---

## 4. Qué podemos hacer nosotros

<div class="eco-card eco-green">
  <div class="eco-title">Acciones individuales</div>
  <p>Los usuarios también podemos contribuir con pequeños gestos diarios.</p>
</div>

<table class="tabla-eco">
  <thead>
    <tr>
      <th>Acción</th>
      <th>Beneficio</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Usar hibernación o reposo</td>
      <td>Reduce el consumo energético diario.</td>
    </tr>
    <tr>
      <td>Ajustar brillo y energía</td>
      <td>Disminuye el gasto eléctrico.</td>
    </tr>
    <tr>
      <td>Apagar dispositivos</td>
      <td>Ahorro significativo a largo plazo.</td>
    </tr>
    <tr>
      <td>Reutilizar cartuchos</td>
      <td>Menos residuos generados.</td>
    </tr>
    <tr>
      <td>Comprar reacondicionados</td>
      <td>Reduce la demanda de nuevos dispositivos.</td>
    </tr>
    <tr>
      <td>Reciclar correctamente</td>
      <td>Evita contaminación y mejora la seguridad.</td>
    </tr>
  </tbody>
</table>

---

## 5. Conclusión

<div class="eco-card eco-red">
  <p>
    La informática ecológica es esencial para reducir el impacto ambiental del sector tecnológico. 
    Fabricantes, organizaciones y usuarios debemos colaborar para disminuir emisiones, ahorrar energía y fomentar la reutilización y el reciclaje.
  </p>
</div>

---

<div style="
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: 40px;
  padding-top: 20px;
  border-top: 1px solid #eee;
">

  <!-- Izquierda -->
  <a href="index.html" 
     style="text-decoration:none; color:#2ea44f; font-weight:bold; font-size:1.1em;">
     🏠 Volver al Inicio
  </a>

  <!-- Derecha -->
  <a href="referencias.html" 
     style="text-decoration:none; color:#2ea44f; font-weight:bold; font-size:1.1em;">
     Referencias ➔
  </a>

</div>

 
