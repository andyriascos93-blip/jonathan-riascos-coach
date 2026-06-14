<!DOCTYPE html>
<html lang="es">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Jonathan Riascos | Bienestar Emocional</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

:root{
--primary:#0f766e;
--secondary:#164e63;
--light:#f8fafc;
--dark:#1e293b;
--white:#ffffff;
}

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

html{
scroll-behavior:smooth;
}

body{
background:var(--light);
color:var(--dark);
}

header{
position:fixed;
width:100%;
top:0;
background:white;
padding:15px 8%;
display:flex;
justify-content:space-between;
align-items:center;
box-shadow:0 2px 10px rgba(0,0,0,.05);
z-index:1000;
}

.logo{
font-size:1.2rem;
font-weight:700;
color:var(--primary);
}

nav a{
text-decoration:none;
margin-left:25px;
color:var(--dark);
font-weight:500;
}

.hero{
padding:150px 8% 80px;
display:grid;
grid-template-columns:1fr 1fr;
gap:50px;
align-items:center;
}

.hero img{
width:100%;
max-width:450px;
border-radius:20px;
}

.hero h1{
font-size:3.5rem;
line-height:1.1;
margin-bottom:20px;
}

.hero p{
font-size:1.1rem;
margin-bottom:25px;
}

.btn{
display:inline-block;
padding:15px 30px;
background:var(--primary);
color:white;
text-decoration:none;
border-radius:10px;
font-weight:600;
}

section{
padding:90px 8%;
}

.section-title{
text-align:center;
font-size:2.5rem;
margin-bottom:50px;
color:var(--primary);
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:white;
padding:30px;
border-radius:15px;
box-shadow:0 5px 20px rgba(0,0,0,.08);
}

.card h3{
margin-bottom:15px;
}

.about{
display:grid;
grid-template-columns:1fr 1fr;
gap:40px;
align-items:center;
}

.about img{
width:100%;
border-radius:20px;
}

.testimonial{
background:white;
padding:30px;
border-radius:15px;
text-align:center;
box-shadow:0 5px 20px rgba(0,0,0,.08);
}

.faq{
max-width:800px;
margin:auto;
}

details{
background:white;
margin-bottom:15px;
padding:20px;
border-radius:10px;
}

.cta{
background:var(--primary);
color:white;
text-align:center;
border-radius:20px;
}

.cta h2{
margin-bottom:20px;
}

footer{
background:var(--secondary);
color:white;
text-align:center;
padding:30px;
}

.whatsapp{
position:fixed;
bottom:20px;
right:20px;
width:65px;
height:65px;
border-radius:50%;
background:#25D366;
display:flex;
justify-content:center;
align-items:center;
font-size:30px;
color:white;
text-decoration:none;
box-shadow:0 5px 15px rgba(0,0,0,.3);
}

@media(max-width:768px){

.hero,
.about{
grid-template-columns:1fr;
text-align:center;
}

.hero h1{
font-size:2.3rem;
}

header{
flex-direction:column;
gap:10px;
}
}

</style>
</head>

<body>

<header>

<div class="logo">
Jonathan Riascos
</div>

<nav>
<a href="#sobre">Sobre mí</a>
<a href="#servicios">Servicios</a>
<a href="#faq">FAQ</a>
<a href="#contacto">Contacto</a>
</nav>

</header>

<section class="hero">

<div>

<h1>
Comprender tus emociones puede cambiar tu vida
</h1>

<p>
Contenido y acompañamiento orientado al bienestar emocional, crecimiento personal y desarrollo de herramientas psicológicas para afrontar los desafíos cotidianos.
</p>

<a href="https://wa.me/573001234567" class="btn">
Agenda una conversación
</a>

</div>

<div>
<img src="foto-profesional.jpg" alt="Jonathan Riascos">
</div>

</section>

<section id="sobre">

<h2 class="section-title">
Sobre mí
</h2>

<div class="about">

<div>
<img src="sobre-mi.jpg" alt="">
</div>

<div>

<p>
Soy Jonathan Riascos, profesional en Psicología próximo a graduarse. Mi misión es acercar el conocimiento psicológico a las personas mediante contenido práctico y acompañamiento orientado al bienestar emocional.
</p>

<br>

<p>
Creo que la salud mental debe ser accesible, comprensible y libre de estigmas.
</p>

</div>

</div>

</section>

<section id="servicios">

<h2 class="section-title">
Áreas de interés
</h2>

<div class="cards">

<div class="card">
<h3>Ansiedad y Estrés</h3>
<p>Herramientas para comprender y gestionar situaciones de alta demanda emocional.</p>
</div>

<div class="card">
<h3>Autoestima</h3>
<p>Fortalecimiento del autoconocimiento y valoración personal.</p>
</div>

<div class="card">
<h3>Relaciones</h3>
<p>Comprensión de dinámicas afectivas y habilidades de comunicación.</p>
</div>

<div class="card">
<h3>Crecimiento Personal</h3>
<p>Desarrollo de hábitos saludables y objetivos de vida.</p>
</div>

</div>

</section>

<section>

<h2 class="section-title">
Lo que encontrarás aquí
</h2>

<div class="cards">

<div class="testimonial">
Contenido basado en psicología.
</div>

<div class="testimonial">
Explicaciones claras y prácticas.
</div>

<div class="testimonial">
Herramientas aplicables a la vida diaria.
</div>

</div>

</section>

<section id="faq">

<h2 class="section-title">
Preguntas frecuentes
</h2>

<div class="faq">

<details>
<summary>¿Atiendes de forma virtual?</summary>
<p>Sí, dependiendo del servicio ofrecido.</p>
</details>

<details>
<summary>¿Cómo puedo contactarte?</summary>
<p>A través de WhatsApp o Instagram.</p>
</details>

<details>
<summary>¿Compartes contenido gratuito?</summary>
<p>Sí. Publico contenido educativo relacionado con salud mental y bienestar emocional.</p>
</details>

</div>

</section>

<section id="contacto" class="cta">

<h2>
¿Listo para dar el primer paso?
</h2>

<p>
Escríbeme y conversemos sobre tus objetivos.
</p>

<br>

<a href="https://wa.me/573001234567" class="btn">
Contactar por WhatsApp
</a>

</section>

<footer>

<p>
© 2026 Jonathan Riascos | Bienestar Emocional
</p>

</footer>

<a href="https://wa.me/573001234567" class="whatsapp">
💬
</a>

</body>
</html>
