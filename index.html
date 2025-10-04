<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Do You Love Me? ❤️</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #ff5f6d, #ffc371);
      background-size: 200% 200%;
      animation: gradientMove 10s ease infinite;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      overflow: hidden;
      margin: 0;
    }

    @keyframes gradientMove {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .img-wrapper {
      position: relative;
      display: inline-block;
      margin-bottom: 15px;
    }

    .img-wrapper img {
      width: 200px;
      border-radius: 20px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.3);
    }

    .heart {
      position: absolute;
      font-size: 24px;
      animation: floatUp 4s ease-in infinite;
      opacity: 0;
    }

    @keyframes floatUp {
      0% {
        transform: translateY(0) scale(1);
        opacity: 1;
      }
      100% {
        transform: translateY(-200px) scale(1.5);
        opacity: 0;
      }
    }

    h1 {
      font-size: 2rem;
      color: #fff;
      text-shadow: 0 0 10px rgba(0,0,0,0.4);
      margin-bottom: 30px;
    }

    .btn {
      font-size: 1.2rem;
      padding: 10px 20px;
      border: none;
      border-radius: 30px;
      cursor: pointer;
      margin: 10px;
      transition: 0.3s;
      position: relative;
    }

    #yesBtn {
      background: #4CAF50;
      color: #fff;
      position: absolute;
    }

    #noBtn {
      background: #f44336;
      color: #fff;
      position: relative;
      z-index: 2;
    }

    #flagBox {
      margin-top: 15px;
      font-size: 1.2rem;
      color: #fff;
      text-shadow: 0 2px 5px rgba(0,0,0,0.3);
      display: none;
    }
  </style>
</head>
<body>

  <div class="img-wrapper">
    <img src="image.png" alt="Love Image">
    <span class="heart" style="left:20%; animation-delay:0s;">❤️</span>
    <span class="heart" style="left:50%; animation-delay:1s;">💖</span>
    <span class="heart" style="left:80%; animation-delay:2s;">💕</span>
    <span class="heart" style="left:30%; animation-delay:1.5s;">💓</span>
    <span class="heart" style="left:70%; animation-delay:0.5s;">💘</span>
  </div>

  <h1>Do you love me? 💖</h1>

  <div>
    <button id="yesBtn" class="btn">Yes 😍</button>
    <button id="noBtn" class="btn">No 😐</button>
  </div>

  <div id="flagBox"></div>

  <script>
    const yesBtn = document.getElementById('yesBtn');
    const noBtn = document.getElementById('noBtn');
    const flagBox = document.getElementById('flagBox');

    // Posisi awal random
    function setRandomPosition(btn) {
      const x = Math.floor(Math.random() * (window.innerWidth - btn.offsetWidth - 20));
      const y = Math.floor(Math.random() * (window.innerHeight - btn.offsetHeight - 20));
      btn.style.left = x + 'px';
      btn.style.top = y + 'px';
    }

    setRandomPosition(yesBtn);

    // Hover → tombol Yes kabur posisi baru
    yesBtn.addEventListener('mouseenter', () => {
      setRandomPosition(yesBtn);
    });

    // Klik Yes → ambil flag.txt
    yesBtn.addEventListener('click', async () => {
      try {
        const res = await fetch('flag.txt');
        const flag = await res.text();
        flagBox.textContent = flag.trim();
        flagBox.style.display = 'block';
      } catch (err) {
        flagBox.textContent = 'Gagal ambil flag 😅';
        flagBox.style.display = 'block';
      }
    });

    // Klik No → teks “yahh ckp tw 😢”
    noBtn.addEventListener('click', () => {
      flagBox.textContent = 'yahh ckp tw 😢';
      flagBox.style.display = 'block';
    });

    // Resize window → reposition
    window.addEventListener('resize', () => setRandomPosition(yesBtn));
  </script>

</body>
</html>
