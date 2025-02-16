<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tu Refugio de Libertad y Aventura</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      color: #333;
      background-color: #f5f5f5;
    }
    header {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
    }
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 2rem;
    }
    .section {
      background-color: white;
      border-radius: 8px;
      padding: 2rem;
      margin-bottom: 2rem;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
      color: #27ae60;
    }
    h2 {
      color: #2c3e50;
      margin-bottom: 1.5rem;
      font-size: 2rem;
    }
    p {
      margin-bottom: 1.5rem;
      font-size: 1.1rem;
    }
    .image-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 1.5rem;
      margin-top: 2rem;
    }
    .image-container {
      position: relative;
      overflow: hidden;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      margin-bottom: 1.5rem;
    }
    .image-container img {
      width: 100%;
      height: auto;
      display: block;
      transition: transform 0.3s ease;
    }
    .image-container:hover img {
      transform: scale(1.05);
    }
    @media (max-width: 768px) {
      .container {
        padding: 1rem;
      }
      h1 {
        font-size: 2rem;
      }
      h2 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Tu Refugio de Libertad y Aventura</h1>
  </header>

  <div class="container">
    <!-- Section 1: Main Message & Land Images -->
    <section class="section">
      <h2>Tu Refugio de Libertad y Aventura</h2>
      <p>Imagina 5 acres para construir tu rancho recreativo: cabalga por senderos, diseña una cabaña acogedora y haz unas carnitas asadas con familia. Aquí no solo hay espacio, sino libertad para crear recuerdos en ATV, junto a una fogata familiar o explorando la vida silvestre.</p>
      <div class="image-grid">
        <div class="image-container">
          <img src="https://raw.githubusercontent.com/Joseg35/Las-Tierras/main/land_image_1.jpeg" alt="Land Image 1">
        </div>
        <div class="image-container">
          <img src="https://raw.githubusercontent.com/Joseg35/Las-Tierras/main/land_image_2.jpeg" alt="Land Image 2">
        </div>
        <div class="image-container">
          <img src="https://raw.githubusercontent.com/Joseg35/Las-Tierras/main/land_image_3.jpeg" alt="Land Image 3">
        </div>
      </div>
    </section>

    <!-- Section 2: Investment Experience -->
    <section class="section">
      <h2>Inversión en Experiencias</h2>
      <p>Esta tierra no solo aumentará su valor, sino que te dará tranquilidad, seguridad y un patrimonio para las futuras generaciones. Explora o acampa en tu propio paraíso privado.</p>
      <div class="image-grid">
        <div class="image-container">
          <img src="https://raw.githubusercontent.com/Joseg35/Las-Tierras/main/land_10.jpg" alt="Land 10">
        </div>
        <div class="image-container">
          <img src="https://raw.githubusercontent.com/Joseg35/Las-Tierras/main/wildlife_view.jpg" alt="Wildlife View">
        </div>
      </div>
    </section>

    <!-- Section 3: Act Now -->
    <section class="section">
      <h2>Actúa Ahora no Pierdas la Oportunidad</h2>
      <p>Terrenos así son tesoros escasos en un mundo que se urbaniza rápido; los lotes vuelan. No dejes que otros se adelanten y tomen el escape soñado que podría ser tuyo.</p>
      <div class="image-grid">
        <div class="image-container"><img src="https://raw.githubusercontent.com/Joseg35/Las-Tierras/main/IMG_0666.jpg" alt="Land Image"></div>
        <div class="image-container"><img src="https://raw.githubusercontent.com/Joseg35/Las-Tierras/main/IMG_0686.jpg" alt="Land Image"></div>
        <div class="image-container"><img src="https://raw.githubusercontent.com/Joseg35/Las-Tierras/main/IMG_0691.jpg" alt="Land Image"></div>
        <div class="image-container"><img src="https://raw.githubusercontent.com/Joseg35/Las-Tierras/main/IMG_0692.jpg" alt="Land Image"></div>
        <div class="image-container"><img src="https://raw.githubusercontent.com/Joseg35/Las-Tierras/main/IMG_0693.jpg" alt="Land Image"></div>
        <div class="image-container"><img src="https://raw.githubusercontent.com/Joseg35/Las-Tierras/main/IMG_0694.jpg" alt="Land Image"></div>
        <div class="image-container"><img src="https://raw.githubusercontent.com/Joseg35/Las-Tierras/main/IMG_0696.jpg" alt="Land Image"></div>
        <div class="image-container"><img src="https://raw.githubusercontent.com/Joseg35/Las-Tierras/main/IMG_0700.jpg" alt="Land Image"></div>
        <div class="image-container"><img src="https://raw.githubusercontent.com/Joseg35/Las-Tierras/main/IMG_0960.jpg" alt="Land Image"></div>
        <div class="image-container"><img src="https://raw.githubusercontent.com/Joseg35/Las-Tierras/main/IMG_0962.jpg" alt="Land Image"></div>
      </div>
    </section>

    <!-- Section 4: Video from Google Drive -->
    <section class="section">
      <h2>Lo que les Espera</h2>
      <p>4x4</p>
      <div class="video-container">
        <iframe width="100%" height="400" src="https://drive.google.com/file/d/1RWEytkznXQzWD5RdID1gNYpAyHfMAgYb/preview" allow="autoplay"></iframe>
      </div>
    </section>

    <!-- Section 5: Artwork -->
    <section class="section">
      <h2>Las Tierras Land Investments</h2>
      <div class="image-container">
        <img src="https://raw.githubusercontent.com/Joseg35/Las-Tierras/main/painting.PNG" alt="Nature Painting">
      </div>
    </section>
  </div>
</body>
</html>
