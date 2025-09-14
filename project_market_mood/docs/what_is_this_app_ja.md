---
layout: null
title: このアプリについて
---

<style>
  :root{
    --fg:#111827;
    --bg:#F4F6F9;
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

# 市場を覗くもう一つの窓。雰囲気をサッとチェック。

<details>
  <summary>このアプリは何ですか？</summary>
  <div class="details-body">
    米国株式市場の雰囲気を手軽に感じ取るためのシンプルな道具です。<br><br>
    CNN Fear &amp; GreedやVIXなど、投資家心理を示す指標を一目で確認できます。
  </div>
</details>

<details>
  <summary>どう使えばいいですか？</summary>
  <div class="details-body">
    注目すべきは3つの指標：Fear &amp; Greed、VIX、長短金利差。<br><br>
    通知を設定すれば、気になる動きを効果的に追跡できます。<br><br>
    画面の配置も自由にカスタマイズできます。<br><br>
    ※本アプリは投資助言を行うものではありません。表示された情報の正確性や、それに基づく判断・行動は利用者自身の責任となります。
  </div>
</details>

<details>
  <summary>Fear &amp; Greedとは？</summary>
  <div class="details-body">
    CNN Businessが算出する指標で、0に近いほど「恐怖」、100に近いほど「強欲」を示します。<br><br>
    市場全体の雰囲気をつかむシンプルな指標として広く使われています。
  </div>
</details>

<details>
  <summary>VIXとは？</summary>
  <div class="details-body">
    Volatility Index、いわゆる「恐怖指数」です。<br><br>
    通常は10～20程度ですが、市場が荒れると急騰する傾向があります。
  </div>
</details>

<details>
  <summary>長短金利の逆転とは？</summary>
  <div class="details-body">
    通常、長期国債の利回りは短期国債より高くなります。<br><br>
    しかし米国10年債の利回りが2年債を下回る「逆イールド」が起きると、景気後退への警戒を意味します。<br><br>
    歴史的に、逆イールドの後に株式市場でショックが起きた事例が多く見られました。
  </div>
</details>

<hr />
<div class="updated">最終更新日: 2025-09-14</div>

</main>
