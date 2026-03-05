

موقع رسمي لشركة صالح للمقاولات والتسويق العقاري

## 📍 العنوان
بنها — القليوبية — مصر  
شارع الملك فاروق، أمام فندق القوات المسلحة

## 📞 التواصل
- هاتف: 01010892928
- واتساب: [اضغط هنا](https://wa.me/201010892928)

## 🌐 الموقع
[زيارة الموقع](https://salehrealestate.github.io/salehreal...): var(--white);
    line-height: 1.2;
  }

  .nav-logo-text span { color: var(--gold); font-size: 0.75rem; font-weight: 400; display: block; }

  .nav-links {
    display: flex; gap: 36px; list-style: none;
  }

  .nav-links a {
    color: rgba(255,255,255,0.75);
    text-decoration: none;
    font-size: 0.9rem; font-weight: 600;
    transition: color 0.3s;
    letter-spacing: 0.5px;
  }

  .nav-links a:hover { color: var(--gold); }

  .nav-cta {
    background: var(--gold);
    color: var(--dark) !important;
    padding: 8px 22px;
    border-radius: 2px;
    font-weight: 700 !important;
  }

  /* HERO */
  .hero {
    min-height: 100vh;
    display: flex; align-items: center; justify-content: center;
    position: relative;
    overflow: hidden;
    background: var(--dark);
  }

  .hero-bg {
    position: absolute; inset: 0;
    background:
      radial-gradient(ellipse 70% 60% at 30% 50%, rgba(201,162,39,0.07) 0%, transparent 70%),
      radial-gradient(ellipse 50% 80% at 80% 30%, rgba(201,162,39,0.04) 0%, transparent 60%);
  }

  .hero-grid {
    position: absolute; inset: 0; opacity: 0.04;
    background-image:
      linear-gradient(rgba(201,162,39,0.5) 1px, transparent 1px),
      linear-gradient(90deg, rgba(201,162,39,0.5) 1px, transparent 1px);
    background-size: 60px 60px;
  }

  .hero-content {
    position: relative; z-index: 2;
    text-align: center;
    padding: 120px 20px 60px;
    max-width: 900px;
  }

  .hero-badge {
    display: inline-block;
    border: 1px solid var(--gold);
    color: var(--gold);
    font-size: 0.75rem;
    letter-spacing: 3px;
    padding: 6px 20px;
    margin-bottom: 30px;
    animation: fadeUp 0.8s ease both;
  }

  .hero-logo-img {
    width: 110px; height: 110px; object-fit: contain;
    margin: 0 auto 24px;
    display: block;
    animation: fadeUp 0.8s 0.1s ease both;
    filter: drop-shadow(0 0 20px rgba(201,162,39,0.3));
  }

  .hero-title {
    font-family: 'Cairo', sans-serif;
    font-size: clamp(3rem, 8vw, 6rem);
    font-weight: 900;
    line-height: 1;
    color: var(--white);
    animation: fadeUp 0.8s 0.2s ease both;
    margin-bottom: 6px;
  }

  .hero-title span { color: var(--gold); }

  .hero-sub {
    font-size: 1rem;
    color: var(--gold);
    letter-spacing: 4px;
    font-weight: 600;
    margin-bottom: 24px;
    animation: fadeUp 0.8s 0.3s ease both;
  }

  .hero-desc {
    font-size: 1.1rem;
    color: rgba(255,255,255,0.6);
    line-height: 1.8;
    max-width: 600px;
    margin: 0 auto 40px;
    animation: fadeUp 0.8s 0.4s ease both;
  }

  .hero-btns {
    display: flex; gap: 16px; justify-content: center; flex-wrap: wrap;
    animation: fadeUp 0.8s 0.5s ease both;
  }

  .btn-primary {
    background: var(--gold);
    color: var(--dark);
    padding: 14px 36px;
    font-family: 'Cairo', sans-serif;
    font-weight: 700; font-size: 1rem;
    border: none; cursor: pointer;
    text-decoration: none;
    display: inline-block;
    transition: all 0.3s;
    clip-path: polygon(8px 0%, 100% 0%, calc(100% - 8px) 100%, 0% 100%);
  }

  .btn-primary:hover { background: var(--gold-light); transform: translateY(-2px); }

  .btn-outline {
    border: 1px solid var(--gold);
    color: var(--gold);
    padding: 14px 36px;
    font-family: 'Cairo', sans-serif;
    font-weight: 600; font-size: 1rem;
    background: transparent;
    cursor: pointer;
    text-decoration: none;
    display: inline-block;
    transition: all 0.3s;
    clip-path: polygon(8px 0%, 100% 0%, calc(100% - 8px) 100%, 0% 100%);
  }

  .btn-outline:hover { background: rgba(201,162,39,0.1); }

  /* CITIES */
  .section { padding: 100px 60px; }
  .section-label {
    font-size: 0.7rem; letter-spacing: 4px; color: var(--gold);
    text-transform: uppercase; margin-bottom: 12px;
  }
  .section-title {
    font-family: 'Cairo', sans-serif;
    font-size: clamp(2rem, 4vw, 3rem);
    font-weight: 900; margin-bottom: 20px;
  }
  .section-title span { color: var(--gold); }
  .section-line {
    width: 60px; height: 2px; background: var(--gold); margin-bottom: 50px;
  }

  .cities-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 2px;
  }

  .city-card {
    position: relative;
    height: 320px;
    overflow: hidden;
    cursor: pointer;
    group: true;
  }

  .city-card-bg {
    position: absolute; inset: 0;
    transition: transform 0.6s ease;
  }

  .city-card:hover .city-card-bg { transform: scale(1.05); }

  /* City backgrounds */
  .city-alamein .city-card-bg {
    background: linear-gradient(160deg, #0d2744 0%, #1a4a7a 50%, #0d2744 100%);
  }
  .city-newcapital .city-card-bg {
    background: linear-gradient(160deg, #1a1200 0%, #3d2e00 50%, #1a1200 100%);
  }
  .city-sahel .city-card-bg {
    background: linear-gradient(160deg, #002a2a 0%, #004d4d 50%, #002a2a 100%);
  }
  .city-tagamoa .city-card-bg {
    background: linear-gradient(160deg, #200a2a 0%, #3d1a52 50%, #200a2a 100%);
  }
  .city-october .city-card-bg {
    background: linear-gradient(160deg, #1a0a00 0%, #3d2200 50%, #1a0a00 100%);
  }
  .city-sokhna .city-card-bg {
    background: linear-gradient(160deg, #00141a 0%, #003040 50%, #00141a 100%);
  }

  .city-card-overlay {
    position: absolute; inset: 0;
    background: linear-gradient(to top, rgba(0,0,0,0.9) 0%, rgba(0,0,0,0.2) 60%, transparent 100%);
  }

  .city-card-content {
    position: absolute; bottom: 0; left: 0; right: 0;
    padding: 30px;
  }

  .city-icon {
    font-size: 2rem; margin-bottom: 10px;
  }

  .city-name {
    font-size: 1.4rem; font-weight: 900;
    margin-bottom: 6px;
  }

  .city-desc {
    font-size: 0.82rem;
    color: rgba(255,255,255,0.6);
    line-height: 1.6;
    transform: translateY(10px);
    opacity: 0;
    transition: all 0.4s ease;
  }

  .city-card:hover .city-desc { opacity: 1; transform: translateY(0); }

  .city-tag {
    display: inline-block;
    background: var(--gold);
    color: var(--dark);
    font-size: 0.65rem; font-weight: 700;
    padding: 3px 10px;
    margin-bottom: 8px;
    letter-spacing: 1px;
  }

  /* STATS */
  .stats-section {
    background: var(--dark3);
    padding: 80px 60px;
    border-top: 1px solid rgba(201,162,39,0.15);
    border-bottom: 1px solid rgba(201,162,39,0.15);
  }

  .stats-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 40px;
    text-align: center;
  }

  .stat-num {
    font-size: 3.5rem; font-weight: 900;
    color: var(--gold);
    line-height: 1;
    margin-bottom: 8px;
  }

  .stat-label {
    font-size: 0.9rem; color: rgba(255,255,255,0.6);
    font-weight: 400;
  }

  /* SERVICES */
  .services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 24px;
  }

  .service-card {
    border: 1px solid rgba(201,162,39,0.2);
    padding: 36px 28px;
    background: var(--dark2);
    transition: all 0.4s;
    position: relative;
    overflow: hidden;
  }

  .service-card::before {
    content: '';
    position: absolute; top: 0; left: 0;
    width: 3px; height: 0;
    background: var(--gold);
    transition: height 0.4s;
  }

  .service-card:hover::before { height: 100%; }
  .service-card:hover { border-color: var(--gold); transform: translateY(-4px); }

  .service-icon { font-size: 2.2rem; margin-bottom: 18px; }
  .service-name { font-size: 1.1rem; font-weight: 700; margin-bottom: 10px; }
  .service-desc { font-size: 0.85rem; color: rgba(255,255,255,0.55); line-height: 1.7; }

  /* WHY US */
  .whyus-section {
    padding: 100px 60px;
    background: radial-gradient(ellipse 80% 60% at 50% 50%, rgba(201,162,39,0.04) 0%, transparent 70%);
  }

  .whyus-grid {
    display: grid; grid-template-columns: 1fr 1fr; gap: 80px; align-items: center;
  }

  .whyus-items { display: flex; flex-direction: column; gap: 28px; }

  .whyus-item {
    display: flex; gap: 20px; align-items: flex-start;
  }

  .whyus-num {
    font-size: 3rem; font-weight: 900; color: rgba(201,162,39,0.15);
    line-height: 1; min-width: 60px;
    font-family: 'Playfair Display', serif;
  }

  .whyus-text h3 { font-size: 1.1rem; font-weight: 700; margin-bottom: 6px; }
  .whyus-text p { font-size: 0.85rem; color: rgba(255,255,255,0.55); line-height: 1.7; }

  .whyus-visual {
    position: relative;
    height: 500px;
    border: 1px solid rgba(201,162,39,0.2);
    background: var(--dark2);
    display: flex; align-items: center; justify-content: center;
    overflow: hidden;
  }

  .whyus-visual-inner {
    text-align: center;
    position: relative; z-index: 2;
  }

  .whyus-visual img {
    width: 160px; height: 160px; object-fit: contain;
    filter: drop-shadow(0 0 40px rgba(201,162,39,0.4));
    animation: float 4s ease-in-out infinite;
  }

  .whyus-visual-text {
    margin-top: 20px;
    font-size: 0.8rem; letter-spacing: 3px; color: var(--gold);
  }

  .whyus-visual::before {
    content: '';
    position: absolute; inset: 20px;
    border: 1px solid rgba(201,162,39,0.1);
    animation: pulse 3s ease-in-out infinite;
  }

  /* CONTACT */
  .contact-section {
    padding: 100px 60px;
    background: var(--dark3);
    border-top: 1px solid rgba(201,162,39,0.15);
  }

  .contact-grid {
    display: grid; grid-template-columns: 1fr 1fr; gap: 80px;
  }

  .contact-info { display: flex; flex-direction: column; gap: 30px; }

  .contact-item {
    display: flex; gap: 18px; align-items: flex-start;
  }

  .contact-item-icon {
    width: 48px; height: 48px;
    border: 1px solid var(--gold);
    display: flex; align-items: center; justify-content: center;
    font-size: 1.2rem;
    flex-shrink: 0;
    color: var(--gold);
  }

  .contact-item-text h4 { font-size: 0.75rem; letter-spacing: 2px; color: var(--gold); margin-bottom: 6px; }
  .contact-item-text p { font-size: 1rem; font-weight: 600; line-height: 1.5; }
  .contact-item-text a { color: var(--white); text-decoration: none; }
  .contact-item-text a:hover { color: var(--gold); }

  .contact-form { display: flex; flex-direction: column; gap: 16px; }

  .form-group { display: flex; flex-direction: column; gap: 8px; }
  .form-group label { font-size: 0.75rem; letter-spacing: 2px; color: rgba(255,255,255,0.5); }
  .form-group input, .form-group textarea, .form-group select {
    background: rgba(255,255,255,0.04);
    border: 1px solid rgba(201,162,39,0.2);
    color: var(--white);
    padding: 14px 18px;
    font-family: 'Cairo', sans-serif;
    font-size: 0.9rem;
    outline: none;
    transition: border-color 0.3s;
    width: 100%;
  }
  .form-group input:focus, .form-group textarea:focus, .form-group select:focus {
    border-color: var(--gold);
  }
  .form-group select option { background: var(--dark2); }
  .form-group textarea { min-height: 100px; resize: vertical; }

  /* FOOTER */
  footer {
    background: var(--dark);
    border-top: 1px solid rgba(201,162,39,0.15);
    padding: 40px 60px;
    display: flex; align-items: center; justify-content: space-between;
    flex-wrap: wrap; gap: 20px;
  }

  .footer-logo { display: flex; align-items: center; gap: 12px; }
  .footer-logo img { height: 44px; }
  .footer-logo span { font-size: 0.85rem; color: rgba(255,255,255,0.5); }

  .footer-copy { font-size: 0.8rem; color: rgba(255,255,255,0.35); text-align: center; }

  .footer-social { display: flex; gap: 12px; }
  .social-btn {
    width: 38px; height: 38px;
    border: 1px solid rgba(201,162,39,0.3);
    display: flex; align-items: center; justify-content: center;
    color: var(--gold); font-size: 0.9rem;
    text-decoration: none;
    transition: all 0.3s;
  }
  .social-btn:hover { background: var(--gold); color: var(--dark); }

  /* ANIMATIONS */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(30px); }
    to { opacity: 1; transform: translateY(0); }
  }

  @keyframes float {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-15px); }
  }

  @keyframes pulse {
    0%, 100% { opacity: 0.3; }
    50% { opacity: 0.7; }
  }

  /* SCROLL REVEAL */
  .reveal {
    opacity: 0; transform: translateY(40px);
    transition: opacity 0.8s ease, transform 0.8s ease;
  }
  .reveal.visible { opacity: 1; transform: translateY(0); }

  /* MOBILE */
  @media (max-width: 768px) {
    nav { padding: 16px 24px; }
    .nav-links { display: none; }
    .section { padding: 70px 24px; }
    .stats-section { padding: 60px 24px; }
    .stats-grid { grid-template-columns: 1fr 1fr; gap: 30px; }
    .whyus-section { padding: 70px 24px; }
    .whyus-grid { grid-template-columns: 1fr; gap: 40px; }
    .whyus-visual { height: 300px; }
    .contact-section { padding: 70px 24px; }
    .contact-grid { grid-template-columns: 1fr; gap: 50px; }
    footer { padding: 30px 24px; flex-direction: column; text-align: center; }
    .hero-content { padding: 100px 20px 40px; }
  }

  /* PHONE FLOATING BTN */
  .phone-float {
    position: fixed; bottom: 30px; left: 30px; z-index: 200;
    background: var(--gold);
    color: var(--dark);
    width: 58px; height: 58px;
    border-radius: 50%;
    display: flex; align-items: center; justify-content: center;
    font-size: 1.4rem;
    box-shadow: 0 4px 20px rgba(201,162,39,0.4);
    text-decoration: none;
    animation: phoneRing 2s ease-in-out infinite;
    transition: transform 0.3s;
  }

  .phone-float:hover { transform: scale(1.1); }

  @keyframes phoneRing {
    0%, 100% { box-shadow: 0 4px 20px rgba(201,162,39,0.4); }
    50% { box-shadow: 0 4px 40px rgba(201,162,39,0.7); }
  }

  /* DECORATIVE LINE */
  .gold-line {
    height: 1px; background: linear-gradient(90deg, transparent, var(--gold), transparent);
    margin: 0 60px;
  }
