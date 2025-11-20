<!doctype html>
<html lang="uz">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Akmal — akmal_buston_222.uz</title>

  <meta name="description" content="Akmalning shaxsiy sahifasi — akmal_buston_222.uz. Bu yerda mening ishim, ijtimoiy profillarim va tezkor aloqa ma'lumotlari.">
  <link rel="canonical" href="https://akmal_buston_222.uz/">

  <style>
    :root{ 
      --bg:#0f1724; 
      --card:#0b1220; 
      --accent:#7dd3fc; 
      --muted:#9aa5b1; 
      --glass: rgba(255,255,255,0.03);
      --yt:#ff4c4c;
    }
    *{box-sizing:border-box} 
    body{
      margin:0;
      font-family:Inter,ui-sans-serif,system-ui,Segoe UI,Roboto,'Helvetica Neue',Arial;
      background:linear-gradient(180deg,var(--bg),#071021);
      color:#e6eef6;
      min-height:100vh;
      display:flex;
      align-items:center;
      justify-content:center;
      padding:24px;
    }
    .card{
      width:100%;
      max-width:820px;
      background:linear-gradient(180deg,var(--card),#071226);
      border-radius:16px;
      padding:28px;
      box-shadow:0 10px 30px rgba(2,6,23,0.6);
      backdrop-filter: blur(6px);
      border:1px solid rgba(255,255,255,0.04);
      transition: transform 0.3s ease;
    }
    .card:hover{ transform: translateY(-5px); }
    .row{ display:flex; gap:20px; align-items:center }
    .avatar{
      width:120px; height:120px; border-radius:16px; flex:0 0 120px;
      background:linear-gradient(135deg,#0ea5a4,#60a5fa);
      display:flex; align-items:center; justify-content:center;
      font-weight:700; font-size:36px; color:#021022; overflow:hidden;
    }
    .avatar img{ width:100%; height:100%; object-fit:cover; border-radius:16px; }
    h1{ margin:0 0 6px 0; font-size:24px }
    p.lead{ margin:0; color:var(--muted) }
    .actions{ display:flex; gap:10px; margin-top:18px; flex-wrap:wrap }
    .btn{
      padding:10px 14px; border-radius:10px; text-decoration:none; font-weight:600;
      border:1px solid rgba(255,255,255,0.06); background:var(--glass);
      color:inherit; cursor:pointer; transition: all 0.3s ease;
    }
    .btn:hover{ transform: translateY(-2px); box-shadow: 0 6px 18px rgba(96,165,250,0.2); }
    .btn.primary{ background:linear-gradient(90deg,var(--accent),#60a5fa); color:#012; box-shadow:0 6px 18px rgba(96,165,250,0.12); }
    .btn.youtube{ background:var(--yt); color:#fff; box-shadow:0 6px 18px rgba(255,76,76,0.2); }
    .grid{ display:grid; grid-template-columns:repeat(3,1fr); gap:14px; margin-top:18px }
    .card-mini{ background:rgba(255,255,255,0.02); padding:12px; border-radius:10px; border:1px solid rgba(255,255,255,0.02); font-size:14px }
    footer{ margin-top:22px; color:var(--muted); font-size:13px; text-align:center }
    @media (max-width:640px){
      .row{ flex-direction:column; align-items:flex-start }
      .grid{ grid-template-columns:repeat(1,1fr) }
      .avatar{ width:96px; height:96px }
    }
  </style>
</head>
<body>
  <main class="card">
    <div class="row">
      <div class="avatar">
        <img src="https://i.ibb.co/7r1wQ0H/avatar.jpg" alt="Akmal">
      </div>
      <div style="flex:1">
        <h1>Akmal / <small style="opacity:.7">akmal_buston_222.uz</small></h1>

        <p class="lead">
          Salom sinfdoshlarim! Men Akmal Norqo'ziyev. 
          Bu saytga vaqtingizni ajratib kirganingiz uchun rahmat! 
          Yaxshimi yoqmi — maktabda aytasizlar 😊 
          YouTube va Instagram akkauntlarimga obuna bo‘linglar, oldindan rahmat!
        </p>

        <div class="actions">
          <a class="btn primary" href="#projects">Loyihalarim</a>
          <a class="btn" href="mailto:akmalnorqoziyev77@gmail.com">Email</a>
          <a class="btn" href="https://www.instagram.com/09.11.11_iwul_13/" target="_blank">Instagram</a>
          <a class="btn youtube" href="https://www.youtube.com/@akm.al_666" target="_blank">YouTube</a>
        </div>
      </div>
    </div>

    <section id="projects" style="margin-top:20px">
      <h2 style="margin:10px 0 10px 0;font-size:18px">Tezkor havolalar</h2>
      <div class="grid">
        <div class="card-mini"><strong>Video proyektlar</strong><div style="color:var(--muted);margin-top:6px">Free Fire videolar va montajlar.</div></div>
        <div class="card-mini"><strong>Portfolio</strong><div style="color:var(--muted);margin-top:6px">O'yin loyihalari va dizayn.</div></div>
        <div class="card-mini"><strong>Kontakt</strong><div style="color:var(--muted);margin-top:6px">Email yoki ijtimoiy tarmoqlar orqali bog'laning.</div></div>
      </div>
    </section>

    <footer>
      &copy; <span id="year"></span> Akmal — akmal_buston_222.uz
    </footer>
  </main>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>

