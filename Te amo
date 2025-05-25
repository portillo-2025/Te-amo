<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Te Amo</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #ffe4e1;
      overflow: hidden;
      font-family: 'Arial', sans-serif;
    }

    .te-amo {
      position: absolute;
      font-size: 2em;
      color: #d6336c;
      font-weight: bold;
      opacity: 0.8;
      animation: flotar 10s linear infinite;
    }

    @keyframes flotar {
      0% {
        transform: translateY(100vh) rotate(0deg);
        opacity: 1;
      }
      100% {
        transform: translateY(-10vh) rotate(360deg);
        opacity: 0;
      }
    }

    iframe {
      position: fixed;
      bottom: 10px;
      left: 10px;
      width: 300px;
      height: 80px;
      border: none;
    }
  </style>
</head>
<body>

  <!-- Generar muchos "Te amo" -->
  <script>
    const cantidad = 100;
    for (let i = 0; i < cantidad; i++) {
      const div = document.createElement("div");
      div.className = "te-amo";
      div.textContent = "❤️ Te amo ❤️";
      div.style.left = Math.random() * 100 + "vw";
      div.style.animationDuration = (5 + Math.random() * 5) + "s";
      div.style.fontSize = (1 + Math.random() * 2) + "em";
      document.body.appendChild(div);
    }
  </script>

  <!-- Reproductor de SoundCloud -->
  <iframe 
    scrolling="no" 
    allow="autoplay" 
    src="https://w.soundcloud.com/player/?url=https%3A//soundcloud.com/t3relemento/t3r-elemento-labios-de-1&color=%23ffb6c1&auto_play=true&hide_related=false&show_comments=false&show_user=false&show_reposts=false&show_teaser=false">
  </iframe>
</body>
</html>