</style>
</head>
<body>

<!-- Navigation -->
<nav>
  <div class="nav-logo">
    <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAyAAAAMgCAYAAADbcAZoAAAACXBIWXMAAC4jAAAuIwF4pT92AAA3cklEQVR4nO3dd5RV5b344Xf6DDNDlaaARMSKvSB2xW7sqFjTbhIlienVX5J7Y3pMbqrR5OZeYzQm9q6o2GPDLqJiQYoCIgxMYfrM7w9DgjjlzMyZ7wzyPGu5Vuacvd/z7n0InM/svc/OKSsb2poAAAAC5Pb1BAAAgI2HAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgTH62Bpp10fBvZmssAACg/5k6Y/mPejpG1gIkpexMCAAA6H+ydcDBKVgAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEye/rCQCwYXnppp1eW/+xbY59dkJfzAWADY8jIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQJj8vp4AAD3z0k079fUUwuewzbHPhr4eANkjQADoqgl9PQEANlxOwQIAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMII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Ir3y6uu9+joAkA2OgAAfSPX19emT5345LVi4KON1Ntt0dEbL9ccLvx0FAWBDIUCAD6y6urp02eVXZbz84MEDO11m4sQt0h6779KTafWKU08+LhXkO6gNQP8nQIB+5TPnfjzts/fkrI0354WXMl62oKCg02XO6sLF55GGDRuaDj/s4L6eBgB0SoAA/cYXP39O+s75X0lX/Pn3WYuQrnwjVkNDQ4fPFxYWplOmHdfTKfWa06af2NdTAIBOCRCgX/jSF85N3/jqeSmld79l6m+XX5JOPfn4Ho+7y047ZLzsOysqOnz+yCOmduuO6VEOPnDftOnokX09DQDokAAB+txXv/SZ9PWvfO49jxUWFqZf//cP029++aM0eFDn12a0ZejQIekTHz8j4+XfeGNBh8/319Ov1srNzU3TT3UUBID+zRWLQJ/62pc/m778xRntPn/KtOPSoVMPSL/+3R/TZZdflaqrazIad+KWW6Q//P7naeSI4RnP5ZlnX2j3uc3HjU377pO9a1N6y+mnnph++etLunUzxraUlZamQQPLszLW+lZXVmVlnN6c41p19Q2pvr6+V18DYGMhQIA+882vfT594bxPd7rckCGD03f/31fTV7/02XTXrPvTAw8+kua88GJa/OZbafWqytTc0pIGDChJo0ePTDtsv1068oip6agjDkn5+Xldms+se9u/+d8Zp5+UcnJyujReXxg7drO07z6T0wMPPpKV8f76l0uyMk5bRo7ZLivj9OYc17rwF79LP/vF73r9dQA2BgIE6BPf+voX0uc/96kurTNgQEk67pgj0nHHHJH1+by1ZFl65NEn2nwuPz8vTT/lhIzH+uuV16YvfvXb2ZpaGjZsaHruyfszDqozpp+UtQABgGxzDQgQbvfddu5yfPS231/yf6m5ubnN56YevH+XTuX629XXZ2taKaWUVqxYme69/6GMlz/6qEP79cXyAGzcBAgQ7oknn0k//Mkv+3oa//La62+kSy/7W7vPd+Xi80WL3kyPz346G9N6j6uvvSnjZQsKCtK0E4/J+hwAIBsECNAnfvWbP6SfXPibvp5GamxsTDM+97V27wGy6eiRaerB+2c83t+vviG1trZma3r/csfMe1JVVXXGy595+rSszwEAskGAAH3mF7/8ffr6t77X7qlPva2lpSV95vPfSM88O6fdZaafemLKzc38r8pr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VbV87pTyty6/YNjLDz5dP3DRsuai4sKclh22LFizy9YF1W8tby48//erx69YnflFsc0t795I7+JvDHk129u7ridfbCj7fxdXjv/+OQPf+Ol5g+af//vV45+d11i65Zj8uglj8usuvLxqTGdj3PFw3ZDzppe9tcvWhdVPvdRQllLP9mlv6my/XnPPu99M9MkTypZeccHQl2bPbSh/dXFTSW19a+6Q8tymnbcqrN568/zahUubizq6xuD/bq4ZNWlCwZovnFb25kG7F616Zl5DWW19a+6mm+Q17Ldz0epBZbnNf71jzYhD9yqu+MGMQW988RertujO9T7tvX/rLrP56Lz6kw4uafc+KC/ObxrQ0Nia25P3O9PXuvae9r/5KZN5zp3fOOA//1A57sefG/TGJd8a8uojz9eXv7qoqaShMeVuOjy3/sBdi1cXFqSWP15fM6qz7VhXT/+8d1Wm29qdsYENkwCBjdAN99UOe2JuQ9m0qSXv7LFdYfVRexc31De25r6+uKn413+r3vTWf9QObWpu+1uGbnmobugz8xpL1657+F7FqxqbWnPeWNJc9Ptrqkff/FDd0O58bec/L2Ie8fFjS5f1fAvb9+SLDWXfumj1+B/MGLTgx58ZNP87l1RuPmWHwqq6htbc+57s/PSoWbPrBp87rXTJUXsXV6z7gawn+7Q3dbZfr7mndpNHnm8YeOwBJSt237agevftCqsL83NaVlW15L+yqKnkp5dVjZn1RN3gpqb2576mrjX38z9fNeG4A4pXHLx78arphw5YXliQ07K8oqXg0TkN5dfeU7vJ/Leaiu96vG7wr7885LWfnjdo/ud/vmrCW924oLyt92/2OteVbDk2v3bLsWXtnqJ12a1rRgwqy2nu6fudyWt1FCCZzHPu/MYBryxqKvnEBRUTTzmk5J3Jkwqr9ppUWJWfl9O6srIl/8mXGsquuGPNiNff7FrMHbVP8cpsbH+mMt3W7owNbJhyysqGZuX3cbMuGv7NqTOW/ygbYwEAAP1Ltj7vuwYEAAAII0AAAIAwAgQAAAgjQAAAgDACBAAACCNAAACAMAIEAAAII0AAAIAwAgQAAAgjQAAAgDACBAAACCNAAACAMAIEAAAII0AAAIAwAgQAAAgjQAAAgDACBAAACCNAAACAMPl9PQGAjdHHP37ujbW1tUXrPpafX9B8//137bZw4RujUkrpYx8796a6utrC9dd94YVnJzz33NMTp0//yMybbrrmgDVraorXX2batDPuvuaaKw5Z+/NJJ50269prr5za1lzaeq6oqKjh7LM/deull158TGNjY7f+rehs/kVFRQ2HHnr0Y+XlA2taW1tzcnJyWlNKqaWlJffhh+/fqaGhIX/ZsiXD1l9/+PCRFXV1tUVVVZUD2tqPTU1NeTNn3jxlxIhRFXvsMeWFtY+PGDGq4u23lw5Z+/Ps2Y9s/+qrL4/tzrYB0H0CBKAP1NbWFl155aVHrPtYScmA+uOPP+XehQvffbyurrZw/WXWlZeX17Lrrnu+9NBD9+68/nMFBQVN6/5cWFjU2N44bT23ww67vPrqqy+P3WabSfOff/7piRls0vt0Nv/99jv46Zdfnrv5K6+8NG7dx4cMGVp1yCFHPdrS0pJ7441XHdjU1JS39rm8vLzm/fY76Ombb752/5Ta3o8jR45ecdBBhz1x441XH7huYJx22kfv6Gg+AMRwChZAP1Fbu6aotbU1J9PlW1pacubMeWbCjjvu8ko255GTk9M6btz4pffdd9du48dvsSSbY69r+PCRFevHR0opVVSsLK+oWDFw9uyHt58yZb/n1n1uypT9nn/yyce37eiozLJlS4YNGFBa1xtzBqDnBAhAPzFkyNCqtk6n6siqVRXldXV1hSNHjl6RrXl86ENbvvnaa6+MaW1tzVm8eOHIMWPGvZ2tsTN19923T1648I1RAwaU1Q0fPrIipZSGDx9RUVpaXrtgweujo+cDQPY4BQugD5SWltWddtpH71j7c25ubuvo0Zu9c/XV/75uI1Pz5r24+V577ft8RcWKQQ0NDT3+e33bbSfNnznz5r1TSmnOnGcmHHTQ4bMXL144oqfjdscDD9y969FHn/jg9df/7eADDjj0yVtvvW6/ztaZMGHi4lWrKsoj5gdA1wkQgD5QU1NdvP71CGPHbr5s8uR95qz9Df/6kbJs2ZJh99wzc4+2xnvqqce33W23yXMfeeTBHdt6fv2x1n9u7f8eMmRoVWXl6rK11100Njbm19fXFZaVla+prq4asP66U6bs/9wjjzyQ0Wt2NP+1TjzxtHuKiooampub8q666vJDa2tri1544dkJp5/+sduffPKxbde/4Hz918jJyUmrV1eUzZrV8esA0HcECEA/sWjRgpH77z/1qbU/txUp7WloaMh//fVXN9tqq20XzJv34ubrP9/RWOt+gN9llz1e2myzsW+PGTNu2drH8vMLmpubm/Ieeui+nddft7346Or817ruuisPXn9OL74450O77z5l7ty5z2+RjdcAoG8JEIB+pKWlJeOL0Ne3bNmSYcOHj6wYPHhIVXfWLywsbCovH7jmL3/5n6PXf+7YY6fdn5eX19Lc3Bxy7eD6F+M3NTXmtbcsABsWF6ED9BPDhg1fVVu7pksXoa9vzpxnttx++x1fz83Nbe3quttvv9Nrc+Y8O6Gt515+ee74rbbadkFP5ra+5cuXDdl66+3eWP/x0aM3faeqanVpNl8LgP7DERCAPlBSUlK//jUZra2tOXfeecuUjpZJKaU5c56d8PzzT09s76ton3rq8W3GjNl82bqPNTY2FLQ3l7XPrVlTU/T6669s1tYyr7zy0rgttpi4uOOteq/O5v/gg/fscuihRz+2++57vbjukZ+GhoaCmTNvnrLuOu1ta1duklhfX/++myICEC+nrGxol39L1pZZFw3/5tQZy3+UjbEAAID+JVuf952CBQAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAECY/GwONuui4d/M5ngAAMAHS05Z2dDWvp4EAACwcXAKFgAAEEaAAAAAYQQIAAAQRoAAAABhBAgAABBGgAAAAGEECAAAEEaAAAAAYQQIAAAQRoAAAABhBAgAABBGgAAAAGEECAAAEEaAAAAAYQQIAAAQRoAAAABh/j9EJfmEglRwIQAAAABJRU5ErkJggg==" alt="صالح للعقارات" onerror="this.style.display='none'">
    <div class="nav-logo-text">
      صالح
      <span>للمقاولات والتسويق العقاري</span>
    </div>
  </div>
  <ul class="nav-links">
    <li><a href="#cities">المدن الجديدة</a></li>
    <li><a href="#services">خدماتنا</a></li>
    <li><a href="#about">لماذا نحن</a></li>
    <li><a href="#contact" class="nav-cta">تواصل معنا</a></li>
  </ul>
