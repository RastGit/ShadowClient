<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ShadowClient — The Ultimate Minecraft Client</title>
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --bg:         #04000c;
    --purple-900: #1a003a;
    --purple-700: #3b0080;
    --purple-500: #7c3aed;
    --purple-400: #a855f7;
    --purple-300: #c084fc;
    --text:       #f5eeff;
    --muted:      #6b5880;
    --border:     rgba(168,85,247,.16);
    --border-h:   rgba(168,85,247,.42);
    --glow:       rgba(124,58,237,.4);
  }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'Inter', sans-serif;
    overflow-x: hidden;
    line-height: 1.6;
  }

  body::after {
    content: '';
    position: fixed;
    inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='400' height='400'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.75' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='400' height='400' filter='url(%23n)' opacity='0.03'/%3E%3C/svg%3E");
    pointer-events: none;
    z-index: 9000;
  }

  /* ── NAV ── */
  nav {
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 500;
    height: 64px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 56px;
    background: rgba(4,0,12,.82);
    border-bottom: 1px solid var(--border);
    backdrop-filter: blur(22px);
    -webkit-backdrop-filter: blur(22px);
  }

  .logo {
    font-family: 'Orbitron', sans-serif;
    font-weight: 900;
    font-size: 1.2rem;
    letter-spacing: .06em;
    text-decoration: none;
    background: linear-gradient(130deg, #fff 0%, var(--purple-300) 55%, var(--purple-400) 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }

  .nav-links { display: flex; gap: 32px; list-style: none; }

  .nav-links a {
    color: var(--muted);
    text-decoration: none;
    font-size: .82rem;
    font-weight: 500;
    letter-spacing: .1em;
    text-transform: uppercase;
    transition: color .25s;
  }

  .nav-links a:hover { color: var(--purple-300); }

  /* ── HERO ── */
  .hero {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 130px 24px 100px;
    position: relative;
    overflow: hidden;
  }

  .blob {
    position: absolute;
    border-radius: 50%;
    filter: blur(90px);
    pointer-events: none;
  }
  .blob-1 {
    width: 720px; height: 520px;
    background: radial-gradient(ellipse, rgba(124,58,237,.2), transparent 70%);
    top: -120px; left: 50%;
    transform: translateX(-50%);
  }
  .blob-2 {
    width: 420px; height: 420px;
    background: radial-gradient(ellipse, rgba(59,0,128,.38), transparent 70%);
    bottom: 0; left: -120px;
  }
  .blob-3 {
    width: 360px; height: 360px;
    background: radial-gradient(ellipse, rgba(100,0,200,.22), transparent 70%);
    top: 80px; right: -80px;
  }

  .hero-grid {
    position: absolute;
    inset: 0;
    background-image:
      linear-gradient(var(--border) 1px, transparent 1px),
      linear-gradient(90deg, var(--border) 1px, transparent 1px);
    background-size: 72px 72px;
    mask-image: radial-gradient(ellipse 75% 75% at 50% 40%, black 10%, transparent 100%);
    opacity: .55;
  }

  .badge {
    position: relative; z-index: 2;
    display: inline-flex;
    align-items: center;
    gap: 8px;
    background: rgba(168,85,247,.09);
    border: 1px solid rgba(168,85,247,.32);
    border-radius: 100px;
    padding: 5px 16px 5px 10px;
    font-size: .71rem;
    letter-spacing: .15em;
    text-transform: uppercase;
    color: var(--purple-300);
    margin-bottom: 32px;
    animation: fadeUp .7s ease both;
  }

  .badge-dot {
    width: 6px; height: 6px;
    border-radius: 50%;
    background: var(--purple-400);
    box-shadow: 0 0 8px var(--purple-400);
    animation: blink 2s ease-in-out infinite;
  }

  @keyframes blink { 0%,100%{opacity:1} 50%{opacity:.2} }

  .hero h1 {
    position: relative; z-index: 2;
    font-family: 'Orbitron', sans-serif;
    font-weight: 900;
    font-size: clamp(3.8rem, 11vw, 9rem);
    line-height: .94;
    letter-spacing: -.03em;
    background: linear-gradient(150deg, #ffffff 0%, #ddbfff 32%, var(--purple-400) 70%, var(--purple-500) 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    filter: drop-shadow(0 0 55px rgba(168,85,247,.32));
    animation: fadeUp .8s ease .08s both;
    margin-bottom: 14px;
  }

  .hero-eye {
    position: relative; z-index: 2;
    font-family: 'Orbitron', sans-serif;
    font-size: clamp(.72rem, 1.4vw, .95rem);
    letter-spacing: .42em;
    color: var(--purple-400);
    text-transform: uppercase;
    opacity: .6;
    margin-bottom: 28px;
    animation: fadeUp .8s ease .16s both;
  }

  .hero p {
    position: relative; z-index: 2;
    max-width: 500px;
    font-size: 1.04rem;
    color: #9c8ab0;
    line-height: 1.78;
    font-weight: 400;
    margin-bottom: 52px;
    animation: fadeUp .8s ease .24s both;
  }

  .hero-cta {
    position: relative; z-index: 2;
    display: flex;
    gap: 14px;
    flex-wrap: wrap;
    justify-content: center;
    animation: fadeUp .8s ease .32s both;
  }

  /* buttons */
  .btn {
    display: inline-flex;
    align-items: center;
    gap: 9px;
    padding: 14px 36px;
    font-family: 'Orbitron', sans-serif;
    font-weight: 700;
    font-size: .76rem;
    letter-spacing: .13em;
    text-transform: uppercase;
    text-decoration: none;
    border-radius: 8px;
    cursor: pointer;
    border: none;
    transition: transform .3s cubic-bezier(.34,1.56,.64,1), box-shadow .3s;
  }

  .btn-fill {
    color: #fff;
    background: linear-gradient(135deg, #5b21b6, var(--purple-500) 60%, var(--purple-400));
    box-shadow: 0 0 30px rgba(124,58,237,.45), inset 0 1px 0 rgba(255,255,255,.12);
  }

  .btn-fill:hover {
    transform: translateY(-3px);
    box-shadow: 0 0 52px rgba(168,85,247,.62), inset 0 1px 0 rgba(255,255,255,.12);
  }

  .btn-ghost {
    color: var(--purple-300);
    background: transparent;
    border: 1px solid var(--border-h);
  }

  .btn-ghost:hover {
    background: rgba(168,85,247,.08);
    border-color: var(--purple-400);
    color: #fff;
    transform: translateY(-2px);
  }

  /* ── STATS ── */
  .stats-bar {
    background: rgba(255,255,255,.018);
    border-top: 1px solid var(--border);
    border-bottom: 1px solid var(--border);
  }

  .stats-inner {
    max-width: 900px;
    margin: 0 auto;
    display: flex;
  }

  .stat {
    flex: 1;
    text-align: center;
    padding: 38px 20px;
    border-right: 1px solid var(--border);
  }
  .stat:last-child { border-right: none; }

  .stat-n {
    font-family: 'Orbitron', sans-serif;
    font-size: 2.3rem;
    font-weight: 900;
    color: var(--purple-400);
    text-shadow: 0 0 24px rgba(168,85,247,.48);
    line-height: 1;
  }

  .stat-l {
    font-size: .76rem;
    color: var(--muted);
    letter-spacing: .13em;
    text-transform: uppercase;
    margin-top: 8px;
  }

  /* ── SECTIONS ── */
  .section {
    padding: 110px 60px;
    max-width: 1200px;
    margin: 0 auto;
  }

  .tag {
    display: inline-flex;
    align-items: center;
    gap: 10px;
    font-size: .71rem;
    letter-spacing: .2em;
    text-transform: uppercase;
    color: var(--purple-400);
    margin-bottom: 18px;
  }

  .tag::before {
    content: '';
    width: 18px; height: 1px;
    background: var(--purple-400);
    flex-shrink: 0;
  }

  .section-h {
    font-family: 'Orbitron', sans-serif;
    font-size: clamp(1.8rem, 3.4vw, 2.8rem);
    font-weight: 900;
    line-height: 1.1;
    margin-bottom: 14px;
  }

  .section-h em {
    font-style: normal;
    background: linear-gradient(130deg, var(--purple-300), var(--purple-500));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }

  .section-sub {
    color: var(--muted);
    font-size: 1rem;
    max-width: 460px;
    margin-bottom: 60px;
    line-height: 1.7;
  }

  /* ── FEATURES ── */
  .features-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(290px, 1fr));
    gap: 16px;
  }

  .card {
    background: linear-gradient(145deg, rgba(255,255,255,.028) 0%, rgba(168,85,247,.04) 100%);
    border: 1px solid var(--border);
    border-radius: 14px;
    padding: 32px 28px;
    transition: border-color .3s, transform .35s cubic-bezier(.34,1.56,.64,1), box-shadow .3s;
    position: relative;
    overflow: hidden;
  }

  .card::after {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 1px;
    background: linear-gradient(90deg, transparent, var(--purple-500), transparent);
    opacity: 0;
    transition: opacity .3s;
  }

  .card:hover {
    border-color: var(--border-h);
    transform: translateY(-5px);
    box-shadow: 0 18px 52px rgba(124,58,237,.14);
  }
  .card:hover::after { opacity: 1; }

  .card-icon {
    width: 44px; height: 44px;
    background: rgba(124,58,237,.13);
    border: 1px solid rgba(168,85,247,.22);
    border-radius: 10px;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 20px;
    color: var(--purple-300);
    flex-shrink: 0;
  }

  .card-icon svg { width:20px; height:20px; stroke:currentColor; fill:none; stroke-width:1.8; stroke-linecap:round; stroke-linejoin:round; }

  .card-title {
    font-family: 'Orbitron', sans-serif;
    font-size: .88rem;
    font-weight: 700;
    letter-spacing: .07em;
    margin-bottom: 10px;
    color: #fff;
  }

  .card-desc {
    font-size: .94rem;
    color: #7a6890;
    line-height: 1.68;
    font-weight: 400;
  }

  /* ── DOWNLOAD ── */
  #download {
    padding: 120px 24px;
    position: relative;
    overflow: hidden;
  }

  #download .blob-dl {
    position: absolute;
    inset: 0;
    background: radial-gradient(ellipse 68% 78% at 50% 50%, rgba(59,0,128,.32) 0%, transparent 70%);
    pointer-events: none;
  }

  .dl-box {
    position: relative; z-index: 2;
    max-width: 580px;
    margin: 0 auto;
    text-align: center;
    background: rgba(255,255,255,.028);
    border: 1px solid var(--border-h);
    border-radius: 20px;
    padding: 64px 48px;
    backdrop-filter: blur(14px);
    box-shadow: 0 0 80px rgba(124,58,237,.11), inset 0 1px 0 rgba(255,255,255,.055);
  }

  .dl-version {
    font-family: 'Orbitron', sans-serif;
    font-size: .67rem;
    letter-spacing: .24em;
    color: var(--purple-300);
    opacity: .6;
    margin-bottom: 10px;
  }

  .dl-title {
    font-family: 'Orbitron', sans-serif;
    font-size: 2rem;
    font-weight: 900;
    margin-bottom: 14px;
  }

  .dl-desc {
    color: #7a6890;
    font-size: 1rem;
    line-height: 1.72;
    margin-bottom: 36px;
  }

  .dl-meta {
    display: flex;
    justify-content: center;
    gap: 10px;
    margin-bottom: 40px;
    flex-wrap: wrap;
  }

  .dl-chip {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    font-size: .76rem;
    color: var(--muted);
    background: rgba(255,255,255,.035);
    border: 1px solid var(--border);
    border-radius: 100px;
    padding: 4px 14px;
    letter-spacing: .04em;
  }

  .dl-chip svg { width:11px; height:11px; stroke:currentColor; fill:none; stroke-width:2; stroke-linecap:round; stroke-linejoin:round; flex-shrink:0; }

  .btn-dl {
    display: inline-flex;
    align-items: center;
    gap: 12px;
    padding: 18px 56px;
    font-family: 'Orbitron', sans-serif;
    font-weight: 900;
    font-size: .86rem;
    letter-spacing: .16em;
    text-transform: uppercase;
    color: #fff;
    background: linear-gradient(135deg, #4c1d95, var(--purple-500) 50%, var(--purple-400));
    border: none;
    border-radius: 10px;
    cursor: pointer;
    text-decoration: none;
    transition: transform .3s cubic-bezier(.34,1.56,.64,1), box-shadow .3s;
    box-shadow: 0 0 40px rgba(124,58,237,.5), 0 0 80px rgba(124,58,237,.18), inset 0 1px 0 rgba(255,255,255,.18);
  }

  .btn-dl:hover {
    transform: translateY(-4px) scale(1.025);
    box-shadow: 0 0 60px rgba(168,85,247,.7), 0 0 120px rgba(124,58,237,.28), inset 0 1px 0 rgba(255,255,255,.18);
  }

  .btn-dl svg { width:20px; height:20px; stroke:currentColor; fill:none; stroke-width:2.4; stroke-linecap:round; stroke-linejoin:round; }

  /* ── DIVIDER ── */
  .divider {
    height: 1px;
    background: linear-gradient(90deg, transparent, var(--border-h), transparent);
    margin: 0 60px;
  }

  /* ── COMMENTS ── */
  .comments-wrap {
    max-width: 820px;
    margin: 0 auto;
    padding: 0 60px 120px;
  }

  .comments-head {
    display: flex;
    align-items: flex-end;
    justify-content: space-between;
    margin-bottom: 40px;
    flex-wrap: wrap;
    gap: 12px;
  }

  .c-badge {
    font-size: .78rem;
    color: var(--muted);
    background: rgba(168,85,247,.07);
    border: 1px solid var(--border);
    border-radius: 100px;
    padding: 4px 14px;
  }

  .cform {
    background: rgba(255,255,255,.022);
    border: 1px solid var(--border);
    border-radius: 14px;
    padding: 28px;
    margin-bottom: 28px;
  }

  .cform-row {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 12px;
    margin-bottom: 12px;
  }

  .cinput, .ctextarea {
    width: 100%;
    background: rgba(255,255,255,.038);
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 11px 16px;
    color: var(--text);
    font-family: 'Inter', sans-serif;
    font-size: .94rem;
    outline: none;
    transition: border-color .22s, box-shadow .22s;
  }

  .cinput::placeholder, .ctextarea::placeholder { color: #4a3a5a; }

  .cinput:focus, .ctextarea:focus {
    border-color: var(--purple-500);
    box-shadow: 0 0 0 3px rgba(124,58,237,.11);
  }

  .ctextarea { resize: vertical; min-height: 96px; }

  .cform-foot {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    gap: 14px;
    margin-top: 12px;
  }

  .cform-hint { font-size: .76rem; color: #4a3a5a; }

  .btn-submit {
    padding: 10px 28px;
    font-family: 'Orbitron', sans-serif;
    font-weight: 700;
    font-size: .7rem;
    letter-spacing: .13em;
    text-transform: uppercase;
    color: #fff;
    background: linear-gradient(135deg, var(--purple-700), var(--purple-500));
    border: none;
    border-radius: 7px;
    cursor: pointer;
    transition: transform .25s cubic-bezier(.34,1.56,.64,1), box-shadow .25s;
    box-shadow: 0 0 20px rgba(124,58,237,.3);
  }

  .btn-submit:hover {
    transform: translateY(-2px);
    box-shadow: 0 0 32px rgba(168,85,247,.5);
  }

  .c-list { display: flex; flex-direction: column; gap: 14px; }

  .c-card {
    background: rgba(255,255,255,.022);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 22px 24px;
    transition: border-color .25s, transform .28s cubic-bezier(.22,1,.36,1);
  }

  .c-card:hover {
    border-color: var(--border-h);
    transform: translateX(3px);
  }

  .c-meta {
    display: flex;
    align-items: center;
    gap: 12px;
    margin-bottom: 10px;
  }

  .c-av {
    width: 36px; height: 36px;
    border-radius: 8px;
    background: linear-gradient(135deg, var(--purple-700), var(--purple-500));
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: 'Orbitron', sans-serif;
    font-weight: 900;
    font-size: .76rem;
    color: #fff;
    flex-shrink: 0;
    letter-spacing: .04em;
  }

  .c-nick {
    font-family: 'Orbitron', sans-serif;
    font-size: .8rem;
    font-weight: 700;
    color: var(--purple-300);
    letter-spacing: .05em;
  }

  .c-date {
    font-size: .73rem;
    color: var(--muted);
    margin-left: auto;
  }

  .c-text {
    font-size: .96rem;
    color: #9a88ad;
    line-height: 1.66;
    font-weight: 400;
  }

  .c-empty {
    text-align: center;
    padding: 60px 20px;
    color: var(--muted);
    font-size: .94rem;
    border: 1px dashed var(--border);
    border-radius: 12px;
  }

  /* ── FOOTER ── */
  footer {
    border-top: 1px solid var(--border);
    padding: 44px 60px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 16px;
  }

  .footer-logo {
    font-family: 'Orbitron', sans-serif;
    font-weight: 900;
    font-size: 1.05rem;
    background: linear-gradient(130deg, #fff, var(--purple-300));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }

  footer p { color: var(--muted); font-size: .82rem; }

  /* ── ANIMATIONS ── */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(28px); }
    to   { opacity: 1; transform: translateY(0); }
  }

  .reveal {
    opacity: 0;
    transform: translateY(22px);
    transition: opacity .7s cubic-bezier(.22,1,.36,1), transform .7s cubic-bezier(.22,1,.36,1);
  }
  .reveal.visible { opacity: 1; transform: none; }
  .reveal:nth-child(2) { transition-delay: .08s; }
  .reveal:nth-child(3) { transition-delay: .16s; }
  .reveal:nth-child(4) { transition-delay: .24s; }
  .reveal:nth-child(5) { transition-delay: .32s; }
  .reveal:nth-child(6) { transition-delay: .40s; }

  /* scrollbar */
  ::-webkit-scrollbar { width: 5px; }
  ::-webkit-scrollbar-track { background: var(--bg); }
  ::-webkit-scrollbar-thumb { background: var(--purple-700); border-radius: 4px; }
  ::-webkit-scrollbar-thumb:hover { background: var(--purple-500); }

  @media (max-width: 768px) {
    nav { padding: 0 20px; }
    .nav-links { gap: 18px; }
    .section { padding: 70px 24px; }
    .comments-wrap { padding: 0 24px 80px; }
    .cform-row { grid-template-columns: 1fr; }
    footer { padding: 36px 24px; flex-direction: column; text-align: center; }
    .stats-inner { flex-wrap: wrap; }
    .stat { min-width: 140px; border-right: none; border-bottom: 1px solid var(--border); }
    .stat:last-child { border-bottom: none; }
    .dl-box { padding: 40px 24px; }
  }
</style>
</head>
<body>

<!-- NAV -->
<nav>
  <a href="#" class="logo">Shadow<span style="-webkit-text-fill-color:var(--purple-400)">Client</span></a>
  <ul class="nav-links">
    <li><a href="#features">Features</a></li>
    <li><a href="#download">Download</a></li>
    <li><a href="#download">Download</a></li>
  </ul>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="blob blob-1"></div>
  <div class="blob blob-2"></div>
  <div class="blob blob-3"></div>
  <div class="hero-grid"></div>

  <div class="badge">
    <span class="badge-dot"></span>
    Version 2.4.1 — Now Available
  </div>

  <h1>ShadowClient</h1>
  <div class="hero-eye">The Ultimate PvP Client</div>
  <p>A high-performance Minecraft client engineered for competitive players. Precision modules, maximum FPS, total control.</p>

  <div class="hero-cta">
    <a href="#download" class="btn btn-fill">
      <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round" stroke-linejoin="round">
        <path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/>
        <polyline points="7 10 12 15 17 10"/>
        <line x1="12" y1="15" x2="12" y2="3"/>
      </svg>
      Download .jar
    </a>
    <a href="#features" class="btn btn-ghost">
      Explore Features
      <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round" stroke-linejoin="round">
        <line x1="5" y1="12" x2="19" y2="12"/>
        <polyline points="12 5 19 12 12 19"/>
      </svg>
    </a>
  </div>
</section>

<!-- STATS -->
<div class="stats-bar">
  <div class="stats-inner">
    <div class="stat">
      <div class="stat-n" id="stat-dl">—</div>
      <div class="stat-l">Total Downloads</div>
    </div>
    <div class="stat">
      <div class="stat-n" id="stat-users">—</div>
      <div class="stat-l">Active Players</div>
    </div>
    <div class="stat">
      <div class="stat-n">64</div>
      <div class="stat-l">Modules</div>
    </div>
    <div class="stat">
      <div class="stat-n">1.21.4</div>
      <div class="stat-l">Minecraft Version</div>
    </div>
  </div>
</div>

<!-- FEATURES -->
<section class="section" id="features">
  <div class="tag">What we offer</div>
  <div class="section-h">Built for <em>winners</em></div>
  <p class="section-sub">Every module is crafted with precision, giving you a measurable edge in every match.</p>

  <div class="features-grid">

    <div class="card reveal">
      <div class="card-icon">
        <svg viewBox="0 0 24 24"><path d="M18 3a3 3 0 0 0-3 3v12a3 3 0 0 0 3 3 3 3 0 0 0 3-3 3 3 0 0 0-3-3H6a3 3 0 0 0-3 3 3 3 0 0 0 3 3 3 3 0 0 0 3-3V6a3 3 0 0 0-3-3 3 3 0 0 0-3 3 3 3 0 0 0 3 3h12a3 3 0 0 0 3-3 3 3 0 0 0-3-3z"/></svg>
      </div>
      <div class="card-title">KillAura</div>
      <div class="card-desc">Advanced combat system with multi-target filtering, configurable range, swing speed, and humanized attack patterns that pass anticheats.</div>
    </div>

    <div class="card reveal">
      <div class="card-icon">
        <svg viewBox="0 0 24 24"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>
      </div>
      <div class="card-title">AntiKnockback</div>
      <div class="card-desc">Reduce or nullify knockback on impact. Stay grounded while opponents fly across the map. Fully adjustable horizontal and vertical multipliers.</div>
    </div>

    <div class="card reveal">
      <div class="card-icon">
        <svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="2"/><path d="M2 12s3-7 10-7 10 7 10 7-3 7-10 7-10-7-10-7z"/></svg>
      </div>
      <div class="card-title">ESP & Tracers</div>
      <div class="card-desc">See players and items through walls with customizable colors, fill opacity, outline thickness, and distance-based fade. Full RGB support.</div>
    </div>

    <div class="card reveal">
      <div class="card-icon">
        <svg viewBox="0 0 24 24"><polygon points="13 2 3 14 12 14 11 22 21 10 12 10 13 2"/></svg>
      </div>
      <div class="card-title">Velocity</div>
      <div class="card-desc">Take full control of your velocity values. Dodge incoming damage, move unpredictably, and deny opponents any consistent hit registration.</div>
    </div>

    <div class="card reveal">
      <div class="card-icon">
        <svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="10"/><line x1="22" y1="12" x2="18" y2="12"/><line x1="6" y1="12" x2="2" y2="12"/><line x1="12" y1="6" x2="12" y2="2"/><line x1="12" y1="22" x2="12" y2="18"/></svg>
      </div>
      <div class="card-title">AimAssist</div>
      <div class="card-desc">Subtle, humanized aim correction that snaps to the nearest valid target. Configurable FOV, smoothing, and priority targeting.</div>
    </div>

    <div class="card reveal">
      <div class="card-icon">
        <svg viewBox="0 0 24 24"><rect x="3" y="3" width="7" height="7"/><rect x="14" y="3" width="7" height="7"/><rect x="14" y="14" width="7" height="7"/><rect x="3" y="14" width="7" height="7"/></svg>
      </div>
      <div class="card-title">Scaffold & Bridge</div>
      <div class="card-desc">Place blocks beneath your feet at any speed. Cross gaps in seconds with automated bridging modes — straight, diagonal, and god-bridge supported.</div>
    </div>

  </div>
</section>

<div class="divider"></div>

<!-- DOWNLOAD -->
<div id="download">
  <div class="blob-dl"></div>
  <div class="dl-box reveal">
    <div class="dl-version">Release v2.4.1 — Stable Build</div>
    <div class="dl-title">Download <span style="background:linear-gradient(130deg,var(--purple-300),var(--purple-500));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text">ShadowClient</span></div>
    <div class="dl-desc">Drop the .jar into your mods folder and launch through any 1.8.9 loader. No installer required.</div>

    <div class="dl-meta">
      <span class="dl-chip">
        <svg viewBox="0 0 24 24"><path d="M21 16V8a2 2 0 0 0-1-1.73l-7-4a2 2 0 0 0-2 0l-7 4A2 2 0 0 0 3 8v8a2 2 0 0 0 1 1.73l7 4a2 2 0 0 0 2 0l7-4A2 2 0 0 0 21 16z"/></svg>
        12.4 MB
      </span>
      <span class="dl-chip">
        <svg viewBox="0 0 24 24"><polyline points="20 6 9 17 4 12"/></svg>
        Minecraft 1.21.4
      </span>
      <span class="dl-chip">
        <svg viewBox="0 0 24 24"><rect x="2" y="3" width="20" height="14" rx="2"/><line x1="8" y1="21" x2="16" y2="21"/><line x1="12" y1="17" x2="12" y2="21"/></svg>
        Windows / Linux
      </span>
    </div>

    <a href="shadowclient.jar" class="btn-dl" id="dl-btn" download onclick="handleDownload()">
      <svg viewBox="0 0 24 24">
        <path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/>
        <polyline points="7 10 12 15 17 10"/>
        <line x1="12" y1="15" x2="12" y2="3"/>
      </svg>
      Download .jar
    </a>
  </div>
</div>



<!-- FOOTER -->
<footer>
  <div class="footer-logo">ShadowClient</div>
  <p>Not affiliated with Mojang or Microsoft.</p>
  <p>&copy; 2026 ShadowClient. All rights reserved.</p>
</footer>

<script>
/* ── KEYS ── */
const DL_KEY      = 'sc_dl_count';
const DL_DONE_KEY = 'sc_dl_done';
const BASE_DL     = 12;

/* ── DOWNLOAD COUNTER ── */
function getDownloads() {
  return parseInt(localStorage.getItem(DL_KEY) || BASE_DL, 10);
}
function saveDownloads(n) { localStorage.setItem(DL_KEY, n); }

function renderDownloads() {
  document.getElementById('stat-dl').textContent = getDownloads().toLocaleString('en');
}

function handleDownload() {
  if (!localStorage.getItem(DL_DONE_KEY)) {
    saveDownloads(getDownloads() + 1);
    localStorage.setItem(DL_DONE_KEY, '1');
    renderDownloads();
  }
}

/* ── ACTIVE PLAYERS ──
   Rule: for download count N (min 12):
     range low  = N - 6
     range high = N - 3
   Examples:
     12 → 6–9   (12-6=6, 12-3=9)
     13 → 7–10  (13-6=7, 13-3=10)
     14 → 8–11  (14-6=8, 14-3=11)
   A new random value within range is picked each page load.
── */
function getActivePlayers() {
  const dl  = getDownloads();
  const low  = dl - 6;
  const high = dl - 3;
  return Math.floor(Math.random() * (high - low + 1)) + low;
}

function renderPlayers() {
  document.getElementById('stat-users').textContent = getActivePlayers().toLocaleString('en');
}

/* ── REVEAL ON SCROLL ── */
const revEls = document.querySelectorAll('.reveal');
const ro = new IntersectionObserver(entries => {
  entries.forEach(e => {
    if (e.isIntersecting) { e.target.classList.add('visible'); ro.unobserve(e.target); }
  });
}, { threshold: 0.07 });
revEls.forEach(el => ro.observe(el));

/* ── INIT ── */
renderDownloads();
renderPlayers();
</script>
</body>
</html>
