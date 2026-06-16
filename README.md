<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">


<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;600;700;900&family=Orbitron:wght@400;700;900&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
font-family:'Cairo',sans-serif;
background:#050505;
color:white;
overflow-x:hidden;
}

body::before{
content:"";
position:fixed;
width:800px;
height:800px;
background:#7a00ff;
filter:blur(250px);
opacity:.15;
top:-300px;
right:-200px;
z-index:-2;
}

body::after{
content:"";
position:fixed;
width:700px;
height:700px;
background:#ff00ff;
filter:blur(250px);
opacity:.1;
bottom:-250px;
left:-200px;
z-index:-2;
}

header{
min-height:100vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
background:
linear-gradient(rgba(0,0,0,.7),rgba(0,0,0,.7)),
url('https://images.unsplash.com/photo-1542751371-adc38448a05e?w=1920');
background-size:cover;
background-position:center;
}

.hero h1{
font-family:'Orbitron',sans-serif;
font-size:70px;
font-weight:900;
text-transform:uppercase;
background:linear-gradient(45deg,#ffd700,#ffffff,#b300ff);
-webkit-background-clip:text;
-webkit-text-fill-color:transparent;
}

.hero p{
font-size:22px;
color:#ddd;
margin-top:15px;
}

.hero-buttons{
margin-top:35px;
display:flex;
gap:15px;
justify-content:center;
flex-wrap:wrap;
}

.btn{
padding:15px 35px;
border:none;
border-radius:50px;
font-size:18px;
font-weight:bold;
cursor:pointer;
text-decoration:none;
transition:.3s;
}

.btn-primary{
background:linear-gradient(45deg,#8a00ff,#d400ff);
color:white;
}

.btn-secondary{
background:linear-gradient(45deg,#ffd700,#ffb700);
color:black;
}

.btn:hover{
transform:translateY(-5px);
}

section{
padding:80px 10%;
}

.title{
text-align:center;
font-size:40px;
margin-bottom:50px;
font-family:'Orbitron',sans-serif;
}

.stats{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:rgba(255,255,255,.05);
border:1px solid rgba(255,255,255,.08);
border-radius:20px;
padding:30px;
text-align:center;
backdrop-filter:blur(10px);
transition:.3s;
}

.card:hover{
transform:translateY(-10px);
border-color:#a100ff;
}

.card h3{
font-size:35px;
color:#ffd700;
}

.card p{
margin-top:10px;
color:#ccc;
}

.socials{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.social{
padding:20px;
border-radius:18px;
text-align:center;
text-decoration:none;
color:white;
font-weight:bold;
font-size:20px;
transition:.3s;
}

.tiktok{
background:linear-gradient(45deg,#111,#ff0050);
}

.youtube{
background:linear-gradient(45deg,#111,#ff0000);
}

.instagram{
background:linear-gradient(45deg,#833ab4,#fd1d1d,#fcb045);
}

.discord{
background:linear-gradient(45deg,#5865F2,#404eed);
}

.social:hover{
transform:scale(1.05);
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:20px;
}

.gallery img{
width:100%;
height:250px;
object-fit:cover;
border-radius:20px;
transition:.3s;
}

.gallery img:hover{
transform:scale(1.03);
}

.live-box{
text-align:center;
background:linear-gradient(45deg,#5f00ff,#d000ff);
padding:50px;
border-radius:30px;
}

.live-box h2{
font-size:40px;
}

.live-dot{
width:15px;
height:15px;
background:red;
border-radius:50%;
display:inline-block;
margin-left:10px;
animation:pulse 1s infinite;
}

@keyframes pulse{
0%{opacity:1;}
50%{opacity:.2;}
100%{opacity:1;}
}

footer{
padding:30px;
text-align:center;
background:#090909;
border-top:1px solid rgba(255,255,255,.1);
}

footer p{
color:#999;
}

</style>
</head>

<body>

<header>

<div class="hero">

<h1>BaGGaRee Gaming</h1>

<p>
PUBG Mobile Player • TikTok Live Streamer • Content Creator
</p>

<div class="hero-buttons">

<a href="#" class="btn btn-primary">
TikTok
</a>

<a href="#" class="btn btn-secondary">
Watch Live
</a>

</div>

</div>

</header>

<section>

<h2 class="title">PUBG PROFILE</h2>

<div class="stats">

<div class="card">
<h3>5702953334</h3>
<p>PUBG ID</p>
</div>

<div class="card">
<h3>BGR</h3>
<p>Gaming Brand</p>
</div>

<div class="card">
<h3>LIVE</h3>
<p>TikTok Streaming</p>
</div>

</div>

</section>

<section>

<h2 class="title">SOCIAL LINKS</h2>

<div class="socials">

<a href="#" class="social tiktok">
TikTok
</a>

<a href="#" class="social youtube">
YouTube
</a>

<a href="#" class="social instagram">
Instagram
</a>

<a href="#" class="social discord">
Discord
</a>

</div>

</section>

<section>

<h2 class="title">GALLERY</h2>

<div class="gallery">

<img src="https://images.unsplash.com/photo-1511512578047-dfb367046420?w=800">

<img src="https://images.unsplash.com/photo-1542751371-adc38448a05e?w=800">

<img src="https://images.unsplash.com/photo-1493711662062-fa541adb3fc8?w=800">

</div>

</section>

<section>

<div class="live-box">

<h2>
<span class="live-dot"></span>
LIVE STREAM STATUS
</h2>

<p style="margin-top:20px;font-size:20px;">
تابع بثوث BaGGaRee Gaming مباشرة على TikTok
</p>

</div>

</section>

<footer>

<p>
© 2026 BaGGaRee Gaming - All Rights Reserved
</p>

</footer>

</body>
</html>
