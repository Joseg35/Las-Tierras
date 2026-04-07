 <!DOCTYPE html>
  <html lang="es">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lotes En Venta De 5 Acres</title>
    <meta name="description" content="Lotes de 5 acres rodeados de naturaleza,
  espacio y tranquilidad para disfrutar grandes momentos en familia.">
    <style>
      :root {
        --bg: #efe7d6;
        --bg-soft: #f7f2e8;
        --surface: rgba(255, 250, 241, 0.92);
        --text: #2f241b;
        --muted: #6d5a4b;
        --accent: #b86a2f;
        --accent-dark: #8e4f20;
        --olive: #5b6b3c;
        --border: rgba(105, 79, 52, 0.14);
        --shadow: 0 18px 50px rgba(53, 36, 19, 0.12);
        --radius: 22px;
      }

      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }

      html {
        scroll-behavior: smooth;
      }

      body {
        font-family: Georgia, "Times New Roman", serif;
        color: var(--text);
        background:
          radial-gradient(circle at top, rgba(255,255,255,0.55), transparent
  35%),
          linear-gradient(180deg, #e7dcc8 0%, #f4ecdf 45%, #eee3d1 100%);
        line-height: 1.65;
      }

      img {
        display: block;
        width: 100%;
        height: 100%;
        object-fit: cover;
      }

      .container {
        width: min(1120px, 92%);
        margin: 0 auto;
      }

      header {
        padding: 28px 0 20px;
      }

      .hero {
        min-height: 78vh;
        border-radius: 30px;
        overflow: hidden;
        position: relative;
        display: grid;
        align-items: end;
        background:
          linear-gradient(to top, rgba(25, 18, 12, 0.72), rgba(25, 18, 12,
  0.16)),
          url("land_image_1.jpeg") center center / cover no-repeat;
        box-shadow: var(--shadow);
        isolation: isolate;
      }

      .hero::after {
        content: "";
        position: absolute;
        inset: 0;
        background:
          linear-gradient(135deg, rgba(184,106,47,0.18), transparent 40%),
          linear-gradient(0deg, rgba(91,107,60,0.12), transparent 45%);
        z-index: -1;
      }

      .hero-content {
        padding: clamp(2rem, 5vw, 4.5rem);
        max-width: 760px;
        color: #fffaf2;
      }

      .eyebrow {
        display: inline-block;
        margin-bottom: 1rem;
        padding: 0.45rem 0.8rem;
        border-radius: 999px;
        background: rgba(255,255,255,0.14);
        border: 1px solid rgba(255,255,255,0.22);
        font-size: 0.85rem;
        letter-spacing: 0.08em;
        text-transform: uppercase;
      }

      h1 {
        font-size: clamp(2.8rem, 7vw, 5.5rem);
        line-height: 0.95;
        margin-bottom: 1.2rem;
        font-weight: 700;
      }

      .hero p {
        max-width: 60ch;
        font-size: clamp(1.05rem, 2vw, 1.22rem);
        color: rgba(255, 248, 239, 0.92);
      }

      main {
        padding: 30px 0 70px;
      }

      .section {
        background: var(--surface);
        backdrop-filter: blur(8px);
        border: 1px solid var(--border);
        border-radius: var(--radius);
        padding: clamp(1.4rem, 3vw, 2.2rem);
        box-shadow: var(--shadow);
        margin-bottom: 26px;
      }

      .section-header {
        max-width: 720px;
        margin-bottom: 1.5rem;
      }

      h2 {
        font-size: clamp(1.8rem, 3vw, 2.6rem);
        line-height: 1.05;
        color: var(--olive);
        margin-bottom: 0.7rem;
      }

      .section p {
        font-size: 1.06rem;
        color: var(--muted);
      }

      .split {
        display: grid;
        grid-template-columns: 1.15fr 0.85fr;
        gap: 1.2rem;
        align-items: stretch;
      }

      .feature-card {
        border-radius: 20px;
        overflow: hidden;
        min-height: 360px;
        background: #ddd;
        box-shadow: 0 10px 30px rgba(0,0,0,0.08);
      }

      .feature-text {
        display: flex;
        flex-direction: column;
        justify-content: center;
        padding: 1.5rem;
        border-radius: 20px;
        background: linear-gradient(180deg, #fffaf1, #f4ebdc);
        border: 1px solid rgba(105, 79, 52, 0.1);
      }

      .feature-text strong {
        color: var(--accent-dark);
        font-size: 1.1rem;
        margin-bottom: 0.8rem;
      }

      .gallery {
        display: grid;
        grid-template-columns: repeat(12, 1fr);
        gap: 14px;
        margin-top: 1.2rem;
      }

      .tile {
        overflow: hidden;
        border-radius: 18px;
        min-height: 220px;
        box-shadow: 0 10px 28px rgba(0,0,0,0.08);
        position: relative;
        background: #d9cfbf;
      }

      .tile img {
        transition: transform 0.45s ease, filter 0.45s ease;
      }

      .tile:hover img {
        transform: scale(1.06);
        filter: saturate(1.06) contrast(1.03);
      }

      .tile.large {
        grid-column: span 7;
        min-height: 340px;
      }

      .tile.medium {
        grid-column: span 5;
        min-height: 340px;
      }

      .tile.small {
        grid-column: span 4;
      }

      .video-frame {
        margin-top: 1.2rem;
        border-radius: 20px;
        overflow: hidden;
        aspect-ratio: 16 / 9;
        box-shadow: 0 14px 36px rgba(0,0,0,0.12);
      }

      .video-frame iframe {
        width: 100%;
        height: 100%;
        border: 0;
      }

      .closing {
        text-align: center;
        padding: 2.2rem 1.5rem;
        background:
          linear-gradient(135deg, rgba(184,106,47,0.12),
  rgba(91,107,60,0.08)),
          #fff8ee;
      }

      .closing h2 {
        color: var(--accent-dark);
      }

      footer {
        text-align: center;
        padding: 0 0 50px;
        color: #7a6758;
        font-size: 0.95rem;
      }

      @media (max-width: 900px) {
        .split {
          grid-template-columns: 1fr;
        }

        .tile.large,
        .tile.medium,
        .tile.small {
          grid-column: span 12;
          min-height: 260px;
        }

        .hero {
          min-height: 68vh;
        }
      }

      @media (max-width: 640px) {
        .container {
          width: min(94%, 1120px);
        }

        .hero-content {
          padding: 1.4rem;
        }

        .section {
          padding: 1.2rem;
        }

        h1 {
          font-size: 2.5rem;
        }

        h2 {
          font-size: 1.65rem;
        }

        .tile.large,
        .tile.medium,
        .tile.small {
          min-height: 220px;
        }
      }
    </style>
  </head>
  <body>
    <header class="container">
      <section class="hero">
        <div class="hero-content">
          <span class="eyebrow">Espacio, Naturaleza, Libertad</span>
          <h1>Lotes En Venta De 5 Acres</h1>
          <p>
            Un lugar para desconectarte, disfrutar con tu familia y construir
  recuerdos
            rodeado de campo, cielo abierto y tranquilidad.
          </p>
        </div>
      </section>
    </header>

    <main class="container">
      <section class="section">
        <div class="section-header">
          <h2>Libertad Y Aventura</h2>
          <p>
            Imagina tu propio espacio para montar a caballo, construir una
  cabaña,
            disfrutar una fogata y vivir fines de semana rodeado de
  naturaleza.
          </p>
        </div>

        <div class="split">
          <div class="feature-card">
            <img src="land_image_2.jpeg" alt="Vista amplia del terreno con
  paisaje natural">
          </div>
          <div class="feature-text">
            <strong>Un lugar para crear momentos</strong>
            <p>
              Aquí no solo hay terreno. Hay espacio para respirar, reunirte
  con los tuyos
              y disfrutar experiencias sencillas que se vuelven inolvidables.
            </p>
          </div>
        </div>
      </section>

      <section class="section">
        <div class="section-header">
          <h2>Galería Del Terreno</h2>
          <p>
            Una presentación más limpia y visual para mostrar mejor la belleza
  y la amplitud
            de estos lotes.
          </p>
        </div>

        <div class="gallery">
          <div class="tile large">
            <img src="land_image_1.jpeg" alt="Vista principal del lote en
  venta">
          </div>
          <div class="tile medium">
            <img src="land_image_3.jpeg" alt="Terreno abierto con vegetación
  natural">
          </div>
          <div class="tile small">
            <img src="IMG_0666.jpg" alt="Paisaje del lote bajo cielo abierto">
          </div>
          <div class="tile small">
            <img src="IMG_0686.jpg" alt="Área natural dentro del terreno">
          </div>
          <div class="tile small">
            <img src="IMG_0691.jpg" alt="Vista del campo y sendero">
          </div>
          <div class="tile small">
            <img src="IMG_0692.jpg" alt="Extensión del terreno con
  vegetación">
          </div>
          <div class="tile small">
            <img src="IMG_0693.jpg" alt="Vista del paisaje natural del lote">
          </div>
          <div class="tile small">
            <img src="IMG_0694.jpg" alt="Terreno ideal para descanso y
  recreación">
          </div>
          <div class="tile small">
            <img src="IMG_0696.jpg" alt="Vista natural de uno de los lotes">
          </div>
          <div class="tile small">
            <img src="IMG_0700.jpg" alt="Vista amplia del terreno disponible">
          </div>
          <div class="tile small">
            <img src="IMG_0960.jpg" alt="Paisaje del lote con entorno
  abierto">
          </div>
          <div class="tile small">
            <img src="IMG_0962.jpg" alt="Imagen del terreno en venta">
          </div>
        </div>
      </section>

      <section class="section">
        <div class="section-header">
          <h2>Experiencias Que Inspiran</h2>
          <p>
            Explora, acampa y disfruta de un entorno que invita al descanso,
  la convivencia
            y la aventura al aire libre.
          </p>
        </div>

        <div class="gallery">
          <div class="tile medium">
            <img src="land_10.jpg" alt="Terreno con espacio para explorar y
  acampar">
          </div>
          <div class="tile large">
            <img src="wildlife_view.jpg" alt="Vista natural con fauna y
  paisaje abierto">
          </div>
        </div>
      </section>

      <section class="section">
        <div class="section-header">
          <h2>Lo Que Les Espera</h2>
          <p>
            Descubre mejor la energía y la amplitud de estos 5 acres en video.
          </p>
        </div>

        <div class="video-frame">
          <iframe
            src="https://drive.google.com/file/
  d/1RCnAt18aZtZuJiooEHwaxEjazsiTjS_v/preview"
            allow="autoplay"
            title="Video del terreno"
            allowfullscreen>
          </iframe>
        </div>
      </section>

      <section class="section closing">
        <div class="section-header" style="margin: 0 auto;">
          <h2>Las Tierras Land Investments</h2>
          <p>
            Naturaleza, amplitud y una forma distinta de imaginar tu propio
  lugar.
          </p>
        </div>

        <div class="gallery">
          <div class="tile small">
            <img src="painting.PNG" alt="Ilustración inspirada en la
  naturaleza del lugar">
          </div>
          <div class="tile small">
            <img src="entrance.jpg" alt="Entrada al terreno">
          </div>
          <div class="tile small">
            <img src="birds.JPG" alt="Aves y entorno natural del terreno">
          </div>
        </div>
      </section>
    </main>

    <footer class="container">
      Las Tierras Land Investments
    </footer>
  </body>
  </html>
