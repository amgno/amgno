# Hi! 👋

I'm Alessandro Magnocavallo, a developer with a background in Communication Design from Politecnico di Milano. I focus on bridging design thinking with technical implementation, specializing in AI integration and prompt engineering.

I work mainly with **JavaScript**, **Python**, **HTML**, and **CSS**, building tools that leverage LLMs in practical applications. My primary development tools are **Claude Code** and **Cursor**.

## Featured Projects

### [Cornocopia](https://github.com/amgno/cornocopia) — AI-Powered Music Player

A web-based music player with an iTunes-inspired interface, featuring intelligent playlist generation and track recommendations.

**AI Implementation:**
- **Playlist Generation:** Sends complete library metadata to Claude API with structured prompts that analyze musical coherence, genre compatibility, temporal cohesion, and energy characteristics. The AI creates thematic playlists while avoiding album-centric grouping.
- **AI Next Song:** Predictive track selection that preloads recommendations 20 seconds before the current track ends. Uses weighted sampling (50% genre match, 30% decade match, 20% random) to optimize API token usage for large libraries.
- **Caching Strategy:** Playlists cached for 7 days with MD5 hash invalidation on library changes. Next song selections cached 24 hours with 60-75% expected hit rate.
- **Fallback System:** Deterministic algorithms activate when API is unavailable, maintaining functionality without AI.

**Stack:** React, Express.js, Anthropic SDK, Docker

---

### [Photography Portfolio](https://github.com/amgno/photos) — AI-Tagged Image Gallery

A static photography portfolio with client-side semantic search powered by AI-generated metadata.

**AI Implementation:**
- **Automated Tagging Pipeline:** Python script (`tag_photos.py`) processes the image library through Vision AI models, generating structured JSON metadata for each photograph.
- **Extracted Taxonomies:** Photography style and technique, lighting conditions, scene context, object detection with confidence scores, and dominant color palette (HEX codes with coverage percentages).
- **Semantic Search:** Client-side search indexes all metadata on page load, supporting both structured queries (`style:street`, `lighting:golden hour`) and free-text search against AI-generated descriptions.

**Stack:** Jekyll, Vanilla JavaScript, Python, Vision AI

---

### [FinanceBro](https://github.com/amgno/financebro) — Stock Analysis Telegram Bot

A Telegram bot for automated financial analysis and portfolio management, deployed on Cloudflare Workers.

**AI Implementation:**
- **Multi-Step Analysis:** The `/analyze` command triggers Claude 3.5 Sonnet to collect market data via Tool Use, then generates structured reports covering fundamental analysis, technical analysis, and weighted scoring (Technical 35%, Fundamentals 30%, Sector 20%, Sentiment 15%).
- **Natural Language Parsing:** Accepts both structured commands (`/buy AAPL 150 10`) and conversational input ("I bought 10 Apple shares at 150 dollars"). AI parses intent when pattern matching fails.
- **Durable Objects:** Background processing via Cloudflare Alarms handles long-running AI executions without timeout issues.

**Stack:** Cloudflare Workers, Durable Objects, Anthropic API, Financial Modeling Prep API

---

### [Personal Website](https://github.com/amgno/amagno.github.io)

Minimal landing page hosted on GitHub Pages at [a.magno.me](https://a.magno.me).

## Certifications

**Google**
- UX Design

**Anthropic**
- AI Fluency: Framework & Foundations
- Building with the Claude API
- Claude Code in Action

## Links

- 🌐 [Personal Website](https://a.magno.me)
- 📸 [University Portfolio](https://a.magno.me/portfolio/)

## Get in Touch

📧 ale@magno.me