</nav>

<!-- Hero -->
<section class="hero">
  <div class="hero-bg"></div>
  <div class="hero-grid"></div>
  <div class="hero-content">
    <div class="hero-badge">مرحباً بكم في عالم العقارات الراقي</div>
    <img class="hero-logo-img" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAyAAAAMgCAYAAADbcAZoAAAACXBIWXMAAC4jAAAuIwF4pT92AAA3cklEQVR4nO3dd5RV5b344Xf6DDNDlaaARMSKvSB2xW7sqFjTbhIlienVX5J7Y3pMbqrR5OZeYzQm9q6o2GPDLqJiQYoCIgxMYfrM7w9DgjjlzMyZ7wzyPGu5Vuacvd/z7n0InM/svc/OKSsb2poAAAAC5Pb1BAAAgI2HAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgTH62Bpp10fBvZmssAACg/5k6Y/mPejpG1gIkpexMCAAA6H+ydcDBKVgAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEye/rCQCwYXnppp1eW/+xbY59dkJfzAWADY8jIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQJj8vp4AAD3z0k079fUUwuewzbHPhr4eANkjQADoqgl9PQEANlxOwQIAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMII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Ir3y6uu9+joAkA2OgAAfSPX19emT5345LVi4KON1Ntt0dEbL9ccLvx0FAWBDIUCAD6y6urp02eVXZbz84MEDO11m4sQt0h6779KTafWKU08+LhXkO6gNQP8nQIB+5TPnfjzts/fkrI0354WXMl62oKCg02XO6sLF55GGDRuaDj/s4L6eBgB0SoAA/cYXP39O+s75X0lX/Pn3WYuQrnwjVkNDQ4fPFxYWplOmHdfTKfWa06af2NdTAIBOCRCgX/jSF85N3/jqeSmld79l6m+XX5JOPfn4Ho+7y047ZLzsOysqOnz+yCOmduuO6VEOPnDftOnokX09DQDokAAB+txXv/SZ9PWvfO49jxUWFqZf//cP029++aM0eFDn12a0ZejQIekTHz8j4+XfeGNBh8/319Ov1srNzU3TT3UUBID+zRWLQJ/62pc/m778xRntPn/KtOPSoVMPSL/+3R/TZZdflaqrazIad+KWW6Q//P7naeSI4RnP5ZlnX2j3uc3HjU377pO9a1N6y+mnnph++etLunUzxraUlZamQQPLszLW+lZXVmVlnN6c41p19Q2pvr6+V18DYGMhQIA+882vfT594bxPd7rckCGD03f/31fTV7/02XTXrPvTAw8+kua88GJa/OZbafWqytTc0pIGDChJo0ePTDtsv1068oip6agjDkn5+Xldms+se9u/+d8Zp5+UcnJyujReXxg7drO07z6T0wMPPpKV8f76l0uyMk5bRo7ZLivj9OYc17rwF79LP/vF73r9dQA2BgIE6BPf+voX0uc/96kurTNgQEk67pgj0nHHHJH1+by1ZFl65NEn2nwuPz8vTT/lhIzH+uuV16YvfvXb2ZpaGjZsaHruyfszDqozpp+UtQABgGxzDQgQbvfddu5yfPS231/yf6m5ubnN56YevH+XTuX629XXZ2taKaWUVqxYme69/6GMlz/6qEP79cXyAGzcBAgQ7oknn0k//Mkv+3oa//La62+kSy/7W7vPd+Xi80WL3kyPz346G9N6j6uvvSnjZQsKCtK0E4/J+hwAIBsECNAnfvWbP6SfXPibvp5GamxsTDM+97V27wGy6eiRaerB+2c83t+vviG1trZma3r/csfMe1JVVXXGy595+rSszwEAskGAAH3mF7/8ffr6t77X7qlPva2lpSV95vPfSM88O6fdZaafemLKzc38r8pr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VbV87pTyty6/YNjLDz5dP3DRsuai4sKclh22LFizy9YF1W8tby48//erx69YnflFsc0t795I7+JvDHk129u7ridfbCj7fxdXjv/+OQPf+Ol5g+af//vV45+d11i65Zj8uglj8usuvLxqTGdj3PFw3ZDzppe9tcvWhdVPvdRQllLP9mlv6my/XnPPu99M9MkTypZeccHQl2bPbSh/dXFTSW19a+6Q8tymnbcqrN568/zahUubizq6xuD/bq4ZNWlCwZovnFb25kG7F616Zl5DWW19a+6mm+Q17Ldz0epBZbnNf71jzYhD9yqu+MGMQW988RertujO9T7tvX/rLrP56Lz6kw4uafc+KC/ObxrQ0Nia25P3O9PXuvae9r/5KZN5zp3fOOA//1A57sefG/TGJd8a8uojz9eXv7qoqaShMeVuOjy3/sBdi1cXFqSWP15fM6qz7VhXT/+8d1Wm29qdsYENkwCBjdAN99UOe2JuQ9m0qSXv7LFdYfVRexc31De25r6+uKn413+r3vTWf9QObWpu+1uGbnmobugz8xpL1657+F7FqxqbWnPeWNJc9Ptrqkff/FDd0O58bec/L2Ie8fFjS5f1fAvb9+SLDWXfumj1+B/MGLTgx58ZNP87l1RuPmWHwqq6htbc+57s/PSoWbPrBp87rXTJUXsXV6z7gawn+7Q3dbZfr7mndpNHnm8YeOwBJSt237agevftCqsL83NaVlW15L+yqKnkp5dVjZn1RN3gpqb2576mrjX38z9fNeG4A4pXHLx78arphw5YXliQ07K8oqXg0TkN5dfeU7vJ/Leaiu96vG7wr7885LWfnjdo/ud/vmrCW924oLyt92/2OteVbDk2v3bLsWXtnqJ12a1rRgwqy2nu6fudyWt1FCCZzHPu/MYBryxqKvnEBRUTTzmk5J3Jkwqr9ppUWJWfl9O6srIl/8mXGsquuGPNiNff7FrMHbVP8cpsbH+mMt3W7owNbJhyysqGZuX3cbMuGv7NqTOW/ygbYwEAAP1Ltj7vuwYEAAAII0AAAIAwAgQAAAgjQAAAgDACBAAACCNAAACAMAIEAAAII0AAAIAwAgQAAAgjQAAAgDACBAAACCNAAACAMAIEAAAII0AAAIAwAgQAAAgjQAAAgDACBAAACCNAAACAMPl9PQGAjdHHP37ujbW1tUXrPpafX9B8//137bZw4RujUkrpYx8796a6utrC9dd94YVnJzz33NMTp0//yMybbrrmgDVraorXX2batDPuvuaaKw5Z+/NJJ50269prr5za1lzaeq6oqKjh7LM/deull158TGNjY7f+rehs/kVFRQ2HHnr0Y+XlA2taW1tzcnJyWlNKqaWlJffhh+/fqaGhIX/ZsiXD1l9/+PCRFXV1tUVVVZUD2tqPTU1NeTNn3jxlxIhRFXvsMeWFtY+PGDGq4u23lw5Z+/Ps2Y9s/+qrL4/tzrYB0H0CBKAP1NbWFl155aVHrPtYScmA+uOPP+XehQvffbyurrZw/WXWlZeX17Lrrnu+9NBD9+68/nMFBQVN6/5cWFjU2N44bT23ww67vPrqqy+P3WabSfOff/7piRls0vt0Nv/99jv46Zdfnrv5K6+8NG7dx4cMGVp1yCFHPdrS0pJ7441XHdjU1JS39rm8vLzm/fY76Ombb752/5Ta3o8jR45ecdBBhz1x441XH7huYJx22kfv6Gg+AMRwChZAP1Fbu6aotbU1J9PlW1pacubMeWbCjjvu8ko255GTk9M6btz4pffdd9du48dvsSSbY69r+PCRFevHR0opVVSsLK+oWDFw9uyHt58yZb/n1n1uypT9nn/yyce37eiozLJlS4YNGFBa1xtzBqDnBAhAPzFkyNCqtk6n6siqVRXldXV1hSNHjl6RrXl86ENbvvnaa6+MaW1tzVm8eOHIMWPGvZ2tsTN19923T1648I1RAwaU1Q0fPrIipZSGDx9RUVpaXrtgweujo+cDQPY4BQugD5SWltWddtpH71j7c25ubuvo0Zu9c/XV/75uI1Pz5r24+V577ft8RcWKQQ0NDT3+e33bbSfNnznz5r1TSmnOnGcmHHTQ4bMXL144oqfjdscDD9y969FHn/jg9df/7eADDjj0yVtvvW6/ztaZMGHi4lWrKsoj5gdA1wkQgD5QU1NdvP71CGPHbr5s8uR95qz9Df/6kbJs2ZJh99wzc4+2xnvqqce33W23yXMfeeTBHdt6fv2x1n9u7f8eMmRoVWXl6rK11100Njbm19fXFZaVla+prq4asP66U6bs/9wjjzyQ0Wt2NP+1TjzxtHuKiooampub8q666vJDa2tri1544dkJp5/+sduffPKxbde/4Hz918jJyUmrV1eUzZrV8esA0HcECEA/sWjRgpH77z/1qbU/txUp7WloaMh//fVXN9tqq20XzJv34ubrP9/RWOt+gN9llz1e2myzsW+PGTNu2drH8vMLmpubm/Ieeui+nddft7346Or817ruuisPXn9OL74450O77z5l7ty5z2+RjdcAoG8JEIB+pKWlJeOL0Ne3bNmSYcOHj6wYPHhIVXfWLywsbCovH7jmL3/5n6PXf+7YY6fdn5eX19Lc3Bxy7eD6F+M3NTXmtbcsABsWF6ED9BPDhg1fVVu7pksXoa9vzpxnttx++x1fz83Nbe3quttvv9Nrc+Y8O6Gt515+ee74rbbadkFP5ra+5cuXDdl66+3eWP/x0aM3faeqanVpNl8LgP7DERCAPlBSUlK//jUZra2tOXfeecuUjpZJKaU5c56d8PzzT09s76ton3rq8W3GjNl82bqPNTY2FLQ3l7XPrVlTU/T6669s1tYyr7zy0rgttpi4uOOteq/O5v/gg/fscuihRz+2++57vbjukZ+GhoaCmTNvnrLuOu1ta1duklhfX/++myICEC+nrGxol39L1pZZFw3/5tQZy3+UjbEAAID+JVuf952CBQAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAECY/GwONuui4d/M5ngAAMAHS05Z2dDWvp4EAACwcXAKFgAAEEaAAAAAYQQIAAAQRoAAAABhBAgAABBGgAAAAGEECAAAEEaAAAAAYQQIAAAQRoAAAABhBAgAABBGgAAAAGEECAAAEEaAAAAAYQQIAAAQRoAAAABh/j9EJfmEglRwIQAAAABJRU5ErkJggg==" alt="صالح">
    <h1 class="hero-title"><span>صالح</span></h1>
    <p class="hero-sub">للمقاولات والتسويق العقاري</p>
    <p class="hero-desc">
      نحن متخصصون في تسويق أفضل الفرص العقارية في المدن الجديدة والمناطق المتميزة بمصر — العلمين، العاصمة الإدارية، الساحل الشمالي، التجمع الخامس، أكتوبر، والسخنة
    </p>
    <div class="hero-btns">
      <a href="#cities" class="btn-primary">اكتشف المشاريع</a>
      <a href="tel:01010892928" class="btn-outline">📞 اتصل الآن</a>
    </div>
  </div>
