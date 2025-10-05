# stolyvlastimil.github.io
Stoly zalité pryskyřicí s elegantním designem.
<!DOCTYPE html>
<html lang="cs">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Truhlářství EpoxyArt – Luxusní stoly z pryskyřice</title>
  <style>
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

    footer {
      background: #2c2c2c;
      color: #fff;
      text-align: center;
      padding: 20px;
      margin-top: 50px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Truhlářství EpoxyArt</h1>
    <p>Originální stoly z masivu a pryskyřice – česká ruční výroba</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#galerie">Galerie</a>
    <a href="#cenik">Ceník</a>
    <a href="#kontakt">Kontakt</a>
  </nav>

  <section id="home">
    <h2>Vítejte</h2>
    <p>Vyrábíme jedinečné stoly z masivu kombinované s barevnou epoxidovou pryskyřicí. Každý kus je originál – vytvořen s láskou k přírodě i řemeslu.</p>
  </section>

  <section id="galerie">
    <h2>Galerie našich výrobků</h2>
    <div class="gallery">
      <img src="images/stul1.jpg" alt="Epoxidový stůl 1">
      <img src="images/stul2.jpg" alt="Epoxidový stůl 2">
      <img src="images/stul3.jpg" alt="Epoxidový stůl 3">
      <img src="images/stul4.jpg" alt="Epoxidový stůl 4">
    </div>
  </section>

  <section id="cenik">
    <h2>Ceník</h2>
    <div class="price-list">
      <div class="product">
        <h3>Kávový stůl „Modrá řeka“</h3>
        <p>Rozměry: 100×60 cm</p>
        <strong>12 900 Kč</strong>
      </div>
      <div class="product">
        <h3>Jídelní stůl „Ořechová vlna“</h3>
        <p>Rozměry: 180×90 cm</p>
        <strong>29 900 Kč</strong>
      </div>
      <div class="product">
        <h3>Konferenční stolek „Zelený les“</h3>
        <p>Rozměry: 120×70 cm</p>
        <strong>17 900 Kč</strong>
      </div>
    </div>
  </section>

  <section id="kontakt">
    <h2>Kontakt</h2>
    <p style="text-align:center;">Máte zájem o vlastní stůl na míru? Ozvěte se nám!</p>
    <p style="text-align:center;">
      📞 +420 777 123 456<br>
      ✉️ info@epoxyart.cz<br>
      📍 Dílna: Brno, Česká republika
    </p>
  </section>

  <footer>
    &copy; 2025 Truhlářství EpoxyArt | Design & kód: [Tvoje jméno]
  </footer>

</body>
</html>
