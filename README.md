<!doctype html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="description" content="Realidades Invisibles: prevención y conciencia sobre el consumo problemático de drogas.">
<title>Realidades Invisibles · Proyecto Escolar</title>
<style>
:root{--bg:#090b0f;--panel:#121720;--panel2:#181f2a;--text:#f4f6fa;--muted:#a7b0bf;--red:#ed3948;--line:#293241}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;background:#090b0f;color:#f4f6fa;font:16px/1.55 system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif}
a{color:inherit;text-decoration:none}
.wrap{width:min(1120px,92%);margin:auto}
header{position:sticky;top:0;z-index:10;background:rgba(9,11,15,.95);border-bottom:1px solid var(--line)}
nav{height:72px;display:flex;align-items:center;justify-content:space-between;gap:20px}
.brand{font-weight:900;letter-spacing:.08em}
.brand span{color:var(--red)}
.navlinks{display:flex;gap:18px;color:var(--muted);font-size:.9rem}
.navlinks a:hover{color:#fff}
.btn{display:inline-flex;align-items:center;justify-content:center;border:0;border-radius:9px;padding:12px 18px;background:var(--red);color:#fff;font-weight:750;cursor:pointer}
.btn:hover{filter:brightness(1.1)}
.btn.secondary{background:#252e3b;border:1px solid #3a4657}

.hero{padding:62px 0;background:radial-gradient(ellipse at 80% 20%,#4b1820 0,transparent 40%),linear-gradient(130deg,#10151d,#090b0f 70%);border-bottom:1px solid var(--line)}
.hero-content{text-align:center;max-width:850px;margin:0 auto}
.eyebrow{color:#ff7781;font-weight:800;font-size:.78rem;letter-spacing:.16em;text-transform:uppercase}
.hero h1{font-size:clamp(2.5rem,6vw,4.8rem);line-height:.98;margin:18px 0}
.hero h1 em{font-style:normal;color:var(--red)}
.hero p{color:var(--muted);font-size:1.1rem;margin:0 auto 26px;max-width:650px}
.actions{display:flex;gap:12px;flex-wrap:wrap;justify-content:center}

.section{padding:62px 0}
.section h2{font-size:clamp(1.7rem,4vw,2.5rem);margin:0 0 8px}
.lead{color:var(--muted);margin:0 0 28px}
.grid-2{display:grid;grid-template-columns:repeat(2,1fr);gap:22px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:22px}
.card .q-num{display:inline-block;color:var(--red);font-weight:900;font-size:.82rem;letter-spacing:.1em;text-transform:uppercase;margin-bottom:6px}
.card p{margin:0;color:var(--muted)}

.theory-container{display:grid;grid-template-columns:1fr;gap:24px;margin-top:20px}
.theory-box{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:26px}
.theory-box h3{color:var(--red);margin-top:0;font-size:1.25rem}
.theory-box p,.theory-box li{color:var(--muted);line-height:1.6}
.theory-box ul{margin:10px 0 0 20px;padding:0}

.table-wrap{width:100%;overflow-x:auto;margin-top:20px}
table.help-table{width:100%;border-collapse:collapse;background:var(--panel);border:1px solid var(--line);border-radius:10px;overflow:hidden}
table.help-table th,table.help-table td{padding:14px 16px;text-align:left;border-bottom:1px solid var(--line);font-size:.92rem}
table.help-table th{background:var(--panel2);color:#fff;font-weight:700}
table.help-table td{color:var(--muted)}
table.help-table tr:last-child td{border-bottom:0}

.law-box{background:linear-gradient(145deg,#151a24,#0e1219);border:1px solid #3a4657;border-left:4px solid var(--red);border-radius:12px;padding:30px;margin-top:25px}
.law-box h3{color:#fff;margin-top:0}
.law-box h4{color:var(--red);margin:20px 0 8px;font-size:1.05rem}

.q-index{background:var(--panel2);border:1px solid var(--line);border-radius:14px;padding:18px 22px;margin-bottom:28px}
.q-index-title{font-size:.82rem;font-weight:800;text-transform:uppercase;letter-spacing:.1em;color:var(--muted);margin:0 0 12px}
.q-index-list{display:flex;flex-wrap:wrap;gap:10px}
.q-index-list a{background:var(--panel);border:1px solid var(--line);padding:8px 14px;border-radius:8px;font-size:.9rem;font-weight:600}
.q-index-list a:hover{border-color:var(--red);color:#fff;background:#1e161d}
.q-index-list a span{color:var(--red);font-weight:900;margin-right:6px}
.q-card{scroll-margin-top:92px}

.unified-video-slot{margin-top:36px;background:var(--panel);border:2px solid var(--red);border-radius:16px;padding:28px;box-shadow:0 14px 34px rgba(237,57,72,.12)}
.unified-video-slot h2.yt-big-title{margin:0 0 10px;color:#fff;font-size:clamp(1.6rem,3.5vw,2.4rem);line-height:1.15;letter-spacing:-.01em}
.unified-video-slot h2.yt-big-title span{color:var(--red)}
.unified-video-slot p.yt-subtitle{margin:0 0 18px;color:var(--muted);font-size:1rem}
.youtube-embed{position:relative;width:100%;aspect-ratio:16/9;background:#000;border-radius:12px;overflow:hidden;border:1px solid var(--line)}
.youtube-embed iframe{position:absolute;top:0;left:0;width:100%;height:100%;border:0}

footer{border-top:1px solid var(--line);padding:28px 0;color:var(--muted);font-size:.88rem;background:var(--panel2)}
.foot{display:flex;justify-content:space-between;gap:20px;flex-wrap:wrap;text-align:center}
@media(max-width:760px){.navlinks{display:none}.grid-2{grid-template-columns:1fr}.hero{padding:40px 0}.section{padding:46px 0}.foot{flex-direction:column;align-items:center}}
</style>
</head>
<body>

<header><div class="wrap"><nav>
<a class="brand" href="#">REALIDADES <span>INVISIBLES</span></a>
<div class="navlinks">
  <a href="#preguntas">Preguntas &amp; Video</a>
  <a href="#teoria">Teoría</a>
  <a href="#ley">Proyecto de Ley</a>
</div>
<a class="btn" href="#video-youtube">Ver video</a>
</nav></div></header>

<main>
<section class="hero"><div class="wrap"><div class="hero-content">
  <div class="eyebrow">Trabajo Práctico Grupal · Secundario de Adultos</div>
  <h1>REALIDADES<br><em>INVISIBLES.</em></h1>
  <p>Una problemática social y de salud pública. Encuesta comunitaria, marco teórico y propuesta de Proyecto de Ley.</p>
  <div class="actions">
    <a class="btn" href="#video-youtube">▶ Ver video de preguntas</a>
    <a class="btn secondary" href="#teoria">Leer marco teórico</a>
  </div>
</div></div></section>

<!-- 1. PREGUNTAS Y VIDEO DE YOUTUBE -->
<section class="section" id="preguntas" style="background:var(--panel2);border-bottom:1px solid var(--line);"><div class="wrap">
<h2>Preguntas para encontrar una solución</h2>
<p class="lead">Elegí un eje en el índice para ir directo a la pregunta. Abajo encontrás el video completo con las entrevistas en YouTube.</p>

<nav class="q-index" aria-label="Índice de preguntas">
  <div class="q-index-title">Índice rápido de preguntas</div>
  <div class="q-index-list">
    <a href="#pregunta-1"><span>01</span> Prevención en la escuela</a>
    <a href="#pregunta-2"><span>02</span> Diálogo en la familia</a>
    <a href="#pregunta-3"><span>03</span> Estado y salud mental</a>
    <a href="#pregunta-4"><span>04</span> Prejuicios y salud</a>
  </div>
</nav>

<div class="grid-2">
  <article class="card q-card" id="pregunta-1">
    <div>
      <span class="q-num">Pregunta 01 · Escuela</span>
      <p>¿Qué charlas o información creés que faltan en la escuela para que los jóvenes entiendan los riesgos de empezar a consumir a una edad temprana?</p>
    </div>
  </article>

  <article class="card q-card" id="pregunta-2">
    <div>
      <span class="q-num">Pregunta 02 · Familia</span>
      <p>¿Qué harías en tu casa o familia para mejorar el diálogo y evitar que los chicos o adolescentes busquen refugio en las sustancias?</p>
    </div>
  </article>

  <article class="card q-card" id="pregunta-3">
    <div>
      <span class="q-num">Pregunta 03 · Estado y comunidad</span>
      <p>Sabiendo que el Estado muchas veces no invierte ni cuida lo suficiente la salud mental, ¿qué le exigirías al gobierno o qué solución propondrías en tu comunidad?</p>
    </div>
  </article>

  <article class="card q-card" id="pregunta-4">
    <div>
      <span class="q-num">Pregunta 04 · Prejuicios y salud</span>
      <p>Muchas veces se juzga a las personas adictas creyendo que es "falta de voluntad", ¿qué harías para cambiar esos prejuicios y lograr que se vea como un problema de salud que necesita ayuda?</p>
    </div>
  </article>
</div>

<!-- VIDEO FIJO DE YOUTUBE -->
<div class="unified-video-slot" id="video-youtube">
  <h2 class="yt-big-title">VIDEO DE LAS ENTREVISTAS <span>EN YOUTUBE</span></h2>
  <p class="yt-subtitle">Mirá las respuestas y reflexiones de la comunidad frente a las cuatro preguntas del proyecto.</p>

  <div class="youtube-embed">
    <iframe src="https://www.youtube.com/embed/aaL339CLyVQ" title="Video de las entrevistas en YouTube" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</div>

</div></section>

<!-- 2. MARCO TEÓRICO -->
<section class="section" id="teoria"><div class="wrap">
<h2>Marco Teórico y Conceptual</h2>
<p class="lead">Comprender la problemática desde una perspectiva social, humana y de salud pública, evitando prejuicios y estigmas.</p>

<div class="theory-container">
  <div class="theory-box">
    <h3>1. ¿Qué son las drogas y cómo actúan en el organismo?</h3>
    <p>Son sustancias químicas o naturales que, al ingresar al cuerpo por diversas vías (inhalada, absorbida, inyectada, oral o fumada), alteran el funcionamiento normal del sistema nervioso central y del cerebro.</p>
    <p><strong>Clasificación según su marco legal y uso clínico:</strong></p>
    <ul>
      <li><strong>Drogas legales:</strong> Alcohol, tabaco y cafeína. Permitidas por ley pero de alto riesgo de dependencia con el uso abusivo o prolongado.</li>
      <li><strong>Drogas ilegales:</strong> Estimulantes ilícitos, opioides no autorizados y compuestos alucinógenos prohibidos por su alto poder adictivo.</li>
      <li><strong>Fármacos de prescripción:</strong> Medicamentos controlados (ansiolíticos, analgésicos opioides) cuyo uso sin supervisión médica constituye abuso de sustancias.</li>
    </ul>
    <p style="margin-top:14px;"><strong>Acción en el organismo:</strong> Modifican la comunicación neuronal y la liberación de neurotransmisores como la dopamina (estimulantes, depresores o alucinógenos).</p>
  </div>

  <div class="theory-box">
    <h3>2. Factores de riesgo de la drogadicción</h3>
    <p>No responde a una sola causa ni a una falta de fuerza de voluntad, sino a múltiples factores interactivos:</p>
    <ul>
      <li><strong>Biológicos y genéticos:</strong> Predisposición familiar y edad de inicio temprana (durante la infancia o adolescencia con cerebro en desarrollo).</li>
      <li><strong>Psicológicos:</strong> Trastornos de salud mental (depresión, ansiedad, TDAH) y dificultad en la regulación emocional o tolerancia a la frustración.</li>
      <li><strong>Sociales y ambientales:</strong> Entornos familiares disfuncionales, presión de grupo, normalización del consumo y accesibilidad a las sustancias.</li>
    </ul>
  </div>

  <div class="theory-box">
    <h3>3. Síntomas y signos de la adicción</h3>
    <ul>
      <li>Compulsión por el consumo y pérdida de control sobre la cantidad o frecuencia.</li>
      <li>Desarrollo de tolerancia (necesidad de mayor dosis) y síndrome de abstinencia al interrumpir el uso.</li>
      <li>Preocupación excesiva, abandono de responsabilidades escolares/laborales/familiares y aislamiento social.</li>
      <li>Conductas de riesgo y persistencia a pesar del daño físico, psicológico o económico evidente.</li>
    </ul>
  </div>

  <div class="theory-box">
    <h3>4. Consecuencias en la salud física, mental y cognitiva</h3>
    <ul>
      <li><strong>Salud física:</strong> Alteración neuronal crónica, hipertensión, arritmias, infartos, daño hepático severo (cirrosis) e infecciones graves por uso compartido de jeringas (VIH, Hepatitis B y C).</li>
      <li><strong>Salud mental y cognitiva:</strong> Cuadros depresivos, ataques de pánico, psicosis, deterioro cognitivo, pérdida de memoria, desregulación emocional y anhedonia (incapacidad para sentir placer).</li>
    </ul>
  </div>

  <div class="theory-box">
    <h3>5. Tratamiento multidisciplinario</h3>
    <p>Requiere un abordaje personalizado que incluye desintoxicación médica supervisada, intervención farmacológica (para patología dual), psicoterapia especializada (TCC), grupos de apoyo, reinserción social y acompañamiento terapéutico cotidiano.</p>
  </div>

  <div class="theory-box">
    <h3>6. Lugares donde se puede pedir ayuda</h3>
    <div class="table-wrap">
      <table class="help-table">
        <thead>
          <tr><th>Institución / Servicio</th><th>Modalidad de atención y contacto</th></tr>
        </thead>
        <tbody>
          <tr><td><strong>SEDRONAR (Línea 141)</strong></td><td>Disponible las 24 horas para orientación y contención gratuita a nivel nacional.</td></tr>
          <tr><td><strong>Línea 108, Opción 3</strong></td><td>Atención y orientación en adicciones en la Ciudad de Buenos Aires.</td></tr>
          <tr><td><strong>Hospital Fernández</strong></td><td>Atención en su División de Toxicología (las 24 hs).</td></tr>
          <tr><td><strong>Hospitales Públicos</strong></td><td>Cuentan con servicios de salud mental y evaluación profesional.</td></tr>
          <tr><td><strong>Centro de Salud Mental Municipal (Ituzaingó)</strong></td><td>Dirección: Bernal 1508, esq. La Piedad. Atención psicológica y consumos problemáticos. Tel: 2120-1941.</td></tr>
          <tr><td><strong>Centro de Salud Mental (Ituzaingó)</strong></td><td>Dirección: Mansilla 1483.</td></tr>
        </tbody>
      </table>
    </div>
  </div>
</div>
</div></section>

<!-- 3. PROYECTO DE LEY -->
<section class="section" id="ley" style="background:var(--panel2);border-top:1px solid var(--line);"><div class="wrap">
<h2>Propuesta Legislativa Grupal</h2>
<p class="lead">Nuestra iniciativa para debatir y transformar la realidad desde las leyes y la comunidad.</p>

<div class="law-box">
  <h3>Proyecto de Ley: "Prevención integral, acompañamiento temprano y protección judicial frente a los consumos problemáticos"</h3>
  
  <h4>Fundamentación (Estudiantes de Secundario de Adultos):</h4>
  <p>Como estudiantes de un secundario de adultos, observamos con profunda preocupación cómo el consumo problemático avanza cada día más rápido y a edades más tempranas, destruyendo la salud física y mental y la paz de las familias. La drogadicción no es una simple "falta de voluntad", sino una problemática compleja. Por eso exigimos al Estado atacar el problema desde dos frentes: prevención real y cercana (en escuelas, hogares y redes sociales) y una justicia firme que corte la venta y proteja a los menores.</p>

  <h4>Texto del Proyecto</h4>
  <p><strong>Artículo 1° — Objeto de la Ley:</strong> Garantizar la protección integral de niños, niñas y adolescentes frente al consumo problemático de sustancias mediante políticas obligatorias de prevención temprana, acompañamiento, difusión masiva y endurecimiento de procesos judiciales contra el narcotráfico a baja y gran escala.</p>
  
  <p><strong>Artículo 2° — Prevención y Acompañamiento Obligatorio:</strong> Establecer talleres permanentes de prevención y educación emocional en escuelas primarias y secundarias. Contar con equipos interdisciplinarios (psicólogos y trabajadores sociales) para detectar señales de alerta sin estigmas.</p>

  <p><strong>Artículo 3° — Campañas de Información:</strong> Garantizar campañas obligatorias de alto impacto en redes sociales, medios de comunicación, cartelería en espacios públicos y guías enviadas a los hogares difundiendo los riesgos y canales gratuitos como la Línea 141 de SEDRONAR.</p>

  <p><strong>Artículo 4° — Espacios Comunitarios de Salud Mental:</strong> Creación y financiamiento efectivo de centros barriales de escucha, contención y actividades recreativas y deportivas gratuitas sin listas de espera.</p>

  <p><strong>Artículo 5° — Acción Judicial Rápida y Castigo a la Venta:</strong> Penas efectivas e inexcarcelables para quienes vendan o distribuyan sustancias ilícitas a menos de 500 metros de escuelas, clubes o plazas, y creación de fiscalías especializadas para denuncias anónimas de "búnkeres".</p>

  <p><strong>Artículo 6° — De forma:</strong> Comuníquese al Poder Ejecutivo para su reglamentación y asignación presupuestaria.</p>
</div>
</div></section>

</main>

<footer><div class="wrap foot">
  <span>© <span id="year"></span> Realidades Invisibles · Todos los derechos reservados a Ezequiel Gullotta, Viviana Suero, Ian Di Rosa y Estrella Ortiz.</span>
  <span>Informar con respeto también es prevenir.</span>
</div></footer>

<script>
document.getElementById('year').textContent = new Date().getFullYear();
</script>
</body>
</html>