</section>

<div class="gold-line"></div>

<!-- Stats -->
<div class="stats-section">
  <div class="stats-grid reveal">
    <div>
      <div class="stat-num">+500</div>
      <div class="stat-label">وحدة سكنية تم تسويقها</div>
    </div>
    <div>
      <div class="stat-num">6</div>
      <div class="stat-label">مدن جديدة ومتميزة</div>
    </div>
    <div>
      <div class="stat-num">+15</div>
      <div class="stat-label">سنة خبرة في السوق</div>
    </div>
    <div>
      <div class="stat-num">%98</div>
      <div class="stat-label">رضا العملاء</div>
    </div>
  </div>
</div>

<!-- Cities -->
<section class="section" id="cities">
  <div class="reveal">
    <p class="section-label">المناطق الحصرية</p>
    <h2 class="section-title">وجهاتنا <span>العقارية المتميزة</span></h2>
    <div class="section-line"></div>
  </div>
  <div class="cities-grid reveal">
    <div class="city-card city-alamein">
      <div class="city-card-bg">
        <div style="position:absolute;inset:0;background:url('https://images.unsplash.com/photo-1545324418-cc1a3fa10c00?w=600&q=80') center/cover;opacity:0.3;"></div>
      </div>
      <div class="city-card-overlay"></div>
      <div class="city-card-content">
        <div class="city-tag">ساحلي</div>
        <div class="city-name">🌊 العلمين الجديدة</div>
        <div class="city-desc">مدينة ساحلية عصرية على البحر المتوسط، الوجهة الأرقى في مصر</div>
      </div>
    </div>
    <div class="city-card city-newcapital">
      <div class="city-card-bg">
        <div style="position:absolute;inset:0;background:url('https://images.unsplash.com/photo-1486325212027-8081e485255e?w=600&q=80') center/cover;opacity:0.3;"></div>
      </div>
      <div class="city-card-overlay"></div>
      <div class="city-card-content">
        <div class="city-tag">إداري</div>
        <div class="city-name">🏛️ العاصمة الإدارية</div>
        <div class="city-desc">قلب مصر الجديد، مشاريع راقية وفرص استثمارية ضخمة</div>
      </div>
    </div>
    <div class="city-card city-sahel">
      <div class="city-card-bg">
        <div style="position:absolute;inset:0;background:url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e?w=600&q=80') center/cover;opacity:0.3;"></div>
      </div>
      <div class="city-card-overlay"></div>
      <div class="city-card-content">
        <div class="city-tag">صيفي</div>
        <div class="city-name">🏖️ الساحل الشمالي</div>
        <div class="city-desc">شاطئ البحر الأبيض المتوسط، فيلات وشاليهات بأجمل الأماكن</div>
      </div>
    </div>
    <div class="city-card city-tagamoa">
      <div class="city-card-bg">
        <div style="position:absolute;inset:0;background:url('https://images.unsplash.com/photo-1555636222-cae831e670b3?w=600&q=80') center/cover;opacity:0.3;"></div>
      </div>
      <div class="city-card-overlay"></div>
      <div class="city-card-content">
        <div class="city-tag">راقي</div>
        <div class="city-name">🏙️ التجمع الخامس</div>
        <div class="city-desc">الحي الأرقى في القاهرة الجديدة، مجمعات سكنية فاخرة</div>
      </div>
    </div>
    <div class="city-card city-october">
      <div class="city-card-bg">
        <div style="position:absolute;inset:0;background:url('https://images.unsplash.com/photo-1560518883-ce09059eeffa?w=600&q=80') center/cover;opacity:0.3;"></div>
      </div>
      <div class="city-card-overlay"></div>
      <div class="city-card-content">
        <div class="city-tag">سكني</div>
        <div class="city-name">🌆 أكتوبر</div>
        <div class="city-desc">مدينة 6 أكتوبر، وحدات متنوعة تناسب جميع الاحتياجات</div>
      </div>
    </div>
    <div class="city-card city-sokhna">
      <div class="city-card-bg">
        <div style="position:absolute;inset:0;background:url('https://images.unsplash.com/photo-1682686580003-22d3d65399a8?w=600&q=80') center/cover;opacity:0.3;"></div>
      </div>
      <div class="city-card-overlay"></div>
      <div class="city-card-content">
        <div class="city-tag">سياحي</div>
        <div class="city-name">⛱️ العين السخنة</div>
        <div class="city-desc">الوجهة السياحية الأولى على البحر الأحمر، استثمار مضمون</div>
      </div>
    </div>
  </div>
