<!doctype html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pixel Love</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet" />
  <style>
    :root {
      --bg: #fffaf9;
      --pink-1: #ffe2e6;
      --pink-2: #f9ccd4;
      --pink-3: #f39ca9;
      --pink-4: #ea7f8f;
      --pink-5: #d75f73;
      --dark: #3f2e34;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      min-height: 100vh;
      display: grid;
      place-items: center;
      background: radial-gradient(circle at 30% 10%, #ffffff 0%, var(--bg) 40%, #ffeef1 100%);
      font-family: "Press Start 2P", cursive;
      overflow: hidden;
      color: var(--dark);
    }

    .heart-field {
      position: fixed;
      inset: 0;
      z-index: 0;
      pointer-events: none;
    }

    .heart {
      position: absolute;
      color: var(--pink-5);
      font-size: 12px;
      opacity: 0.65;
      animation: drift 5s ease-in-out infinite;
      text-shadow: 1px 1px 0 #ffffff;
      user-select: none;
    }

    @keyframes drift {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-8px); }
    }

    .window {
      position: relative;
      z-index: 1;
      width: min(92vw, 560px);
      border: 7px solid var(--pink-4);
      background: var(--pink-1);
      box-shadow:
        0 0 0 4px #ffd4dc,
        0 0 0 10px var(--pink-3);
      image-rendering: pixelated;
    }

    .topbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 14px 14px 10px;
      border-bottom: 6px solid var(--pink-4);
      color: var(--pink-5);
      font-size: 1rem;
      background: #ffdbe2;
      letter-spacing: 2px;
    }

    .controls {
      display: flex;
      gap: 10px;
      align-items: center;
      font-size: 0.9rem;
      line-height: 1;
    }

    .hearts-row {
      border-bottom: 6px solid var(--pink-4);
      display: flex;
      justify-content: space-around;
      padding: 10px 8px;
      color: var(--pink-4);
      font-size: 1.9rem;
      line-height: 1;
      background: #ffd5de;
      text-shadow: 3px 3px 0 #f6b5c0;
    }

    .content {
      margin: 14px;
      border: 6px solid var(--pink-4);
      padding: 18px 18px 26px;
      text-align: center;
      background:
        linear-gradient(45deg, #f9d2da 25%, transparent 25%) -8px 0 / 16px 16px,
        linear-gradient(-45deg, #f9d2da 25%, transparent 25%) -8px 0 / 16px 16px,
        linear-gradient(45deg, transparent 75%, #f9d2da 75%) -8px 0 / 16px 16px,
        linear-gradient(-45deg, transparent 75%, #f9d2da 75%) -8px 0 / 16px 16px,
        #ffdbe2;
    }

    h1 {
      margin: 8px 0 14px;
      font-size: clamp(0.7rem, 1.8vw, 0.95rem);
      color: var(--dark);
      line-height: 1.5;
    }

    .sprite {
      width: min(220px, 60vw);
      margin: 0 auto 20px;
      display: block;
    }

    .gif-wrap {
      width: min(220px, 60vw);
      margin: 0 auto 20px;
    }

    .sprite--success {
      display: none;
      margin-bottom: 14px;
    }

    .buttons {
      position: relative;
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 18px;
      min-height: 90px;
    }

    .btn {
      border: 4px solid var(--pink-4);
      background: #ffd6df;
      color: var(--pink-5);
      font-family: inherit;
      font-size: 1rem;
      padding: 10px 18px;
      cursor: pointer;
      transition: transform 0.15s ease;
      box-shadow: 0 0 0 3px #ffe6ea;
      text-transform: uppercase;
    }

    .btn:hover {
      transform: translateY(-2px);
    }

    .no-wrapper {
      position: relative;
      width: 120px;
      height: 58px;
      transition: left 0.12s steps(2), top 0.12s steps(2);
    }

    #noBtn {
      position: absolute;
      left: 0;
      top: 0;
      width: 100%;
      height: 100%;
    }

    .result-note {
      margin: 0;
      padding: 10px 8px;
      border: 4px solid #f1b4bf;
      background: #ffdbe3;
      color: #2d2327;
      font-size: clamp(0.52rem, 1.45vw, 0.66rem);
      line-height: 1.45;
      display: none;
    }

    .window.success #promptTitle {
      margin-bottom: 8px;
    }

    .window.success .sprite--question {
      display: none;
    }

    .window.success .sprite--success {
      display: block;
    }

    .window.success .buttons {
      display: none;
    }

    .window.success .result-note {
      display: block;
    }

    @media (max-width: 500px) {
      .topbar { font-size: 0.82rem; }
      .btn { font-size: 0.82rem; }
      .buttons { min-height: 80px; }
      .no-wrapper { width: 100px; height: 52px; }
    }
  </style>
</head>
<body>
  <div class="heart-field" id="heartField"></div>

  <main class="window" id="mainWindow">
    <header class="topbar">
      <span>LOVE</span>
      <span class="controls"><span>_</span><span>▢</span><span>✕</span></span>
    </header>

    <div class="hearts-row"><span>❤</span><span>❤</span><span>❤</span></div>

    <section class="content">
      <h1 id="promptTitle">Will you be my Valentine?</h1>

      <div class="gif-wrap sprite--question">
        <div class="tenor-gif-embed" data-postid="9800642306294720318" data-share-method="host" data-aspect-ratio="1.20874" data-width="100%">
          <a href="https://tenor.com/view/scemer-staring-cat-sus-the-rock-tabby-cat-gif-9800642306294720318">Scemer Staring Cat Sticker</a>from
          <a href="https://tenor.com/search/scemer-stickers">Scemer Stickers</a>
        </div>
      </div>

      <div class="gif-wrap sprite--success">
        <div class="tenor-gif-embed" data-postid="6836240159603239538" data-share-method="host" data-aspect-ratio="1" data-width="100%">
          <a href="https://tenor.com/view/jh-gif-6836240159603239538">Jh GIF</a>from
          <a href="https://tenor.com/search/jh-gifs">Jh GIFs</a>
        </div>
      </div>

      <div class="buttons" id="buttonsArea">
        <button class="btn" id="yesBtn" type="button">YES</button>
        <div class="no-wrapper" id="noWrap">
          <button class="btn" id="noBtn" type="button">NO</button>
        </div>
      </div>

      <p class="result-note">Valentine Date: en tu casa a las 1:30 para hacer galletas ❤️💕!</p>
    </section>
  </main>

  <script>
    const field = document.getElementById("heartField");
    const yesBtn = document.getElementById("yesBtn");
    const noBtn = document.getElementById("noBtn");
    const noWrap = document.getElementById("noWrap");
    const mainWindow = document.getElementById("mainWindow");
    const promptTitle = document.getElementById("promptTitle");

    for (let i = 0; i < 130; i++) {
      const heart = document.createElement("span");
      heart.className = "heart";
      heart.textContent = "❤";
      heart.style.left = `${Math.random() * 100}%`;
      heart.style.top = `${Math.random() * 100}%`;
      heart.style.fontSize = `${8 + Math.random() * 8}px`;
      heart.style.animationDelay = `${Math.random() * 4}s`;
      field.appendChild(heart);
    }

    function moveNoButton() {
      const area = document.getElementById("buttonsArea").getBoundingClientRect();
      const w = noWrap.offsetWidth;
      const h = noWrap.offsetHeight;
      const maxX = Math.max(0, area.width - w);
      const maxY = Math.max(0, area.height - h);
      noWrap.style.left = `${Math.random() * maxX - maxX / 2}px`;
      noWrap.style.top = `${Math.random() * maxY - maxY / 3}px`;
    }

    noBtn.addEventListener("click", (event) => {
      event.preventDefault();
      moveNoButton();
    });

    yesBtn.addEventListener("click", () => {
      promptTitle.textContent = "Yippeeee!";
      mainWindow.classList.add("success");
    });
  </script>
  <script type="text/javascript" async src="https://tenor.com/embed.js"></script>
</body>
</html>
