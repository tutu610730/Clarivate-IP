<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Clarivate 智慧財產權解決方案｜VtR 法德利科技</title>
  <style>
    :root{
      --navy:#071b3a;
      --blue:#123b7a;
      --cyan:#00b7c7;
      --teal:#00a88e;
      --light:#f5f8fb;
      --text:#1d2b3a;
      --muted:#5f6f82;
      --white:#ffffff;
      --card:#ffffff;
      --shadow:0 14px 35px rgba(7,27,58,.12);
      --radius:20px;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family:"Microsoft JhengHei Light","Microsoft JhengHei","PingFang TC",Arial,sans-serif;
      color:var(--text);
      background:var(--light);
      line-height:1.75;
    }
    a{color:inherit;text-decoration:none}
    .topbar{
      position:sticky;top:0;z-index:20;
      background:rgba(7,27,58,.92);
      backdrop-filter:blur(12px);
      color:#fff;
      border-bottom:1px solid rgba(255,255,255,.14);
    }
    .nav{
      max-width:1180px;margin:auto;padding:14px 22px;
      display:flex;align-items:center;justify-content:space-between;gap:18px;
    }
    .brand{font-weight:700;letter-spacing:.3px}
    .brand span{color:var(--cyan)}
    .navlinks{display:flex;gap:18px;font-size:14px;flex-wrap:wrap}
    .navlinks a{opacity:.88}
    .navlinks a:hover{opacity:1;color:var(--cyan)}
    .hero{
      background:
        radial-gradient(circle at 78% 22%, rgba(0,183,199,.38), transparent 30%),
        linear-gradient(135deg, #06152f 0%, #123b7a 58%, #045d6f 100%);
      color:#fff;
      padding:88px 22px 72px;
      overflow:hidden;
    }
    .hero-inner{max-width:1180px;margin:auto;display:grid;grid-template-columns:1.2fr .8fr;gap:42px;align-items:center}
    .eyebrow{
      display:inline-block;
      padding:6px 12px;
      border:1px solid rgba(255,255,255,.28);
      border-radius:999px;
      color:#bff8ff;
      font-size:13px;
      letter-spacing:.08em;
      text-transform:uppercase;
      margin-bottom:18px;
    }
    h1{font-size:48px;line-height:1.18;margin:0 0 18px;font-weight:800}
    .subtitle{font-size:19px;color:#d9ecff;margin:0 0 28px;max-width:760px}
    .actions{display:flex;gap:14px;flex-wrap:wrap}
    .btn{
      display:inline-flex;align-items:center;justify-content:center;
      padding:12px 18px;border-radius:999px;font-weight:700;
      transition:.2s ease;min-width:148px;
    }
    .btn-primary{background:var(--cyan);color:#032331}
    .btn-primary:hover{transform:translateY(-2px);box-shadow:0 10px 24px rgba(0,183,199,.28)}
    .btn-ghost{border:1px solid rgba(255,255,255,.38);color:#fff}
    .btn-ghost:hover{background:rgba(255,255,255,.1)}
    .hero-card{
      background:rgba(255,255,255,.1);
      border:1px solid rgba(255,255,255,.18);
      border-radius:var(--radius);
      padding:26px;
      box-shadow:var(--shadow);
    }
    .hero-card h3{margin:0 0 12px;color:#fff}
    .hero-card ul{margin:0;padding-left:20px;color:#e9f7ff}
    section{padding:64px 22px}
    .container{max-width:1180px;margin:auto}
    .section-title{font-size:32px;margin:0 0 14px;color:var(--navy)}
    .section-desc{color:var(--muted);max-width:820px;margin:0 0 28px}
    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:22px}
    .card{
      background:var(--card);
      border-radius:var(--radius);
      padding:26px;
      box-shadow:var(--shadow);
      border:1px solid #e7edf4;
      min-height:220px;
    }
    .card .tag{
      display:inline-block;font-size:12px;color:#006b78;background:#e7fbfd;
      border-radius:999px;padding:4px 10px;margin-bottom:12px;font-weight:700;
    }
    .card h3{margin:0 0 10px;color:var(--blue);font-size:21px}
    .card p{margin:0 0 18px;color:#4a5969}
    .link{color:#007c89;font-weight:700}
    .link:hover{text-decoration:underline}
    .feature{
      background:#fff;
      border-top:1px solid #e8eef5;
      border-bottom:1px solid #e8eef5;
    }
    .two-col{display:grid;grid-template-columns:.9fr 1.1fr;gap:30px;align-items:start}
    .highlight{
      background:linear-gradient(135deg,#eefcff,#f8fbff);
      border-left:5px solid var(--cyan);
      padding:24px;border-radius:16px;
    }
    .list{display:grid;gap:14px}
    .item{
      background:#fff;border:1px solid #e7edf4;border-radius:16px;
      padding:18px 20px;
    }
    .item strong{color:var(--blue)}
    .contact{
      background:linear-gradient(135deg,#06152f,#0e375d);
      color:#fff;
    }
    .contact .section-title{color:#fff}
    .contact .section-desc{color:#dcecff}
    form{
      background:#fff;color:var(--text);
      border-radius:var(--radius);
      padding:26px;
      box-shadow:var(--shadow);
      display:grid;gap:14px;
    }
    label{font-weight:700;font-size:14px;color:#203044}
    input,select,textarea{
      width:100%;padding:12px 13px;border:1px solid #d7e0ea;border-radius:12px;
      font-family:inherit;font-size:15px;background:#fbfdff;
    }
    textarea{min-height:120px;resize:vertical}
    .submit{
      border:none;cursor:pointer;background:var(--cyan);color:#032331;
      font-weight:800;border-radius:999px;padding:13px 20px;font-size:15px;
    }
    .note{font-size:13px;color:#6d7b88;margin:0}
    footer{
      background:#041126;color:#cbd8e6;padding:24px 22px;font-size:13px;
    }
    footer .container{display:flex;justify-content:space-between;gap:16px;flex-wrap:wrap}
    @media(max-width:900px){
      .hero-inner,.two-col{grid-template-columns:1fr}
      .grid{grid-template-columns:1fr}
      h1{font-size:36px}
      .nav{align-items:flex-start;flex-direction:column}
    }
  </style>
</head>
<body>
  <header class="topbar">
    <nav class="nav">
      <div class="brand">Clarivate <span>IP Solutions</span>｜VtR</div>
      <div class="navlinks">
        <a href="#overview">概述</a>
        <a href="#featured">精選</a>
        <a href="#products">產品</a>
        <a href="#solutions">解決方案</a>
        <a href="#contact">聯絡我們</a>
      </div>
    </nav>
  </header>

  <main>
    <section class="hero" id="overview">
      <div class="hero-inner">
        <div>
          <div class="eyebrow">Intellectual Property</div>
          <h1>改變您創造、管理與保護智慧財產權的方式</h1>
          <p class="subtitle">
            Clarivate 提供智慧財產權資料、軟體平台與專業知識，協助企業推動創新、法律事務所提升執業效能，並幫助全球組織有效管理與保護關鍵 IP 資產。
          </p>
          <div class="actions">
            <a class="btn btn-primary" href="#contact">預約諮詢</a>
            <a class="btn btn-ghost" href="https://clarivate.com/intellectual-property/" target="_blank" rel="noopener">前往 Clarivate 原廠頁面 ↗</a>
          </div>
        </div>
        <div class="hero-card">
          <h3>完整 IP 生命週期支援</h3>
          <ul>
            <li>專利檢索與專利情報分析</li>
            <li>商標檢索、監控與品牌保護</li>
            <li>IP 組合管理與流程最佳化</li>
            <li>訴訟情報與全球判例資料</li>
            <li>專家顧問與行政支援服務</li>
          </ul>
        </div>
      </div>
    </section>

    <section id="featured">
      <div class="container">
        <h2 class="section-title">精選資訊</h2>
        <p class="section-desc">掌握 Clarivate 智慧財產權產品訓練、使用者交流與產業洞察。</p>
        <div class="card">
          <span class="tag">Featured</span>
          <h3>Ignite 2026 現已開放報名</h3>
          <p>
            邀請 Clarivate IP 產品使用者參與，透過獨家洞察、深度產品訓練與互動式工作坊，協助使用者充分發揮 IP 解決方案的最大價值。
          </p>
          <a class="link" href="https://clarivate.com/intellectual-property/" target="_blank" rel="noopener">查看 Clarivate IP 最新活動與資訊 ↗</a>
        </div>
      </div>
    </section>

    <section class="feature" id="products">
      <div class="container">
        <h2 class="section-title">關鍵產品</h2>
        <p class="section-desc">從 IP 管理、專利情報到商標分析，支援研發、法務、智財與管理層做出更有信心的決策。</p>
        <div class="grid">
          <div class="card">
            <span class="tag">IP Management</span>
            <h3>IPfolio</h3>
            <p>Clarivate 領先的雲端 IP 管理平台，專為不同規模的企業智慧財產團隊設計，支援專利與商標組合管理。</p>
            <a class="link" href="https://clarivate.com/intellectual-property/ip-management-software/ipfolio/" target="_blank" rel="noopener">原廠產品頁 ↗</a>
          </div>
          <div class="card">
            <span class="tag">Patent Search</span>
            <h3>Derwent Patent Search</h3>
            <p>前身為 Derwent Innovation，結合高品質專利資料、AI 檢索與專家撰寫摘要，提供值得信賴的專利檢索結果。</p>
            <a class="link" href="https://clarivate.com/intellectual-property/derwent/patent-search/" target="_blank" rel="noopener">原廠產品頁 ↗</a>
          </div>
          <div class="card">
            <span class="tag">Trademark Analytics</span>
            <h3>Trademark Analytics</h3>
            <p>整合 Darts-ip 判例資料與 CompuMark 商標資料，提供深入商標分析與品牌風險洞察。</p>
            <a class="link" href="https://clarivate.com/intellectual-property/" target="_blank" rel="noopener">原廠 IP 頁面 ↗</a>
          </div>
        </div>
      </div>
    </section>

    <section id="solutions">
      <div class="container two-col">
        <div>
          <h2 class="section-title">解決方案領域</h2>
          <p class="section-desc">
            Clarivate IP 解決方案涵蓋專利、商標、訴訟情報、管理軟體與顧問服務，協助企業建立可追溯、可分析、可決策的智慧財產管理體系。
          </p>
          <div class="highlight">
            <strong>一句話總結：</strong><br>
            從創新發想、專利布局、商標保護、競爭情報分析到訴訟風險管理，支援完整智慧財產生命週期。
          </div>
        </div>
        <div class="list">
          <div class="item"><strong>IP Management Software：</strong>提升 IP 營運效率，簡化專利與商標組合管理流程。</div>
          <div class="item"><strong>Patent Services：</strong>透過專家行政支援，優化專利申請、維護與管理流程。</div>
          <div class="item"><strong>Derwent Patent Intelligence：</strong>以世界級專利資料、分析軟體與專家服務取得清晰洞察。</div>
          <div class="item"><strong>CompuMark Trademark Solutions：</strong>協助企業建立、管理與保護強勢品牌。</div>
          <div class="item"><strong>Litigation Intelligence：</strong>利用 Darts-ip 全球 IP 判例資料，支援更有依據的智慧財產決策。</div>
          <div class="item"><strong>Consulting Services：</strong>以客製化顧問服務協助制定策略性 IP 決策。</div>
        </div>
      </div>
    </section>

    <section class="contact" id="contact">
      <div class="container two-col">
        <div>
          <h2 class="section-title">聯絡我們</h2>
          <p class="section-desc">
            如需 Clarivate 智慧財產權解決方案介紹、產品 Demo、報價或導入評估，請填寫右方表單。送出後將開啟您的電子郵件程式，寄送至 murphychen@vtr.asia。
          </p>
          <p><strong>VtR 法德利科技股份有限公司</strong><br>Clarivate 智慧財產權解決方案諮詢</p>
        </div>
        <form action="mailto:murphychen@vtr.asia" method="post" enctype="text/plain">
          <div>
            <label for="company">公司／學校</label>
            <input id="company" name="公司／學校" type="text" placeholder="請輸入公司或學校名稱" required>
          </div>
          <div>
            <label for="department">單位／部門</label>
            <input id="department" name="單位／部門" type="text" placeholder="例如：研發、智財、法務、技轉中心">
          </div>
          <div>
            <label for="name">姓名</label>
            <input id="name" name="姓名" type="text" placeholder="請輸入姓名" required>
          </div>
          <div>
            <label for="email">Email</label>
            <input id="email" name="Email" type="email" placeholder="name@example.com" required>
          </div>
          <div>
            <label for="phone">電話</label>
            <input id="phone" name="電話" type="tel" placeholder="請輸入聯絡電話">
          </div>
          <div>
            <label for="topic">希望了解的項目</label>
            <select id="topic" name="希望了解的項目">
              <option>Clarivate IP 整體解決方案</option>
              <option>IPfolio 智慧財產管理平台</option>
              <option>Derwent Patent Search / Patent Intelligence</option>
              <option>Trademark Analytics / CompuMark</option>
              <option>Darts-ip / Litigation Intelligence</option>
              <option>產品 Demo / 報價 / 導入評估</option>
            </select>
          </div>
          <div>
            <label for="message">需求說明</label>
            <textarea id="message" name="需求說明" placeholder="請簡述目前需求、使用情境或希望安排的會議時間"></textarea>
          </div>
          <button class="submit" type="submit">送出聯絡資訊</button>
          <p class="note">提醒：mailto 表單會依使用者電腦或手機設定開啟預設郵件軟體。若需寫入 Google Sheet，可再改為 Google Apps Script 表單。</p>
        </form>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">
      <div>© 2026 VtR Inc.｜Clarivate IP Solutions Taiwan</div>
      <div>
        <a href="https://clarivate.com/intellectual-property/" target="_blank" rel="noopener">Clarivate Intellectual Property</a>
        ｜ <a href="mailto:murphychen@vtr.asia">murphychen@vtr.asia</a>
      </div>
    </div>
  </footer>
</body>
</html>