</section>

<!-- Services -->
<section class="section" id="services" style="background: var(--dark2);">
  <div class="reveal">
    <p class="section-label">ما نقدمه</p>
    <h2 class="section-title">خدماتنا <span>المتكاملة</span></h2>
    <div class="section-line"></div>
  </div>
  <div class="services-grid reveal">
    <div class="service-card">
      <div class="service-icon">🏠</div>
      <div class="service-name">تسويق عقاري</div>
      <div class="service-desc">نسوّق أفضل الوحدات السكنية والتجارية في أرقى المدن الجديدة بمصر</div>
    </div>
    <div class="service-card">
      <div class="service-icon">🔑</div>
      <div class="service-name">بيع وشراء العقارات</div>
      <div class="service-desc">نسهل عملية البيع والشراء بخبرة عالية وتفاوض احترافي لضمان أفضل صفقة</div>
    </div>
    <div class="service-card">
      <div class="service-icon">🏗️</div>
      <div class="service-name">المقاولات والبناء</div>
      <div class="service-desc">خدمات مقاولات شاملة من التصميم حتى التسليم بأعلى معايير الجودة</div>
    </div>
    <div class="service-card">
      <div class="service-icon">📊</div>
      <div class="service-name">الاستشارات الاستثمارية</div>
      <div class="service-desc">نرشدك لأفضل الفرص الاستثمارية في السوق العقاري المصري</div>
    </div>
    <div class="service-card">
      <div class="service-icon">📋</div>
      <div class="service-name">التوثيق والتعاقد</div>
      <div class="service-desc">نتولى كافة إجراءات التوثيق القانوني والتعاقد بشكل احترافي وآمن</div>
    </div>
    <div class="service-card">
      <div class="service-icon">🤝</div>
      <div class="service-name">خدمة ما بعد البيع</div>
      <div class="service-desc">نبقى معك حتى بعد الاستلام ونقدم الدعم الكامل لراحة بالك</div>
    </div>
  </div>
</section>

