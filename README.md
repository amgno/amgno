# Hi! 👋

I'm Alessandro Magnocavallo, a developer with a background in Communication Design from Politecnico di Milano. I focus on bridging design thinking with technical implementation, specializing in AI integration and prompt engineering.

### Languages & Tools

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=anthropic&logoColor=white) ![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat&logo=cursor&logoColor=white)

---

## Featured Projects

### [Cornocopia](https://github.com/amgno/cornocopia) — AI-Powered Music Player

> A web-based music player with an iTunes-inspired interface, featuring intelligent playlist generation and track recommendations.

**AI Implementation:**
- **Playlist Generation:** Sends complete library metadata to Claude API with structured prompts that analyze musical coherence, genre compatibility, temporal cohesion, and energy characteristics. The AI creates thematic playlists while avoiding album-centric grouping.
- **AI Next Song:** Predictive track selection that preloads recommendations 20 seconds before the current track ends. Uses weighted sampling (50% genre match, 30% decade match, 20% random) to optimize API token usage for large libraries.
- **Caching Strategy:** Playlists cached for 7 days with MD5 hash invalidation on library changes. Next song selections cached 24 hours with 60-75% expected hit rate.
- **Fallback System:** Deterministic algorithms activate when API is unavailable, maintaining functionality without AI.

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black) ![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white) ![Anthropic](https://img.shields.io/badge/Anthropic_SDK-D97757?style=flat&logo=anthropic&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

---

### [Photography Portfolio](https://github.com/amgno/photos) — AI-Tagged Image Gallery

> A static photography portfolio with client-side semantic search powered by AI-generated metadata.

**AI Implementation:**
- **Automated Tagging Pipeline:** Python script (`tag_photos.py`) processes the image library through Vision AI models, generating structured JSON metadata for each photograph.
- **Extracted Taxonomies:** Photography style and technique, lighting conditions, scene context, object detection with confidence scores, and dominant color palette (HEX codes with coverage percentages).
- **Semantic Search:** Client-side search indexes all metadata on page load, supporting both structured queries (`style:street`, `lighting:golden hour`) and free-text search against AI-generated descriptions.

![Jekyll](https://img.shields.io/badge/Jekyll-CC0000?style=flat&logo=jekyll&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

---

### [FinanceBro](https://github.com/amgno/financebro) — Stock Analysis Telegram Bot

> A Telegram bot for automated financial analysis and portfolio management, deployed on Cloudflare Workers.

**AI Implementation:**
- **Multi-Step Analysis:** The `/analyze` command triggers Claude 3.5 Sonnet to collect market data via Tool Use, then generates structured reports covering fundamental analysis, technical analysis, and weighted scoring (Technical 35%, Fundamentals 30%, Sector 20%, Sentiment 15%).
- **Natural Language Parsing:** Accepts both structured commands (`/buy AAPL 150 10`) and conversational input ("I bought 10 Apple shares at 150 dollars"). AI parses intent when pattern matching fails.
- **Durable Objects:** Background processing via Cloudflare Alarms handles long-running AI executions without timeout issues.

![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat&logo=cloudflare&logoColor=white) ![Anthropic](https://img.shields.io/badge/Anthropic_API-D97757?style=flat&logo=anthropic&logoColor=white) ![Telegram](https://img.shields.io/badge/Telegram_Bot-26A5E4?style=flat&logo=telegram&logoColor=white)

---

### [Personal Website](https://github.com/amgno/amagno.github.io)

> Minimal landing page hosted on GitHub Pages at [a.magno.me](https://a.magno.me).

![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat&logo=github&logoColor=white)

---

## Certifications

| Provider | Certification |
|----------|---------------|
| ![Google](https://img.shields.io/badge/Google-4285F4?style=flat&logo=google&logoColor=white) | UX Design |
| ![Anthropic](https://img.shields.io/badge/Anthropic-D97757?style=flat&logo=anthropic&logoColor=white) | AI Fluency: Framework & Foundations |
| ![Anthropic](https://img.shields.io/badge/Anthropic-D97757?style=flat&logo=anthropic&logoColor=white) | Building with the Claude API |
| ![Anthropic](https://img.shields.io/badge/Anthropic-D97757?style=flat&logo=anthropic&logoColor=white) | Claude Code in Action |

---

## Connect

[Website](https://a.magno.me)

[University Portfolio](https://a.magno.me/portfolio/)

[ale@magno.me](mailto:ale@magno.me)
