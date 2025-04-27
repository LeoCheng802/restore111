<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>騰揚開發會場佈置</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Noto Sans TC', '微軟正黑體', sans-serif; }
    body { background: url('https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/assest/images/%E8%8D%B7%E8%8A%B1.jpg') no-repeat center center fixed; background-size: cover; position: relative; min-height: 100vh; }
    body::after { content: ""; position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(255, 255, 255, 0.7); z-index: -1; }
    header { text-align: center; padding: 2rem 1rem; color: darkgreen; }
    header img { max-width: 90%; height: auto; margin-bottom: 1rem; border-radius: 10px; }
    header h1 { font-size: 3rem; margin-bottom: 1rem; }
    header p { font-size: 1.2rem; }
    .overview { text-align: center; padding: 2rem 1rem; }
    .overview img { max-width: 90%; height: auto; border-radius: 10px; margin-top: 1rem; }
    .overview h2 { font-size: 2rem; color: darkgreen; margin-bottom: 1rem; }
    .product-grid { display: grid; grid-template-columns: repeat(2, 1fr); gap: 1rem; padding: 2rem; }
    @media (min-width: 768px) {
      .product-grid { grid-template-columns: repeat(3, 1fr); }
    }
    @media (min-width: 1024px) {
      .product-grid { grid-template-columns: repeat(4, 1fr); }
    }
    .product-card { background: white; border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.2); overflow: hidden; text-align: center; transition: transform 0.4s, box-shadow 0.4s; }
    .product-card:hover { transform: translateY(-10px) scale(1.03); box-shadow: 0 8px 16px rgba(0,0,0,0.3); }
    .product-card img { width: 100%; height: 150px; object-fit: cover; transition: transform 0.3s ease; }
    .product-card img:hover { transform: scale(1.1); }
    .product-card h2 { font-size: 1.2rem; margin: 0.5rem 0; color: darkgreen; }
    .product-card button { background-color: darkgreen; color: white; border: none; padding: 0.5rem 1rem; margin-bottom: 1rem; border-radius: 5px; cursor: pointer; transition: background 0.3s; font-size: 0.9rem; }
    .product-card button:hover { background-color: green; }
    .back-to-top { text-align: center; margin: 2rem; }
    .back-to-top a { display: inline-block; padding: 0.8rem 1.5rem; background-color: darkgreen; color: white; border-radius: 5px; text-decoration: none; transition: background 0.3s; }
    .back-to-top a:hover { background-color: green; }
    footer { text-align: center; padding: 2rem; font-size: 1rem; color: gray; }
  </style>
