---
layout: default
title: Residuos Informáticos
---
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Residuos Informáticos - Manuel | Informática Ambiental</title>
    <style>
        :root {
            --bg-dark: #0f172a; 
            --sidebar-bg: #1e293b;
            --card-bg: #ffffff;
            --pablo: #38bdf8;
            --manuel: #4ade80;
            --sergio: #c084fc;
            --text-muted: #94a3b8;
        }
        body {
            font-family: 'Inter', -apple-system, sans-serif;
            margin: 0;
            display: flex;
            background-color: var(--bg-dark);
            color: #1e293b;
            min-height: 100vh;
        }

        /* --- NAVEGACIÓN IZQUIERDA (Fija) --- */
        nav {
            width: 260px;
            background-color: var(--sidebar-bg);
            position: fixed;
            left: 0;
            height: 100vh;
            padding: 40px 20px;
            display: flex;
            flex-direction: column;
            box-sizing: border-box;
            z-index: 10;
        }
        nav h1 {
            color: white;
            font-size: 1rem;
            text-transform: uppercase;
            letter-spacing: 2px;
            margin-bottom: 40px;
            text-align: center;
            border-bottom: 1px solid rgba(255,255,255,0.1);
            padding-bottom: 20px;
        }
        nav ul { list-style: none; padding: 0; margin: 0; }
        nav ul li { margin-bottom: 8px; }
        nav ul li a {
            color: var(--text-muted);
            text-decoration: none;
            display: block;
            padding: 12px 15px;
            border-radius: 10px;
            transition: 0.3s;
            font-weight: 600;
        }
        .nav-pablo:hover { color: var(--pablo) !important; background: rgba(56, 189, 248, 0.1); }
        .nav-manuel:hover { color: var(--manuel) !important; background: rgba(74, 222, 128, 0.1); }
        .nav-sergio:hover { color: var(--sergio) !important; background: rgba(192, 132, 252, 0.1); }

        /* --- PANEL DERECHO (Fijo) --- */
        aside {
            width: 200px;
            position: fixed;
            right: 0;
            height: 100vh;
            padding: 40px 20px;
            display: flex;
            flex-direction: column;
            gap: 15px;
            z-index: 10;
        }
        .author-card {
            background: rgba(30, 41, 59, 0.8);
            padding: 12px;
            border-radius: 12px;
            border-right: 4px solid transparent;
            text-align: right;
        }
        .author-name { font-weight: 700; font-size: 0.85rem; }
        .card-pablo { border-color: var(--pablo); color: var(--pablo); }
        .card-manuel { border-color: var(--manuel); color: var(--manuel); }
        .card-sergio { border-color: var(--sergio); color: var(--sergio); }

        /* --- CONTENIDO CENTRAL (ANCHO TOTAL) --- */
        main {
            margin-left: 260px; /* Espacio para nav */
            margin-right: 200px; /* Espacio para aside */
            flex-grow: 1;
            padding: 40px;
            display: flex;
            justify-content: center;
        }
        .content-card {
            background: var(--card-bg);
            width: 100%;
            max-width: 1000px; /* Aumentado para que no se vea encogido */
            padding: 60px;
            border-radius: 30px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.3);
        }

        /* --- ESTILOS INTERNOS --- */
        h1 { color: var(--bg-dark); font-size: 2.5rem; margin-bottom: 20px; border-bottom: 4px solid var(--manuel); display: inline-block; padding-bottom: 10px; }
        h2 { color: #334155; margin-top: 40px; font-size: 1.8rem; }
        p { line-height: 1.8; color: #475569; font-size: 1.15rem; }

        .grid-info {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
            margin: 30px 0;
        }
        .info-box {
            background: #f8fafc;
            padding: 25px;
            border-radius: 20px;
            border-left: 6px solid var(--manuel);
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
        }
        .info-box h3 { margin-top: 0; color: #0f172a; }

        table { width: 100%; border-collapse: collapse; margin: 30px 0; background: white; border-radius: 15px; overflow: hidden; }
        th { background: var(--sidebar-bg); color: white; padding: 15px; text-align: left; }
        td { padding: 15px; border-bottom: 1px solid #e2e8f0; color: #475569; }
        tr:hover { background: #f1f5f9; }

        .stats-banner {
            background: linear-gradient(135deg, #1e293b 0%, #0f172a 100%);
            color: white;
            padding: 40px;
            border-radius: 25px;
            margin: 40px 0;
            text-align: center;
        }
        .big-number { font-size: 3.5rem; font-weight: 800; color: var(--manuel); display: block; }

        footer {
            display: flex;
            justify-content: space-between;
            margin-top: 60px;
            padding-top: 30px;
            border-top: 2px solid #f1f5f9;
        }
        .btn {
            text-decoration: none;
            padding: 15px 30px;
            border-radius: 12px;
            font-weight: bold;
            transition: 0.3s;
        }
        .btn-prev { color: var(--pablo); background: rgba(56, 189, 248, 0.1); }
        .btn-next { color: white; background: var(--sergio); }
        .btn:hover { transform: translateY(-3px); filter: brightness(1.1); }

        @media (max-width: 1200px) {
            main { margin: 20px; padding: 0; }
            nav, aside { display: none; } /* En móviles se ocultan para dar espacio */
            .content-card { padding: 30px; }
        }
    </style>
</head>
<body>
    <nav>
        <h1>Eco-IT</h1>
        <ul>
            <li><a href="./index.html" style="color:white">Inicio</a></li>
            <li><a href="./Pablo_contaminacion.html" class="nav-pablo">1. Contaminación</a></li>
            <li><a href="./Manuel_residuos.html" class="nav-manuel" style="color: var(--manuel); background: rgba(74, 222, 128, 0.1);">2. Residuos RAEE</a></li>
            <li><a href="./Sergio_obsolescencia.html" class="nav-sergio">3. Obsolescencia</a></li>
            <li><a href="./Sergio_informatica.html" class="nav-sergio">4. Informática Verde</a></li>
        </ul>
    </nav>

    <main>
        <div class="content-card">
            <h1>Residuos Informáticos 🗑️</h1>
            <p>Los residuos electrónicos o <strong>e-waste</strong> representan el flujo de desechos domésticos que más rápido crece en el mundo. Son dispositivos que, tras cumplir su función, se convierten en una amenaza si no se gestionan con responsabilidad.</p>

            <div class="grid-info">
                <div class="info-box">
                    <h3>¿Qué desechamos?</h3>
                    <p>Desde smartphones y laptops hasta servidores, cables de red, baterías y periféricos obsoletos.</p>
                </div>
                <div class="info-box" style="border-left-color: var(--pablo);">
                    <h3>Causas Clave</h3>
                    <p>La alta demanda de novedades tecnológicas y la obsolescencia programada disparan la generación de basura.</p>
                </div>
            </div>

            <hr style="border:0; border-top: 1px solid #eee; margin: 40px 0;">

            <h2>Peligros Químicos en el Hardware</h2>
            <p>El interior de tus dispositivos es una mezcla compleja de materiales valiosos y sustancias altamente tóxicas.</p>
            
            <table>
                <thead>
                    <tr>
                        <th>Material</th>
                        <th>Riesgo para la Salud / Ambiente</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><strong>Plomo</strong></td>
                        <td>Neurotóxico que afecta el desarrollo cerebral y el suelo.</td>
                    </tr>
                    <tr>
                        <td><strong>Mercurio</strong></td>
                        <td>Bioacumulativo en el agua; daña riñones y sistema nervioso.</td>
                    </tr>
                    <tr>
                        <td><strong>Cadmio</strong></td>
                        <td>Altamente carcinógeno y persistente en la fauna local.</td>
                    </tr>
                    <tr>
                        <td><strong>Litio</strong></td>
                        <td>Extremadamente inflamable; riesgo de incendios químicos.</td>
                    </tr>
                </tbody>
            </table>

            <div class="stats-banner">
                <span class="big-number">50M+ Toneladas</span>
                <p>Es la cantidad de e-waste que generamos al año. Solo el <strong>20%</strong> se recicla mediante canales oficiales.</p>
            </div>

            <h2>Impacto Ambiental Directo</h2>
            <p>Cuando los RAEE terminan en vertederos comunes, los metales pesados se filtran (lixiviados) hacia las aguas subterráneas. La quema informal para extraer cobre libera <strong>dioxinas y furanos</strong>, gases letales para el aire y los pulmones de quienes viven cerca.</p>

            <h2>Soluciones de Economía Circular</h2>
            <div class="grid-info">
                <div class="info-box" style="border-left-color: var(--sergio);">
                    <h3>Reutilizar y Reparar</h3>
                    <p>Donar equipos funcionales o instalar sistemas ligeros (Linux) para alargar su vida útil.</p>
                </div>
                <div class="info-box">
                    <h3>Reciclaje Urbano</h3>
                    <p>Recuperar metales preciosos (Oro, Plata, Cobalto) para fabricar nuevos dispositivos sin minería.</p>
                </div>
            </div>

            <footer>
                <a href="./Pablo_contaminacion.html" class="btn btn-prev">← 1. Contaminación</a>
                <a href="./Sergio_obsolescencia.html" class="btn btn-next">3. Obsolescencia →</a>
            </footer>
        </div>
    </main>

    <aside>
        <div class="author-card card-pablo"><span class="author-name">Pablo</span></div>
        <div class="author-card card-manuel"><span class="author-name">Manuel</span></div>
        <div class="author-card card-sergio"><span class="author-name">Sergio</span></div>
    </aside>
</body>
</html>
