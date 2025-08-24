---
layout: null
title: About This App
---

<style>
  :root{
    --fg:#111827;
    --bg:#F4F6F9;     /* 앱 전역 배경색 고정 */
    --muted:#6b7280;
    --border:#d1d5db;
    --card:#ffffff;
    --primary:#142743;
  }

  html, body {
    margin:0; padding:0;
    background:var(--bg); color:var(--fg);
    font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Noto Sans","Apple SD Gothic Neo",sans-serif;
    line-height:1.6; font-size:16px;
    -webkit-font-smoothing:antialiased; text-rendering:optimizeLegibility;
  }
  main.doc {
    max-width: 720px; margin: 0 auto; padding: 20px 16px 48px;
  }

  .lang-switch {
    display:flex; gap:8px; margin-bottom:16px;
  }
  .lang-switch a {
    padding:5px 12px; border-radius:6px;
    border:1px solid var(--primary);
    color:var(--primary);
    font-size:14px; font-weight:600;
    text-decoration:none;
    transition: all .2s;
    background:var(--bg);
  }
  .lang-switch a:hover {
    background:var(--primary); color:white;
  }

  h1 {
    font-size: 22px; font-weight: 800; letter-spacing:-0.2px;
    margin: 6px 0 12px;
  }
  p.lead { margin: 0 0 12px; color: var(--muted); }

  details {
    border:1px solid var(--border);
    border-radius:12px; background:var(--card);
    overflow:hidden; margin:12px 0;
    box-shadow:0 1px 2px rgba(0,0,0,0.03);
  }
  summary {
    list-style:none; cursor:pointer; font-weight:600;
    padding:14px 16px; user-select:none;
  }
  summary::-webkit-details-marker { display:none; }
  summary::before {
    content:"▸"; display:inline-block; margin-right:8px;
    transition: transform .18s ease;
  }
  details[open] summary::before { transform: rotate(90deg); }
  .details-body { padding: 0 16px 14px; }

  hr { border:0; border-top:1px solid var(--border); margin:20px 0; }
  .updated { color:var(--muted); font-style:italic; font-size:.95rem; margin-top:16px; }
</style>

<main class="doc">

<div class="lang-switch">
  <a href="https://thinker89.github.io/docs_hub/project_market_mood/docs/what_is_this_app_en.html">English</a>
  <a href="https://thinker89.github.io/docs_hub/project_market_mood/docs/what_is_this_app_ko.html">한국어</a>
</div>

# What is this app?

<p class="lead">이 앱은 금융 시장의 심리를 간단하게 확인할 수 있도록 여러 지표를 시각화해주는 도구입니다.</p>

<details>
  <summary>Fear &amp; Greed Index란?</summary>
  <div class="details-body">
    CNN이 제공하는 지수로, 투자자들의 공포와 탐욕 심리를 0~100 점수로 나타냅니다. 낮을수록 공포, 높을수록 탐욕을 의미합니다.
  </div>
</details>

<details>
  <summary>VIX란?</summary>
  <div class="details-body">
    흔히 "공포 지수"라고 불리며, 향후 30일간 S&amp;P 500의 변동성에 대한 시장 기대치를 보여줍니다. 값이 높을수록 불확실성이 크다는 뜻입니다.
  </div>
</details>

<details>
  <summary>미국 국채 10년-2년물 스프레드란?</summary>
  <div class="details-body">
    장단기 금리차를 의미합니다. 음수 구간(단기 금리가 장기보다 높음)은 경기 침체 가능성을 시사하는 지표로 자주 인용됩니다.
  </div>
</details>

<details>
  <summary>앱의 주요 기능은?</summary>
  <div class="details-body">
    - 실시간 Fear &amp; Greed Index 확인<br>
    - VIX 및 주요 시장 지표 모니터링<br>
    - 알림 설정을 통한 심리 지수 변화 감지<br>
    - 간단한 차트와 시각화
  </div>
</details>

<details>
  <summary>데이터 출처는?</summary>
  <div class="details-body">
    CNN, Google Finance, FRED 등 공신력 있는 공개 데이터 소스를 활용합니다. 출처는 각 화면에 명시됩니다.
  </div>
</details>

<hr />
<div class="updated">Last updated: 2025-08-24</div>

</main>
