# hero
<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <meta
    name="description"
    content="ابرینو؛ زیرساخت ابری سریع، امن و مقیاس‌پذیر برای اجرای برنامه‌ها."
  />

  <title>ابرینو | اجرای سریع برنامه روی سرور</title>

  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Vazirmatn:wght@400;500;600;700;800;900&display=swap"
    rel="stylesheet"
  />

  <link rel="stylesheet" href="style.css" />
</head>

<body>
  <!-- نورهای پس‌زمینه -->
  <div class="background-glow glow-one"></div>
  <div class="background-glow glow-two"></div>
  <div class="background-grid"></div>

  <!-- هدر -->
  <header class="site-header">
    <div class="container navbar">
      <a href="#" class="brand" aria-label="صفحه اصلی ابرینو">
        <span class="brand-mark">
          <span></span>
          <span></span>
          <span></span>
        </span>

        <span class="brand-name">ابرینو</span>
      </a>

      <nav class="nav-links" aria-label="منوی اصلی">
        <a href="#products">محصولات</a>
        <a href="#why-us">چرا ابرینو؟</a>
        <a href="#docs">مستندات</a>
        <a href="#pricing">قیمت‌ها</a>
      </nav>

      <div class="header-actions">
        <a class="phone-number" href="tel:+982191234567">
          <span class="phone-icon">☎</span>
          <span>۰۲۱-۹۱۲۳۴۵۶۷</span>
        </a>

        <a class="button button-small button-light" href="#start">
          ورود یا ثبت‌نام
        </a>
      </div>
    </div>
  </header>

  <main>
    <!-- Hero -->
    <section class="hero" id="start">
      <div class="container hero-layout">
        <div class="hero-content">
          <div class="eyebrow">
            <span class="eyebrow-dot"></span>
            زیرساخت ابری برای تیم‌های سریع
          </div>

          <h1>
            در کمتر از <span>۵ دقیقه</span>
            <br />
            برنامهٔ خود را روی سرور اجرا کنید.
          </h1>

          <p class="hero-description">
            از ایده تا استقرار، بدون درگیری با پیچیدگی‌های سرور.
            اپلیکیشن خود را با چند کلیک اجرا کنید، مقیاس دهید و با خیال
            راحت رشد کنید.
          </p>

          <div class="hero-buttons">
            <a class="button button-primary" href="#products">
              <span>امتحان کنید</span>
              <span class="arrow">←</span>
            </a>

            <a class="button button-outline" href="#docs">
              مشاهدهٔ مستندات
            </a>
          </div>

          <div class="trust-row">
            <div class="trust-item">
              <strong>۹۹٫۹٪</strong>
              <span>پایداری سرویس</span>
            </div>

            <span class="trust-divider"></span>

            <div class="trust-item">
              <strong>۲۴/۷</strong>
              <span>پشتیبانی فنی</span>
            </div>

            <span class="trust-divider"></span>

            <div class="trust-item">
              <strong>۵ دقیقه</strong>
              <span>تا استقرار</span>
            </div>
          </div>
        </div>

        <!-- تصویرسازی Hero -->
        <div class="hero-visual" aria-hidden="true">
          <div class="visual-orbit orbit-one"></div>
          <div class="visual-orbit orbit-two"></div>
          <div class="visual-orbit orbit-three"></div>

          <div class="halo halo-large"></div>
          <div class="halo halo-small"></div>

          <div class="tech-bubble bubble-python">
            <div class="tech-icon python-icon">Py</div>
            <span>Python</span>
          </div>

          <div class="tech-bubble bubble-node">
            <div class="tech-icon node-icon">JS</div>
            <span>Node.js</span>
          </div>

          <div class="tech-bubble bubble-docker">
            <div class="tech-icon docker-icon">▣</div>
            <span>Docker</span>
          </div>

          <div class="tech-bubble bubble-cloud">
            <div class="tech-icon cloud-icon">☁</div>
            <span>Cloud</span>
          </div>

          <div class="sculpture-wrapper">
            <div class="sculpture-shadow"></div>

            <div class="sculpture">
              <div class="sculpture-light"></div>

              <div class="face">
                <div class="hair hair-left"></div>
                <div class="hair hair-right"></div>

                <div class="forehead"></div>

                <div class="eye eye-right">
                  <span></span>
                </div>

                <div class="eye eye-left">
                  <span></span>
                </div>

                <div class="nose"></div>
                <div class="mouth"></div>
                <div class="chin"></div>

                <div class="neck"></div>
                <div class="shoulders"></div>
              </div>
            </div>
          </div>

          <div class="code-card code-card-one">
            <span class="code-dot pink"></span>
            <span class="code-dot yellow"></span>
            <span class="code-dot blue"></span>
            <code>deploy --production</code>
          </div>

          <div class="code-card code-card-two">
            <span class="terminal-sign">›_</span>
            <code>status: online</code>
          </div>
        </div>
      </div>
    </section>

    <!-- محصولات -->
    <section class="section products-section" id="products">
      <div class="container">
        <div class="section-heading">
          <span class="section-label">محصولات ابرینو</span>
          <h2>هرآنچه برای اجرای محصول دیجیتال نیاز دارید</h2>
          <p>
            زیرساختی منعطف برای ساخت، اجرا و مقیاس‌دهی پروژه‌های کوچک تا
            سرویس‌های بزرگ.
          </p>
        </div>

        <div class="cards-grid">
          <article class="service-card">
            <div class="service-icon purple">☁</div>
            <h3>سرور ابری</h3>
            <p>
              منابع اختصاصی، قابل ارتقا و آماده برای اجرای سرویس‌های حیاتی شما.
            </p>
            <a href="#pricing">بیشتر بدانید ←</a>
          </article>

          <article class="service-card featured-card">
            <div class="service-icon blue">◈</div>
            <h3>استقرار خودکار</h3>
            <p>
              پروژه‌تان را به Git متصل کنید تا هر تغییر به‌صورت خودکار منتشر شود.
            </p>
            <a href="#pricing">بیشتر بدانید ←</a>
          </article>

          <article class="service-card">
            <div class="service-icon pink">◌</div>
            <h3>پایگاه دادهٔ مدیریت‌شده</h3>
            <p>
              نگهداری، پشتیبان‌گیری و مقیاس‌پذیری پایگاه داده را به ما بسپارید.
            </p>
            <a href="#pricing">بیشتر بدانید ←</a>
          </article>
        </div>
      </div>
    </section>

    <!-- مزایا -->
    <section class="section benefits-section" id="why-us">
      <div class="container benefits-layout">
        <div class="benefits-content">
          <span class="section-label">چرا ابرینو؟</span>

          <h2>
            روی ساخت محصول تمرکز کنید،
            <br />
            نه مدیریت سرور.
          </h2>

          <p>
            ما بخش پیچیدهٔ زیرساخت را ساده کرده‌ایم؛ تا تیم شما بتواند انرژی‌اش
            را صرف تجربهٔ کاربر، توسعهٔ قابلیت‌ها و رشد کسب‌وکار کند.
          </p>

          <ul class="benefit-list">
            <li>
              <span class="check">✓</span>
              استقرار سریع از GitHub و GitLab
            </li>
            <li>
              <span class="check">✓</span>
              مانیتورینگ دائمی و هشدار هوشمند
            </li>
            <li>
              <span class="check">✓</span>
              پشتیبانی انسانی و تخصصی
            </li>
            <li>
              <span class="check">✓</span>
              پرداخت ریالی و شفاف
            </li>
          </ul>
        </div>

        <div class="dashboard-preview">
          <div class="dashboard-top">
            <div>
              <span class="dashboard-label">وضعیت سرویس</span>
              <strong>اپلیکیشن فروشگاه</strong>
            </div>

            <span class="status-badge">
              <span></span>
              آنلاین
            </span>
          </div>

          <div class="dashboard-chart">
            <div class="chart-bars">
              <i style="height: 31%"></i>
              <i style="height: 48%"></i>
              <i style="height: 42%"></i>
              <i style="height: 69%"></i>
              <i style="height: 57%"></i>
              <i style="height: 82%"></i>
              <i style="height: 63%"></i>
              <i style="height: 92%"></i>
              <i style="height: 74%"></i>
              <i style="height: 87%"></i>
            </div>
          </div>

          <div class="dashboard-stats">
            <div>
              <span>مصرف پردازنده</span>
              <strong>۲۴٪</strong>
            </div>

            <div>
              <span>بازدید امروز</span>
              <strong>۱۲٬۴۸۰</strong>
            </div>

            <div>
              <span>زمان پاسخ</span>
              <strong>۱۲۰ms</strong>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- مستندات -->
    <section class="section docs-section" id="docs">
      <div class="container docs-box">
        <div>
          <span class="section-label">شروع آسان</span>
          <h2>از همین امروز شروع کنید.</h2>
          <p>
            مستندات قدم‌به‌قدم، نمونه‌کد و راهنمای کامل برای استقرار اولین
            پروژهٔ شما آماده است.
          </p>
        </div>

        <a href="#start" class="button button-primary">
          شروع رایگان
          <span class="arrow">←</span>
        </a>
      </div>
    </section>

    <!-- قیمت -->
    <section class="section pricing-section" id="pricing">
      <div class="container">
        <div class="section-heading">
          <span class="section-label">قیمت‌گذاری شفاف</span>
          <h2>از کوچک شروع کنید، هر زمان خواستید رشد کنید.</h2>
        </div>

        <div class="pricing-card">
          <div>
            <span class="pricing-title">پلن شروع</span>
            <h3>برای پروژه‌های شخصی و نمونهٔ اولیه</h3>
          </div>

          <div class="pricing-price">
            <strong>رایگان</strong>
            <span>برای شروع</span>
          </div>

          <a href="#start" class="button button-light">ساخت حساب</a>
        </div>
      </div>
    </section>
  </main>

  <!-- فوتر -->
  <footer class="site-footer">
    <div class="container footer-content">
      <a href="#" class="brand">
        <span class="brand-mark">
          <span></span>
          <span></span>
          <span></span>
        </span>

        <span class="brand-name">ابرینو</span>
      </a>

      <p>زیرساخت ابری برای ساختن سریع‌تر و مطمئن‌تر.</p>

      <div class="footer-links">
        <a href="#products">محصولات</a>
        <a href="#docs">مستندات</a>
        <a href="#pricing">قیمت‌ها</a>
      </div>
    </div>

    <div class="container footer-bottom">
      <span>© ۱۴۰۵ ابرینو — همهٔ حقوق محفوظ است.</span>
      <span>ساخته‌شده برای انتشار در GitHub Pages</span>
    </div>
  </footer>
</body>
</html>
