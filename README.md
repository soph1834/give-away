<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pink Room Melbourne Giveaway</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #fff;
      overflow: hidden;
    }

    /* Scrolling container */
    .feed {
      width: 100vw;
      height: 100vh;
      display: flex;
      flex-direction: column;
      overflow: hidden;
      position: relative;
    }

    .post {
      height: 100vh;
      background-size: cover;
      background-position: center;
      animation: scrollFeed 12s linear infinite;
    }

    /* Replace with images of your Instagram posts */
    .post1 { background-image: url('https://www.instagram.com/p/DCLupKLzQOG/?utm_source=ig_web_copy_link&igsh=MzRlODBiNWFlZA=='); }
    .post2 { background-image: url('https://www.instagram.com/p/DBsoi42PYai/?utm_source=ig_web_copy_link&igsh=MzRlODBiNWFlZA=='); }
    .post3 { background-image: url('https://www.instagram.com/reel/DBoFWtiKMss/?utm_source=ig_web_copy_link&igsh=MzRlODBiNWFlZA=='); }

    /* Popup styles */
    .popup {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%) scale(0);
      background: rgba(255, 255, 255, 0.9);
      border: 2px solid #ffc0cb;
      padding: 20px;
      text-align: center;
      color: #ff69b4;
      font-size: 24px;
      font-weight: bold;
      border-radius: 10px;
      animation: showPopup 12s linear infinite;
    }

    .popup h1 {
      margin: 0 0 10px 0;
    }

    .popup p {
      margin: 0;
      font-size: 16px;
      color: #555;
    }

    /* Animations */
    @keyframes scrollFeed {
      0%, 33% { transform: translateY(0); }
      34%, 66% { transform: translateY(-100vh); }
      67%, 100% { transform: translateY(-200vh); }
    }

    @keyframes showPopup {
      0%, 75% { transform: translate(-50%, -50%) scale(0); opacity: 0; }
      76%, 100% { transform: translate(-50%, -50%) scale(1); opacity: 1; }
    }
  </style>
</head>
<body>
  <div class="feed">
    <div class="post post1"></div>
    <div class="post post2"></div>
    <div class="post post3"></div>
    <div class="popup">
      <h1>🎉 GIVEAWAY ALERT! 🎉</h1>
      <p>Win a Romantic Room Setup by <strong>Pink Room Melbourne</strong></p>
      <p>In collaboration with <strong>BouquetbyM</strong></p>
    </div>
  </div>
</body>
</html>
