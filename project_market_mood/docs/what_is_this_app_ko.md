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
  <a href="https://thinker89.github.io/docs_hub/project_market_mood/docs/what_is_this_app_ja.html">日本語</a>
</div>

# 시장을 바라보는 또 하나의 창. 한눈에 보는 시장 심리.

<details>
  <summary>이 앱은 무엇인가요?</summary>
  <div class="details-body">
    현재 미국 주식 시장 분위기를 쉽고 빠르게 파악하기 위한 보조 도구예요.<br><br>
    CNN Fear &amp; Greed, VIX 등 시장 심리를 나타내는 지표를 한눈에 쉽게 확인할 수 있어요.
  </div>
</details>

<details>
  <summary>어떻게 사용하나요?</summary>
  <div class="details-body">
    Fear &amp; Greed, VIX, 장단기 금리차. 3개 지표를 중점적으로 살펴보세요.<br><br>
    알림 설정을 통해 관찰하고자 하는 지표를 효과적으로 추적하세요.<br><br>
    화면 배치를 원하는 대로 바꿔보세요.<br><br>
    ※ 이 앱은 투자 자문을 제공하지 않아요. 앱에 표시된 모든 정보가 올바른지, 어떤 투자 결정이 올바른지 판단하는 책임은 사용자의 몫이에요.
  </div>
</details>

<details>
  <summary>Fear &amp; Greed란?</summary>
  <div class="details-body">
    CNN Business에서 산출하는 지표로 0에 가까우면 공포, 100에 가까우면 탐욕을 나타내요.<br><br>
    시장 분위기를 손쉽게 파악할 수 있는 지표로 널리 알려져 있어요.
  </div>
</details>

<details>
  <summary>VIX란?</summary>
  <div class="details-body">
    Market Volatility Index. 시장 변동성 지표예요.<br><br>
    평소에는 10 ~ 20 수준이지만, 시장이 혼란스러운 경우 급격히 치솟는 경향이 있어요.
  </div>
</details>

<details>
  <summary>장단기 금리 역전이란?</summary>
  <div class="details-body">
    채권 금리는 일반적으로 장기채가 높고 단기채가 낮아요.<br><br>
    그런데 미국 10년물 채권 금리와 2년물 채권 금리가 역전되는 경우, 채권 시장이 불황을 예상한다는 뜻이에요.<br><br>
    역사적으로, 장단기 금리 역전 이후 주식 시장에 충격이 전파된 사례가 자주 있었어요.
  </div>
</details>

<hr />
<div class="updated">Last updated: 2025-09-14</div>

</main>
