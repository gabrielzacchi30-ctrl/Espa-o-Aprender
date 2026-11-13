
<!doctype html>
<html lang="pt-BR">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Espaço Aprender | Neuropsicopedagoga Franciele Levandovski – Seara/SC</title>
<meta name="description" content="Espaço Aprender – Atendimentos neuropsicopedagógicos com Franciele Levandovski, Mestre em Educação e Neuropsicopedagoga Clínica, em Seara/SC.">
<meta property="og:title" content="Espaço Aprender – Franciele Levandovski">
<meta property="og:description" content="Atendimentos neuropsicopedagógicos em Seara/SC. Um espaço acolhedor para aprender do seu jeito.">
<meta property="og:image" content="img/logo-horizontal.png">
<link rel="icon" type="image/png" sizes="32x32" href="img/favicon-32.png">
<link rel="icon" type="image/png" sizes="48x48" href="img/favicon-48.png">
<link rel="icon" type="image/png" sizes="512x512" href="img/icone-512.png">
<link rel="apple-touch-icon" href="img/apple-touch-icon.png">
<script>document.documentElement.classList.add("js")</script>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Baloo+2:wght@500;600;700;800&family=Caveat:wght@600;700&family=Nunito:wght@400;600;700;800&display=swap" rel="stylesheet">
<style>
  :root{
    --navy:#163a6b;
    --ink:#2b3550;
    --muted:#5d6782;
    --cream:#fff8ef;
    --peach:#ffe7d6;
    --mint:#dff5ec;
    --sky:#e2f0ff;
    --lilac:#efe6ff;
    --rose:#ffe9f0;
    --butter:#fff3cc;
    --blue:#2f8ee0;
    --green:#2bb673;
    --yellow:#ffc533;
    --orange:#ff8a3d;
    --pink:#f2547d;
    --purple:#8b5cf6;
    --wa:#25d366;
    --radius:28px;
    --shadow:0 10px 30px -12px rgba(22,58,107,.25);
  }
  *{box-sizing:border-box;margin:0;padding:0}
  html{scroll-behavior:smooth}
  body{font-family:"Nunito",system-ui,sans-serif;color:var(--ink);background:var(--cream);line-height:1.65;font-size:17px}
  html,body{overflow-x:clip}
  img{max-width:100%;display:block}
  a{color:inherit}
  h1,h2,h3{font-family:"Baloo 2",system-ui,sans-serif;color:var(--navy);line-height:1.15}
  .wrap{width:min(1120px,100% - 32px);margin-inline:auto}
  .hand{font-family:"Caveat",cursive;font-weight:700}
  .i{width:1em;height:1em;flex:none;fill:none;stroke:currentColor;stroke-width:2;stroke-linecap:round;stroke-linejoin:round}

  /* ===== topo ===== */
  header{position:sticky;top:0;z-index:50;background:rgba(255,248,239,.94);backdrop-filter:blur(10px);
         border-bottom:1px solid rgba(22,58,107,.06);transition:transform .35s ease}
  header.hide{transform:translateY(-100%)}
  .nav{display:flex;align-items:center;justify-content:space-between;gap:16px;padding:10px 0}
  .brand img{height:50px;width:auto}
  .menu{display:flex;gap:6px;list-style:none}
  .menu a{text-decoration:none;font-weight:700;color:var(--navy);padding:8px 14px;border-radius:999px;transition:.2s}
  .menu a:hover{background:var(--sky)}
  .btn{display:inline-flex;align-items:center;gap:10px;font-weight:800;text-decoration:none;border:0;cursor:pointer;
       padding:14px 24px;border-radius:999px;font-family:"Baloo 2";font-size:1.05rem;transition:transform .2s, box-shadow .2s, background .2s}
  .btn:hover{transform:translateY(-2px)}
  .btn-wa{background:var(--wa);color:#fff;box-shadow:0 10px 24px -10px rgba(37,211,102,.7)}
  .btn-soft{background:#fff;color:var(--navy);box-shadow:var(--shadow)}
  .btn-route{background:var(--navy);color:#fff;box-shadow:0 10px 24px -10px rgba(22,58,107,.6)}
  .btn-route:hover{background:#1d4a88}
  .btn .i{font-size:1.25rem}
  .btn svg.wa{width:22px;height:22px;flex:none}
  .nav .btn{padding:10px 18px;font-size:.98rem}
  .burger{display:none;background:none;border:0;width:44px;height:44px;border-radius:12px;cursor:pointer}
  .burger span{display:block;width:24px;height:3px;border-radius:3px;background:var(--navy);margin:5px auto;transition:.3s}

  /* ===== hero ===== */
  .hero{position:relative;padding:96px 0 110px;overflow-x:clip;text-align:center}
  .hero-grid{max-width:780px;position:relative;z-index:1}
  .hero{isolation:isolate}
  .hero p.lead{margin-inline:auto}
  .hero .cta{justify-content:center}
  .tag{display:inline-flex;align-items:center;gap:6px;background:#fff;color:var(--navy);font-weight:700;font-size:.9rem;padding:6px 14px;border-radius:999px;box-shadow:var(--shadow);margin-bottom:18px}
  .tag .i{color:var(--pink)}
  .hero h1{font-size:clamp(2.3rem,5.4vw,3.9rem);font-weight:800;margin-bottom:6px}
  .scribble{position:relative;white-space:nowrap;display:inline-block}
  .scribble svg{position:absolute;left:-2%;bottom:-6px;width:104%;height:16px;z-index:-1}
  .hero .hand{font-size:2.1rem;color:var(--orange);display:block;margin-bottom:18px;transform:rotate(-2deg)}
  .hero p.lead{font-size:1.15rem;color:var(--muted);max-width:600px;margin-bottom:30px}
  .cta{display:flex;flex-wrap:wrap;gap:14px}
  .photo{position:relative;justify-self:center;width:min(420px,100%)}
  .photo .frame{border-radius:46% 54% 42% 58% / 52% 44% 56% 48%;overflow:hidden;aspect-ratio:4/5;background:var(--peach);
        border:8px solid #fff;box-shadow:0 30px 60px -25px rgba(22,58,107,.45)}
  .photo .frame img{width:100%;height:100%;object-fit:cover;object-position:center 15%}
  .sticker{position:absolute;background:#fff;border-radius:16px;padding:9px 15px;box-shadow:var(--shadow);font-weight:800;font-size:.9rem;color:var(--navy);display:flex;align-items:center;gap:8px}
  .sticker::before{content:"";width:10px;height:10px;border-radius:50%;background:var(--c)}
  .sticker.s1{left:-18px;bottom:60px;transform:rotate(-4deg)}
  .sticker.s2{right:-10px;top:30px;transform:rotate(5deg)}
  .dot{position:absolute;border-radius:50%;z-index:-1}
  .blob{position:absolute;z-index:-1;border-radius:50%}

  /* ===== seções ===== */
  section{padding:80px 0;position:relative;scroll-margin-top:72px}
  .sec-head{text-align:center;max-width:640px;margin:0 auto 44px}
  .sec-head h2{font-size:clamp(1.9rem,4vw,2.7rem);margin-bottom:6px}
  .sec-head .squig{display:block;width:90px;height:14px;margin:0 auto 14px}
  .sec-head p{color:var(--muted)}

  /* sobre */
  .about{background:#fff;border-radius:48px;margin-inline:16px}
  .about-grid{display:grid;grid-template-columns:.85fr 1.15fr;gap:48px;align-items:center}
  .about .hand{font-size:1.7rem;color:var(--pink);display:block}
  .about h2{font-size:clamp(1.9rem,4vw,2.5rem);margin-bottom:14px}
  .about p{color:var(--muted);margin-bottom:22px}
  .chips{display:flex;flex-wrap:wrap;gap:10px}
  .chip{padding:9px 16px;border-radius:999px;font-weight:700;font-size:.95rem;color:var(--navy)}

  /* como ajudo */
  .cards{display:grid;grid-template-columns:repeat(3,1fr);gap:22px}
  .card{background:#fff;border-radius:var(--radius);padding:28px;box-shadow:var(--shadow);transition:transform .25s}
  .card:hover{transform:translateY(-6px)}
  .card .ico{width:56px;height:56px;border-radius:18px;display:grid;place-items:center;font-size:1.6rem;margin-bottom:14px}
  .card h3{font-size:1.3rem;margin-bottom:6px}
  .card p{color:var(--muted);font-size:.98rem}

  /* passos */
  .steps{display:grid;grid-template-columns:repeat(3,1fr);gap:22px;counter-reset:s}
  .step{position:relative;background:#fff;border-radius:var(--radius);padding:38px 26px 26px;box-shadow:var(--shadow);text-align:center}
  .step::before{counter-increment:s;content:counter(s);position:absolute;top:-22px;left:50%;transform:translateX(-50%);
        width:46px;height:46px;border-radius:50%;display:grid;place-items:center;font-family:"Baloo 2";font-weight:800;font-size:1.3rem;color:#fff}
  .step:nth-child(1)::before{background:var(--blue)}
  .step:nth-child(2)::before{background:var(--orange)}
  .step:nth-child(3)::before{background:var(--purple)}
  .step h3{font-size:1.2rem;margin:6px 0}
  .step p{color:var(--muted);font-size:.97rem}

  /* horários + local */
  .info-grid{display:grid;grid-template-columns:1fr 1.2fr;gap:24px;align-items:stretch}
  .box{background:#fff;border-radius:var(--radius);padding:30px;box-shadow:var(--shadow)}
  .box h3{font-size:1.45rem;margin-bottom:16px;display:flex;align-items:center;gap:10px}
  .box h3 .i{color:var(--orange)}
  .hours{list-style:none}
  .hours li{display:flex;justify-content:space-between;padding:11px 14px;border-radius:14px;font-weight:600}
  .hours li:nth-child(odd){background:var(--cream)}
  .hours li.closed span:last-child{color:#868ea3}
  .hours li.today{background:var(--mint)!important;outline:2px solid var(--green)}
  .hours li.today span:first-child::after{content:" • hoje";color:var(--green);font-weight:800;font-size:.85rem}
  .note{font-size:.88rem;color:var(--muted);margin-top:12px}
  .addr{margin-bottom:16px}
  .addr strong{color:var(--navy)}
  .map{border-radius:20px;overflow:hidden;aspect-ratio:16/10;background:var(--sky);margin-bottom:16px}
  .map iframe{width:100%;height:100%;border:0}
  .access{display:flex;flex-wrap:wrap;gap:10px;margin-bottom:20px}
  .access span{display:inline-flex;align-items:center;gap:8px;background:var(--sky);color:var(--navy);font-weight:700;font-size:.9rem;padding:8px 14px;border-radius:999px}
  .access .i{font-size:1.1rem;color:var(--blue)}

  /* CTA final */
  .final{padding:0 0 90px}
  .final-box{position:relative;overflow:hidden;background:var(--navy);color:#fff;border-radius:44px;padding:56px 32px;text-align:center;isolation:isolate}
  .final-box h2{color:#fff;font-size:clamp(1.9rem,4.4vw,2.8rem);margin-bottom:10px}
  .final-box p{opacity:.85;max-width:540px;margin:0 auto 26px}
  .final-box .hand{color:var(--yellow);font-size:1.7rem}
  .final-box .dot{z-index:-1}

  footer{background:#fff;border-radius:48px 48px 0 0;padding:56px 0 0;color:var(--muted);font-size:.95rem;box-shadow:0 -12px 40px -24px rgba(22,58,107,.25)}
  .f-grid{display:grid;grid-template-columns:1.5fr 1fr 1fr 1.2fr;gap:36px}
  .f-brand .flogo{width:min(230px,100%);height:auto;margin:0 0 12px -4px}
  .f-brand p{max-width:300px;margin-bottom:16px}
  footer h4{font-family:"Baloo 2";color:var(--navy);font-size:1.15rem;margin-bottom:12px}
  .f-links,.f-info{list-style:none;display:grid;gap:10px}
  footer a{text-decoration:none;color:var(--ink);transition:color .2s}
  .f-links a:hover,.f-info a:hover{color:var(--blue)}
  .f-info li{display:flex;gap:10px;align-items:flex-start;line-height:1.45}
  .f-info .i{font-size:1.15rem;color:var(--orange);margin-top:2px}
  footer .soc{display:inline-flex;align-items:center;gap:8px;background:var(--cream);padding:9px 16px;border-radius:999px;font-weight:700;color:var(--navy)}
  footer .soc .i{font-size:1.1rem;color:var(--pink)}
  .f-bottom{display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap;margin-top:44px;padding:20px 0 24px;border-top:2px dashed #efe6da;font-size:.88rem}
  .to-top{font-weight:800;color:var(--navy)!important}
  .f-rainbow{height:8px;background:linear-gradient(90deg,var(--blue),var(--green),var(--yellow),var(--orange),var(--pink),var(--purple))}
  @media (max-width:960px){ .f-grid{grid-template-columns:1fr 1fr} .f-brand{grid-column:1/-1} }
  @media (max-width:560px){
    footer{border-radius:32px 32px 0 0;padding-top:36px;font-size:.92rem}
    .f-grid{grid-template-columns:1fr;gap:16px}
    .f-brand{text-align:center;margin-bottom:6px}
    .f-brand .flogo{width:170px;margin:0 auto 10px}
    .f-brand p{margin:0 auto 14px;font-size:.9rem}
    .f-grid > div:not(.f-brand){background:var(--cream);border-radius:20px;padding:16px 18px}
    footer h4{font-size:1rem;margin-bottom:8px}
    .f-links{display:flex;flex-wrap:wrap;gap:6px}
    .f-links a{display:inline-block;background:#fff;padding:6px 12px;border-radius:999px;font-size:.85rem;font-weight:700;color:var(--navy)}
    .f-info{gap:8px}
    .f-bottom{flex-direction:column;text-align:center;gap:6px;margin-top:24px;padding:16px 0 20px;font-size:.8rem}
  }

  /* animação de entrada */
  .js .reveal{opacity:0;transform:translateY(24px);transition:opacity .7s ease, transform .7s ease}
  .js .reveal.in{opacity:1;transform:none}
  .js .card.reveal.in{transition:opacity .7s ease, transform .25s ease}
  .js .card.reveal.in:hover{transform:translateY(-6px)}
  @media (prefers-reduced-motion:reduce){.js .reveal{opacity:1;transform:none;transition:none}html{scroll-behavior:auto}header{transition:none}}

  /* ===== responsivo ===== */
  @media (max-width:960px){
    .about-grid,.info-grid{grid-template-columns:1fr}
    .hero{padding:64px 0 76px}
    .cta{justify-content:center}
    .photo{width:min(330px,86%)}
    .cards{grid-template-columns:1fr 1fr}
    .about{text-align:center}
    .chips{justify-content:center}
    /* menu vira "hambúrguer" já no tablet, para não estourar a largura */
    .burger{display:block}
    .nav > .btn{display:none}
    .menu{position:absolute;top:100%;left:0;right:0;flex-direction:column;background:var(--cream);padding:8px 16px 18px;gap:2px;
          box-shadow:0 20px 30px -20px rgba(22,58,107,.3);transform-origin:top;transform:scaleY(0);opacity:0;pointer-events:none;transition:.25s}
    .menu.open{transform:none;opacity:1;pointer-events:auto}
    .menu a{display:block;padding:12px 14px}
    .burger.x span:nth-child(1){transform:translateY(8px) rotate(45deg)}
    .burger.x span:nth-child(2){opacity:0}
    .burger.x span:nth-child(3){transform:translateY(-8px) rotate(-45deg)}
  }
  @media (max-width:760px){
    body{font-size:16px}
    .brand img{height:40px}
    section{padding:60px 0}
    .about{margin-inline:8px;border-radius:36px}
    .cards,.steps{grid-template-columns:1fr}
    .steps{gap:38px}
    .sticker{font-size:.8rem;padding:7px 12px}
    .sticker.s1{left:-6px}
    .sticker.s2{right:-6px}
    .box{padding:22px}
    .btn{width:100%;justify-content:center}
    .cta{flex-direction:column}
    .final-box{padding:44px 20px;border-radius:32px}
    .hero .blob{transform:scale(.6)}
    .hero .hand{font-size:1.65rem}
    .hero .no-m{display:none}
    .hero h1{font-size:clamp(2rem,9vw,2.3rem)}
  }
</style>
</head>
<body>

<!-- ícones (desenhados uma vez, usados com <use>) -->
<svg width="0" height="0" style="position:absolute" aria-hidden="true">
  <symbol id="i-pin" viewBox="0 0 24 24"><path d="M12 22s7-6.2 7-12a7 7 0 0 0-14 0c0 5.8 7 12 7 12Z"/><circle cx="12" cy="10" r="2.5"/></symbol>
  <symbol id="i-search" viewBox="0 0 24 24"><circle cx="11" cy="11" r="7"/><path d="m20 20-3.5-3.5"/></symbol>
  <symbol id="i-puzzle" viewBox="0 0 24 24"><path d="M9 4h3a2 2 0 1 1 4 0h3v5a2 2 0 1 1 0 4v6h-5a2 2 0 1 0-4 0H4v-6a2 2 0 1 0 0-4V4h5Z"/></symbol>
  <symbol id="i-book" viewBox="0 0 24 24"><path d="M4 5.5A2.5 2.5 0 0 1 6.5 3H20v15H6.5A2.5 2.5 0 0 0 4 20.5v-15Z"/><path d="M4 20.5A2.5 2.5 0 0 0 6.5 23H20v-5"/></symbol>
  <symbol id="i-family" viewBox="0 0 24 24"><circle cx="8" cy="7" r="3"/><circle cx="17" cy="9" r="2.2"/><path d="M2.5 20a5.5 5.5 0 0 1 11 0M14 20a3.5 3.5 0 0 1 7 0"/></symbol>
  <symbol id="i-school" viewBox="0 0 24 24"><path d="m3 9 9-5 9 5-9 5-9-5Z"/><path d="M7 11.5V16c0 1.5 2.2 3 5 3s5-1.5 5-3v-4.5"/></symbol>
  <symbol id="i-mic" viewBox="0 0 24 24"><rect x="9" y="3" width="6" height="11" rx="3"/><path d="M5 11a7 7 0 0 0 14 0M12 18v3"/></symbol>
  <symbol id="i-clock" viewBox="0 0 24 24"><circle cx="12" cy="12" r="9"/><path d="M12 7v5l3 2"/></symbol>
  <symbol id="i-access" viewBox="0 0 24 24"><circle cx="12" cy="4.5" r="1.8"/><path d="M8 9h8M12 9v5l3.5 6M12 14l-3.5 6"/></symbol>
  <symbol id="i-car" viewBox="0 0 24 24"><path d="M5 16V11l2-5h10l2 5v5M3 16h18v3H3zM7 19v2M17 19v2"/><path d="M5 11h14"/></symbol>
  <symbol id="i-route" viewBox="0 0 24 24"><path d="M3 11 21 3l-8 18-2-8-8-2Z"/></symbol>
  <symbol id="i-ig" viewBox="0 0 24 24"><rect x="3" y="3" width="18" height="18" rx="5"/><circle cx="12" cy="12" r="4"/><circle cx="17.5" cy="6.5" r=".6"/></symbol>
  <symbol id="i-wa" viewBox="0 0 24 24"><path stroke="none" fill="currentColor" d="M12 2a10 10 0 0 0-8.6 15.1L2 22l5-1.3A10 10 0 1 0 12 2Zm0 18.2a8.2 8.2 0 0 1-4.2-1.2l-.3-.2-3 .8.8-2.9-.2-.3A8.2 8.2 0 1 1 12 20.2Zm4.5-6.1c-.2-.1-1.5-.7-1.7-.8-.2-.1-.4-.1-.6.1l-.8 1c-.1.2-.3.2-.5.1a6.7 6.7 0 0 1-3.3-2.9c-.2-.4.3-.4.8-1.3.1-.2 0-.3 0-.4l-.8-1.8c-.2-.5-.4-.4-.6-.4h-.5a1 1 0 0 0-.7.3 3 3 0 0 0-.9 2.2 5.2 5.2 0 0 0 1.1 2.8 11.9 11.9 0 0 0 4.6 4c1.7.7 2.4.8 3.2.7.5-.1 1.5-.6 1.8-1.2.2-.6.2-1.1.1-1.2l-.2-.2Z"/></symbol>
  <symbol id="squig" viewBox="0 0 90 14"><path d="M2 8c8-6 14-6 22 0s14 6 22 0 14-6 22 0 12 5 20 0" fill="none" stroke-width="4" stroke-linecap="round"/></symbol>
</svg>

<header id="topo">
  <nav class="wrap nav">
    <a class="brand" href="#inicio" aria-label="Espaço Aprender – início">
      <img src="img/logo-cabecalho.png" alt="Espaço Aprender">
    </a>
    <ul class="menu" id="menu">
      <li><a href="#sobre">Sobre</a></li>
      <li><a href="#como-ajudo">Como ajudo</a></li>
      <li><a href="#como-funciona">Como funciona</a></li>
      <li><a href="#onde">Horários e local</a></li>
    </ul>
    <a class="btn btn-wa wa-link" href="#" target="_blank" rel="noopener">
      <svg class="wa"><use href="#i-wa"/></svg> Agendar
    </a>
    <button class="burger" id="burger" aria-label="Abrir menu" aria-expanded="false" aria-controls="menu"><span></span><span></span><span></span></button>
  </nav>
</header>

<main>
  <!-- ===== HERO ===== -->
  <section class="hero" id="inicio">
    <span class="blob" style="width:340px;height:340px;background:#ffe3cf;top:-60px;right:-80px"></span>
    <span class="blob" style="width:260px;height:260px;background:#dff0ff;bottom:-40px;left:-90px"></span>
    <div class="wrap hero-grid">
      <div class="reveal">
        <span class="tag"><svg class="i"><use href="#i-pin"/></svg> Seara · Santa Catarina</span>
        <h1>Cada criança aprende <span class="scribble">do seu jeito<svg viewBox="0 0 200 16" preserveAspectRatio="none" aria-hidden="true"><path d="M3 10c40-7 90-8 130-5 22 2 44 3 64 0" fill="none" stroke="#ffc533" stroke-width="7" stroke-linecap="round"/></svg></span></h1>
        <span class="hand">e aqui a gente respeita isso</span>
        <p class="lead">No <strong>Espaço Aprender</strong>, a neuropsicopedagoga <strong>Franciele Levandovski</strong> acolhe crianças para entender como cada uma aprende — e transformar as dificuldades em novas descobertas.</p>
        <div class="cta">
          <a class="btn btn-wa wa-link" href="#" target="_blank" rel="noopener"><svg class="wa"><use href="#i-wa"/></svg> Conversar no WhatsApp</a>
          <a class="btn btn-soft" href="#sobre">Conhecer a Franciele</a>
        </div>
      </div>
    </div>
    <span class="dot" style="width:22px;height:22px;background:var(--yellow);top:14%;left:12%"></span>
    <span class="dot no-m" style="width:14px;height:14px;background:var(--pink);top:58%;left:6%"></span>
    <span class="dot" style="width:30px;height:30px;background:var(--green);bottom:12%;right:10%"></span>
    <span class="dot" style="width:12px;height:12px;background:var(--purple);top:12%;right:22%"></span>
    <span class="dot no-m" style="width:16px;height:16px;background:var(--blue);bottom:20%;left:20%"></span>
    <span class="dot no-m" style="width:10px;height:10px;background:var(--orange);top:40%;right:6%"></span>
  </section>

  <!-- ===== SOBRE ===== -->
  <section class="about" id="sobre">
    <div class="wrap about-grid">
      <div class="photo reveal">
        <span class="dot" style="width:22px;height:22px;background:var(--yellow);top:-14px;left:30px"></span>
        <span class="dot" style="width:14px;height:14px;background:var(--pink);top:40px;left:-26px"></span>
        <span class="dot" style="width:30px;height:30px;background:var(--green);bottom:-10px;right:40px"></span>
        <span class="dot" style="width:12px;height:12px;background:var(--purple);bottom:90px;right:-24px"></span>
        <div class="frame"><img src="img/franciele.webp" alt="Franciele Levandovski sorrindo, sentada à mesa com um jogo educativo de balança"></div>
        <div class="sticker s1" style="--c:var(--purple)">Neuropsicopedagoga Clínica</div>
        <div class="sticker s2" style="--c:var(--orange)">Mestre em Educação</div>
      </div>
      <div class="reveal">
        <span class="hand">prazer, eu sou a Fran!</span>
        <h2>Franciele Levandovski</h2>
        <p>Educadora de coração e de profissão. Unindo a experiência de anos dentro da escola com o conhecimento sobre como o cérebro aprende, criei o <strong>Espaço Aprender</strong>: um lugar leve, acolhedor e cheio de brincadeira com propósito, onde cada conquista é celebrada.</p>
        <div class="chips">
          <span class="chip" style="background:var(--sky)">Mestre em Educação</span>
          <span class="chip" style="background:var(--lilac)">Neuropsicopedagoga Clínica</span>
          <span class="chip" style="background:var(--peach)">Gestora escolar</span>
          <span class="chip" style="background:var(--mint)">Palestrante</span>
          <span class="chip" style="background:var(--rose)">Estudante de Fonoaudiologia</span>
        </div>
      </div>
    </div>
  </section>

  <!-- ===== COMO AJUDO ===== -->
  <section id="como-ajudo">
    <div class="wrap">
      <div class="sec-head reveal">
        <h2>Como posso ajudar</h2>
        <svg class="squig" style="stroke:var(--pink)"><use href="#squig"/></svg>
        <p>A neuropsicopedagogia investiga como funcionam a atenção, a memória, a linguagem e o raciocínio — e cria caminhos para que o aprender fique mais fácil.</p>
      </div>
      <div class="cards">
        <article class="card reveal">
          <div class="ico" style="background:var(--sky);color:var(--blue)"><svg class="i"><use href="#i-search"/></svg></div>
          <h3>Avaliação</h3>
          <p>Uma investigação cuidadosa para entender as habilidades, os desafios e o jeito único de aprender de cada criança.</p>
        </article>
        <article class="card reveal">
          <div class="ico" style="background:var(--peach);color:var(--orange)"><svg class="i"><use href="#i-puzzle"/></svg></div>
          <h3>Intervenção</h3>
          <p>Atendimentos com jogos, materiais concretos e atividades lúdicas que estimulam o desenvolvimento de forma prazerosa.</p>
        </article>
        <article class="card reveal">
          <div class="ico" style="background:var(--mint);color:var(--green)"><svg class="i"><use href="#i-book"/></svg></div>
          <h3>Dificuldades de aprendizagem</h3>
          <p>Apoio na leitura, escrita, matemática, atenção e organização — respeitando o tempo de cada criança.</p>
        </article>
        <article class="card reveal">
          <div class="ico" style="background:var(--lilac);color:var(--purple)"><svg class="i"><use href="#i-family"/></svg></div>
          <h3>Orientação aos pais</h3>
          <p>Durante o acompanhamento da criança, pais e responsáveis recebem orientações para apoiar o desenvolvimento também em casa.</p>
        </article>
        <article class="card reveal">
          <div class="ico" style="background:var(--rose);color:var(--pink)"><svg class="i"><use href="#i-school"/></svg></div>
          <h3>Parceria com a escola</h3>
          <p>Com a vivência de gestora escolar, a Fran ajuda a construir pontes entre família, escola e criança.</p>
        </article>
        <article class="card reveal">
          <div class="ico" style="background:var(--butter);color:#d89a00"><svg class="i"><use href="#i-mic"/></svg></div>
          <h3>Palestras</h3>
          <p>Palestras e formações sobre educação e aprendizagem para escolas, professores e famílias.</p>
        </article>
      </div>
    </div>
  </section>

  <!-- ===== COMO FUNCIONA ===== -->
  <section id="como-funciona" style="padding-top:20px">
    <div class="wrap">
      <div class="sec-head reveal">
        <h2>Como funciona</h2>
        <svg class="squig" style="stroke:var(--blue)"><use href="#squig"/></svg>
      </div>
      <div class="steps">
        <div class="step reveal"><h3>Chame no WhatsApp</h3><p>Conte um pouquinho sobre o que está acontecendo. Sem compromisso, sem pressa.</p></div>
        <div class="step reveal"><h3>Primeiro encontro</h3><p>Uma conversa acolhedora para conhecer a criança, a família e as necessidades.</p></div>
        <div class="step reveal"><h3>Caminho personalizado</h3><p>Um plano pensado especialmente para cada criança, com acompanhamento de perto.</p></div>
      </div>
    </div>
  </section>

  <!-- ===== HORÁRIOS E LOCAL ===== -->
  <section id="onde">
    <div class="wrap">
      <div class="sec-head reveal">
        <h2>Horários e localização</h2>
        <svg class="squig" style="stroke:var(--orange)"><use href="#squig"/></svg>
      </div>
      <div class="info-grid">
        <div class="box reveal">
          <h3><svg class="i"><use href="#i-clock"/></svg> Horário de atendimento</h3>
          <ul class="hours" id="hours">
            <li data-d="1" class="closed"><span>Segunda</span><span>Fechado</span></li>
            <li data-d="2"><span>Terça</span><span>16:30 – 22:00</span></li>
            <li data-d="3"><span>Quarta</span><span>16:30 – 22:00</span></li>
            <li data-d="4"><span>Quinta</span><span>16:30 – 22:00</span></li>
            <li data-d="5"><span>Sexta</span><span>16:30 – 22:00</span></li>
            <li data-d="6" class="closed"><span>Sábado</span><span>Fechado</span></li>
            <li data-d="0" class="closed"><span>Domingo</span><span>Fechado</span></li>
          </ul>
          <p class="note">Atendimentos com hora marcada. Em feriados os horários podem mudar — confirme pelo WhatsApp.</p>
        </div>

        <div class="box reveal">
          <h3><svg class="i" style="color:var(--pink)"><use href="#i-pin"/></svg> Onde estamos</h3>
          <div class="addr"><strong>Espaço Aprender</strong><br>Rua Nereu Ramos, 121 – Centro<br>Seara/SC · CEP 89770-000</div>
          <div class="map">
            <iframe loading="lazy" title="Mapa – Espaço Aprender em Seara/SC" referrerpolicy="no-referrer-when-downgrade"
              src="https://www.google.com/maps?q=-27.149641,-52.3098535&z=17&output=embed"></iframe>
          </div>
          <div class="access">
            <span><svg class="i"><use href="#i-access"/></svg> Entrada acessível para cadeira de rodas</span>
            <span><svg class="i"><use href="#i-car"/></svg> Estacionamento acessível</span>
          </div>
          <a class="btn btn-route" href="https://www.google.com/maps/dir/?api=1&destination=-27.149641,-52.3098535" target="_blank" rel="noopener">
            <svg class="i"><use href="#i-route"/></svg> Ver rota no Google Maps
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- ===== CTA FINAL ===== -->
  <section class="final">
    <div class="wrap">
      <div class="final-box reveal">
        <span class="dot" style="width:130px;height:130px;background:#24508f;top:-46px;left:-36px"></span>
        <span class="dot" style="width:100px;height:100px;background:#24508f;bottom:-40px;right:8%"></span>
        <span class="dot" style="width:22px;height:22px;background:var(--yellow);top:30px;right:16%"></span>
        <span class="dot" style="width:12px;height:12px;background:var(--pink);bottom:40px;left:12%"></span>
        <span class="hand">vamos conversar?</span>
        <h2>O primeiro passo é um “oi”</h2>
        <p>Tire suas dúvidas e agende um horário diretamente pelo WhatsApp. Será um prazer receber vocês e o seu pequeno.</p>
        <a class="btn btn-wa wa-link" href="#" target="_blank" rel="noopener"><svg class="wa"><use href="#i-wa"/></svg> Chamar no WhatsApp</a>
      </div>
    </div>
  </section>
</main>

<footer>
  <div class="wrap">
    <div class="f-grid">
      <div class="f-brand">
        <img class="flogo" src="img/logo-horizontal.png" alt="Espaço Aprender – Atendimentos Neuropsicopedagógicos">
        <p>Um espaço acolhedor para crianças descobrirem o seu jeito de aprender.</p>
        <a class="soc" href="https://www.instagram.com/espacoapren_der/" target="_blank" rel="noopener">
          <svg class="i"><use href="#i-ig"/></svg> @espacoapren_der
        </a>
      </div>

      <div>
        <h4>Navegue</h4>
        <ul class="f-links">
          <li><a href="#inicio">Início</a></li>
          <li><a href="#sobre">Sobre a Fran</a></li>
          <li><a href="#como-ajudo">Como ajudo</a></li>
          <li><a href="#como-funciona">Como funciona</a></li>
          <li><a href="#onde">Horários e local</a></li>
        </ul>
      </div>

      <div>
        <h4>Atendimento</h4>
        <ul class="f-info">
          <li><svg class="i"><use href="#i-clock"/></svg><span>Terça a sexta<br>16:30 às 22:00</span></li>
          <li><svg class="i"><use href="#i-access"/></svg><span>Entrada e estacionamento acessíveis</span></li>
        </ul>
      </div>

      <div>
        <h4>Contato</h4>
        <ul class="f-info">
          <li><svg class="i"><use href="#i-wa"/></svg><a class="wa-link" href="#" target="_blank" rel="noopener">Agendar pelo WhatsApp</a></li>
          <li><svg class="i"><use href="#i-pin"/></svg><a href="https://www.google.com/maps/dir/?api=1&destination=-27.149641,-52.3098535" target="_blank" rel="noopener">Rua Nereu Ramos, 121 – Centro<br>Seara/SC · 89770-000</a></li>
        </ul>
      </div>
    </div>

    <div class="f-bottom">
      <p>© <span id="y"></span> Espaço Aprender · Neuropsicopedagoga Franciele Levandovski</p>
      <a href="#inicio" class="to-top">Voltar ao topo ↑</a>
    </div>
  </div>
  <div class="f-rainbow"></div>
</footer>

<script>
  // Link do WhatsApp (um só lugar para alterar)
  const WA = "https://wa.me/5549999311051?text=" + encodeURIComponent("Olá, Franciele! Vim pelo site do Espaço Aprender e gostaria de mais informações.");
  document.querySelectorAll(".wa-link").forEach(a => a.href = WA);

  // Menu mobile
  const burger = document.getElementById("burger"), menu = document.getElementById("menu");
  const closeMenu = () => { menu.classList.remove("open"); burger.classList.remove("x"); burger.setAttribute("aria-expanded", false); };
  burger.addEventListener("click", () => {
    const open = menu.classList.toggle("open");
    burger.classList.toggle("x", open);
    burger.setAttribute("aria-expanded", open);
  });
  menu.querySelectorAll("a").forEach(a => a.addEventListener("click", closeMenu));

  // Cabeçalho: some ao rolar e volta quando a página retorna ao topo
  const header = document.getElementById("topo");
  // Cabeçalho: some ao rolar para baixo e reaparece ao rolar para cima
  let lastY = window.scrollY;
  const onScroll = () => {
    const y = window.scrollY, diff = y - lastY;
    if (Math.abs(diff) < 6 && y > 80) return;      // ignora micro-movimentos
    const hide = y > 80 && diff > 0;
    lastY = y;
    if (hide && !header.classList.contains("hide")) closeMenu();
    header.classList.toggle("hide", hide);
  };
  window.addEventListener("scroll", onScroll, { passive: true });
  onScroll();

  // Destaca o dia de hoje nos horários
  const li = document.querySelector('#hours li[data-d="' + new Date().getDay() + '"]');
  if (li) li.classList.add("today");

  document.getElementById("y").textContent = new Date().getFullYear();

  // Animação ao rolar
  const io = new IntersectionObserver(es => es.forEach(e => {
    if (e.isIntersecting) { e.target.classList.add("in"); io.unobserve(e.target); }
  }), { threshold: .12 });
  document.querySelectorAll(".reveal").forEach(el => io.observe(el));
</script>
</body>
</html>
