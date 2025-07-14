<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Happy Birthday Rummi 🎂</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(120deg, #ffe6e6, #ffe0f0);
      font-family: 'Comic Sans MS', cursive;
      text-align: center;
      color: #333;
      overflow: hidden;
    }

    h1 {
      font-size: 3em;
      margin-top: 50px;
      color: #e91e63;
      animation: bounce 2s infinite;
    }

    h2 {
      font-size: 2em;
      margin-top: 10px;
      color: #ff4081;
    }

    p {
      font-size: 1.2em;
      margin-top: 30px;
      padding: 0 20px;
    }

    .heart {
      font-size: 2.5em;
      color: red;
      animation: heartbeat 1s infinite;
      margin: 30px 0;
    }

    @keyframes bounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-20px); }
    }

    @keyframes heartbeat {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.4); }
    }

    .btn {
      background-color: #e91e63;
      color: white;
      border: none;
      padding: 15px 25px;
      font-size: 1em;
      border-radius: 20px;
      cursor: pointer;
      transition: background 0.3s ease;
      box-shadow: 0 0 15px rgba(233, 30, 99, 0.4);
    }

    .btn:hover {
      background-color: #c2185b;
    }

    .balloon {
      position: absolute;
      width: 50px;
      height: 70px;
      background: pink;
      border-radius: 50% 50% 50% 50%;
      animation: float 6s ease-in-out infinite;
    }

    @keyframes float {
      0% { transform: translateY(100vh) rotate(0deg); }
      100% { transform: translateY(-100vh) rotate(360deg); }
    }

    /* Random positions for fun balloons */
    .balloon1 { left: 10%; animation-delay: 0s; }
    .balloon2 { left: 30%; animation-delay: 2s; }
    .balloon3 { left: 50%; animation-delay: 4s; }
    .balloon4 { left: 70%; animation-delay: 1s; }
    .balloon5 { left: 90%; animation-delay: 3s; }
  </style>
</head>
<body>

  <div class="balloon balloon1"></div>
  <div class="balloon balloon2"></div>
  <div class="balloon balloon3"></div>
  <div class="balloon balloon4"></div>
  <div class="balloon balloon5"></div>

  <h1>🎉 Happy Birthday Rummi! 🎂</h1>
  <h2>From Mujtaba ❤️</h2>
  <p>May your day be filled with sunshine, laughter, and endless love. You make my world beautiful every single day.</p>
  <div class="heart">💖 💖 💖</div>
  <button class="btn" onclick="alert('Rummi, you’re the most special person in my life. I love you! 💕')">Click for a Surprise</button>

</body>
</html>
