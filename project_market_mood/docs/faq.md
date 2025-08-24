---
layout: null
title: FAQ
---

<style>
  :root{
    --fg:#111827;      /* 본문 글자 */
    --bg:#ffffff;      /* 배경 */
    --muted:#6b7280;   /* 보조 텍스트 */
    --border:#e5e7eb;  /* 경계선 */
    --card:#ffffff;    /* 카드 배경 */
    --primary:#142743; /* 브랜드 포인트(필요시) */
  }
  @media (prefers-color-scheme: dark){
    :root{
      --fg:#e5e7eb;
      --bg:#0b1220;
      --muted:#94a3b8;
      --border:#1f2a44;
      --card:#0f172a;
    }
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

# Frequently Asked Questions (FAQ)

<p class="lead">아래 항목을 탭(클릭)해 내용을 펼쳐보세요.</p>

<details>
  <summary>앱은 무료인가요?</summary>
  <div class="details-body">
    기본 기능은 무료입니다. 일부 고급 기능(예: 고급 알림, 추가 차트)은 구독 기반으로 제공될 수 있습니다.
  </div>
</details>

<details>
  <summary>문서(이용약관/개인정보처리방침)는 어떻게 업데이트되나요?</summary>
  <div class="details-body">
    GitHub Pages의 Markdown 문서를 수정/커밋하면 즉시 반영됩니다. 앱은 해당 URL을 로드하므로 새로고침 시 최신 내용이 표시됩니다.
  </div>
</details>

<details>
  <summary>FAQ는 오프라인에서도 볼 수 있나요?</summary>
  <div class="details-body">
    이 페이지는 WebView로 제공되어 네트워크 연결이 필요합니다. 중요한 고지 문서는 앱 내부 Markdown 화면으로도 제공할 수 있습니다.
  </div>
</details>

<details>
  <summary>데이터 출처는 무엇인가요?</summary>
  <div class="details-body">
    시장 지표는 공신력 있는 공개 소스(CNN Fear &amp; Greed, Google Finance 등)를 참고합니다. 각 화면 하단에 출처를 표기합니다.
  </div>
</details>

<details>
  <summary>알림 시간과 조건은 어떻게 설정하나요?</summary>
  <div class="details-body">
    앱의 Settings에서 알림 허용, 시간대, 임계값(예: 점수 ≤ 25)을 조정할 수 있습니다. 기기 설정에서 알림 권한을 허용해야 동작합니다.
  </div>
</details>

<details>
  <summary>개인정보는 어떻게 처리되나요?</summary>
  <div class="details-body">
    필수 최소한의 정보만 사용하며, 법령 및 개인정보 처리방침에 따라 관리됩니다. 자세한 내용은 Privacy Policy 문서를 참고하세요.
  </div>
</details>

<details>
  <summary>문제가 발생했어요. 어디로 문의하나요?</summary>
  <div class="details-body">
    앱의 About 화면에 표기된 이메일/이슈 트래커로 연락 주세요. 가능한 한 빠르게 답변드리겠습니다.
  </div>
</details>

<hr />
<div class="updated">Last updated: 2025-08-24</div>

</main>
