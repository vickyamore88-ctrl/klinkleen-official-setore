<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>KlinKleen — Cloth Stain Remover | Membersihkan semua noda yang membandel</title>
  <meta name="description" content="KlinKleen — sabun butiran detergen hijau untuk mengangkat noda membandel tanpa merusak serat kain. Varian Fresh, aman & wangi." />
  <meta name="keywords" content="KlinKleen, sabun pencuci noda, stain remover, detergen butiran, sabun hijau" />
  <meta name="author" content="KlinKleen" />
  <!-- Open Graph -->
  <meta property="og:title" content="KlinKleen — Cloth Stain Remover" />
  <meta property="og:description" content="Membersihkan semua noda yang membandel — KlinKleen varian Fresh. Aman untuk semua kain, aroma segar." />
  <meta property="og:image" content="https://via.placeholder.com/1200x630.png?text=KlinKleen+Fresh" />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://www.klinkleen.com" />
  <!-- Twitter -->
  <meta name="twitter:card" content="summary_large_image" />
  <link rel="icon" href="data:," />

  <!-- Structured data (Product / Organization) -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Product",
    "name": "KlinKleen Fresh",
    "image": "https://via.placeholder.com/800x800.png?text=KlinKleen+Fresh",
    "description": "Sabun butiran detergen hijau — efektif mengangkat noda membandel, aman untuk kain.",
    "brand": {
      "@type": "Brand",
      "name": "KlinKleen"
    },
    "offers": {
      "@type": "Offer",
      "url": "https://www.klinkleen.com",
      "priceCurrency": "IDR",
      "price": "15000",
      "availability": "https://schema.org/InStock"
    }
  }
  </script>

  <style>
    :root{
      --green-700:#1f8f5a;
      --green-500:#27ae60;
      --green-200:#e9fcec;
      --muted:#6b7280;
      --max-width:1100px;
      --accent: #2b8b5a;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family:Inter,ui-sans-serif,system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial;
      line-height:1.5;
      color:#0b1220;
      background: linear-gradient(180deg,#f9fff8 0%, #ffffff 40%);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
    }
    header{
      background:transparent;
      padding:20px 16px;
      display:flex;
      align-items:center;
      justify-content:space-between;
      max-width:var(--max-width);
      margin:0 auto;
    }
    .brand{
      display:flex;
      gap:12px;
      align-items:center;
    }
    .logo{
      width:56px;height:56px;border-radius:12px;
      display:flex;align-items:center;justify-content:center;
      background:linear-gradient(135deg,var(--green-500),var(--green-700));
      color:white;font-weight:700;font-size:18px;box-shadow:0 6px 18px rgba(39,174,96,0.18);
    }
    .brand h1{ margin:0; font-size:18px; }
    nav{ display:flex; gap:12px; align-items:center; }
    nav a{ color:var(--muted); text-decoration:none; font-weight:600; font-size:14px; padding:8px 12px; border-radius:10px; }
    nav a:hover{ background:rgba(39,174,96,0.06); color:var(--green-700); }

    /* HERO */
    .hero{
      max-width:var(--max-width);
      margin:18px auto;
      display:grid;
      grid-template-columns: 1fr 420px;
      gap:36px;
      align-items:center;
      padding:36px 18px;
    }
    .hero-card{ padding:28px; background:linear-gradient(180deg,rgba(255,255,255,0.9),rgba(255,255,255,0.8)); border-radius:16px; box-shadow:0 10px 30px rgba(16,24,40,0.06); }
    .kicker{ display:inline-block; background:var(--green-200); color:var(--green-700); padding:6px 10px; border-radius:999px; font-weight:700; font-size:13px; margin-bottom:12px; }
    .hero-card h2{ margin:8px 0 10px; font-size:36px; color:var(--green-700); line-height:1.05; }
    .hero-card p{ margin:0 0 18px; color:var(--muted); font-size:16px; }
    .cta-row{ display:flex; gap:12px; align-items:center; flex-wrap:wrap; }
    .btn-primary{
      background:linear-gradient(90deg,var(--green-700),var(--green-500));
      color:white; padding:12px 18px; border-radius:12px; text-decoration:none; font-weight:700; display:inline-flex; gap:10px; align-items:center;
      box-shadow:0 8px 20px rgba(39,174,96,0.18); transition:transform .14s ease,box-shadow .14s;
    }
    .btn-primary:hover{ transform:translateY(-3px); box-shadow:0 18px 36px rgba(39,174,96,0.2); }
    .btn-secondary{ background:transparent; border:1px solid rgba(16,24,40,0.06); color:var(--muted); padding:10px 14px; border-radius:10px; text-decoration:none; font-weight:600; }

    /* product card */
    .product-card{ background:white; border-radius:16px; padding:18px; box-shadow:0 8px 24px rgba(16,24,40,0.06); display:flex; flex-direction:column; align-items:center; gap:12px; }
    .product-image{ width:320px; height:320px; border-radius:16px; overflow:hidden; display:flex; align-items:center; justify-content:center; background:linear-gradient(180deg,#f0fff6,#ffffff); }
    .product-image img{ max-width:86%; max-height:86%; object-fit:contain; }
    .price{ font-weight:800; color:var(--green-700); font-size:20px; }

    /* sections */
    .section{ max-width:var(--max-width); margin:34px auto; padding:22px 18px; }
    .grid-3{ display:grid; grid-template-columns:repeat(3,1fr); gap:18px; align-items:start; }
    .feature{ background:white; padding:18px; border-radius:12px; box-shadow:0 8px 18px rgba(16,24,40,0.04); text-align:left; }
    .feature h4{ margin:0 0 8px; color:var(--green-700); font-size:16px; }
    .feature p{ margin:0; color:var(--muted); font-size:14px; }

    /* advantages list */
    .advantages{ display:flex; gap:18px; flex-wrap:wrap; justify-content:center; }
    .adv{ background:linear-gradient(180deg,#ffffff,#f6fff8); padding:14px 16px; border-radius:12px; min-width:220px; box-shadow:0 6px 18px rgba(16,24,40,0.04); text-align:left; }
    .adv b{ color:var(--green-700); display:block; margin-bottom:6px; }

    /* contact / footer */
    .contact-card{ background:white; padding:18px; border-radius:12px; box-shadow:0 8px 18px rgba(16,24,40,0.04); display:flex; flex-direction:column; gap:8px; align-items:center; }
    footer{ text-align:center; color:var(--muted); padding:34px 18px; }

    /* floating whatsapp */
    .wa-float{ position:fixed; right:18px; bottom:18px; z-index:999; }
    .wa-btn{ background:linear-gradient(90deg,#25d366,#128c7e); color:white; width:56px;height:56px;border-radius:999px; display:flex;align-items:center;justify-content:center; box-shadow:0 12px 30px rgba(18,140,126,0.18); text-decoration:none; transition:transform .12s; }
    .wa-btn:hover{ transform:translateY(-4px); }

    /* animation util */
    .fadein{ opacity:0; transform: translateY(14px); transition:opacity .6s ease, transform .6s ease; will-change:opacity,transform; }
    .fadein.show{ opacity:1; transform:none; }

    /* responsive */
    @media (max-width:980px){
      .hero{ grid-template-columns: 1fr; padding:24px 14px; gap:18px; }
      .product-image{ width:260px; height:260px; }
      .grid-3{ grid-template-columns:1fr; }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <div class="brand">
      <div class="logo">KK</div>
      <div>
        <h1 style="font-size:18px;margin:0">KlinKleen</h1>
        <div style="font-size:12px;color:var(--muted)">Cloth Stain Remover</div>
      </div>
    </div>
    <nav>
      <a href="#home">Home</a>
      <a href="#produk">Produk</a>
      <a href="#keunggulan">Keunggulan</a>
      <a href="#kontak">Kontak</a>
    </nav>
  </header>

  <!-- Hero -->
  <main id="home" class="hero">
    <div class="hero-card fadein">
      <span class="kicker">Varian: Fresh</span>
      <h2>KlinKleen — Membersihkan semua noda yang membandel</h2>
      <p>Sabun butiran detergen hijau: ampuh mengangkat noda minyak, keringat, dan kotoran tanpa merusak serat kain. Aman untuk keluarga & ramah lingkungan.</p>

      <div class="cta-row">
        <a class="btn-primary" href="https://wa.me/6287823236878?text=Halo%20saya%20ingin%20memesan%20KlinKleen%20(Fresh)" target="_blank" rel="noreferrer">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" aria-hidden><path d="M21 3a2 2 0 0 0-2-2H5C3.9 1 3 1.9 3 3v18l4-4h12a2 2 0 0 0 2-2V3z" fill="currentColor"/></svg>
          Beli via WhatsApp
        </a>
        <a class="btn-secondary" href="#keunggulan">Lihat Keunggulan</a>
      </div>

      <div style="margin-top:18px;color:var(--muted); font-size:13px">
        <strong>Harga contoh:</strong> KlinKleen 250g — Rp15.000 • 500g — Rp25.000 • Refill 1kg — Rp45.000
      </div>
    </div>

    <div class="product-card fadein" style="align-self:center">
      <div class="product-image">
        <img src="https://via.placeholder.com/800x800.png?text=KlinKleen+Fresh" alt="KlinKleen Fresh placeholder" />
      </div>
      <div style="text-align:center">
        <div style="font-weight:700;font-size:18px;color:var(--green-700)">KlinKleen — Fresh</div>
        <div class="price">Rp15.000 (250g)</div>
      </div>
    </div>
  </main>

  <!-- About / Features -->
  <section class="section fadein" id="produk">
    <h3 style="color:var(--green-700)">Tentang Produk</h3>
    <p style="max-width:820px;margin:12px auto;color:var(--muted)">KlinKleen adalah solusi praktis untuk mengatasi noda pada pakaian: butiran hijau aktif yang cepat larut, mudah dibilas, dan efektif mengangkat noda membandel tanpa merusak serat. Cocok untuk pakaian sehari-hari dan seragam kerja.</p>

    <div class="grid-3" style="margin-top:18px">
      <div class="feature fadein">
        <h4>Efektif vs Noda</h4>
        <p>Formulasi butiran aktif yang menarget noda minyak, saus, dan kotoran membandel.</p>
      </div>
      <div class="feature fadein">
        <h4>Lembut pada Serat</h4>
        <p>Aman untuk berbagai jenis kain termasuk pakaian berwarna dan linen rumah tangga.</p>
      </div>
      <div class="feature fadein">
        <h4>Ramah Lingkungan</h4>
        <p>Mudah dibilas, tanpa residu berbahaya, dan dikemas hemat untuk refill.</p>
      </div>
    </div>
  </section>

  <!-- Advantages -->
  <section class="section fadein" id="keunggulan">
    <h3 style="color:var(--green-700)">Keunggulan KlinKleen</h3>
    <div class="advantages" style="margin-top:16px">
      <div class="adv fadein">
        <b>Mengangkat Noda Membandel</b>
        Noda minyak & saus hilang lebih cepat setelah perendaman singkat.
      </div>
      <div class="adv fadein">
        <b>Wangi Segar Tahan Lama</b>
        Aroma fresh yang lembut membuat pakaian terasa bersih & nyaman.
      </div>
      <div class="adv fadein">
        <b>Praktis & Ekonomis</b>
        Tersedia paket 250g, 500g, dan refill 1kg untuk kebutuhan rumah tangga.
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section class="section fadein" id="kontak">
    <div style="max-width:800px;margin:0 auto;display:grid;grid-template-columns:1fr 320px;gap:20px;align-items:start">
      <div>
        <h3 style="color:var(--green-700)">Pesan Sekarang</h3>
        <p style="color:var(--muted)">Pesan cepat via WhatsApp untuk pembelian dan reseller. Kami siap bantu dan kirimkan rincian harga & ongkir.</p>
        <p style="margin-top:12px"><strong>Telpon / WhatsApp:</strong> <a href="https://wa.me/6287823236878" target="_blank" rel="noreferrer">+62 878-2323-6878</a></p>
        <p><strong>Email:</strong> <a href="mailto:info@klinkleen.com">info@klinkleen.com</a></p>
      </div>

      <div class="contact-card fadein">
        <h4 style="margin:0;color:var(--green-700)">Ringkasan</h4>
        <p style="margin:0;color:var(--muted);font-size:14px">Varian: Fresh • Format: Butiran detergen hijau • Aman untuk semua kain</p>
        <a class="btn-primary" style="margin-top:12px" href="https://wa.me/6287823236878?text=Halo%20saya%20ingin%20memesan%20KlinKleen%20(Fresh)" target="_blank" rel="noreferrer">Pesan via WhatsApp</a>
      </div>
    </div>
  </section>

  <footer>
    <div style="max-width:var(--max-width);margin:0 auto;padding:10px 18px">
      <div style="font-weight:700;color:var(--green-700)">KlinKleen</div>
      <div style="font-size:13px;color:var(--muted);margin-top:6px">© <span id="year"></span> KlinKleen. Semua Hak Dilindungi.</div>
    </div>
  </footer>

  <!-- Floating WhatsApp -->
  <div class="wa-float">
    <a class="wa-btn" href="https://wa.me/6287823236878?text=Halo%20saya%20ingin%20memesan%20KlinKleen" target="_blank" rel="noreferrer" aria-label="Beli via WhatsApp">
      <svg width="26" height="26" viewBox="0 0 24 24" fill="none"><path d="M20.52 3.48A11.95 11.95 0 0012 .0C5.37 0 0 5.37 0 12c0 2.11.55 4.09 1.59 5.86L0 24l6.26-1.63A11.94 11.94 0 0012 24c6.63 0 12-5.37 12-12 0-3.2-1.22-6.15-3.48-8.52z" fill="#fff" opacity="0.04"></path><path d="M17.5 14.6c-.3-.15-1.78-.88-2.06-.98-.27-.1-.47-.15-.67.15-.2.3-.78.98-.95 1.18-.17.2-.33.22-.61.07-.28-.15-1.17-.43-2.23-1.37-.82-.73-1.37-1.64-1.53-1.92-.16-.28-.02-.43.13-.57.14-.14.31-.35.47-.52.15-.16.2-.27.3-.45.1-.18.05-.34-.02-.49-.07-.15-.67-1.62-.92-2.23-.24-.58-.49-.5-.67-.51l-.57-.01c-.19 0-.5.07-.76.34-.26.28-1 1-.99 2.44.01 1.44 1.03 2.84 1.17 3.04s2.02 3.2 4.9 4.49c.69.3 1.22.48 1.64.62.69.24 1.32.21 1.81.13.55-.09 1.78-.73 2.03-1.44.25-.71.25-1.32.17-1.44-.08-.12-.3-.2-.6-.35z" fill="#fff"/></svg>
    </a>
  </div>

  <script>
    // set year
    document.getElementById('year').textContent = new Date().getFullYear();

    // IntersectionObserver for fade-in
    const io = new IntersectionObserver((entries) => {
      entries.forEach(e => {
        if(e.isIntersecting) e.target.classList.add('show');
      });
    }, { threshold: 0.12 });

    document.querySelectorAll('.fadein').forEach(el => io.observe(el));

    // small enhancement: smooth scroll for nav links
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click', (e)=>{
        e.preventDefault();
        const t = document.querySelector(a.getAttribute('href'));
        if(t) t.scrollIntoView({behavior:'smooth', block:'start'});
      });
    });
  </script>
</body>
</html>
