<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Carte pour Granella</title>
  <style>
    body {
      background: linear-gradient(#ffccf9, #fff0f5);
      font-family: 'Segoe UI', sans-serif;
      text-align: center;
      padding: 30px;
    }
    h1 {
      color: #d63384;
    }
    .map {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      margin-top: 20px;
    }
    .heart {
      width: 120px;
      height: 120px;
      background: red;
      position: relative;
      margin: 20px;
      border-radius: 50%;
      transform: rotate(-45deg);
      cursor: pointer;
      transition: transform 0.2s;
    }
    .heart::before,
    .heart::after {
      content: "";
      width: 120px;
      height: 120px;
      background: red;
      border-radius: 50%;
      position: absolute;
    }
    .heart::before {
      top: -60px;
      left: 0;
    }
    .heart::after {
      left: 60px;
      top: 0;
    }
    .tooltip {
      display: none;
      position: absolute;
      top: -30px;
      left: 50%;
      transform: translateX(-50%);
      background: white;
      color: #d63384;
      padding: 8px 12px;
      border-radius: 10px;
      font-size: 14px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    .heart:hover .tooltip {
      display: block;
    }
  </style>
</head>
<body>

  <h1>🌍 Carte de mon cœur pour Granella 💖</h1>
  <p>Chaque cœur représente une partie de ce que tu représentes pour moi.</p>

  <div class="map">
    <div class="heart">
      <div class="tooltip">Tendresse 💫</div>
    </div>
    <div class="heart">
      <div class="tooltip">Beauté 🌹</div>
    </div>
    <div class="heart">
      <div class="tooltip">Douceur ☁️</div>
    </div>
    <div class="heart">
      <div class="tooltip">Inspiration ✨</div>
    </div>
  </div>

  <!-- 🎵 Musique d’ambiance (YouTube Audio Library - libre de droits) -->
  <audio autoplay loop>
    <source src="https://www.bensound.com/bensound-music/bensound-love.mp3" type="audio/mpeg">
    Ton navigateur ne supporte pas l’audio HTML5.
  </audio>

</body>
</html>
