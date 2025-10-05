body {
  font-family: 'Poppins', sans-serif;
  margin: 0;
  background-color: #f9f9f9;
  color: #333;
}

header {
  background: #2c2c2c;
  color: #fff;
  padding: 20px 0;
  text-align: center;
}

nav {
  display: flex;
  justify-content: center;
  background: #444;
  flex-wrap: wrap;
}

nav a {
  color: white;
  text-decoration: none;
  padding: 15px 25px;
  display: inline-block;
  transition: background 0.3s;
}

nav a:hover {
  background: #666;
}

section {
  padding: 40px 10%;
}

h1, h2 {
  text-align: center;
}

footer {
  background: #2c2c2c;
  color: #fff;
  text-align: center;
  padding: 20px;
  margin-top: 50px;
}

/* Galerie */
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  margin-top: 30px;
}

.gallery img {
  width: 100%;
  border-radius: 8px;
  box-shadow: 0 3px 10px rgba(0,0,0,0.2);
  transition: transform 0.3s;
}

.gallery img:hover {
  transform: scale(1.05);
}

/* Ceník */
.price-list {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 30px;
  margin-top: 30px;
}

.product {
  background: white;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 3px 10px rgba(0,0,0,0.1);
  width: 280px;
  text-align: center;
}

/* Formulář */
form {
  max-width: 500px;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  gap: 15px;
}

input, select, textarea, button {
  padding: 10px;
  font-size: 16px;
  border: 1px solid #ccc;
  border-radius: 6px;
  width: 100%;
  box-sizing: border-box;
}

button {
  background: #2c2c2c;
  color: white;
  cursor: pointer;
  transition: background 0.3s;
}

button:hover {
  background: #444;
}
<!DOCTYPE html>
<html lang="cs">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>EpoxyArt – Úvod</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>Truhlářství EpoxyArt</h1>
  <p>Originální stoly z masivu a pryskyřice – česká ruční výroba</p>
</header>

<nav>
  <a href="index.html">Home</a>
  <a href="galerie.html">Galerie</a>
  <a href="cenik.html">Ceník</a>
  <a href="kontakt.html">Kontakt</a>
</nav>

<section>
  <h2>Vítejte</h2>
  <p>Vyrábíme jedinečné stoly z masivu kombinované s epoxidovou pryskyřicí. Každý kus je originál – vytvořen s láskou k přírodě i řemeslu. Naším cílem je spojit estetiku s funkčností a nabídnout vám kus nábytku, který vydrží po generace.</p>
</section>

<footer>
  &copy; 2025 Truhlářství EpoxyArt | Design & kód: [Tvoje jméno]
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="cs">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>EpoxyArt – Galerie</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>Galerie našich výrobků</h1>
  <p>Každý kus je originál – ručně vyráběný z kvalitního dřeva a pryskyřice.</p>
</header>

<nav>
  <a href="index.html">Home</a>
  <a href="galerie.html" style="background:#666;">Galerie</a>
  <a href="cenik.html">Ceník</a>
  <a href="kontakt.html">Kontakt</a>
</nav>

<section>
  <h2>Naše práce</h2>
  <p style="text-align:center;">Zde budou fotografie stolů – můžeš je později přidat do složky <code>images/</code> a doplnit jejich popisy.</p>

  <div class="gallery">
    <img src="images/stul1.jpg" alt="Ukázka produktu">
    <img src="images/stul2.jpg" alt="Ukázka produktu">
    <img src="images/stul3.jpg" alt="Ukázka produktu">
  </div>
</section>

<footer>
  &copy; 2025 Truhlářství EpoxyArt
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="cs">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>EpoxyArt – Ceník</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>Ceník</h1>
  <p>Každý stůl vyrábíme individuálně podle přání zákazníka.</p>
</header>

<nav>
  <a href="index.html">Home</a>
  <a href="galerie.html">Galerie</a>
  <a href="cenik.html" style="background:#666;">Ceník</a>
  <a href="kontakt.html">Kontakt</a>
</nav>

<section>
  <h2>Nabídka stolů</h2>
  <p style="text-align:center;">Zde později přidáš produkty s jejich názvy, popisem a cenami.</p>

  <div class="price-list">
    <!-- Příklad, který můžeš později odkomentovat -->
    <!--
    <div class="product">
      <h3>Kávový stůl „Modrá řeka“</h3>
      <p>Rozměry: 100×60 cm</p>
      <strong>12 900 Kč</strong>
    </div>
    -->
  </div>
</section>

<footer>
  &copy; 2025 Truhlářství EpoxyArt
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="cs">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>EpoxyArt – Kontakt</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>Kontakt a objednávka</h1>
  <p>Máte zájem o stůl na míru? Napište nám.</p>
</header>

<nav>
  <a href="index.html">Home</a>
  <a href="galerie.html">Galerie</a>
  <a href="cenik.html">Ceník</a>
  <a href="kontakt.html" style="background:#666;">Kontakt</a>
</nav>

<section>
  <h2>Kontaktní formulář</h2>
  <p style="text-align:center;">Vyplňte formulář a my se vám ozveme s nezávaznou nabídkou.</p>

  <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
    <input type="text" name="Jméno" placeholder="Vaše jméno" required>
    <input type="email" name="Email" placeholder="Váš e-mail" required>
    <textarea name="Zpráva" rows="5" placeholder="Popište, o jaký stůl máte zájem..." required></textarea>
    <button type="submit">Odeslat</button>
  </form>

  <p style="text-align:center; margin-top:20px;">
    📞 +420 777 123 456<br>
    ✉️ info@epoxyart.cz<br>
    📍 Brno, Česká republika
  </p>
</section>

<footer>
  &copy; 2025 Truhlářství EpoxyArt
</footer>

</body>
</html>
