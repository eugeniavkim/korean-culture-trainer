# 한국어 타이핑 — Korean American Typing Trainer

A typing trainer built for Korean Americans — closing the gap between kitchen Korean and fluent Korean. Practice the vocabulary that actually shows up in your life: family dynamics, church, food culture, history, emotions, holidays, and more.

Works offline. Installable on iPhone as a home screen app.

---

## What's inside

**239 terms across 14 categories**, every single one with a definition, a date, and a note on why it matters for Korean Americans specifically.

| Category | What it covers |
|---|---|
| 🏠 가족 | Family honorifics, generational titles, 정, 눈치, 효도 |
| ⛪ 교회 | Church vocabulary, roles, rituals, community life |
| 🍚 밥상 | Food culture, table rituals, restaurant vocabulary |
| 📜 역사 | Korean history from 단군 to 한류 |
| 🧑‍🎓 인물 | Famous Koreans — kings, activists, athletes, artists |
| 🗺 지리 | Korean geography with cultural context |
| 💬 감정 | Untranslatable emotions: 한, 서운하다, 억울하다, 설레다 |
| 👶 육아 | Phrases for raising kids in Korean |
| 📰 격식 | Formal Hanja vocabulary for news and professional contexts |
| 🎵 대중문화 | Pop culture, traditional arts, K-drama, K-pop |
| 🏥 건강 | Health, traditional medicine, 화병 |
| 🌏 사회 | Modern Korean society — 빨리빨리, 헬조선, 재벌 |
| 📿 명절 | Holidays and rituals — 설날, 추석, 돌잔치, 결혼식 |
| 🗣 문장 | Real sentences for real conversations |

---

## Features

- **Smart timer** — color shifts green → yellow → red as you use up your time budget per word
- **Three difficulty levels** — 🌱 Easy (0.9s/char) · ⚡ Medium (0.55s/char) · 🔥 Hard (0.30s/char)
- **🔀 Shuffle mode** — randomizes the word list so you're never just memorizing order
- **▸ Context panel** — every term has a definition, a date, and a "why this matters for Korean Americans" note
- **Romanization toggle** — show or hide pronunciation guides
- **Personal best tracking** — records your fastest time per word, saved to local storage
- **Glossary tab** — browse all terms by category, tap to expand definitions
- **Keyboard tab** — full 두벌식 layout reference + setup instructions for iPhone and Windows
- **Offline PWA** — install once, works forever without internet

---

## Install on iPhone

1. Deploy to GitHub Pages (or any static host)
2. Open the URL in **Safari**
3. Tap the Share button → **Add to Home Screen**
4. Open it once on WiFi to cache everything
5. Works offline from then on

## Enable Korean keyboard on iPhone

Settings → General → Keyboard → Keyboards → Add New Keyboard → **Korean (2-Set)**

Tap the 🌐 globe key while typing to switch between English and Korean.

---

## Files

```
index.html      — the entire app (all vocab, logic, and styles in one file)
manifest.json   — PWA metadata (name, icon, theme color)
sw.js           — service worker for offline caching
```

Only `index.html` needs to be updated when making changes. `manifest.json` and `sw.js` are static.

---

## Who this is for

Korean Americans who grew up hearing Korean at home but never formalized it. You understand more than you can say. You know 밥 먹었어? is love, not a question about food. You freeze up when Korean relatives talk to you. This is the gap this trainer is designed to close.

---

## Built with

Vanilla HTML/CSS/JS · Noto Sans KR · IBM Plex Mono · No frameworks · No dependencies · No server
