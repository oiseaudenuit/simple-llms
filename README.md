> [!IMPORTANT]
> **Simple LLMS is sunset and this repository is archived.**
> As Shopify shifts toward native agentic commerce — where stores expose their catalogs to AI agents directly — a standalone `llms.txt` layer is no longer necessary. The app is no longer maintained or distributed. The code remains here as a past project.

<div align="center">

<img src="assets/icon.png" alt="Simple LLMS" width="96" height="96" />

# Simple LLMS

**Your catalog, legible to every AI.**

A Shopify app that auto-generated `llms.txt` and `llms-full.txt` for any store — turning products, collections, pages, and policies into a structured map that AI assistants could parse in one read, instead of scraping raw HTML.

Built on Cloudflare Workers · Made by [ODN-io](https://github.com/oiseaudenuit)

<img src="assets/hero.jpg" alt="Simple LLMS — your catalog, legible to every AI" />

</div>

---

## Why it's sunset

Simple LLMS was built for a web where AI assistants crawled raw HTML and needed a hand-curated `llms.txt` map to understand a catalog. That gap is closing: Shopify is moving toward **native agentic commerce**, where stores expose structured catalog and checkout data to AI agents directly, through the platform itself. A bolt-on `llms.txt` layer no longer adds enough on top of that to justify maintaining a standalone app.

The repository stays public and archived as a record of the build.

---

## The problem it solved

When a shopper asked ChatGPT, Claude, or Perplexity *"where can I buy [product]?"*, the AI did not crawl your beautifully designed Shopify storefront. It read raw HTML — ads, navigation, theme markup, all of it — and gave up before it understood what you actually sold.

Simple LLMS auto-generated `llms.txt` and `llms-full.txt` for any Shopify store and served them through the app proxy, so AI assistants got a clean, structured map of your catalog instead.

- One-click install — no theme edits, no copy-paste, no maintenance
- Auto-synced every day — always reflected the current catalog
- Real-time analytics — see exactly which AI bots were reading your store

---

## Features

### 🧬 Business DNA — tell AI who you really are

<img src="assets/business-dna.jpg" alt="Business DNA — structured brand profile" />

A structured profile of your brand — identity, languages, channels, and story — pulled from Shopify and shaped into signals every AI assistant could quote with confidence.

- Brand identity, description & AI-written brand story
- Default + secondary languages for global reach
- Sales channels, social handles & custom sections

---

### 🎛️ Granular Control — decide what AI sees, item by item

<img src="assets/granular-control.jpg" alt="Granular Control — per-item include/exclude" />

Every product, collection, page, and article — toggled in or out with one click. Write custom AI descriptions, or schedule what's surfaced when.

- Per-item Include / Exclude with live status badges
- AI-written or hand-crafted descriptions per item
- Search, filters & scheduling rules for seasonal control

---

### 📊 AI Visibility — see which AI reads your store

<img src="assets/ai-visibility.jpg" alt="AI Visibility — analytics dashboard" />

Every request to your `llms.txt` was logged and classified — so you finally knew whether ChatGPT, Claude, or Perplexity was actually pulling your catalog.

- Total visits, AI visits & AI discovery rate at a glance
- Visits broken down by AI assistant — ChatGPT, Claude, Perplexity, Gemini, Copilot
- Per-visit log with file, country & timestamp

---

## About

Simple LLMS started as an internal tool to make my own Shopify store readable to AI assistants — then turned into something I believed every Shopify merchant would need. Agentic commerce arrived faster than the gap it filled, and the project is now retired.

If you want to chat about the build, the AI-SEO space, or commerce + LLMs in general — [reach out](https://github.com/oiseaudenuit).

---

<div align="center">

© 2026 ODN-io. All rights reserved.

</div>
