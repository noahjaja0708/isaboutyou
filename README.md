#<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Proposal</title>
  <link rel="stylesheet" href="proposal.css">
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Roboto&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      background-color: #fdf6f9;
      margin: 0;
      padding: 0;
      text-align: center;
    }

    .group1, .images1, .images2 {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
      margin: 20px;
    }

    button {
      padding: 10px 20px;
      font-size: 16px;
      border-radius: 10px;
      background-color: #ffb6c1;
      border: none;
      cursor: pointer;
      transition: all 0.3s ease;
    }

    button:hover {
      background-color: #ff69b4;
      color: white;
      transform: scale(1.1);
    }

    .sadcat, .crying, .sadboi, .sadman, .hahahuhu, #hang, #frog, #sadsad {
      width: 200px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    .ask {
      margin: 40px auto;
      padding: 20px;
      background-color: #fff0f5;
      border-radius: 20px;
      width: 80%;
      max-width: 500px;
      box-shadow: 0 8px 15px rgba(0, 0, 0, 0.2);
    }

    .crush {
      font-family: 'Pacifico', cursive;
      font-size: 32px;
      color: #ff1493;
    }

    .btn {
      margin-top: 20px;
    }

    #btn1 {
      background-color: #32cd32;
    }

    #btn2 {
      background-color: #ff6347;
    }

    #hands {
      width: 100px;
      margin-top: 20px;
      animation: wave 1s infinite alternate;
    }

    @keyframes wave {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(10deg); }
    }

    .fff {
      margin-top: 40px;
      font-size: 14px;
      color: #999;
    }
  </style>
</head>
<body>

  <div class="g1">
    <div class="group1">
      <!-- 12 No buttons -->
      ${Array.from({ length: 12 }, (_, i) => `<button id="btt${i + 1}">No</button>`).join('')}
    </div>

    <div class="images1">
      <video controls autoplay muted class="sadcat" src="coma.mp4"></video>
      <img class="crying" src="https://c.tenor.com/36JFV8pDtXIAAAAd/sad-your-friends-are-togheter.gif" alt="crying">
      <img class="sadboi" src="https://c.tenor.com/6CujUsC1CIkAAAAM/crying-black-guy-meme50fps-interpolated-interpolated.gif" alt="sadboi">
      <img id="sadsad" src="sadsad.jpeg" alt="sadsad">
    </div>
  </div>

  <div class="ask">
    <p>
      <span class="crush">HI CRUSH</span> <br>
      Gusto kita, can I court you?
    </p>
    <div class="btn">
      <a href="yes.html"><button id="btn1">Yes</button></a>
      <button id="btn2">No</button>
    </div>
    <img id="hands" src="image-removebg-preview.png" alt="hands">
  </div>

  <div class="g1">
    <div class="group1">
      <!-- 12 No buttons again -->
      ${Array.from({ length: 12 }, (_, i) => `<button id="bbtt${i + 1}">No</button>`).join('')}
    </div>

    <div class="images2">
      <img class="sadman" src="sadman.jpeg" alt="sadman">
      <img class="hahahuhu" src="https://c.tenor.com/dpUQLSpLPzkAAAAd/sad-man-tik-tok-meme.gif" alt="hahahuhu">
      <img id="hang" src="hang.jpeg" alt="hang">
      <img id="frog" src="cryingcat.jpeg" alt="crying cat">
    </div>
  </div>

  <div class="fff">
    <p>Created by Val</p>
  </div>

  <script src="proposalv2.js"></script>
</body>
</html>