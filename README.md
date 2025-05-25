# Te-amo
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Te Amo</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(to bottom right, #ffb6c1, #ffe4e1);
      font-family: 'Arial', sans-serif;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      text-align: center;
    }

    h1 {
      font-size: 4em;
      color: #d6336c;
      text-shadow: 2px 2px 5px #fff;
      animation: latido 1.5s infinite;
    }

    @keyframes latido {
      0%, 100% {
        transform: scale(1);
      }
      50% {
        transform: scale(1.1);
      }
    }
  </style>
</head>
<body>
  <h1>Te amo</h1>

  <!-- Reproductor de SoundCloud -->
  <iframe width="100%" height="166" scrolling="no" frameborder="no" allow="autoplay"
    src="https://w.soundcloud.com/player/?url=https%3A//soundcloud.com/t3relemento/t3r-elemento-labios-de-1&color=%23ffb6c1&auto_play=true&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true">
  </iframe>
</body>
</html>