<!-- Why Us -->
<section class="whyus-section" id="about">
  <div class="whyus-grid">
    <div class="reveal">
      <p class="section-label">ميزتنا التنافسية</p>
      <h2 class="section-title">لماذا تختار <span>صالح</span> للعقارات؟</h2>
      <div class="section-line"></div>
      <div class="whyus-items">
        <div class="whyus-item">
          <div class="whyus-num">01</div>
          <div class="whyus-text">
            <h3>خبرة عريقة في السوق</h3>
            <p>أكثر من 15 عاماً في السوق العقاري المصري نقدم فيها أفضل الخدمات بثقة واحترافية</p>
          </div>
        </div>
        <div class="whyus-item">
          <div class="whyus-num">02</div>
          <div class="whyus-text">
            <h3>تغطية واسعة للمناطق</h3>
            <p>نغطي أبرز المدن الجديدة في مصر مما يمنحك خيارات متنوعة ومتميزة تناسب كل الأذواق</p>
          </div>
        </div>
        <div class="whyus-item">
          <div class="whyus-num">03</div>
          <div class="whyus-text">
            <h3>شفافية تامة وأمانة</h3>
            <p>نؤمن بالشفافية الكاملة في كل تعاملاتنا — ما تراه هو ما تحصل عليه بالضبط</p>
          </div>
        </div>
        <div class="whyus-item">
          <div class="whyus-num">04</div>
          <div class="whyus-text">
            <h3>خدمة عملاء متميزة</h3>
            <p>فريقنا متاح على مدار الساعة للإجابة على استفساراتك وتقديم المشورة المتخصصة</p>
          </div>
        </div>
      </div>
    </div>
    <div class="whyus-visual reveal">
      <div class="whyus-visual-inner">
        <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAyAAAAMgCAYAAADbcAZoAAAACXBIWXMAAC4jAAAuIwF4pT92AAA3cklEQVR4nO3dd5RV5b344Xf6DDNDlaaARMSKvSB2xW7sqFjTbhIlienVX5J7Y3pMbqrR5OZeYzQm9q6o2GPDLqJiQYoCIgxMYfrM7w9DgjjlzMyZ7wzyPGu5Vuacvd/z7n0InM/svc/OKSsb2poAAAAC5Pb1BAAAgI2HAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgTH62Bpp10fBvZmssAACg/5k6Y/mPejpG1gIkpexMCAAA6H+ydcDBKVgAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEye/rCQCwYXnppp1eW/+xbY59dkJfzAWADY8jIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQJj8vp4AAD3z0k079fUUwuewzbHPhr4eANkjQADoqgl9PQEANlxOwQIAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMII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Ir3y6uu9+joAkA2OgAAfSPX19emT5345LVi4KON1Ntt0dEbL9ccLvx0FAWBDIUCAD6y6urp02eVXZbz84MEDO11m4sQt0h6779KTafWKU08+LhXkO6gNQP8nQIB+5TPnfjzts/fkrI0354WXMl62oKCg02XO6sLF55GGDRuaDj/s4L6eBgB0SoAA/cYXP39O+s75X0lX/Pn3WYuQrnwjVkNDQ4fPFxYWplOmHdfTKfWa06af2NdTAIBOCRCgX/jSF85N3/jqeSmld79l6m+XX5JOPfn4Ho+7y047ZLzsOysqOnz+yCOmduuO6VEOPnDftOnokX09DQDokAAB+txXv/SZ9PWvfO49jxUWFqZf//cP029++aM0eFDn12a0ZejQIekTHz8j4+XfeGNBh8/319Ov1srNzU3TT3UUBID+zRWLQJ/62pc/m778xRntPn/KtOPSoVMPSL/+3R/TZZdflaqrazIad+KWW6Q//P7naeSI4RnP5ZlnX2j3uc3HjU377pO9a1N6y+mnnph++etLunUzxraUlZamQQPLszLW+lZXVmVlnN6c41p19Q2pvr6+V18DYGMhQIA+882vfT594bxPd7rckCGD03f/31fTV7/02XTXrPvTAw8+kua88GJa/OZbafWqytTc0pIGDChJo0ePTDtsv1068oip6agjDkn5+Xldms+se9u/+d8Zp5+UcnJyujReXxg7drO07z6T0wMPPpKV8f76l0uyMk5bRo7ZLivj9OYc17rwF79LP/vF73r9dQA2BgIE6BPf+voX0uc/96kurTNgQEk67pgj0nHHHJH1+by1ZFl65NEn2nwuPz8vTT/lhIzH+uuV16YvfvXb2ZpaGjZsaHruyfszDqozpp+UtQABgGxzDQgQbvfddu5yfPS231/yf6m5ubnN56YevH+XTuX629XXZ2taKaWUVqxYme69/6GMlz/6qEP79cXyAGzcBAgQ7oknn0k//Mkv+3oa//La62+kSy/7W7vPd+Xi80WL3kyPz346G9N6j6uvvSnjZQsKCtK0E4/J+hwAIBsECNAnfvWbP6SfXPibvp5GamxsTDM+97V27wGy6eiRaerB+2c83t+vviG1trZma3r/csfMe1JVVXXGy595+rSszwEAskGAAH3mF7/8ffr6t77X7qlPva2lpSV95vPfSM88O6fdZaafemLKzc38r8pr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VbV87pTyty6/YNjLDz5dP3DRsuai4sKclh22LFizy9YF1W8tby48//erx69YnflFsc0t795I7+JvDHk129u7ridfbCj7fxdXjv/+OQPf+Ol5g+af//vV45+d11i65Zj8uglj8usuvLxqTGdj3PFw3ZDzppe9tcvWhdVPvdRQllLP9mlv6my/XnPPu99M9MkTypZeccHQl2bPbSh/dXFTSW19a+6Q8tymnbcqrN568/zahUubizq6xuD/bq4ZNWlCwZovnFb25kG7F616Zl5DWW19a+6mm+Q17Ldz0epBZbnNf71jzYhD9yqu+MGMQW988RertujO9T7tvX/rLrP56Lz6kw4uafc+KC/ObxrQ0Nia25P3O9PXuvae9r/5KZN5zp3fOOA//1A57sefG/TGJd8a8uojz9eXv7qoqaShMeVuOjy3/sBdi1cXFqSWP15fM6qz7VhXT/+8d1Wm29qdsYENkwCBjdAN99UOe2JuQ9m0qSXv7LFdYfVRexc31De25r6+uKn413+r3vTWf9QObWpu+1uGbnmobugz8xpL1657+F7FqxqbWnPeWNJc9Ptrqkff/FDd0O58bec/L2Ie8fFjS5f1fAvb9+SLDWXfumj1+B/MGLTgx58ZNP87l1RuPmWHwqq6htbc+57s/PSoWbPrBp87rXTJUXsXV6z7gawn+7Q3dbZfr7mndpNHnm8YeOwBJSt237agevftCqsL83NaVlW15L+yqKnkp5dVjZn1RN3gpqb2576mrjX38z9fNeG4A4pXHLx78arphw5YXliQ07K8oqXg0TkN5dfeU7vJ/Leaiu96vG7wr7885LWfnjdo/ud/vmrCW924oLyt92/2OteVbDk2v3bLsWXtnqJ12a1rRgwqy2nu6fudyWt1FCCZzHPu/MYBryxqKvnEBRUTTzmk5J3Jkwqr9ppUWJWfl9O6srIl/8mXGsquuGPNiNff7FrMHbVP8cpsbH+mMt3W7owNbJhyysqGZuX3cbMuGv7NqTOW/ygbYwEAAP1Ltj7vuwYEAAAII0AAAIAwAgQAAAgjQAAAgDACBAAACCNAAACAMAIEAAAII0AAAIAwAgQAAAgjQAAAgDACBAAACCNAAACAMAIEAAAII0AAAIAwAgQAAAgjQAAAgDACBAAACCNAAACAMPl9PQGAjdHHP37ujbW1tUXrPpafX9B8//137bZw4RujUkrpYx8796a6utrC9dd94YVnJzz33NMTp0//yMybbrrmgDVraorXX2batDPuvuaaKw5Z+/NJJ50269prr5za1lzaeq6oqKjh7LM/deull158TGNjY7f+rehs/kVFRQ2HHnr0Y+XlA2taW1tzcnJyWlNKqaWlJffhh+/fqaGhIX/ZsiXD1l9/+PCRFXV1tUVVVZUD2tqPTU1NeTNn3jxlxIhRFXvsMeWFtY+PGDGq4u23lw5Z+/Ps2Y9s/+qrL4/tzrYB0H0CBKAP1NbWFl155aVHrPtYScmA+uOPP+XehQvffbyurrZw/WXWlZeX17Lrrnu+9NBD9+68/nMFBQVN6/5cWFjU2N44bT23ww67vPrqqy+P3WabSfOff/7piRls0vt0Nv/99jv46Zdfnrv5K6+8NG7dx4cMGVp1yCFHPdrS0pJ7441XHdjU1JS39rm8vLzm/fY76Ombb752/5Ta3o8jR45ecdBBhz1x441XH7huYJx22kfv6Gg+AMRwChZAP1Fbu6aotbU1J9PlW1pacubMeWbCjjvu8ko255GTk9M6btz4pffdd9du48dvsSSbY69r+PCRFevHR0opVVSsLK+oWDFw9uyHt58yZb/n1n1uypT9nn/yyce37eiozLJlS4YNGFBa1xtzBqDnBAhAPzFkyNCqtk6n6siqVRXldXV1hSNHjl6RrXl86ENbvvnaa6+MaW1tzVm8eOHIMWPGvZ2tsTN19923T1648I1RAwaU1Q0fPrIipZSGDx9RUVpaXrtgweujo+cDQPY4BQugD5SWltWddtpH71j7c25ubuvo0Zu9c/XV/75uI1Pz5r24+V577ft8RcWKQQ0NDT3+e33bbSfNnznz5r1TSmnOnGcmHHTQ4bMXL144oqfjdscDD9y969FHn/jg9df/7eADDjj0yVtvvW6/ztaZMGHi4lWrKsoj5gdA1wkQgD5QU1NdvP71CGPHbr5s8uR95qz9Df/6kbJs2ZJh99wzc4+2xnvqqce33W23yXMfeeTBHdt6fv2x1n9u7f8eMmRoVWXl6rK11100Njbm19fXFZaVla+prq4asP66U6bs/9wjjzyQ0Wt2NP+1TjzxtHuKiooampub8q666vJDa2tri1544dkJp5/+sduffPKxbde/4Hz918jJyUmrV1eUzZrV8esA0HcECEA/sWjRgpH77z/1qbU/txUp7WloaMh//fVXN9tqq20XzJv34ubrP9/RWOt+gN9llz1e2myzsW+PGTNu2drH8vMLmpubm/Ieeui+nddft7346Or817ruuisPXn9OL74450O77z5l7ty5z2+RjdcAoG8JEIB+pKWlJeOL0Ne3bNmSYcOHj6wYPHhIVXfWLywsbCovH7jmL3/5n6PXf+7YY6fdn5eX19Lc3Bxy7eD6F+M3NTXmtbcsABsWF6ED9BPDhg1fVVu7pksXoa9vzpxnttx++x1fz83Nbe3quttvv9Nrc+Y8O6Gt515+ee74rbbadkFP5ra+5cuXDdl66+3eWP/x0aM3faeqanVpNl8LgP7DERCAPlBSUlK//jUZra2tOXfeecuUjpZJKaU5c56d8PzzT09s76ton3rq8W3GjNl82bqPNTY2FLQ3l7XPrVlTU/T6669s1tYyr7zy0rgttpi4uOOteq/O5v/gg/fscuihRz+2++57vbjukZ+GhoaCmTNvnrLuOu1ta1duklhfX/++myICEC+nrGxol39L1pZZFw3/5tQZy3+UjbEAAID+JVuf952CBQAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAECY/GwONuui4d/M5ngAAMAHS05Z2dDWvp4EAACwcXAKFgAAEEaAAAAAYQQIAAAQRoAAAABhBAgAABBGgAAAAGEECAAAEEaAAAAAYQQIAAAQRoAAAABhBAgAABBGgAAAAGEECAAAEEaAAAAAYQQIAAAQRoAAAABh/j9EJfmEglRwIQAAAABJRU5ErkJggg==" alt="صالح للعقارات">
        <div class="whyus-visual-text">SALEH REAL ESTATE</div>
      </div>
    </div>
  </div>
