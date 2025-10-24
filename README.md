<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Ai ni BOSS DON — AI Studio</title>
  <meta name="description" content="Ai ni BOSS DON — AI Comedy Photos/Videos, Business Logos/Videos, Business Songs/Campaign Songs" />
  <style>
    :root{
      --bg:#f3f4f6;
      --accent:#111827;
      --muted:#6b7280;
      --card:#e5e7eb;
      --primary:#111827;
      --radius:16px;
      --max-width:1100px;
      font-family: Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;background:linear-gradient(180deg,var(--bg),#d1d5db);color:var(--accent)}
    .container{max-width:var(--max-width);margin:40px auto;padding:24px}
    header{display:flex;align-items:center;justify-content:space-between}
    .brand{display:flex;gap:12px;align-items:center}
    .logo{width:60px;height:60px;border-radius:12px;background:var(--primary);display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700}
    h1{font-size:48px;margin:12px 0 6px;line-height:1;padding-right:12px}
    p.lead{color:var(--muted);margin:0 0 18px}
    .grid{display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:start}
    .card{background:linear-gradient(180deg,rgba(255,255,255,0.9),rgba(255,255,255,0.8));border-radius:var(--radius);padding:22px;box-shadow:0 8px 24px rgba(15,23,42,0.08)}
    .services{display:flex;flex-direction:column;gap:12px}
    .service{display:flex;gap:12px;align-items:center}
    .check{width:34px;height:34px;border-radius:50%;background:var(--primary);color:#fff;display:flex;align-items:center;justify-content:center;font-weight:700}
    .cta-row{display:flex;gap:12px;margin-top:14px}
    .btn{padding:12px 18px;border-radius:12px;text-decoration:none;font-weight:600}
    .btn-primary{background:var(--primary);color:white}
    .btn-ghost{background:transparent;border:1px solid rgba(0,0,0,0.08)}
    .contact{display:flex;gap:12px;color:var(--muted);font-size:14px;margin-top:18px}
    .hero-image{background:linear-gradient(180deg,#fff, #f9fafb);border-radius:var(--radius);padding:18px;display:flex;justify-content:center;align-items:center}
    .photo{width:100%;max-width:360px;border-radius:12px;object-fit:cover}
    footer{margin-top:26px;color:var(--muted);font-size:13px;text-align:center}
    @media (max-width:880px){.grid{grid-template-columns:1fr;}h1{font-size:36px}.hero-image{order:-1}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">BD</div>
        <div>
          <div style="font-weight:700;">Ai ni BOSS DON</div>
          <div style="font-size:13px;color:var(--muted);">AI studio • Comedy • Branding • Music</div>
        </div>
      </div>
      <nav style="font-size:14px;color:var(--muted)">
        <a href="portfolio.html" style="margin-right:18px;color:inherit;text-decoration:none">Portfolio</a>
        <a href="services.html" style="margin-right:18px;color:inherit;text-decoration:none">Services</a>
        <a href="about.html" style="margin-right:18px;color:inherit;text-decoration:none">About</a>
        <a href="contact.html" style="color:inherit;text-decoration:none">Contact</a>
      </nav>
    </header>

    <main class="grid" style="margin-top:22px">
      <section>
        <h1>Ai ni<br><strong>BOSS DON</strong></h1>
        <p class="lead">Turning your ideas into AI-powered art, laughs, and brand magic. Fast, affordable, and tailor-made for small businesses and creators.</p>

        <div class="card" id="services">
          <h3 style="margin:0 0 12px">What we do</h3>
          <div class="services">
            <div class="service"><div class="check">✓</div><div><strong>AI Comedy Photos & Videos</strong><div style="color:var(--muted);font-size:13px">Short comedic scenes, memes, and personality-driven clips.</div></div></div>
            <div class="service"><div class="check">✓</div><div><strong>Business Logos & Videos</strong><div style="color:var(--muted);font-size:13px">Branding assets and promo videos designed with AI-assisted workflows.</div></div></div>
            <div class="service"><div class="check">✓</div><div><strong>Business & Campaign Songs</strong><div style="color:var(--muted);font-size:13px">Custom jingles and longer tracks to power your campaigns.</div></div></div>
          </div>

          <div class="cta-row">
            <a class="btn btn-primary" href="portfolio.html">See Our Work</a>
            <a class="btn btn-ghost" href="contact.html">Contact Us</a>
          </div>

          <div class="contact" id="contact">
            <div>ainibossdon@gmail.com</div>
            <div>@ainibossdon</div>
          </div>
        </div>
      </section>

      <aside>
        <div class="hero-image">
          <img class="photo" src="bossdon.jpg" alt="Ai ni BOSS DON" />
        </div>
      </aside>
    </main>
