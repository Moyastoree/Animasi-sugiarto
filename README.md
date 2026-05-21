<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Animasi SU-GI-AR-TO</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(135deg, #000000, #111827, #1e3a8a);
      overflow: hidden;
    }

    .container {
      text-align: center;
      color: white;
    }

    .running-text {
      position: absolute;
      top: 15%;
      width: 100%;
      white-space: nowrap;
      overflow: hidden;
    }

    .running-text span {
      display: inline-block;
      padding-left: 100%;
      font-size: 2rem;
      font-weight: bold;
      animation: slide 10s linear infinite;
      color: #38bdf8;
      text-shadow: 0 0 10px #38bdf8;
    }

    @keyframes slide {
      0% {
        transform: translateX(0);
      }
      100% {
        transform: translateX(-200%);
      }
    }

    .name {
      font-size: 5rem;
      font-weight: bold;
      letter-spacing: 10px;
      animation: glow 2s ease-in-out infinite alternate;
    }

    @keyframes glow {
      from {
        text-shadow: 0 0 10px #fff, 0 0 20px #38bdf8, 0 0 30px #2563eb;
      }
      to {
        text-shadow: 0 0 20px #fff, 0 0 40px #38bdf8, 0 0 60px #2563eb;
      }
    }

    .subtitle {
      margin-top: 20px;
      font-size: 1.2rem;
      color: #d1d5db;
      animation: fade 3s infinite;
    }

    @keyframes fade {
      0%, 100% {
        opacity: 1;
      }
      50% {
        opacity: 0.3;
      }
    }
  </style>
</head>
<body>
  <div class="running-text">
    <span>✨ SELAMAT DATANG DI ANIMASI SU-GI-AR-TO ✨</span>
  </div>

  <div class="container">
    <div class="name">SU-GI-AR-TO</div>
    <div class="subtitle">Animasi teks bergerak modern</div>
  </div>
</body>
</html>