</section>

<!-- Contact -->
<section class="contact-section" id="contact">
  <div class="reveal">
    <p class="section-label">ابدأ رحلتك</p>
    <h2 class="section-title">تواصل <span>معنا الآن</span></h2>
    <div class="section-line"></div>
  </div>
  <div class="contact-grid reveal">
    <div class="contact-info">
      <div class="contact-item">
        <div class="contact-item-icon">📞</div>
        <div class="contact-item-text">
          <h4>اتصل بنا</h4>
          <p><a href="tel:01010892928">01010892928</a></p>
        </div>
      </div>
      <div class="contact-item">
        <div class="contact-item-icon">📍</div>
        <div class="contact-item-text">
          <h4>موقعنا</h4>
          <p>بنها — القليوبية<br>شارع الملك فاروق<br>أمام فندق القوات المسلحة</p>
        </div>
      </div>
      <div class="contact-item">
        <div class="contact-item-icon">🕐</div>
        <div class="contact-item-text">
          <h4>ساعات العمل</h4>
          <p>السبت — الخميس: 9 ص — 9 م<br>الجمعة: 11 ص — 6 م</p>
        </div>
      </div>
      <div style="margin-top: 10px;">
        <a href="tel:01010892928" class="btn-primary" style="display:inline-block;">📞 اتصل بنا مباشرة</a>
      </div>
    </div>
    <div class="contact-form">
      <div class="form-group">
        <label>الاسم الكامل</label>
        <input type="text" placeholder="ما هو اسمك؟">
      </div>
      <div class="form-group">
        <label>رقم الهاتف</label>
        <input type="tel" placeholder="رقم هاتفك">
      </div>
      <div class="form-group">
        <label>المنطقة المفضلة</label>
        <select>
          <option value="">اختر المنطقة</option>
          <option>العلمين الجديدة</option>
          <option>العاصمة الإدارية الجديدة</option>
          <option>الساحل الشمالي</option>
          <option>التجمع الخامس</option>
          <option>مدينة 6 أكتوبر</option>
          <option>العين السخنة</option>
        </select>
      </div>
      <div class="form-group">
        <label>رسالتك</label>
        <textarea placeholder="ما الذي تبحث عنه؟"></textarea>
      </div>
      <button class="btn-primary" onclick="handleSubmit()" style="border:none;width:100%;font-size:1rem;cursor:pointer;">إرسال الطلب ←</button>
    </div>
  </div>
</section>

