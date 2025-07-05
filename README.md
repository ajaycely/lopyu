<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Lopyu 🌈</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      background: linear-gradient(270deg, red, orange, yellow, green, blue, indigo, violet);
      background-size: 1400% 1400%;
      animation: rainbow 10s ease infinite;
    }

    @keyframes rainbow {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    h1 {
      font-size: 5em;
      color: white;
      text-shadow: 2px 2px 10px #000;
      animation: pop 1s ease-in-out infinite alternate;
    }

    @keyframes pop {
      from {
        transform: scale(1);
      }
      to {
        transform: scale(1.1);
      }
    }
  </style>
</head>
<body>
  <h1>Lopyu 💖</h1>
</body>
</html>

