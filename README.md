<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>NoeGamingOficial</title>

<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Orbitron',sans-serif;
}

body{
min-height:100vh;
display:flex;
justify-content:center;
align-items:center;
background:url("tu-foto.jpg") center center/cover no-repeat;
overflow:hidden;
position:relative;
}

/* Overlay gaming */

body::before{
content:"";
position:absolute;
inset:0;
background:
linear-gradient(
135deg,
rgba(5,5,20,.92),
rgba(20,0,40,.80),
rgba(0,40,80,.65)
);
}

/* Partículas */

.particles{
position:absolute;
width:100%;
height:100%;
overflow:hidden;
z-index:0;
}

.particles span{
position:absolute;
width:4px;
height:4px;
background:white;
border-radius:50%;
opacity:.8;
animation:float 15s linear infinite;
}

@keyframes float{
0%{
transform:translateY(100vh);
opacity:0;
}
50%{
opacity:1;
}
100%{
transform:translateY(-100vh);
opacity:0;
}
}

/* Tarjeta principal */

.container{
position:relative;
z-index:2;

width:90%;
max-width:700px;

padding:45px;

border-radius:30px;

background:rgba(255,255,255,.05);

backdrop-filter:blur(20px);

border:1px solid rgba(255,255,255,.15);

box-shadow:
0 0 15px #7b2cff,
0 0 30px #00e5ff,
0 0 60px #7b2cff;
}

/* Logo */

.logo{
width:140px;
height:140px;

margin:auto;

border-radius:50%;

display:flex;
justify-content:center;
align-items:center;

font-size:48px;
font-weight:900;
color:white;

background:
linear-gradient(
135deg,
#7b2cff,
#00e5ff
);

box-shadow:
0 0 20px #7b2cff,
0 0 40px #00e5ff,
0 0 70px #7b2cff;

animation:pulse 3s infinite;
}

@keyframes pulse{
50%{
transform:scale(1.08);
}
}

h1{
text-align:center;
color:white;
font-size:3rem;
margin-top:25px;

text-shadow:
0 0 10px #7b2cff,
0 0 30px #00e5ff;
}

.tagline{
margin-top:15px;
text-align:center;
color:#e0e0e0;
line-height:1.8;
font-size:15px;
}

/* Stats */

.stats{
display:flex;
justify-content:space-around;
margin:35px 0;
}

.stat{
text-align:center;
color:white;
}

.stat h2{
color:#00e5ff;
margin-bottom:5px;
}

/* Botones */

.links{
display:grid;
gap:15px;
}

.links a{
text-decoration:none;
color:white;

padding:18px;

font-weight:700;

border-radius:15px;

background:rgba(255,255,255,.08);

border:1px solid rgba(255,255,255,.15);

transition:.4s;
}

.links a:hover{

transform:
translateY(-6px)
scale(1.05);

background:
linear-gradient(
90deg,
#7b2cff,
#00e5ff
);

box-shadow:
0 0 15px #7b2cff,
0 0 35px #00e5ff,
0 0 60px #7b2cff;
}

/* Footer */

.footer{
margin-top:30px;
text-align:center;
color:#a0a0a0;
font-size:12px;
}

</style>
</head>

<body>

<div class="particles">
<span style="left:5%;animation-delay:0s"></span>
<span style="left:15%;animation-delay:2s"></span>
<span style="left:25%;animation-delay:4s"></span>
<span style="left:40%;animation-delay:1s"></span>
<span style="left:55%;animation-delay:6s"></span>
<span style="left:70%;animation-delay:3s"></span>
<span style="left:85%;animation-delay:5s"></span>
<span style="left:95%;animation-delay:7s"></span>
</div>

<div class="container">

<div class="logo">
NG
</div>

<h1>NoeGamingOficial</h1>

<p class="tagline">
⚡ DOMINA CADA PARTIDA ⚡<br>
🔥 SUPERA CADA DESAFÍO 🔥<br>
🎮 ÚNETE A LA COMUNIDAD MÁS ÉPICA 🎮
</p>

<div class="stats">

<div class="stat">
<h2>24/7</h2>
<p>Gaming</p>
</div>

<div class="stat">
<h2>🔥</h2>
<p>Directos</p>
</div>

<div class="stat">
<h2>⚡</h2>
<p>Comunidad</p>
</div>

</div>

<div class="links">

<a href="https://youtube.com/@NoeGamingoficial" target="_blank">
🎥 YouTube
</a>

<a href="https://www.tiktok.com/@NoeGamingoficial" target="_blank">
🎵 TikTok
</a>

<a href="https://instagram.com/NoeGamingoficial" target="_blank">
📸 Instagram
</a>

<a href="https://twitch.tv/NoeGamingoficial" target="_blank">
🎮 Twitch
</a>

<a href="https://discord.gg/TU-INVITACION" target="_blank">
💬 Discord
</a>

<a href="https://x.com/NoeGamingOficia" target="_blank">
🐦 X / Twitter
</a>

</div>

<div class="footer">
© 2025 NoeGamingOficial • Powered By Gaming ⚡
</div>

</div>

</body>
</html>