---
layout: null
title: FAQ
---

<style>
  :root{
    --fg:#111827;         /* main text */
    --bg:#F4F6F9;         /* global background */
    --muted:#6b7280;      /* secondary text */
    --border:#d1d5db;     /* border */
    --card:#ffffff;       /* card background */
    --primary:#142743;    /* brand color */
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

  /* language switch */
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
  <a href="https://thinker89.github.io/docs_hub/project_market_mood/docs/faq_en.html">English</a>
  <a href="https://thinker89.github.io/docs_hub/project_market_mood/docs/faq_ko.html">한국어</a>
  <a href="https://thinker89.github.io/docs_hub/project_market_mood/docs/faq_ja.html">日本語</a>
</div>

# FAQ

<details>
  <summary>1. I’m not receiving notifications.</summary>
  <div class="details-body">
    Please check if notifications are turned on in the app settings, if your thresholds and time options are set as you want, and if notification permission is granted.<br><br>
    Some devices may automatically put the app into “sleep mode” after long periods of inactivity, which can block notifications.<br><br>
    Check your device manufacturer’s instructions on how to exclude the app from sleep mode. Opening the app at least once a week also helps prevent the system from treating it as inactive.
  </div>
</details>

<details>
  <summary>2. Is the data updated in real time?</summary>
  <div class="details-body">
    No. The app does not provide real-time data.<br><br>
    We show data provided by CNN Business and FRED, and these sources do not update in real time.<br><br>
    The last update time is displayed on the CNN F&amp;G and FRED VIX sections in the app.<br><br>
    Except for Fear &amp; Greed, all indicators are from FRED and share the same update time as FRED VIX.
  </div>
</details>

<details>
  <summary>3. Data is not showing.</summary>
  <div class="details-body">
    First, check your network connection.<br><br>
    If data providers (CNN Business, FRED) are delayed or temporarily unavailable, the app may not be able to display data.
  </div>
</details>

<details>
  <summary>4. Do you collect personal information?</summary>
  <div class="details-body">
    No. This app has no login feature and does not collect any personal information from users.
  </div>
</details>

<details>
  <summary>5. Are there any extra charges?</summary>
  <div class="details-body">
    No. This app is sold as a paid app, and there are no in-app purchases or ads.
  </div>
</details>

<details>
  <summary>6. How can I contact you?</summary>
  <div class="details-body">
    If you have any questions, please send us an email:<br>
    <a href="mailto:arksoft.cs@gmail.com">arksoft.cs@gmail.com</a>
  </div>
</details>

<hr />
<div class="updated">Last updated: 2025-09-14</div>

</main>
