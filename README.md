<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Benvenuto Sul Sito Di EclipseXbert</title>
  <style>
    /* Reset globale */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    html, body {
      width: 100%;
      height: 100%;
      font-family: Arial, sans-serif;
      color: white;
    }
    /* Background con immagine e overlay */
    body {
      background: url('https://leganerd.com/wp-content/uploads/2022/05/storie_di_immaginaria_realta_sole_eclisse_artwork_fantasy.jpg') no-repeat center center fixed;
      background-size: cover;
      position: relative;
    }
    /* Overlay scuro per migliorare la leggibilità */
    .overlay {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.6);
      z-index: 1;
    }
    /* Sezione hero a schermo intero, centrata con Flexbox */
    .hero {
      position: relative;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      z-index: 2;
    }
    /* Contenitore centrale */
    .container {
      padding: 20px;
    }
    /* Titolo principale */
    .top-title {
      font-size: 4em;
      margin-bottom: 0.3em;
      color: #FFD700; /* Giallo oro */
    }
    /* Sottotitolo */
    .welcome {
      font-size: 1.5em;
      margin-bottom: 1em;
    }
    /* Bottone per il canale YouTube */
    .button {
      display: inline-block;
      padding: 15px 30px;
      background: #FFD700;
      color: black;
      font-size: 1.2em;
      text-decoration: none;
      border-radius: 5px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
      transition: transform 0.3s ease;
    }
    .button:hover {
      transform: scale(1.05);
    }
    /* Footer fissato in basso */
    footer {
      background: rgba(0, 0, 0, 0.5);
      text-align: center;
      padding: 10px;
      color: #AAAAAA;
      font-size: 14px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <!-- Overlay per rendere più leggibile il testo -->
  <div class="overlay"></div>
  
  <!-- Sezione Hero -->
  <div class="hero">
    <div class="container">
      <h1 class="top-title">EclipseXbert</h1>
      <p class="welcome">Benvenuto Sul Sito Di EclipseXbert</p>
      <a class="button" href="https://www.youtube.com/@EclipseXbert" target="_blank">
        Visita il canale YouTube
      </a>
    </div>
  </div>
  
  <!-- Footer -->
  <footer>
    <p>&copy; 2025 EclipseXbert. All rights reserved.</p>
  </footer>
</body>
</html>
