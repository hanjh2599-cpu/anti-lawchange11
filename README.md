<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>약사법 시행규칙 개정안 반대 | 서울특별시약사회</title>
<meta name="description" content="약사에게만 과도한 책임을 전가하는 약사법 시행규칙 개정안에 반대 의견을 제출해주세요.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;500;600;700;900&family=Noto+Serif+KR:wght@600;700;900&display=swap" rel="stylesheet">
<style>
  :root {
    --red-900: #7f1d1d;
    --red-700: #b91c1c;
    --red-600: #dc2626;
    --red-500: #ef4444;
    --red-100: #fee2e2;
    --red-50: #fef2f2;
    --slate-900: #0f172a;
    --slate-800: #1e293b;
    --slate-700: #334155;
    --slate-600: #475569;
    --slate-400: #94a3b8;
    --slate-200: #e2e8f0;
    --slate-100: #f1f5f9;
    --slate-50: #f8fafc;
    --white: #ffffff;
    --amber-500: #f59e0b;
    --amber-100: #fef3c7;
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    font-family: 'Noto Sans KR', -apple-system, BlinkMacSystemFont, sans-serif;
    background: var(--slate-50);
    color: var(--slate-800);
    line-height: 1.7;
    -webkit-font-smoothing: antialiased;
  }

  /* ── Top Alert Bar ── */
  .alert-bar {
    background: var(--red-700);
    color: var(--white);
    text-align: center;
    padding: 10px 20px;
    font-size: 13px;
    font-weight: 500;
    letter-spacing: 0.02em;
    animation: pulse-bg 3s ease-in-out infinite;
  }
  @keyframes pulse-bg {
    0%, 100% { background: var(--red-700); }
    50% { background: var(--red-900); }
  }
  .alert-bar span { margin-right: 8px; }

  /* ── Header ── */
  .header {
    background: var(--white);
    border-bottom: 1px solid var(--slate-200);
    padding: 16px 24px;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 12px;
  }
  .header-logo {
    width: 36px; height: 36px;
    background: var(--slate-900);
    border-radius: 8px;
    display: flex; align-items: center; justify-content: center;
    color: var(--white);
    font-weight: 900;
    font-size: 16px;
    flex-shrink: 0;
  }
  .header-text {
    font-size: 15px;
    font-weight: 600;
    color: var(--slate-700);
    letter-spacing: -0.01em;
  }

  /* ── Hero Section ── */
  .hero {
    background: linear-gradient(135deg, var(--slate-900) 0%, var(--red-900) 100%);
    padding: 72px 24px 64px;
    text-align: center;
    position: relative;
    overflow: hidden;
  }
  .hero::before {
    content: '';
    position: absolute;
    top: -50%; left: -50%;
    width: 200%; height: 200%;
    background: radial-gradient(circle at 30% 40%, rgba(239,68,68,0.15) 0%, transparent 50%),
                radial-gradient(circle at 70% 60%, rgba(239,68,68,0.1) 0%, transparent 50%);
    animation: drift 20s ease-in-out infinite;
  }
  @keyframes drift {
    0%, 100% { transform: translate(0, 0); }
    50% { transform: translate(-3%, 2%); }
  }
  .hero-content { position: relative; z-index: 1; max-width: 720px; margin: 0 auto; }
  .hero-badge {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    background: rgba(239,68,68,0.2);
    border: 1px solid rgba(239,68,68,0.3);
    color: var(--red-100);
    padding: 6px 16px;
    border-radius: 100px;
    font-size: 13px;
    font-weight: 600;
    margin-bottom: 28px;
    backdrop-filter: blur(4px);
    letter-spacing: 0.03em;
  }
  .hero h1 {
    font-family: 'Noto Serif KR', serif;
    font-size: clamp(26px, 5vw, 38px);
    font-weight: 900;
    color: var(--white);
    line-height: 1.35;
    margin-bottom: 20px;
    word-break: keep-all;
  }
  .hero h1 em {
    font-style: normal;
    color: var(--red-500);
    text-decoration: underline;
    text-decoration-color: rgba(239,68,68,0.4);
    text-underline-offset: 4px;
  }
  .hero p {
    font-size: 16px;
    color: rgba(255,255,255,0.75);
    max-width: 560px;
    margin: 0 auto;
    word-break: keep-all;
    line-height: 1.8;
  }

  /* ── Main Container ── */
  .container {
    max-width: 720px;
    margin: 0 auto;
    padding: 0 20px;
  }

  /* ── Section Card ── */
  .section-card {
    background: var(--white);
    border-radius: 16px;
    box-shadow: 0 1px 3px rgba(0,0,0,0.06), 0 4px 16px rgba(0,0,0,0.04);
    margin-top: -32px;
    position: relative;
    z-index: 2;
    overflow: hidden;
  }
  .section-card + .section-card {
    margin-top: 20px;
  }
  .card-header {
    padding: 24px 28px 0;
    display: flex;
    align-items: center;
    gap: 10px;
  }
  .card-icon {
    width: 32px; height: 32px;
    border-radius: 8px;
    display: flex; align-items: center; justify-content: center;
    font-size: 15px;
    flex-shrink: 0;
  }
  .card-icon.blue { background: #eff6ff; }
  .card-icon.red { background: var(--red-50); }
  .card-icon.amber { background: var(--amber-100); }
  .card-title {
    font-family: 'Noto Serif KR', serif;
    font-size: 18px;
    font-weight: 700;
    color: var(--slate-900);
  }
  .card-body {
    padding: 20px 28px 28px;
  }
  .card-body p {
    font-size: 15px;
    color: var(--slate-600);
    margin-bottom: 16px;
    word-break: keep-all;
    line-height: 1.8;
  }
  .card-body p:last-child { margin-bottom: 0; }

  /* ── Law Text Block ── */
  .law-block {
    background: var(--slate-50);
    border-left: 3px solid var(--slate-400);
    border-radius: 0 8px 8px 0;
    padding: 20px 24px;
    margin: 16px 0;
  }
  .law-block p {
    font-size: 14px !important;
    color: var(--slate-700) !important;
    margin-bottom: 12px !important;
    line-height: 1.75 !important;
  }
  .law-block p:last-child { margin-bottom: 0 !important; }
  .law-num {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 22px; height: 22px;
    background: var(--slate-800);
    color: var(--white);
    border-radius: 5px;
    font-size: 12px;
    font-weight: 700;
    margin-right: 6px;
    vertical-align: middle;
  }

  /* ── Danger Callout ── */
  .danger-list {
    list-style: none;
    padding: 0;
  }
  .danger-list li {
    display: flex;
    align-items: flex-start;
    gap: 12px;
    padding: 14px 0;
    border-bottom: 1px solid var(--slate-100);
    font-size: 15px;
    color: var(--slate-700);
    word-break: keep-all;
    line-height: 1.7;
  }
  .danger-list li:last-child { border-bottom: none; padding-bottom: 0; }
  .danger-list .icon-circle {
    flex-shrink: 0;
    width: 28px; height: 28px;
    border-radius: 50%;
    background: var(--red-50);
    display: flex; align-items: center; justify-content: center;
    font-size: 14px;
    margin-top: 2px;
  }
  .danger-list strong { color: var(--red-700); font-weight: 600; }

  /* ── Highlight Box ── */
  .highlight-box {
    background: linear-gradient(135deg, var(--red-50) 0%, #fff5f5 100%);
    border: 1px solid rgba(185,28,28,0.12);
    border-radius: 12px;
    padding: 20px 24px;
    margin-top: 8px;
  }
  .highlight-box p {
    font-size: 15px !important;
    color: var(--red-900) !important;
    font-weight: 500;
  }

  /* ── CTA Section ── */
  .cta-section {
    text-align: center;
    padding: 48px 20px 64px;
  }
  .cta-section .cta-label {
    font-size: 13px;
    font-weight: 600;
    color: var(--slate-400);
    text-transform: uppercase;
    letter-spacing: 0.12em;
    margin-bottom: 12px;
  }
  .cta-section h2 {
    font-family: 'Noto Serif KR', serif;
    font-size: clamp(20px, 4vw, 26px);
    font-weight: 700;
    color: var(--slate-900);
    margin-bottom: 8px;
    word-break: keep-all;
  }
  .cta-section .cta-sub {
    font-size: 15px;
    color: var(--slate-500);
    margin-bottom: 32px;
    word-break: keep-all;
  }

  .cta-btn {
    display: inline-flex;
    align-items: center;
    gap: 10px;
    background: var(--red-600);
    color: var(--white);
    text-decoration: none;
    padding: 18px 40px;
    border-radius: 14px;
    font-size: 17px;
    font-weight: 700;
    letter-spacing: -0.01em;
    transition: all 0.25s cubic-bezier(0.4, 0, 0.2, 1);
    box-shadow: 0 4px 14px rgba(220,38,38,0.35), 0 0 0 0 rgba(220,38,38,0);
    position: relative;
    overflow: hidden;
  }
  .cta-btn::before {
    content: '';
    position: absolute;
    inset: 0;
    background: linear-gradient(135deg, transparent 0%, rgba(255,255,255,0.1) 100%);
  }
  .cta-btn:hover {
    background: var(--red-700);
    transform: translateY(-2px);
    box-shadow: 0 8px 24px rgba(220,38,38,0.4), 0 0 0 4px rgba(220,38,38,0.1);
  }
  .cta-btn:active {
    transform: translateY(0);
  }
  .cta-btn .arrow {
    transition: transform 0.25s ease;
  }
  .cta-btn:hover .arrow {
    transform: translateX(3px);
  }

  .cta-note {
    margin-top: 20px;
    font-size: 13px;
    color: var(--slate-400);
    line-height: 1.6;
  }

  /* ── Footer ── */
  .footer {
    border-top: 1px solid var(--slate-200);
    padding: 28px 24px;
    text-align: center;
  }
  .footer p {
    font-size: 13px;
    color: var(--slate-400);
    line-height: 1.7;
  }
  .footer a {
    color: var(--slate-500);
    text-decoration: none;
  }
  .footer a:hover { text-decoration: underline; }

  /* ── Responsive ── */
  @media (max-width: 480px) {
    .card-body { padding: 16px 20px 24px; }
    .card-header { padding: 20px 20px 0; }
    .law-block { padding: 16px 18px; }
    .cta-btn { padding: 16px 32px; font-size: 16px; width: 100%; justify-content: center; }
    .hero { padding: 56px 20px 56px; }
  }

  /* ── Animations ── */
  .fade-up {
    opacity: 0;
    transform: translateY(24px);
    animation: fadeUp 0.7s ease forwards;
  }
  .fade-up:nth-child(1) { animation-delay: 0.1s; }
  .fade-up:nth-child(2) { animation-delay: 0.25s; }
  .fade-up:nth-child(3) { animation-delay: 0.4s; }
  @keyframes fadeUp {
    to { opacity: 1; transform: translateY(0); }
  }
</style>
</head>
<body>

<!-- Alert Bar -->
<div class="alert-bar">
  <span>🚨</span> 입법예고 기간 중입니다 — 지금 바로 반대 의견을 제출해 주세요
</div>

<!-- Header -->
<div class="header">
  <div class="header-logo">Rx</div>
  <div class="header-text">서울특별시약사회</div>
</div>

<!-- Hero -->
<section class="hero">
  <div class="hero-content">
    <div class="hero-badge fade-up">⚡ 긴급 행동 요청</div>
    <h1 class="fade-up">약사에게만 책임을 전가하는<br>'약사법 시행규칙 개정안'<br><em>결사 반대합니다</em></h1>
    <p class="fade-up">약사님들의 권리와 안전을 지키기 위해<br>지금 바로 반대 의견에 동참해 주십시오.</p>
  </div>
</section>

<!-- Content -->
<div class="container">

  <!-- Card 1: 개정안 내용 -->
  <div class="section-card fade-up">
    <div class="card-header">
      <div class="card-icon blue">📃</div>
      <div class="card-title">약사법 시행규칙 일부개정령안 내용</div>
    </div>
    <div class="card-body">
      <p>약사법 시행규칙 일부를 다음과 같이 개정한다.<br>제15조의6제1항제4호를 다음과 같이 하고, 같은 항에 제7호를 다음과 같이 신설하며, 같은 조에 제3항을 다음과 같이 신설한다.</p>

      <div class="law-block">
        <p><span class="law-num">4</span>부작용(상호작용을 비롯하여 해당 의약품 복용 시 운전, 기계조작 등 일상생활에 미칠 수 있는 위험성 및 법령에 따른 제한사항을 포함한다)</p>
        <p><span class="law-num">7</span>그 밖에 국민의 안전한 의약품 사용을 위하여 보건복지부장관이 정하는 정보</p>
        <p><span class="law-num">③</span>보건복지부장관은 국민의 안전한 의약품 사용을 위하여 필요한 정보를 복약지도서에 포함할 것을 약사에게 요청할 수 있다.</p>
      </div>
    </div>
  </div>

  <!-- Card 2: 왜 반대해야 하는가 -->
  <div class="section-card fade-up">
    <div class="card-header">
      <div class="card-icon red">⚠️</div>
      <div class="card-title">왜 반대해야 합니까?</div>
    </div>
    <div class="card-body">
      <p>해당 개정안은 약물 복용 후 운전 시 사고가 발생할 경우, <strong>약국에 과도한 책임을 전가</strong>할 수 있는 독소조항을 포함하고 있습니다.</p>

      <ul class="danger-list">
        <li>
          <span class="icon-circle">🔴</span>
          <span>운전 주의 및 기계 조작 시 우려되는 의약품에 대한 주의사항을 반드시 <strong>복약지도서에 표기·배부</strong>해야 하며, 미이행 시 <strong>과태료 처분</strong> 대상이 됩니다.</span>
        </li>
        <li>
          <span class="icon-circle">🔴</span>
          <span>실제 교통사고 및 기계 조작 사고 발생 시 <strong>약국으로 책임이 전가</strong>되어, 억울한 송사에 휩쓸릴 위험이 있습니다.</span>
        </li>
        <li>
          <span class="icon-circle">🔴</span>
          <span>약물로 인한 부작용은 <strong>처방 의사에게도 책임이 있음에도</strong>, 유독 약사에게만 복약지도서를 강요하며 책임을 묻고 있습니다.</span>
        </li>
      </ul>

      <div class="highlight-box">
        <p>💬 이대로 개정이 시행된다면, 약사님들은 과중한 업무 부담은 물론 언제 발생할지 모르는 사고의 법적 책임까지 떠안게 됩니다. <strong>지금 목소리를 내지 않으면, 부당한 규제가 그대로 확정됩니다.</strong></p>
      </div>
    </div>
  </div>

  <!-- Card 3: 의견 제출 방법 안내 -->
  <div class="section-card fade-up">
    <div class="card-header">
      <div class="card-icon amber">📝</div>
      <div class="card-title">의견 제출 방법 안내</div>
    </div>
    <div class="card-body">
      <p>아래 버튼을 클릭하면 <strong>법제처 국민참여입법센터</strong>의 해당 입법예고 페이지로 이동합니다. 페이지의 <strong>'의견제출'</strong> 버튼 후 로그인을 통해 반대 의견을 직접 작성·제출하실 수 있습니다.</p>
      <p style="font-size:14px; color: var(--slate-500);">소요시간: 약 2~3분</p>
    </div>
  </div>

</div>

<!-- CTA -->
<section class="cta-section">
  <p class="cta-label">Take Action Now</p>
  <h2>약사의 권익을 지키는 데<br>약사님의 한 마디가 필요합니다</h2>
  <p class="cta-sub">잠시만 시간을 내어 부당한 개정안에 반대 의견을 개진해 주십시오.</p>
  <a href="https://opinion.lawmaking.go.kr/gcom/ogLmPp/85896?finishIncludeYn=Y%252525252525252525252525252526opYn%25252525252526pageIndex" target="_blank" rel="noopener noreferrer" class="cta-btn">
    ✍️ 개정안 반대 의견 제출하러 가기 <span class="arrow">→</span>
  </a>
  <p class="cta-note">법제처 국민참여입법센터 (부처)입법예고 페이지로 연결됩니다.</p>
</section>

<!-- Footer -->
<footer class="footer">
  <p>
    서울특별시약사회<br>
    본 페이지는 약사법 시행규칙 개정안에 대한 반대 의견 제출을 독려하기 위해 제작되었습니다.<br>
    문의 : <a href="tel:02-581-1001">02-581-1001</a>
  </p>
</footer>

</body>
</html>
