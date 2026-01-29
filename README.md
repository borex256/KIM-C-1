
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KIM*C MUSIC | Global Artist Platform</title>
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600;800&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
<style>
*{box-sizing:border-box}
body{margin:0;font-family:'Poppins',sans-serif;background:#02020a;color:#fff;overflow-x:hidden;scroll-behavior:smooth}
:root{--n1:#ff3cf0;--n2:#3cf0ff;--n3:#7b5cff;--n4:#00ff9d}

@keyframes float{0%{transform:translateY(0)}50%{transform:translateY(-25px)}100%{transform:translateY(0)}}
@keyframes pulse{0%{opacity:.4}50%{opacity:.8}100%{opacity:.4}}
@keyframes glow{0%{box-shadow:0 0 15px var(--n1)}50%{box-shadow:0 0 50px var(--n2)}100%{box-shadow:0 0 15px var(--n1)}}

.bg-orbs{position:fixed;inset:0;z-index:-1;overflow:hidden}
.orb{position:absolute;border-radius:50%;filter:blur(80px);opacity:.35;animation:float 14s ease-in-out infinite,pulse 6s ease-in-out infinite}
.orb.one{background:var(--n1);width:350px;height:350px;top:10%;left:5%}
.orb.two{background:var(--n2);width:420px;height:420px;top:60%;left:65%;animation-delay:2s}
.orb.three{background:var(--n3);width:300px;height:300px;top:30%;left:40%;animation-delay:4s}

nav{position:fixed;top:0;width:100%;z-index:999;background:rgba(0,0,0,.55);backdrop-filter:blur(14px);display:flex;justify-content:center;gap:30px;padding:15px}
nav a{color:var(--n1);font-weight:600;transition:.3s;letter-spacing:1px}
nav a:hover{color:var(--n2);text-shadow:0 0 12px var(--n2)}

header{min-height:100vh;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;position:relative}
.logo{font-family:'Orbitron',sans-serif;font-size:3.8rem;letter-spacing:5px;color:var(--n1);text-shadow:0 0 30px var(--n1),0 0 60px var(--n3);animation:glow 6s infinite}
header h1{font-size:4.2rem;margin:20px 0;text-shadow:0 0 30px var(--n2)}
header p{max-width:760px;font-size:1.2rem;color:#ddd}
.hero-line{margin-top:30px;font-size:.9rem;letter-spacing:4px;color:var(--n4)}

section{padding:120px 10vw}
section h2{font-family:'Orbitron',sans-serif;color:var(--n2);border-bottom:2px solid var(--n2);display:inline-block;padding-bottom:10px;margin-bottom:50px}

.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:35px}

.card{background:rgba(255,255,255,.05);border:1px solid rgba(255,255,255,.12);border-radius:22px;padding:35px;backdrop-filter:blur(12px);transition:.5s;box-shadow:0 0 30px rgba(0,0,0,.4)}
.card:hover{transform:translateY(-15px) scale(1.02);box-shadow:0 0 60px rgba(60,240,255,.45)}

.shop-card{background:rgba(255,255,255,.06);padding:30px;border-radius:25px;text-align:center;animation:glow 8s infinite}
.shop-card h3{color:var(--n2)}
.shop-card button{margin-top:18px;padding:14px 32px;border:none;border-radius:35px;background:linear-gradient(90deg,var(--n1),var(--n2));color:#fff;font-weight:600;cursor:pointer;transition:.4s}
.shop-card button:hover{transform:scale(1.08);box-shadow:0 0 25px var(--n2)}

.modal{display:none;position:fixed;inset:0;background:rgba(0,0,0,.88);backdrop-filter:blur(10px);justify-content:center;align-items:center;z-index:2000}
.modal-content{background:#0b0b18;padding:40px;border-radius:22px;width:90%;max-width:440px;text-align:center;box-shadow:0 0 50px var(--n1)}
.modal-content input,.modal-content select{width:100%;padding:14px;margin:12px 0;border-radius:12px;border:none;background:#0f0f1f;color:#fff}
.modal-content button{width:100%;margin-top:12px;padding:14px;border:none;border-radius:35px;font-weight:600;cursor:pointer;background:linear-gradient(90deg,var(--n2),var(--n1));color:#fff}

footer{text-align:center;padding:50px;background:#010108;color:#aaa;letter-spacing:1px}
</style>
</head>
<body>

<div class="bg-orbs">
<div class="orb one"></div>
<div class="orb two"></div>
<div class="orb three"></div>
</div>

<nav>
<a href="#global">Global</a>
<a href="#bio">Bio</a>
<a href="#music">Music</a>
<a href="#services">Studio</a>
<a href="#shop">Store</a>
<a href="#contact">Contact</a>
</nav>

<header id="global">
<div class="logo">Ⱥ KIM*C MUSIC</div>
<h1>Global Afro‑Pop & Dancehall Icon</h1>
<p>Connecting Africa to the world through sound, rhythm, culture and futuristic energy.</p>
<div class="hero-line">GLOBAL • AFRICA • FUTURE • SOUND</div>
</header>

<section id="bio">
<h2>Global Identity</h2>
<div class="grid">
<div class="card">Afro‑pop, dancehall and global fusion artist shaping African sound for the world stage.</div>
<div class="card">Inspired by legends, driven by innovation, built for international platforms.</div>
<div class="card">Brand, artist, producer and studio director with a global creative vision.</div>

</section>

<section id="music">
<h2>Global Streaming</h2>
<iframe width="100%" height="166" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//soundcloud.com/user-985438553"></iframe>
</section>

<section id="services">
<h2>Studio & Global Services</h2>
<div class="grid">
<div class="card">International Recording Standards</div>
<div class="card">Global Songwriting & Composition</div>
<div class="card">Artist Development & Branding</div>
<div class="card">Mixing, Mastering & Distribution Prep</div>

</section>

<section id="shop">
<h2>Global Store</h2>
<div class="grid">
<div class="shop-card"><h3>Bayimba</h3><p>UGX 150,000</p><button onclick="openModal('Bayimba',150,000)">Buy</button></div>
<div class="shop-card"><h3>Ambezawo</h3><p>UGX 150,000</p><button onclick="openModal('Ambezawo',150,000)">Buy</button></div>
<div class="shop-card"><h3>Nkukutu</h3><p>UGX 150,000</p><button onclick="openModal('Nkukutu',150,000)">Buy</button></div>

</section>

<div class="modal" id="checkoutModal">
<div class="modal-content">
<h3 id="modalSongName"></h3>
<p>Price: UGX <span id="modalPrice"></span></p>
<input type="text" id="mmNumber" placeholder="Mobile Money Number">
<select id="mmProvider"><option>MTN</option><option>Airtel</option></select>
<button onclick="confirmPayment()">Confirm Payment</button>
<button onclick="closeModal()">Cancel</button>


<section id="contact">
<h2>Global Contact</h2>
<p>Studio: Kansanga Konge Buziga, Upper Poster Road, Kampala</p>
<p>Email: booking@kimcmusic.com</p>
<p>Management: soundbox@kimcmusic.com</p>
</section>

<footer>
<p>© 2026 KIM C MUSIC • Sound box recoreds </p>
</footer>

<script>
let selectedSong='',selectedPrice=0;
function openModal(song,price){selectedSong=song;selectedPrice=price;document.getElementById('modalSongName').innerText=song;document.getElementById('modalPrice').innerText=price;document.getElementById('checkoutModal').style.display='flex'}
function closeModal(){document.getElementById('checkoutModal').style.display='none';document.getElementById('mmNumber').value=''}
function confirmPayment(){let n=document.getElementById('mmNumber').value.trim();if(n===''){alert('Enter number');return;}alert('Payment request sent for '+selectedSong+' UGX '+selectedPrice);closeModal()}
</script>
