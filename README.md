<!doctype html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>tota.land — روابط</title>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg1: #ff8a80;
      --bg2: #7b61ff;
      --card: #fff;
      --accent: #d7261e; /* ظل الزر */
      --btn-height: 60px;
      --max-width: 420px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family: "Cairo", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background: linear-gradient(180deg,var(--bg1) 0%, #ffb299 35%, #c08bff 70%, var(--bg2) 100%);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      display:flex;
      align-items:center;
      justify-content:center;
      padding:24px;
    }

    .frame{
      width:100%;
      max-width:var(--max-width);
      /* لتقليد نسبة 9:16 يمكن ضبط الارتفاع إن رغبت */
      background: transparent;
      border-radius:18px;
    }

    .card{
      background: rgba(255,255,255,0.06);
      padding:18px;
      border-radius:18px;
      backdrop-filter: blur(6px);
      color:#fff;
    }

    .logo-wrap{
      display:flex;
      gap:12px;
      align-items:center;
      margin-bottom:8px;
      justify-content:center;
      flex-direction:column;
      text-align:center;
    }

    .logo{
      width:96px;
      height:96px;
      border-radius:50%;
      background: #fff;
      display:flex;
      align-items:center;
      justify-content:center;
      box-shadow: 0 6px 0 rgba(0,0,0,0.12);
      overflow:hidden;
    }
    .logo img{width:86%; height:auto; display:block}

    h1{
      margin:10px 0 4px;
      font-size:20px;
      font-weight:700;
      color:#fff;
    }
    p.lead{
      margin:0 0 16px;
      opacity:0.95;
      line-height:1.5;
      font-size:14px;
    }

    /* قائمة الأزرار */
    .links{
      display:flex;
      flex-direction:column;
      gap:14px;
      padding:6px 0 18px;
    }

    .btn{
      position:relative;
      display:flex;
      align-items:center;
      gap:14px;
      height:var(--btn-height);
      padding:0 18px;
      background:var(--card);
      border-radius:14px;
      text-decoration:none;
      color:#333;
      font-weight:600;
      box-shadow: 16px 8px 0 rgba(199,0,0,0.95); /* تأثير الظل الأحمر */
      transition:transform .12s ease, box-shadow .12s ease;
      overflow:hidden;
    }
    .btn:active{ transform: translateY(2px); box-shadow: 12px 6px 0 rgba(199,0,0,0.9); }
    .btn .ico{
      width:36px;
      height:36px;
      display:flex;
      align-items:center;
      justify-content:center;
      flex:0 0 36px;
    }
    .btn .text{
      flex:1;
      text-align:right; /* لأن dir=rtl */
      font-size:16px;
    }

    /* أيقونات داخل دائرة لون خفيف */
    .ico svg{ width:24px; height:24px; display:block }

    /* مسافة أسفل للـ footer */
    .footer-space{height:20px}
    /* تصميم للاستجابة */
    @media (max-width:420px){
      .logo{width:84px; height:84px}
      .btn{height:56px; border-radius:12px}
    }
  </style>