<!-- Footer -->
<footer>
  <div class="footer-logo">
    <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAyAAAAMgCAYAAADbcAZoAAAACXBIWXMAAC4jAAAuIwF4pT92AAA3cklEQVR4nO3dd5RV5b344Xf6DDNDlaaARMSKvSB2xW7sqFjTbhIlienVX5J7Y3pMbqrR5OZeYzQm9q6o2GPDLqJiQYoCIgxMYfrM7w9DgjjlzMyZ7wzyPGu5Vuacvd/z7n0InM/svc/OKSsb2poAAAAC5Pb1BAAAgI2HAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgTH62Bpp10fBvZmssAACg/5k6Y/mPejpG1gIkpexMCAAA6H+ydcDBKVgAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEye/rCQCwYXnppp1eW/+xbY59dkJfzAWADY8jIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQJj8vp4AAD3z0k079fUUwuewzbHPhr4eANkjQADoqgl9PQEANlxOwQIAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMIIEAAAIIwAAQAAwggQAAAgjAABAADCCBAAACCMAAEAAMII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Ir3y6uu9+joAkA2OgAAfSPX19emT5345LVi4KON1Ntt0dEbL9ccLvx0FAWBDIUCAD6y6urp02eVXZbz84MEDO11m4sQt0h6779KTafWKU08+LhXkO6gNQP8nQIB+5TPnfjzts/fkrI0354WXMl62oKCg02XO6sLF55GGDRuaDj/s4L6eBgB0SoAA/cYXP39O+s75X0lX/Pn3WYuQrnwjVkNDQ4fPFxYWplOmHdfTKfWa06af2NdTAIBOCRCgX/jSF85N3/jqeSmld79l6m+XX5JOPfn4Ho+7y047ZLzsOysqOnz+yCOmduuO6VEOPnDftOnokX09DQDokAAB+txXv/SZ9PWvfO49jxUWFqZf//cP029++aM0eFDn12a0ZejQIekTHz8j4+XfeGNBh8/319Ov1srNzU3TT3UUBID+zRWLQJ/62pc/m778xRntPn/KtOPSoVMPSL/+3R/TZZdflaqrazIad+KWW6Q//P7naeSI4RnP5ZlnX2j3uc3HjU377pO9a1N6y+mnnph++etLunUzxraUlZamQQPLszLW+lZXVmVlnN6c41p19Q2pvr6+V18DYGMhQIA+882vfT594bxPd7rckCGD03f/31fTV7/02XTXrPvTAw8+kua88GJa/OZbafWqytTc0pIGDChJo0ePTDtsv1068oip6agjDkn5+Xldms+se9u/+d8Zp5+UcnJyujReXxg7drO07z6T0wMPPpKV8f76l0uyMk5bRo7ZLivj9OYc17rwF79LP/vF73r9dQA2BgIE6BPf+voX0uc/96kurTNgQEk67pgj0nHHHJH1+by1ZFl65NEn2nwuPz8vTT/lhIzH+uuV16YvfvXb2ZpaGjZsaHruyfszDqozpp+UtQABgGxzDQgQbvfddu5yfPS231/yf6m5ubnN56YevH+XTuX629XXZ2taKaWUVqxYme69/6GMlz/6qEP79cXyAGzcBAgQ7oknn0k//Mkv+3oa//La62+kSy/7W7vPd+Xi80WL3kyPz346G9N6j6uvvSnjZQsKCtK0E4/J+hwAIBsECNAnfvWbP6SfXPibvp5GamxsTDM+97V27wGy6eiRaerB+2c83t+vviG1trZma3r/csfMe1JVVXXGy595+rSszwEAskGAAH3mF7/8ffr6t77X7qlPva2lpSV95vPfSM88O6fdZaafemLKzc38r8pr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VbV87pTyty6/YNjLDz5dP3DRsuai4sKclh22LFizy9YF1W8tby48//erx69YnflFsc0t795I7+JvDHk129u7ridfbCj7fxdXjv/+OQPf+Ol5g+af//vV45+d11i65Zj8uglj8usuvLxqTGdj3PFw3ZDzppe9tcvWhdVPvdRQllLP9mlv6my/XnPPu99M9MkTypZeccHQl2bPbSh/dXFTSW19a+6Q8tymnbcqrN568/zahUubizq6xuD/bq4ZNWlCwZovnFb25kG7F616Zl5DWW19a+6mm+Q17Ldz0epBZbnNf71jzYhD9yqu+MGMQW988RertujO9T7tvX/rLrP56Lz6kw4uafc+KC/ObxrQ0Nia25P3O9PXuvae9r/5KZN5zp3fOOA//1A57sefG/TGJd8a8uojz9eXv7qoqaShMeVuOjy3/sBdi1cXFqSWP15fM6qz7VhXT/+8d1Wm29qdsYENkwCBjdAN99UOe2JuQ9m0qSXv7LFdYfVRexc31De25r6+uKn413+r3vTWf9QObWpu+1uGbnmobugz8xpL1657+F7FqxqbWnPeWNJc9Ptrqkff/FDd0O58bec/L2Ie8fFjS5f1fAvb9+SLDWXfumj1+B/MGLTgx58ZNP87l1RuPmWHwqq6htbc+57s/PSoWbPrBp87rXTJUXsXV6z7gawn+7Q3dbZfr7mndpNHnm8YeOwBJSt237agevftCqsL83NaVlW15L+yqKnkp5dVjZn1RN3gpqb2576mrjX38z9fNeG4A4pXHLx78arphw5YXliQ07K8oqXg0TkN5dfeU7vJ/Leaiu96vG7wr7885LWfnjdo/ud/vmrCW924oLyt92/2OteVbDk2v3bLsWXtnqJ12a1rRgwqy2nu6fudyWt1FCCZzHPu/MYBryxqKvnEBRUTTzmk5J3Jkwqr9ppUWJWfl9O6srIl/8mXGsquuGPNiNff7FrMHbVP8cpsbH+mMt3W7owNbJhyysqGZuX3cbMuGv7NqTOW/ygbYwEAAP1Ltj7vuwYEAAAII0AAAIAwAgQAAAgjQAAAgDACBAAACCNAAACAMAIEAAAII0AAAIAwAgQAAAgjQAAAgDACBAAACCNAAACAMAIEAAAII0AAAIAwAgQAAAgjQAAAgDACBAAACCNAAACAMPl9PQGAjdHHP37ujbW1tUXrPpafX9B8//137bZw4RujUkrpYx8796a6utrC9dd94YVnJzz33NMTp0//yMybbrrmgDVraorXX2batDPuvuaaKw5Z+/NJJ50269prr5za1lzaeq6oqKjh7LM/deull158TGNjY7f+rehs/kVFRQ2HHnr0Y+XlA2taW1tzcnJyWlNKqaWlJffhh+/fqaGhIX/ZsiXD1l9/+PCRFXV1tUVVVZUD2tqPTU1NeTNn3jxlxIhRFXvsMeWFtY+PGDGq4u23lw5Z+/Ps2Y9s/+qrL4/tzrYB0H0CBKAP1NbWFl155aVHrPtYScmA+uOPP+XehQvffbyurrZw/WXWlZeX17Lrrnu+9NBD9+68/nMFBQVN6/5cWFjU2N44bT23ww67vPrqqy+P3WabSfOff/7piRls0vt0Nv/99jv46Zdfnrv5K6+8NG7dx4cMGVp1yCFHPdrS0pJ7441XHdjU1JS39rm8vLzm/fY76Ombb752/5Ta3o8jR45ecdBBhz1x441XH7huYJx22kfv6Gg+AMRwChZAP1Fbu6aotbU1J9PlW1pacubMeWbCjjvu8ko255GTk9M6btz4pffdd9du48dvsSSbY69r+PCRFevHR0opVVSsLK+oWDFw9uyHt58yZb/n1n1uypT9nn/yyce37eiozLJlS4YNGFBa1xtzBqDnBAhAPzFkyNCqtk6n6siqVRXldXV1hSNHjl6RrXl86ENbvvnaa6+MaW1tzVm8eOHIMWPGvZ2tsTN19923T1648I1RAwaU1Q0fPrIipZSGDx9RUVpaXrtgweujo+cDQPY4BQugD5SWltWddtpH71j7c25ubuvo0Zu9c/XV/75uI1Pz5r24+V577ft8RcWKQQ0NDT3+e33bbSfNnznz5r1TSmnOnGcmHHTQ4bMXL144oqfjdscDD9y969FHn/jg9df/7eADDjj0yVtvvW6/ztaZMGHi4lWrKsoj5gdA1wkQgD5QU1NdvP71CGPHbr5s8uR95qz9Df/6kbJs2ZJh99wzc4+2xnvqqce33W23yXMfeeTBHdt6fv2x1n9u7f8eMmRoVWXl6rK11100Njbm19fXFZaVla+prq4asP66U6bs/9wjjzyQ0Wt2NP+1TjzxtHuKiooampub8q666vJDa2tri1544dkJp5/+sduffPKxbde/4Hz918jJyUmrV1eUzZrV8esA0HcECEA/sWjRgpH77z/1qbU/txUp7WloaMh//fVXN9tqq20XzJv34ubrP9/RWOt+gN9llz1e2myzsW+PGTNu2drH8vMLmpubm/Ieeui+nddft7346Or817ruuisPXn9OL74450O77z5l7ty5z2+RjdcAoG8JEIB+pKWlJeOL0Ne3bNmSYcOHj6wYPHhIVXfWLywsbCovH7jmL3/5n6PXf+7YY6fdn5eX19Lc3Bxy7eD6F+M3NTXmtbcsABsWF6ED9BPDhg1fVVu7pksXoa9vzpxnttx++x1fz83Nbe3quttvv9Nrc+Y8O6Gt515+ee74rbbadkFP5ra+5cuXDdl66+3eWP/x0aM3faeqanVpNl8LgP7DERCAPlBSUlK//jUZra2tOXfeecuUjpZJKaU5c56d8PzzT09s76ton3rq8W3GjNl82bqPNTY2FLQ3l7XPrVlTU/T6669s1tYyr7zy0rgttpi4uOOteq/O5v/gg/fscuihRz+2++57vbjukZ+GhoaCmTNvnrLuOu1ta1duklhfX/++myICEC+nrGxol39L1pZZFw3/5tQZy3+UjbEAAID+JVuf952CBQAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAEAYAQIAAIQRIAAAQBgBAgAAhBEgAABAGAECAACEESAAAECY/GwONuui4d/M5ngAAMAHS05Z2dDWvp4EAACwcXAKFgAAEEaAAAAAYQQIAAAQRoAAAABhBAgAABBGgAAAAGEECAAAEEaAAAAAYQQIAAAQRoAAAABhBAgAABBGgAAAAGEECAAAEEaAAAAAYQQIAAAQRoAAAABh/j9EJfmEglRwIQAAAABJRU5ErkJggg==" alt="صالح" onerror="this.style.display='none'">
    <span>© 2024 صالح للمقاولات والتسويق العقاري</span>
  </div>
  <p class="footer-copy">بنها — القليوبية — مصر<br>شارع الملك فاروق، أمام فندق القوات المسلحة</p>
  <div class="footer-social">
    <a class="social-btn" href="tel:01010892928" title="اتصل">📞</a>
    <a class="social-btn" href="https://wa.me/201010892928" title="واتساب" target="_blank">💬</a>
    <a class="social-btn" href="#" title="فيسبوك">f</a>
  </div>
</footer>

<!-- Phone Float -->
<a href="tel:01010892928" class="phone-float" title="اتصل الآن">📞</a>

<script>
  // Scroll reveal
  const reveals = document.querySelectorAll('.reveal');
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('visible');
      }
    });
  }, { threshold: 0.1 });
  reveals.forEach(el => observer.observe(el));

  function handleSubmit() {
    alert('شكراً! سنتواصل معك في أقرب وقت.\n للتواصل الفوري: 01010892928');
  }

  // Smooth nav highlight
  window.addEventListener('scroll', () => {
    const nav = document.querySelector('nav');
    if (window.scrollY > 50) {
      nav.style.background = 'rgba(10,10,10,0.97)';
    } else {
      nav.style.background = 'rgba(10,10,10,0.92)';
    }
  });
</script>

</body>
</html>
