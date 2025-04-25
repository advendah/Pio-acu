<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Slide Romantis untuk Sayang</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Comic Sans MS', cursive;
      background: url('https://i.imgur.com/ZXBtVw7.jpg') no-repeat center center fixed;
      background-size: cover;
      animation: fadeIn 2s ease-in-out;
    }

    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }

    .container {
      padding: 20px;
      text-align: center;
      color: white;
      background-color: rgba(0, 0, 0, 0.5);
      margin: 100px auto;
      width: 80%;
      border-radius: 25px;
      box-shadow: 0 0 20px white;
      animation: slideUp 1.5s ease-out;
    }

    @keyframes slideUp {
      from {transform: translateY(50px); opacity: 0;}
      to {transform: translateY(0); opacity: 1;}
    }

    .question {
      font-size: 24px;
      margin-bottom: 20px;
    }

    .options button {
      font-size: 18px;
      margin: 10px;
      padding: 10px 20px;
      border: none;
      border-radius: 15px;
      cursor: pointer;
      transition: 0.3s;
      background-color: pink;
    }

    .options button:hover {
      background-color: deeppink;
      color: white;
    }

    audio {
      display: none;
    }
  </style>
</head>
<body>

  <audio autoplay loop>
    <source src="https://archive.org/download/a-thousand-years-christina-perri/A%20thousand%20years%20Christina%20Perri.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>

  <div class="container">
    <div class="question">
      Jika aku di sampingmu sekarang, apa yang paling ingin kamu lakukan?
    </div>
    <div class="options">
      <button onclick="alert('Awww peluk sayang terus ya!')">Peluk kamu erat-erat</button>
      <button onclick="alert('Haha lucu banget kamu!')">Gelitikin kamu biar ketawa</button>
      <button onclick="alert('Wah romantisnya kamu...')">Tatap mata kamu sambil bilang cinta</button>
    </div>
  </div>

</body>
</html>
