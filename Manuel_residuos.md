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
        /* --- BARRA LATERAL IZQUIERDA --- */
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
            border-right: 1px solid rgba(255,255,255,0.05);
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
            transition: all 0.3s ease;
            font-weight: 600;
            font-size: 0.95rem;
        }
        .nav-pablo:hover { color: var(--pablo) !important; background: rgba(56, 189, 248, 0.1); }
        .nav-manuel:hover { color: var(--manuel) !important; background: rgba(74, 222, 128, 0.1); }
        .nav-sergio:hover { color: var(--sergio) !important; background: rgba(192, 132, 252, 0.1); }
        .nav-ref:hover { color: white !important; background: rgba(255, 255, 255, 0.05); }

        /* --- PANEL DERECHO --- */
        aside {
            width: 240px;
            position: fixed;
            right: 0;
            height: 100vh;
            padding: 60px 25px;
            box-sizing: border-box;
            display: flex;
            flex-direction: column;
            gap: 20px;
        }
        .author-card {
            background: rgba(30, 41, 59, 0.5);
            padding: 15px;
            border-radius: 16px;
            border: 1px solid rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            display: flex;
            flex-direction: column;
            align-items: flex-end;
        }
        .author-name { font-weight: 700; font-size: 0.9rem; margin-bottom: 4px; }
        .card-pablo { border-right: 4px solid var(--pablo); color: var(--pablo); }
        .card-manuel { border-right: 4px solid var(--manuel); color: var(--manuel); }
        .card-sergio { border-right: 4px solid var(--sergio); color: var(--sergio); }

        /* --- CONTENIDO CENTRAL --- */
        main {
            margin-left: 260px;
            margin-right: 240px;
            flex-grow: 1;
            display: flex;
            justify-content: center;
            padding: 60px 40px;
        }
        .content-card {
            background: var(--card-bg);
            width: 100%;
            max-width: 750px;
            padding: 50px;
            border-radius: 28px;
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.5);
            min-height: 80vh;
        }
        .content-card h1 { color: var(--bg-dark); border-bottom: 3px solid #eee; padding-bottom: 10px; margin-top: 0;}
        .content-card h2 { color: #1e293b; margin-top: 30px; }
        .content-card p { line-height: 1.8; color: #475569; font-size: 1.1rem; }
        
        /* --- ESTILOS ESPECÍFICOS DE TARJETAS INTERNAS --- */
        .grid-visual {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin: 25px 0;
        }
        .card-premium {
            background: #ffffff;
            border: 1px solid #e2e8f0;
            border-radius: 16px;
            padding: 20px;
            box-shadow: 0 4px 6px -1px rgba(0,0,0,0.05);
            transition: all 0.3s ease;
        }
        .card-premium:hover { transform: translateY(-5px); box-shadow: 0 10px 15px -3px rgba(0,0,0,0.1); }
        .border-blue { border-top: 6px solid var(--pablo); }
        .border-green { border-top: 6px solid var(--manuel); }
        .border-purple { border-top: 6px solid var(--sergio); }
        .card-title { font-weight: 800; color: #0f172a; margin-bottom: 10px; display: flex; align-items: center; gap: 8px; }
        
        table { width: 100%; border-collapse: collapse; margin: 20px 0; font-size: 0.95rem; }
        th { background: #f8fafc; text-align: left; padding: 12px; border-bottom: 2px solid #e2e8f0; }
        td { padding: 12px; border-bottom: 1px solid #e2e8f0; color: #64748b; }

        @media (max-width: 1100px) {
            body { flex-direction: column; }
            nav, aside { width: 100%; height: auto; position: relative; }
            main { margin: 0; padding: 20px; }
            aside { flex-direction: row; justify-content: center; background: none; }
        }
    </style>
</head>
<body>
    <nav>
        <h1>Informática-Ambiental</h1>
        <ul>
            <li><a href="./index.html" class="nav-ref">Inicio</a></li>
            <li><a href="./Pablo_contaminacion.html" class="nav-pablo">Qué es la contaminación</a></li>
            <li><a href="./Manuel_residuos.html" class="nav-manuel">Residuos informáticos</a></li>
            <li><a href="./Sergio_obsolescencia.html" class="nav-sergio">Obsolescencia programada</a></li>
            <li><a href="./Sergio_informatica.html" class="nav-sergio">Informática Ecológica</a></li>
            <li><a href="./referencias.html" class="nav-ref">Referencias</a></li>
        </ul>
    </nav>

    <main>
        <div class="content-card">
            <h1 id="residuos-informaticos">🗑️ 2. Residuos Informáticos</h1>
            <p>
                Los residuos electrónicos, también llamados <strong>e-waste</strong>, son dispositivos que han llegado al final de su vida útil. 
                Representan uno de los mayores desafíos ambientales de nuestra era digital.
            </p>

            <div class="grid-visual">
                <div class="card-premium border-green">
                    <div class="card-title">🔌 ¿Qué incluyen?</div>
                    <p style="font-size: 0.95rem;">Laptops, smartphones, tablets, impresoras, baterías y componentes internos de hardware.</p>
                </div>
            </div>

            <hr style="border: 0; border-top: 1px solid #eee; margin: 40px 0;">

            <h2>2.1 Causas de la generación</h2>
            <div class="grid-visual">
                <div class="card-premium border-blue">
                    <div class="card-title">🚀 Alta demanda</div>
                    <p style="font-size: 0.9rem;">Dependencia absoluta de la tecnología para trabajo y ocio, lo que acelera los ciclos de compra.</p>
                </div>
                <div class="card-premium border-purple">
                    <div class="card-title">⏳ Obsolescencia</div>
                    <p style="font-size: 0.9rem;">Diseño intencionado para fallar o quedar obsoleto (falta de actualizaciones o piezas).</p>
                </div>
            </div>

            <h2>2.2 Componentes Peligrosos</h2>
            
            <table>
                <thead>
                    <tr>
                        <th>Componente</th>
                        <th>Riesgo Ambiental/Salud</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><strong>Plomo</strong></td>
                        <td>Contamina el suelo y daña el sistema nervioso.</td>
                    </tr>
                    <tr>
                        <td><strong>Mercurio</strong></td>
                        <td>Altamente tóxico en agua; afecta a los riñones.</td>
                    </tr>
                    <tr>
                        <td><strong>Cadmio</strong></td>
                        <td>Contaminante carcinógeno persistente.</td>
                    </tr>
                    <tr>
                        <td><strong>Litio</strong></td>
                        <td>Riesgo de incendio y explosión en vertederos.</td>
                    </tr>
                </tbody>
            </table>

            <h2>2.3 Impactos Ambientales</h2>
            <p>La gestión deficiente provoca la filtración de <strong>metales pesados</strong> en cultivos y fuentes de agua. Además, la quema informal de plásticos libera dioxinas tóxicas al aire, afectando la salud respiratoria de comunidades enteras.</p>

            <div style="background: #f8fafc; border-left: 5px solid var(--manuel); padding: 20px; border-radius: 0 15px 15px 0; margin: 30px 0;">
                <h3 style="margin-top:0; font-size:1rem; color:var(--bg-dark);">📈 Estadísticas Globales</h3>
                <p style="font-size:0.95rem; margin-bottom:0;">
                    Se generan más de <strong>50 millones de toneladas</strong> al año. Lamentablemente, según la ONU, solo el <strong>20%</strong> se recicla correctamente bajo estándares de seguridad.
                </p>
            </div>

            <h2>2.4 Soluciones: Economía Circular</h2>
            <ul style="color: #475569; line-height: 2;">
                <li><strong>Reutilización:</strong> Donar y reparar antes de desechar.</li>
                <li><strong>Reciclaje Certificado:</strong> Puntos oficiales de recolección de RAEE.</li>
                <li><strong>Derecho a Reparar:</strong> Exigir productos modulares y duraderos.</li>
            </ul>

            <div style="display: flex; justify-content: space-between; margin-top: 50px; padding-top: 20px; border-top: 1px solid #eee;">
                <a href="./Pablo_contaminacion.html" style="text-decoration:none; color:var(--pablo); font-weight:bold;">🏠 Volver a Contaminación</a>
                <a href="./Sergio_obsolescencia.html" style="text-decoration:none; color:var(--sergio); font-weight:bold;">Obsolescencia Programada ➜</a>
            </div>
        </div>
    </main>

    <aside>
        <div class="author-card card-pablo"><span class="author-name">Pablo</span></div>
        <div class="author-card card-manuel"><span class="author-name">Manuel</span></div>
        <div class="author-card card-sergio"><span class="author-name">Sergio</span></div>
    </aside>
</body>
</html>