</head>
<body>
  <header id="top">
    <img src="/mnt/data/名片.jpg" alt="名片">
    <h1>騰揚開發會場佈置</h1>
    <p>治喪追思 🌼 孝獅護主 🌼 靈獅接引 <br> 雄威體面 🏵️ 莊嚴隆重 🏵️ 代送禮品</p>
    <p>歡迎來電：0976-054-419</p>
  </header>

  <section class="overview">
    <h2>產品總覽</h2>
    <img src="/mnt/data/名片2.jpg" alt="產品總覽">
  </section>

  <section class="product-grid">
    <div class="product-card"><img src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/assest/images/%E8%B6%85%E7%B4%9A%E5%B7%A8%E7%84%A1%E9%9C%B8%E7%B1%B3%E5%A1%943.jpg" alt="超級巨無霸米塔"><h2>超級巨無霸米塔</h2><button>查看產品</button></div>
    <div class="product-card"><img src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/%E5%BB%A3%E5%91%8A%E8%A8%AD%E8%A8%88%E5%9C%96/%E4%B8%AD%E5%B7%A8.jpg" alt="中型巨無霸米塔"><h2>中型巨無霸米塔</h2><button>查看產品</button></div>
    <div class="product-card"><img src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/assest/images/%E5%B9%BB%E5%BD%A9%E7%B1%B3%E5%A1%94.jpg" alt="幻彩平安米塔"><h2>幻彩平安米塔</h2><button>查看產品</button></div>
    <div class="product-card"><img src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/assest/images/%E5%B9%B3%E5%AE%89%E7%B1%B3%E5%A1%94.jpg" alt="燈光平安米塔"><h2>燈光平安米塔</h2><button>查看產品</button></div>
    <div class="product-card"><img src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/assest/images/%E5%B7%A8%E7%84%A1%E9%9C%B8%E8%93%AE%E8%8A%B1%E5%A1%944.jpg" alt="巨無霸蓮花塔"><h2>巨無霸蓮花塔</h2><button>查看產品</button></div>
    <div class="product-card"><img src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/assest/images/%E8%93%AE%E8%8A%B1%E5%A1%94.jpg" alt="蓮花塔"><h2>蓮花塔</h2><button>查看產品</button></div>
    <div class="product-card"><img src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/%E5%BB%A3%E5%91%8A%E8%A8%AD%E8%A8%88%E5%9C%96/%E7%9B%A4%E9%BE%8D%E8%93%AE%E8%8A%B1%E5%A1%94.jpg" alt="九品盤龍塔"><h2>九品盤龍塔</h2><button>查看產品</button></div>
    <div class="product-card"><img src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/assest/images/%E5%9A%B4%E9%81%B8%E6%AA%80%E9%A6%99%E5%A1%94.jpg" alt="嚴選檀香塔"><h2>嚴選檀香塔</h2><button>查看產品</button></div>
    <div class="product-card"><img src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/assest/images/%E8%93%AE%E8%8A%B1%E5%A1%94%EF%BC%8C%E9%87%91%E7%A3%9A%E5%A1%94.jpg" alt="金磚塔"><h2>金磚塔</h2><button>查看產品</button></div>
    <div class="product-card"><img src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/%E5%BB%A3%E5%91%8A%E8%A8%AD%E8%A8%88%E5%9C%96/%E9%96%8B%E5%B9%95%E5%9B%8D%E7%8D%85.jpg" alt="開幕囍獅（紅獅）"><h2>開幕囍獅（紅獅）</h2><button>查看產品</button></div>
    <div class="product-card"><img src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/%E5%BB%A3%E5%91%8A%E8%A8%AD%E8%A8%88%E5%9C%96/%E6%97%A5%E5%BC%8F%E9%85%92%E6%AB%83.jpg" alt="日式酒櫃"><h2>日式酒櫃</h2><button>查看產品</button></div>
    <div class="product-card"><img src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/%E5%BB%A3%E5%91%8A%E8%A8%AD%E8%A8%88%E5%9C%96/%E9%9D%88%E7%8D%85.jpg" alt="守孝靈獅（幻彩）"><h2>守孝靈獅（幻彩）</h2><button>查看產品</button></div>
    <div class="product-card"><img src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/assest/images/%E5%AE%88%E5%AD%9D%E9%9D%88%E7%8D%852.jpg" alt="守孝靈獅（白光）"><h2>守孝靈獅（白光）</h2><button>查看產品</button></div>
    <div class="product-card"><img src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/assest/images/%E7%B1%B3%E6%AB%83%E9%9D%88%E7%8D%85.jpg" alt="米櫃靈獅（幻彩）"><h2>米櫃靈獅（幻彩）</h2><button>查看產品</button></div>
    <div class="product-card"><img src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/%E5%BB%A3%E5%91%8A%E8%A8%AD%E8%A8%88%E5%9C%96/%E9%85%92%E6%AB%83%E9%9D%88%E7%8D%85.jpg" alt="酒櫃靈獅（白光）"><h2>酒櫃靈獅（白光）</h2><button>查看產品</button></div>
    <div class="product-card"><img src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/assest/images/%E6%8C%81%E7%B6%93%E5%A4%A7%E4%BD%9B.jpg" alt="持經觀音大佛"><h2>持經觀音大佛</h2><button>查看產品</button></div>
    <div class="product-card"><img src="https://raw.githubusercontent.com/LeoCheng802/restore111/refs/heads/main/%E5%BB%A3%E5%91%8A%E8%A8%AD%E8%A8%88%E5%9C%96/%E5%B0%8F%E4%BD%9B.jpg" alt="渡化觀音小佛"><h2>渡化觀音小佛</h2><button>查看產品</button></div>
  </section>

  <div class="back-to-top">
    <a href="#top">回到最上層</a>
  </div>

  <footer>
    &copy; 2025 騰揚開發 | 專車配送 | 長期優惠
  </footer>
</body>
</html>
