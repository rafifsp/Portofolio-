
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Rafif Sardiapratama | Portofolio</title>
<meta name="description" content="Portofolio Rafif Sardiapratama">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&family=Plus+Jakarta+Sans:wght@600;700;800&display=swap" rel="stylesheet">
<style>
:root{--accent:#6016d0}
:root{--bg:#fafaf7;--surface:#fff;--text:#1a1a1f;--muted:#62626c;--line:#e6e6df;--soft:color-mix(in srgb,var(--accent) 12%,transparent);--max:1080px}
:root[data-theme=dark]{--bg:#0f0f14;--surface:#17171f;--text:#f1f1f5;--muted:#a0a0ad;--line:#26262f}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth;scroll-padding-top:80px}
body{font-family:Inter,system-ui,sans-serif;background:var(--bg);color:var(--text);line-height:1.65;transition:background .3s,color .3s}
h1,h2,h3{font-family:"Plus Jakarta Sans",Inter,sans-serif;line-height:1.15}
a{color:inherit;text-decoration:none}
ul{list-style:none}
.nav{position:sticky;top:0;z-index:10;display:flex;justify-content:space-between;align-items:center;padding:14px max(20px,calc((100% - var(--max))/2));background:color-mix(in srgb,var(--bg) 85%,transparent);backdrop-filter:blur(10px);border-bottom:1px solid var(--line)}
.logo{font-family:"Plus Jakarta Sans",sans-serif;font-weight:800;font-size:1.3rem}
.logo span{color:var(--accent)}
.nav nav{display:flex;align-items:center;gap:22px;font-size:.95rem}
.nav nav a:not(.btn-nav):hover{color:var(--accent)}
.btn-nav{background:var(--accent);color:#fff;padding:8px 18px;border-radius:999px}
.tt{background:none;border:1px solid var(--line);color:var(--text);width:36px;height:36px;border-radius:50%;cursor:pointer;font-size:1rem}
main,footer{width:min(100% - 40px,var(--max));margin-inline:auto}
.section{padding:90px 0 30px}
.title{font-size:clamp(1.8rem,4vw,2.4rem);margin-bottom:36px}
.hero{padding:100px 0 50px;display:flex;align-items:center;justify-content:space-between;gap:40px}
.eyebrow{color:var(--accent);font-weight:600;margin-bottom:8px}
.hero h1{font-size:clamp(2.6rem,8vw,5rem);font-weight:800;letter-spacing:-.03em}
.dot{color:var(--accent)}
.role{font-size:1.2rem;margin:16px 0;color:var(--muted)}
.role strong{color:var(--text)}
.lead{max-width:560px;color:var(--muted);font-size:1.1rem}
.photo{width:240px;height:240px;border-radius:50%;object-fit:cover;border:4px solid var(--soft);flex-shrink:0}
.btn{display:inline-block;padding:13px 26px;border-radius:999px;font-weight:600;transition:transform .2s}
.btn:hover{transform:translateY(-2px)}
.btn.primary{background:var(--accent);color:#fff;box-shadow:0 8px 24px -8px var(--accent)}
.btn.big{font-size:1.1rem;padding:16px 32px}
.about{display:grid;grid-template-columns:1.4fr 1fr;gap:48px}
.about-text p{margin-bottom:16px;color:var(--muted)}
.skills h3{margin-bottom:14px;font-size:1.1rem}
.chips{display:flex;flex-wrap:wrap;gap:10px}
.chips li,.tags li{background:var(--soft);color:var(--accent);padding:6px 14px;border-radius:999px;font-size:.88rem;font-weight:500}
.card{background:var(--surface);border:1px solid var(--line);border-radius:16px;padding:18px;transition:transform .25s,box-shadow .25s}
.card:hover{transform:translateY(-6px);box-shadow:0 20px 40px -20px rgba(0,0,0,.25)}
.card p{color:var(--muted);font-size:.95rem;margin-top:8px}
.tags{display:flex;flex-wrap:wrap;gap:8px;margin:14px 0}
.tags li{font-size:.78rem;padding:4px 11px}
.contact{text-align:center;padding-bottom:60px}
.contact p{color:var(--muted);margin-bottom:26px}
.socials{display:flex;justify-content:center;gap:24px;margin-top:28px;color:var(--muted)}
.socials a:hover{color:var(--accent)}
footer{padding:30px 0 40px;border-top:1px solid var(--line);text-align:center;color:var(--muted);font-size:.88rem}
.reveal{opacity:0;transform:translateY(24px);transition:opacity .7s,transform .7s}
.reveal.show{opacity:1;transform:none}
@media(max-width:760px){
  .about{grid-template-columns:1fr;gap:30px}
  .nav nav a:not(.btn-nav){display:none}
  .hero{flex-direction:column-reverse;align-items:flex-start;padding-top:60px}
  .photo{width:150px;height:150px}
}
@media(prefers-reduced-motion:reduce){
  *{transition:none!important}
  .reveal{opacity:1;transform:none}
}
</style>
</head>
<body>

<header class="nav">
  <a href="#" class="logo">RS<span>.</span></a>
  <nav>
    <button class="tt" id="tt" aria-label="Ganti tema">◐</button>
    <a href="#tentang">Tentang</a>
    <a href="#pendidikan">Pendidikan</a>
    <a href="#kontak" class="btn-nav">Kontak</a>
  </nav>
</header>

<main>
  <section class="hero">
    <div>
      <p class="eyebrow">Halo, saya</p>
      <h1>Rafif Sardiapratama<span class="dot">.</span></h1>
      <p class="role">Mahasiswa <strong>D3 Sistem Informasi</strong> di <strong>Telkom University</strong></p>
      <p class="lead">Perkenalkan saya seorang Mahasiswa yang mempunyai ambisi untuk terus belajar dan berkembang di dunia IT</p>
      <p class="lead" style="margin-top:10px">Sedang mencari: <strong style="color:var(--text)">Magang Frontend/Backend, dan UI/UX</strong></p>
    </div>
    <img class="photo" src="foto (1).jpg" alt="Foto Rafif Sardiapratama">
  </section>

  <section id="tentang" class="section">
    <h2 class="title">Tentang Saya</h2>
    <div class="about">
      <div class="about-text">
        <p>saya orang yang mempunyai rasa penasaran yang sangat tinggi dalam dunia Teknologi dan mempunyai impian untuk bekerja dengan perusahaan besar seperti Google dan Microsoft</p>
      </div>
      <div class="skills">
        <h3>Keahlian</h3>
        <ul class="chips">
          <li>JAVA</li>
          <li>HTML CSS</li>
        </ul>
      </div>
    </div>
  </section>

  <section id="pendidikan" class="section">
    <h2 class="title">Pendidikan</h2>
    <div class="card">
      <h3>Telkom University</h3>
      <p>D3 Sistem Informasi · Semester 1 · IPK 3,25</p>
      <p style="margin-top:14px">Mata kuliah relevan &amp; minat</p>
      <ul class="tags">
        <li>Pemograman Web</li>
        <li>UI/UX Design</li>
        <li>Web Development</li>
      </ul>
    </div>
  </section>

  <section id="kontak" class="section contact">
    <h2 class="title">Mari Terhubung</h2>
    <p>Terbuka untuk magang, proyek, dan kolaborasi.</p>
    <a href="mailto:pratamarapip2@gmail.com" class="btn primary big">pratamarapip2@gmail.com</a>
    <div class="socials">
      <a href="https://www.linkedin.com/in/rafif-sardiapratama-090098446" target="_blank" rel="noopener">LinkedIn</a>
      <a href="https://github.com/rafifsp" target="_blank" rel="noopener">GitHub</a>
      <a href="https://www.instagram.com/rapipsp" target="_blank" rel="noopener">Instagram</a>
    </div>
  </section>
</main>

<footer>
  <p>© <span id="yr"></span> Rafif Sardiapratama</p>
</footer>

<script>
document.getElementById("yr").textContent = new Date().getFullYear();

var r = document.documentElement, b = document.getElementById("tt");
function g(){ try { return localStorage.getItem("tema"); } catch(e) { return null; } }
r.setAttribute("data-theme", g() || (matchMedia("(prefers-color-scheme: dark)").matches ? "dark" : "light"));
b.onclick = function(){
  var n = r.getAttribute("data-theme") === "dark" ? "light" : "dark";
  r.setAttribute("data-theme", n);
  try { localStorage.setItem("tema", n); } catch(e) {}
};

var T = document.querySelectorAll(".section .title,.card,.item,.about>*,.contact>*");
var io = new IntersectionObserver(function(es){
  es.forEach(function(e){
    if (e.isIntersecting) { e.target.classList.add("show"); io.unobserve(e.target); }
  });
}, { threshold: .1 });
T.forEach(function(el){ el.classList.add("reveal"); io.observe(el); });
</script>

</body>
</html>