</head>
<body>
  <div class="frame" role="main">
    <div class="card" aria-label="صفحة روابط توته لاند">
      <div class="logo-wrap">
        <div class="logo" aria-hidden="true">
          <!-- صورة شعار قابلة للتبديل -->
          <img src="data:image/svg+xml;utf8,
            <svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 200 200'>
              <defs><linearGradient id='g' x1='0' x2='1'><stop offset='0' stop-color='%23ff6f61'/><stop offset='1' stop-color='%23ffb199'/></linearGradient></defs>
              <circle cx='100' cy='90' r='60' fill='url(%23g)'/>
              <path d='M100 60c12 0 22 10 22 22 0 12-22 36-22 36s-22-24-22-36c0-12 10-22 22-22z' fill='%23fff'/>
            </svg>" alt="https://i.ibb.co/RG78GRG2/IMG-20250917-021207-220.jpg" />
        </div>
        <h1>tota.land توته لاند</h1>
        <p class="lead">مرحبًا بكم في #توتـه_لاند — عالم الأطفال السحري: قصص، أغاني، وأنشطة إبداعية. هدفنا زرع حب التعلم والفرح في قلوب الصغار.</p>
      </div>

      <div class="links">
        <!-- غير href إلى الروابط الحقيقية -->
        <a class="btn" href="https://i.ibb.co/RG78GRG2/IMG-20250917-021207-220.jpg/" target="_blank" rel="noopener" aria-label="يوتيوب">
          <span class="ico" aria-hidden="true">
            <!-- أيقونة يوتيوب -->
            <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
              <rect x="2" y="6" width="20" height="12" rx="3" fill="#FF0000"/>
              <path d="M10 9.5v5l4-2.5-4-2.5z" fill="#fff"/>
            </svg>
          </span>
          <span class="text">يوتيوب</span>
        </a>

        <a class="btn" href="https://www.tiktok.com/" target="_blank" rel="noopener" aria-label="تيك توك">
          <span class="ico" aria-hidden="true">
            <!-- أيقونة تيك توك مبسطة -->
            <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
              <path d="M16 8.5c-1.1 0-2-.9-2-2V5h-2v10.5c0 2.2-1.8 4-4 4-1.2 0-2.2-.5-3-1.3v2.3c1.2 1 2.8 1.6 4.6 1.6 3.6 0 6.5-2.9 6.5-6.5V8.5h.9z" fill="#010101"/>
            </svg>
          </span>
          <span class="text">حساب التيك توك الاحتياطي</span>
        </a>

        <a class="btn" href="https://wa.me/123456789" target="_blank" rel="noopener" aria-label="واتساب">
          <span class="ico" aria-hidden="true">
            <!-- أيقونة واتساب -->
            <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
              <path d="M12 2C6.48 2 2 6.48 2 12c0 1.99.52 3.85 1.42 5.47L2 22l4.66-1.45C8.15 21.48 10.03 22 12 22c5.52 0 10-4.48 10-10S17.52 2 12 2z" fill="#25D366"/>
              <path d="M17.6 14.2c-.3-.15-1.76-.86-2.03-.96-.27-.1-.47-.15-.67.15-.2.3-.78.96-.95 1.16-.17.2-.34.22-.64.07-.3-.15-1.28-.47-2.44-1.51-.9-.8-1.51-1.79-1.69-2.09-.17-.3-.02-.46.13-.61.13-.12.3-.32.45-.48.15-.16.2-.27.3-.45.1-.18.05-.34-.02-.48-.07-.14-.67-1.62-.92-2.22-.24-.58-.48-.5-.66-.51-.17-.01-.37-.01-.57-.01-.2 0-.52.07-.79.34-.27.27-1.03 1-1.03 2.44 0 1.44 1.05 2.83 1.19 3.03.14.2 2.07 3.33 5.02 4.64 2.95 1.3 2.95.87 3.48.81.53-.06 1.72-.7 1.97-1.37.25-.67.25-1.25.17-1.37-.08-.12-.27-.2-.57-.35z" fill="#fff"/>
            </svg>
          </span>
          <span class="text">اشترك معنا على قناة الواتساب</span>
        </a>

        <a class="btn" href="https://www.instagram.com/" target="_blank" rel="noopener" aria-label="انستغرام">
          <span class="ico" aria-hidden="true">
            <!-- أيقونة انستغرام مبسطة -->
            <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
              <rect x="3" y="3" width="18" height="18" rx="5" fill="url(#g)"/>
              <defs>
                <linearGradient id="g" x1="0" x2="1">
                  <stop offset="0" stop-color="#f58529"/>
                  <stop offset="0.5" stop-color="#dd2a7b"/>
                  <stop offset="1" stop-color="#8134af"/>
                </linearGradient>
              </defs>
              <circle cx="12" cy="12" r="3" fill="#fff"/>
              <circle cx="17.5" cy="6.5" r="1" fill="#fff"/>
            </svg>
          </span>
          <span class="text">انستغرام</span>
        </a>

        <a class="btn" href="https://www.facebook.com/" target="_blank" rel="noopener" aria-label="فيسبوك">
          <span class="ico" aria-hidden="true">
            <!-- أيقونة فيسبوك -->
            <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
              <rect width="24" height="24" rx="2" fill="#1877F2"/>
              <path d="M15 8h-1.5c-.4 0-.5.2-.5.5V10H16l-.4 2H13v6h-2v-6H8.5V10H11V8.8C11 6.6 12.3 5 14.7 5c.8 0 1.3.1 1.8.2V8z" fill="#fff"/>
            </svg>
          </span>
          <span class="text">فيسبوك</span>
        </a>
      </div>

      <div class="footer-space" aria-hidden="true"></div>
    </div>
  </div>

  <!-- بسيطة: يمكنك إضافة تتبع النقرات أو نسخ الروابط بالـ JS -->
  <script>
    // مثال: تسجيل نقرات للأزرار في الكونسول (يمكن ربط بـ تحليلات)
    document.querySelectorAll('.btn').forEach(btn=>{
      btn.addEventListener('click', (e)=>{
        const label = btn.getAttribute('aria-label') || btn.querySelector('.text')?.textContent || 'link';
        console.log('Link clicked:', label, btn.href);
      });
    });
  </script>
</body>
</html>
