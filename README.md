<!DOCTYPE html>
<html lang="sq">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Vaksinat Moderne</title>
<!-- Meta description for search engines -->
<meta name="description" content="Vaksinat Moderne - Projekti i biologjisë nga Joana Silaj. Zbuloni çfarë janë vaksinat, si funksionojnë vaksinat moderne dhe pse janë të rëndësishme për shëndetin.">
<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
<!-- Animate.css for animations -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>
<style>
  * {margin: 0; padding: 0; box-sizing: border-box;}
  body {
    font-family: 'Poppins', sans-serif;
    line-height: 1.6;
    background: #f0faff;
    color: #222;
    scroll-behavior: smooth;
  }
  header {
    background: linear-gradient(to right, #0096c7, #00b4d8);
    color: white;
    text-align: center;
    padding: 80px 20px;
    animation: fadeInDown 2s;
  }
  header h1 { font-size: 3.5em; margin-bottom: 10px; }
  header p { font-size: 1.5em; font-weight: 400; }
  nav { display: flex; justify-content: center; background: #0077b6; position: sticky; top: 0; z-index: 100; }
  nav a { color: white; text-decoration: none; padding: 15px 25px; font-weight: 600; transition: all 0.3s; }
  nav a:hover { background: #023e8a; transform: scale(1.05); }
  section { padding: 80px 20px; max-width: 1100px; margin: auto; }
  h2 { text-align: center; font-size: 2.8em; color: #0077b6; margin-bottom: 40px; }
  p { font-size: 1.2em; margin-bottom: 25px; }
  .card { background: white; border-radius: 15px; box-shadow: 0 10px 20px rgba(0,0,0,0.1); overflow: hidden; margin: 20px 0; transition: transform 0.5s, box-shadow 0.5s; }
  .card:hover { transform: translateY(-10px); box-shadow: 0 20px 30px rgba(0,0,0,0.2); }
  .card img { width: 100%; display: block; }
  .card-content { padding: 20px; }
  .card-content h3 { color: #0096c7; margin-bottom: 15px; }
  .btn { display: inline-block; padding: 12px 25px; background: linear-gradient(to right, #0096c7, #00b4d8); color: white; text-decoration: none; border-radius: 50px; transition: all 0.3s; font-weight: 600; margin-top: 10px; }
  .btn:hover { transform: scale(1.1); background: linear-gradient(to right, #00b4d8, #0096c7); }
  footer { text-align: center; padding: 40px 20px; background: #0096c7; color: white; font-weight: 600; font-size: 1.2em; }
  .cards-container { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px; }
</style>
</head>
<body>
<header class="animate__animated animate__fadeInDown">
  <h1>Vaksinat Moderne</h1>
  <p>Projekti i Biologjisë - Joana Silaj</p>
</header>
<nav>
  <a href="#about">Rreth Vaksinave</a>
  <a href="#modern">Vaksinat Moderne</a>
  <a href="#benefits">Përfitimet & Mitet</a>
</nav>
<section id="about">
  <h2 class="animate__animated animate__fadeInUp">Rreth Vaksinave</h2>
  <div class="cards-container">
    <div class="card animate__animated animate__fadeInLeft">
      <img src="https://images.unsplash.com/photo-1588776814546-1c7f5d1c8c61" alt="Vaccines">
      <div class="card-content">
        <h3>Çfarë janë vaksinat?</h3>
        <p>Vaksinat janë substanca që ndihmojnë trupin të krijojë imunitet ndaj sëmundjeve të ndryshme. Ato përdoren për të parandaluar infeksione dhe shpesh shpëtojnë jetë.</p>
      </div>
    </div>
  </div>
</section>
<section id="modern" style="background: #e0f7ff;">
  <h2 class="animate__animated animate__fadeInUp">Vaksinat Moderne</h2>
  <div class="cards-container">
    <div class="card animate__animated animate__fadeInRight">
      <img src="https://images.unsplash.com/photo-1606013241766-1f30c48d5eb2" alt="Modern Vaccines">
      <div class="card-content">
        <h3>Shembuj të njohur</h3>
        <p>Vaksinat e reja përdorin teknologji si mRNA dhe protein spike. Shembuj janë vaksinat kundër COVID-19, HPV dhe influenzës moderne.</p>
        <a href="#benefits" class="btn">Më shumë</a>
      </div>
    </div>
  </div>
</section>
<section id="benefits">
  <h2 class="animate__animated animate__fadeInUp">Përfitimet & Mitet</h2>
  <div class="cards-container">
    <div class="card animate__animated animate__fadeInLeft">
      <img src="https://images.unsplash.com/photo-1607746882042-944635dfe10e" alt="Benefits">
      <div class="card-content">
        <h3>Përfitimet</h3>
        <p>Vaksinat shpëtojnë miliona jetë çdo vit dhe mbrojnë komunitetet. Ato parandalojnë shpërthime të rrezikshme të sëmundjeve infektive.</p>
      </div>
    </div>
    <div class="card animate__animated animate__fadeInRight">
      <img src="https://images.unsplash.com/photo-1588776814546-1c7f5d1c8c61" alt="Myths">
      <div class="card-content">
        <h3>Mitet e zakonshme</h3>
        <p>Disa mitet thonë se vaksinat shkaktojnë sëmundje kronike, gjë që nuk është e vërtetë. Të dhënat shkencore tregojnë se vaksinat janë të sigurta.</p>
      </div>
    </div>
  </div>
</section>
<footer>
  <p>Projekti realizuar nga: Joana Silaj</p>
</footer>
</body>
</html>
