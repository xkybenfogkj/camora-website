index.html
<!doctype html>
<html lang="de">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Camora – Capture Your Vision.</title>
  <meta name="description" content="Camora Kamera – jetzt reduziert: 108,99€ auf 104,99€." />

  <style>
    :root{
      --bg:#0b0c10;
      --card:#111319;
      --text:#eef1f6;
      --muted:#b6bcc8;
      --accent:#2f7bff;
      --line:#23273a;
      --radius:18px;
      --sale:#22c55e;
      --max:1080px;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial;
      color:var(--text);
      background:
        radial-gradient(1200px 600px at 20% 0%, rgba(47,123,255,.25), transparent 60%),
        radial-gradient(900px 500px at 100% 10%, rgba(255,255,255,.08), transparent 55%),
        var(--bg);
      line-height:1.45;
    }
    a{color:inherit; text-decoration:none}
    .wrap{max-width:var(--max); margin:0 auto; padding:22px 18px}
    header{
      position:sticky; top:0; z-index:10;
      background:rgba(11,12,16,.7);
      backdrop-filter: blur(10px);
      border-bottom:1px solid rgba(255,255,255,.10);
    }
    nav{display:flex; align-items:center; justify-content:space-between; gap:14px}
    .brand{display:flex; align-items:center; gap:12px; font-weight:900; letter-spacing:.3px}
    .brand img{height:40px; width:auto}
    .menu{display:flex; gap:14px; align-items:center; flex-wrap:wrap}
    .menu a{opacity:.86; font-size:14px}
    .menu a:hover{opacity:1}
    .btn{
      display:inline-flex; align-items:center; justify-content:center;
      padding:10px 14px; border-radius:999px;
      background:linear-gradient(180deg, rgba(47,123,255,.95), rgba(47,123,255,.75));
      border:1px solid rgba(47,123,255,.65);
      box-shadow:0 12px 34px rgba(47,123,255,.18);
      font-weight:800; font-size:14px;
    }
    main{padding:34px 0 68px}
    .hero{
      max-width:var(--max);
      margin:0 auto;
      padding:0 18px;
      display:grid;
      grid-template-columns: 1.15fr .85fr;
      gap:18px;
      align-items:center;
    }
    h1{font-size:48px; margin:0 0 10px; letter-spacing:-.8px}
    .sub{color:var(--muted); font-size:16px; margin:0 0 18px; max-width:60ch}
    .cta{display:flex; gap:10px; flex-wrap:wrap; margin-top:10px}
    .ghost{
      background:rgba(255,255,255,.04);
      border:1px solid rgba(255,255,255,.12);
      box-shadow:none;
      font-weight:700;
    }

    .card{
      border:1px solid rgba(255,255,255,.10);
      background:rgba(255,255,255,.03);
      border-radius:var(--radius);
      padding:16px;
    }

    .product-card{
      background:linear-gradient(180deg, rgba(255,255,255,.06), rgba(255,255,255,.02));
      border:1px solid rgba(255,255,255,.12);
      overflow:hidden;
    }

    .product-img{
      width:100%;
      height:260px;
      object-fit:cover;
      display:block;
      border-bottom:1px solid rgba(255,255,255,.10);
    }

    .badge{
      display:inline-flex;
      gap:8px; align-items:center;
      background:rgba(34,197,94,.14);
      border:1px solid rgba(34,197,94,.25);
      color:#d1fae5;
      padding:6px 10px;
      border-radius:999px;
      font-size:12px;
      font-weight:800;
    }
    .prices{margin-top:10px}
    .old{color:rgba(255,255,255,.55); text-decoration:line-through; font-size:14px}
    .new{font-size:34px; font-weight:900; margin-top:2px}
    ul{margin:12px 0 0; padding-left:18px; color:var(--muted)}
    li{margin:6px 0}

    section{max-width:var(--max); margin:0 auto; padding:18px}
    .grid3{display:grid; grid-template-columns:repeat(3,minmax(0,1fr)); gap:12px}
    .card h3{margin:0 0 6px; font-size:16px}
    .card p{margin:0; color:var(--muted); font-size:14px}

    footer{
      border-top:1px solid rgba(255,255,255,.10);
      color:var(--muted);
      font-size:13px;
    }

    @media (max-width: 900px){
      .hero{grid-template-columns:1fr}
      h1{font-size:40px}
      .product-img{height:220px}
      .grid3{grid-template-columns:1fr}
    }
  </style>
</head>

<body>
<header>
  <div class="wrap">
    <nav>
      <a class="brand" href="#top">
        <img src="logo.png" alt="Camora Logo">
        <span>Camora</span>
      </a>
      <div class="menu">
        <a href="#features">Features</a>
        <a href="#preis">Preis</a>
        <a href="#kontakt">Kontakt</a>
        <a class="btn" href="#preis">Jetzt sichern</a>
      </div>
    </nav>
  </div>
</header>

<main id="top">
  <div class="hero">
    <div>
      <h1>Capture Your Vision.</h1>
      <p class="sub">
        Camora steht für modernes Design und einfache Bedienung — perfekt für Alltag, Reisen und Content.
        Jetzt für kurze Zeit reduziert.
      </p>

      <div class="cta">
        <a class="btn" href="#preis">Zum Angebot</a>
        <a class="btn ghost" href="#features">Mehr erfahren</a>
      </div>
    </div>

    <div class="card product-card" id="preis">
      <!-- Produktfoto -->
      <img class="product-img" src="produkt.jpg" alt="Camora Produktfoto">

      <div style="padding:16px;">
        <span class="badge">Jetzt reduziert</span>

        <div class="prices">
          <div class="old">108,99 €</div>
          <div class="new">104,99 €</div>
        </div>

        <ul>
          <li>Hochwertige Kamera im Premium-Look</li>
          <li>App inklusive (Bearbeitung & Export)</li>
          <li>Optional: Upload/Cloud & Trend-Cases</li>
        </ul>

        <div style="margin-top:14px;">
          <a class="btn" href="#kontakt" style="width:100%;">Interesse / Vorbestellen</a>
        </div>
      </div>
    </div>
  </div>

  <section id="features">
    <div class="grid3">
      <div class="card">
        <h3>App inklusive</h3>
        <p>Bearbeiten, exportieren, teilen — schnell und einfach.</p>
      </div>
      <div class="card">
        <h3>Modernes Zubehör</h3>
        <p>Trendige Cases & Bundles als Add-on für euren Shop.</p>
      </div>
      <div class="card">
        <h3>Optional: Upload & Cloud</h3>
        <p>Komfort-Upgrade für automatische Sicherung der Bilder.</p>
      </div>
    </div>
  </section>
</main>

<footer id="kontakt">
  <div class="wrap">
    © 2026 Camora · Capture Your Vision. · Schulprojekt WIWAG
  </div>
</footer>
</body>
</html>
