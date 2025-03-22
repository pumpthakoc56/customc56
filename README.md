<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cute Theme Store</title>
<center>
  <style>
    /* Customize the background with your image */
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      background-image: url('https://www.dropbox.com/scl/fi/916v77f7olp7hvwpavsf2/20250322_170441.jpg?rlkey=f3ic69jbvknd2v0odaujuflfp&st=lsjhiy2f&dl=1'); /* Add your own image URL here */
      background-size: cover;
      background-position: center;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    header {
      background-color: rgba(255, 102, 178, 0.9); /* Semi-transparent for background image */
      width: 100%;
      padding: 10px 20px;
      text-align: center;
      border-bottom: 5px solid #ff3385;
      margin-top: 0px;
      border-radius: 0px;
    }
    header h1 {
      color: white;
      font-size: 35px;
      margin: 0;
      letter-spacing: 2px;
      font-family: 'Cursive', sans-serif;
    }
    header p {
      color: white;
      font-size: 18px;
      margin-top: 10px;
    }

    nav {
      background-color: #ff99cc;
      width: 10%;
      padding: 12px 0;
      display: flex;
      justify-content: center;
      gap: 15px;
      margin-top: 0px;
      border-radius: 0px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-size: 18px;
      padding: 12px 25px;
      background-color: #ff66b2;
      border-radius: 25px;
      transition: all 0.3s ease;
    }
    nav a:hover {
      background-color: #ff3385;
      transform: scale(1.1);
    }
    
    nav1 {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin: 5px 0;
        }

        nav1 a {
            text-decoration: none;
            padding: 5px 10px;
            background: #ff9a9e;
            color: white;
            border-radius: 10px;
            font-weight: bold;
            transition: all 0.3s ease;
        }

        nav1 a:hover {
            background: #000000;
        }
    .search-bar {
      padding: 10px;
      width: 75%;
      border-radius: 15px;
      border: none;
      font-size: 18px;
      margin-right: 10px;
    }
    .search-btn {
      padding: 12px 20px;
      background-color: #ff3385;
      color: white;
      border-radius: 30px;
      border: none;
      font-size: 18px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    .search-btn:hover {
      background-color: #ff66b2;
    }

    .theme-container {
      display: grid;
      grid-template-columns: repeat(2, 1fr); /* 2 cards per row */
      gap: 15px;
      padding: 15px;
      margin-top: 0ppx;
      width: 100%;
      max-width: 1000px;
    }

    .theme-card {
      background-color: white;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 0px 0px rgba(0, 0, 0, 0.1);
      text-align: center;
      transition: transform 0.3s ease;
      border: 2px solid #ff66b2;
      overflow: hidden;
      transition: transform 0.2s ease-in-out;
    }

    .theme-card img {
      width: 150px;
      height: 150px;
      object-fit: cover;
      border-radius: 10%;
      transition: transform 0.3s ease;
    }

    .theme-card:hover {
      transform: translateY(-8px); /* Slight hover lift */
      box-shadow: 0 0px 0px rgba(0, 0, 0, 0.0);
    }

    .theme-card img:hover {
      transform: scale(1.15); /* Slight image zoom */
    }

    .theme-card h3 {
      color: #ff66b2;
      font-size: 20px;
      margin: 0px 0;
    }

    .theme-card p {
      color: #888;
      font-size: 16px;
      margin-bottom: 20px;
    }

    .theme-card button {
      background-color: #ff66b2;
      color: white;
      padding: 15px;
      border: none;
      border-radius: 10px;
      font-size: 18px;
      cursor: pointer;
      width: 100%;
      transition: background-color 0.3s;
    }

    .theme-card button:hover {
      background-color: #ff3385;
    }

    .footer {
      background-color: rgba(255, 102, 178, 0.9);
      color: white;
      text-align: center;
      padding: 20px;
      width: 100%;
      margin-top: 40px;
      border-radius: 0px;
    }
    .footer p {
      font-size: 16px;
      margin: 0;
    }

  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Telegram Template Myanmar</h1>
    <p>Thank you to each and every one who visits the website</p></p>
  </header>

  <!-- Main Content Container -->
  <div class="theme-container">
    <div class="theme-card">
      <img src="https://www.dropbox.com/scl/fi/jxgmnmysz8mvh2tmohrxd/IMG_20250321_172239_047.jpg?rlkey=52a98lf2daxekqe9tbsyp1fcb&st=dj2ywin3&dl=1" alt="Theme 1">
      <h3>Cute Theme 1</h3>
      <p>Minimalistic design for clean aesthetics.</p>
      <button>View Theme</button>
    </div>
    <div class="theme-card">
      <img src="https://www.dropbox.com/scl/fi/69jch961v6ihaw850062g/IMG_20250322_171316_909.jpg?rlkey=bke0cohhybtvsa3tefi11io95&st=xcuzyema&dl=1" alt="Theme 2">
      <h3>Cute Theme 2</h3>
      <p>Vibrant and colorful for a playful look.</p>
      <button>View Theme</button>
    </div>
    <div class="theme-card">
      <img src="https://www.dropbox.com/scl/fi/d0bmoxm6cjf1meqvyarr1/IMG_20250322_171325_877.jpg?rlkey=sd1t7j1pw24n3d7wltmyno2d6&st=hh4n0hwt&dl=1" alt="Theme 3">
      <h3>Cute Theme 3</h3>
      <p>Perfect for a fun and quirky experience.</p>
      <button>View Theme</button>
    </div>
    <div class="theme-card">
      <img src="https://www.dropbox.com/scl/fi/gbk8c2kwh6uvq2ni5zoai/IMG_20250322_171329_560.jpg?rlkey=19sz9tk3n9ukvy28b80w2fihr&st=t2ua5e1j&dl=1" alt="Theme 4">
      <h3>Cute Theme 4</h3>
      <p>Light and dreamy for relaxing vibes.</p>
      <button>View Theme</button>
    </div>
  </div>
    <div class="theme-container">
    <div class="theme-card">
      <img src="https://www.dropbox.com/scl/fi/onyvtcxp1298zvc12jrl5/IMG_20250322_171336_413.jpg?rlkey=4hijs292rgziv5bvbhngw450s&st=gqhdiw0u&dl=1" alt="Theme 1">
      <h3>Cute Theme 1</h3>
      <p>Minimalistic design for clean aesthetics.</p>
      <button>View Theme</button>
    </div>
    <div class="theme-card">
      <img src="https://www.dropbox.com/scl/fi/115psby3islnpetx3m4tq/IMG_20250322_171349_478.jpg?rlkey=0dywxbuqs8wmzsqlflplky06k&st=yqawz8a8&dl=1" alt="Theme 2">
      <h3>Cute Theme 2</h3>
      <p>Vibrant and colorful for a playful look.</p>
      <button>View Theme</button>
    </div>
    <div class="theme-card">
      <img src="https://www.dropbox.com/scl/fi/wnrh5nmpzv2afjc02y916/20250320_065843.jpg?rlkey=0hza3iqlqos9cebrwjsr7hnfn&st=ogpn0v34&dl=1" alt="Theme 3">
      <h3>Cute Theme 3</h3>
      <p>Perfect for a fun and quirky experience.</p>
      <button>View Theme</button>
    </div>
    <div class="theme-card">
      <img src="https://www.dropbox.com/scl/fi/vghzryfg5pv6xfsp2hwyq/IMG_20250322_171353_438.jpg?rlkey=yidhecdmh3wljam7zh839mea7&st=2m4k9np7&dl=1" alt="Theme 4">
      <h3>Cute Theme 4</h3>
      <p>Light and dreamy for relaxing vibes.</p>
      <button>View Theme</button>
    </div>
  </div>
  <div class="theme-container">
    <div class="theme-card">
      <img src="https://www.dropbox.com/scl/fi/93icqck6091a3xiifrtg4/IMG_20250322_171357_533.jpg?rlkey=njeobkmqc8b9ml2dbnj8qau2g&st=1r4c6kj9&dl=1" alt="Theme 1">
      <h3>Cute Theme 1</h3>
      <p>Minimalistic design for clean aesthetics.</p>
      <button>View Theme</button>
    </div>
    <div class="theme-card">
      <img src="https://www.dropbox.com/scl/fi/lv6tjeyg7l8b4efg3x2ds/IMG_20250322_171401_048.jpg?rlkey=5j0qi1wyw2sgcsyd0ao87zozx&st=fjqpdjnd&dl=1" alt="Theme 2">
      <h3>Cute Theme 2</h3>
      <p>Vibrant and colorful for a playful look.</p>
      <button>View Theme</button>
    </div>
    <div class="theme-card">
      <img src="https://www.dropbox.com/scl/fi/7zx14c4nf6jel0kfgao7p/IMG_20250322_171408_325.jpg?rlkey=nnvus9pk7501m9au4q2biu3s5&st=kcdx6n9r&dl=1" alt="Theme 3">
      <h3>Cute Theme 3</h3>
      <p>Perfect for a fun and quirky experience.</p>
      <button>View Theme</button>
    </div>
    <div class="theme-card">
      <img src="https://www.dropbox.com/scl/fi/4woob39hcc2tb1pqjbj3t/IMG_20250322_171412_740.jpg?rlkey=t5wrstf0k2vn164o988deyl9t&st=izf5fdgo&dl=1" alt="Theme 4">
      <h3>Cute Theme 4</h3>
      <p>Light and dreamy for relaxing vibes.</p>
      <button>View Theme</button>
    </div>
  </div>
  <!-- Footer -->
  <div class="footer">
    <p>"Please join the 'Telegram Template Myanmar C56' channel by clicking on the JOIN CHANNEL below to visit and explore."
 </p>
    <nav1> <a href="https://t.me/pump_telegram_theme">JOIN CHANNEL</a></nav1>
  </div>
</body>
</html>
<center/>
