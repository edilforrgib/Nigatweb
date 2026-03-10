<!DOCTYPE html>
<html lang="am">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ንጋት የዜማ መሳሪያዎች</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
<style>

/* Base */
*{margin:0;padding:0;box-sizing:border-box;font-family:Poppins,sans-serif;}
body{background:url("background.jpg") no-repeat center/cover fixed;color:white;overflow-x:hidden;}

/* Overlay */
.overlay{background:rgba(0,0,0,0.6);min-height:100vh;}

/* Hero */
header{
text-align:center;padding:100px 20px;
background:linear-gradient(270deg,#ff4e50,#f9d423,#24c6dc);
background-size:600% 600%;
animation:gradientMove 15s ease infinite;
position:relative;
z-index:1;
}
@keyframes gradientMove{0%{background-position:0% 50%}50%{background-position:100% 50%}100%{background-position:0% 50%}}
header h1{font-size:48px;font-weight:700;margin-bottom:10px;text-shadow:0 2px 10px rgba(0,0,0,0.6);}
header p{font-size:20px;opacity:.9;margin-bottom:20px;}
.order-tag{display:inline-block;background:#fff;color:#ff4e50;padding:12px 30px;border-radius:30px;font-weight:bold;font-size:18px;animation:pulse 2s infinite;}
@keyframes pulse{0%{transform:scale(1)}50%{transform:scale(1.1)}100%{transform:scale(1)}}

/* Description */
.description{padding:40px 20px;text-align:center;font-size:18px;line-height:1.8;}

/* Product Grid */
.products{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:40px;padding:40px;}
.card{background:rgba(255,255,255,0.15);backdrop-filter:blur(15px);border-radius:25px;padding:20px;text-align:center;transition:0.5s;animation:float 4s ease-in-out infinite;transform-style:preserve-3d;}
@keyframes float{0%{transform:translateY(0)}50%{transform:translateY(-15px)}100%{transform:translateY(0)}}
.card:hover{transform:scale(1.08) rotateY(10deg) rotateX(5deg);box-shadow:0 20px 50px rgba(0,0,0,0.5);}
.card img{width:100%;height:220px;object-fit:cover;border-radius:20px;margin-bottom:15px;transition:0.3s;}

/* Order Section */
.contact{padding:50px;text-align:center;background:rgba(0,0,0,0.65);}
.order-buttons{display:flex;justify-content:center;gap:25px;flex-wrap:wrap;margin-top:30px;}
button{padding:16px 32px;border:none;border-radius:30px;font-size:16px;cursor:pointer;transition:0.3s;}
.call{background:#28a745;color:white;}
.telegram{background:#0088cc;color:white;}
.whatsapp{background:#25D366;color:white;}
button:hover{transform:scale(1.1);}

/* Footer */
footer{text-align:center;padding:25px;opacity:.8;}

/* Music Wave Animation */
.wave-container{position:relative;width:100%;height:50px;margin-top:20px;overflow:hidden;}
.wave{position:absolute;width:200%;height:100%;background:linear-gradient(to right,#ff512f,#f9d423,#24c6dc);animation:waveMove 4s linear infinite;}
@keyframes waveMove{0%{transform:translateX(0)}100%{transform:translateX(-50%)}}

</style>
</head>
<body>
<div class="overlay">

<header>
<h1>🌅 ንጋት የዜማ መሳሪያዎች</h1>
<p>Nigat Melody Instruments</p>
<div class="order-tag">#Order_now</div>
<div class="wave-container"><div class="wave"></div></div>
</header>

<section class="description">
<h2>ንጋት ዜማ</h2>
<p>
በከፍተኛ ጥራት የተመረቱ <br>
Glossy • Reflective • Waterproof<br><br>
👉 በገና <br>
👉 ክራር <br>
👉 ቤዝ ክራር <br>
👉 መሰንቆ <br>
👉 ዋሽንት <br>
👉 ቦርሳ
</p>
</section>

<section class="products">
<div class="card"><img src="begenna.jpg"><h3>በገና</h3></div>
<div class="card"><img src="krar.jpg"><h3>ክራር</h3></div>
<div class="card"><img src="basekrar.jpg"><h3>ቤዝ ክራር</h3></div>
<div class="card"><img src="masenqo.jpg"><h3>መሰንቆ</h3></div>
<div class="card"><img src="washint.jpg"><h3>ዋሽንት</h3></div>
<div class="card"><img src="bag.jpg"><h3>ቦርሳ</h3></div>
</section>

<section class="contact">
<h2>📦 Order Now</h2>
<p>☎️ 0920300011 / 0991109365</p>
<p>🚖 በፍጥነት ይዘዙን ባሉበት ቦታ ያለምንም ተጨማሪ ክፍያ እናደርሳለን 🏍</p>
<p>📲 Telegram: @Nigatmelody</p>
<p>🏢 አድራሻ : ኮልፌ 18 አጠናተራ ፊሊጶስ ቤተክርስቲያን ዝቅ ብሎ</p>

<div class="order-buttons">
<a href="tel:0920300011"><button class="call">📞 Call</button></a>
<a href="https://t.me/Nigatmelody" target="_blank"><button class="telegram">📲 Telegram</button></a>
<a href="https://wa.me/251920300011" target="_blank"><button class="whatsapp">💬 WhatsApp</button></a>
</div>
</section>

<footer>© 2026 ንጋት የዜማ መሳሪያዎች</footer>

</div>
</body>
</html>
