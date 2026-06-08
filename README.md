# insight brand assets

> **하나의 insight, 세 계층의 색.**
> insight 제품군(Family)의 브랜드 일관성을 위한 로고·컬러·가이드 에셋 모음.

`"sight"`는 모든 형제 제품이 공유하는 **가족색(네이비)** 입니다. 각 제품의 이름이 고유색을 갖고, 특화 에디션은 한 단계 더 색을 더합니다. 모든 색은 휴(hue)를 고정한 채 라이트·다크에서 명도만 적응합니다 — 그래서 제품이 무한히 늘어나도 한 가족으로 읽힙니다.

---

## 🎨 패밀리 소개 페이지

브랜드 시스템과 패밀리 프로그램을 한 페이지로 소개하는 standalone HTML.

| 파일 | 설명 |
|------|------|
| [`insight-family.html`](insight-family.html) | 가벼움(~40KB). 폰트는 Google Fonts CDN 사용 — **온라인 권장** |
| [`insight-family-offline.html`](insight-family-offline.html) | 278KB. IBM Plex 폰트를 서브셋·base64로 **내장** — 서버·인터넷 없이 `file://`로 열림. **USB·오프라인·배포용** |

**구성:** 색의 세 계층 · 패밀리 프로그램(Analytics · Data Hub · Analytics Prop) · 컬러 토큰 · 차트 팔레트 · 워드마크 잠금 규칙
**기능:** 라이트/다크 테마 토글(상태 저장) · 인라인 SVG 로고 · 모바일 반응형 · 빌드/의존성 없음

```bash
# 그냥 더블클릭하거나, 미리보기 서버로:
python3 -m http.server 7475   # → http://localhost:7475/insight-family.html
```

---

## 🧩 제품 로고 에셋

각 제품/에디션의 로고·파비콘. 코드에서 바로 사용하세요.

| 폴더 | 제품 | 대표색 |
|------|------|--------|
| [`insight platform brand aseet/`](insight%20platform%20brand%20aseet/logos/platform/) | insight **platform** (패밀리 우산) | 네이비 `#3050aa` |
| [`insight Analytics brand asset/`](insight%20Analytics%20brand%20asset/) | insight **Analytics** | 오렌지 `#e76709` |
| [`insight DataHub brand asset/`](insight%20DataHub%20brand%20asset/) | insight **Data Hub** | 시안 `#00a4bf` |
| [`insight Analytics Prop brand asset/`](insight%20Analytics%20Prop%20brand%20asset/) | insight **Analytics Prop** (에디션) | 연두 `#87ce5b` |

각 폴더 구성: `logo.svg`(라이트), `logo-dark.svg`(다크), `favicon.svg`, `favicon-32/180/512.png`, `README.md`

---

## 📐 브랜드 스펙 (standalone HTML)

- [`insight Brand System (standalone) (1).html`](insight%20Brand%20System%20(standalone)%20(1).html) — 패밀리 전체 시스템
- [`insight Analytics Brand Spec (standalone) ver2.html`](insight%20Analytics%20Brand%20Spec%20(standalone)%20ver2.html)
- [`insight Analytics Prop Brand Spec (standalone) ver2.html`](insight%20Analytics%20Prop%20Brand%20Spec%20(standalone)%20ver2.html)
- [`insight Data Hub Brand Spec (standalone) ver2.html`](insight%20Data%20Hub%20Brand%20Spec%20(standalone)%20ver2.html)

---

## 🎯 컬러 토큰

휴는 라이트·다크에서 **고정**, 명도(첫 값)만 적응합니다.

| 계층 | 이름 | tile | light | dark |
|------|------|------|-------|------|
| 가족 | 네이비 · `"sight"` | `#3050aa` | `#26418d` | `#7ba1fc` |
| 제품 | 오렌지 · Analytics | `#e76709` | `#c95200` | `#fb8a44` |
| 제품 | 시안 · Data Hub | `#00a4bf` | `#0090ae` | `#50d2e6` |
| 에디션 | 연두 · Prop | `#87ce5b` | `#43963c` | `#98da6a` |

**차트 팔레트:** 가족색 네이비를 1번 앵커로, 휴를 45°씩 등간격 회전해 8색. 모든 제품이 공유합니다.

---

## ✍️ 워드마크 잠금 규칙

`in`(중립) + `sight`(네이비) + `제품명`(제품색) + (선택) `에디션`(에디션색)

- ✅ `"sight"`는 항상 네이비 — 제품명 단어만 제품색으로
- ✕ `"sight"`에 제품색 칠하기 / 한 워드마크에 3색(역할) 초과 금지
- ◐ 휴 고정, 명도만 적응 (라이트=어둡게, 다크=밝게)
- ▭ 최소 표시 크기: 마크 20px, 워드마크 높이 18px

---

## 🔤 타이포그래피

IBM Plex Sans · IBM Plex Sans KR · IBM Plex Mono (SIL OFL)
