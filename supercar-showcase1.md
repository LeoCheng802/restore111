<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>超跑展示專區</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Noto Sans TC', '微軟正黑體', sans-serif; scroll-behavior: smooth; }
    body { background: #000; color: #fff; min-height: 100vh; }
    header { text-align: center; padding: 2rem 1rem; background: linear-gradient(to bottom, #111, #000); }
    header h1 { font-size: 3rem; margin-bottom: 1rem; color: #ffd700; text-shadow: 0 0 15px #ffd700; }
    header p { font-size: 1.2rem; color: #ccc; }

    .overview { text-align: center; padding: 2rem 1rem; }
    .overview p { font-size: 1.3rem; color: #bbb; max-width: 800px; margin: auto; line-height: 1.8; }

    .product-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1.5rem; padding: 2rem; }
    .product-card { background: #111; border-radius: 10px; overflow: hidden; text-align: center; transition: transform 0.4s, box-shadow 0.4s; box-shadow: 0 4px 10px rgba(255, 215, 0, 0.3); }
    .product-card:hover { transform: scale(1.05); box-shadow: 0 6px 14px rgba(255, 215, 0, 0.5); }
    .product-card img { width: 100%; height: 200px; object-fit: cover; }
    .product-card h2 { margin: 1rem 0; font-size: 1.2rem; color: #ffd700; }

    .video-section { text-align: center; padding: 2rem; background: #111; }
    .video-section video { width: 90%; border-radius: 10px; box-shadow: 0 0 20px rgba(255, 215, 0, 0.5); }

    footer { text-align: center; padding: 1rem; background: #111; color: #888; font-size: 0.9rem; }
  </style>
</head>
<body>
  <header>
    <h1>超跑展示專區</h1>
    <p>專業規劃｜隆重呈現</p>
  </header>

  <section class="overview">
    <p>提供開幕慶典與治喪儀式之尊榮用車服務，以尊貴氣勢與莊重典雅，為每一場重要時刻，增添無上的禮遇與敬意。</p>
  </section>

  <section class="product-grid">
    <div class="product-card">
      <img src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/assest/images/%E5%9C%96%E6%AA%94/%E5%B0%8F%E7%89%9B%20(1).jpg" alt="小牛 1">
      <h2>Huracán 小牛 (1)</h2>
    </div>
    <div class="product-card">
      <img src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/assest/images/%E5%9C%96%E6%AA%94/%E5%B0%8F%E7%89%9B%20(2).jpg" alt="小牛 2">
      <h2>Huracán 小牛 (2)</h2>
    </div>
    <div class="product-card">
      <img src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/assest/images/%E5%9C%96%E6%AA%94/%E5%B0%8F%E7%89%9B%20(3).jpg" alt="小牛 3">
      <h2>Huracán 小牛 (3)</h2>
    </div>
    <div class="product-card">
      <img src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/assest/images/%E5%9C%96%E6%AA%94/%E5%A4%A7%E7%89%9B%20(1).jpg" alt="大牛 1">
      <h2>Aventador 大牛 (1)</h2>
    </div>
    <div class="product-card">
      <img src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/assest/images/%E5%9C%96%E6%AA%94/%E5%A4%A7%E7%89%9B%20(2).jpg" alt="大牛 2">
      <h2>Aventador 大牛 (2)</h2>
    </div>
  </section>

  <section class="video-section">
    <h2>現場實拍影片</h2>
    <video controls>
      <source src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/assest/images/%E5%9C%96%E6%AA%94/%E5%B0%8F%E7%89%9B%20(3).jpg" type="video/mp4">
      您的瀏覽器不支援影片播放。
    </video>
  </section>

  <footer>
    &copy; 2025 超跑展示專區｜用心成就每一份尊榮
  </footer>
</body>
</html>
