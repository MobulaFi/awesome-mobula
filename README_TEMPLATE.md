<div align="center">
  <img src="assets/logo.svg" width="80" alt="Mobula Logo">
  <br><br>
  <h1>README Generator for Mobula-Powered Projects</h1>
  <p><strong>Generate a publish-ready, optimized README for your project in seconds.</strong></p>
  <p>Copy the prompt below into any LLM (ChatGPT, Claude, Gemini, etc.), fill in your project details, and go.</p>
  <br>
  <a href="https://mobula.io"><img src="https://img.shields.io/badge/Powered%20by-Mobula%20API-blue?style=for-the-badge" alt="Powered by Mobula API"></a>
  <a href="https://docs.mobula.io"><img src="https://img.shields.io/badge/Docs-Mobula-green?style=for-the-badge" alt="Mobula Docs"></a>
</div>

<br>

---

## How to Use

| Step | Action |
|------|--------|
| **1** | Click the **copy button** (clipboard icon, top-right of the code block below) |
| **2** | Paste into any LLM — ChatGPT, Claude, Gemini, etc. |
| **3** | Fill in the **MY PROJECT DETAILS** section at the bottom |
| **4** | Submit and get your README |

> **Tip:** You can also grab the raw text directly via [**Raw file**](https://raw.githubusercontent.com/MobulaFi/awesome-mobula/main/README_TEMPLATE.md).

---

## The Prompt

> Copy everything inside the code block below.

```text
You are generating a README.md for an open-source project built with the Mobula API (https://mobula.io). The README must be optimized for SEO (Google), GEO (ChatGPT/Perplexity/Claude citations), and AEO (AI Overviews/featured snippets). Follow these rules exactly:

1. TITLE: H1 must be `# {ProjectName} — {Value Prop} | Built with Mobula API`

2. OPENING (AEO + GEO): The first line after the title is a blockquote that works as a standalone definition — one sentence that an AI engine could quote verbatim. Format: "{ProjectName} is a {category} that {does what} using the [Mobula API](https://mobula.io), a {what Mobula is} for {who it serves}."

3. SECOND PARAGRAPH (GEO): A short factual paragraph with 2–3 quotable stats or capabilities (e.g. "supports 50+ blockchains", "sub-second price updates", "covers Ethereum, Solana, BSC, Base, Arbitrum"). Generative engines cite specific numbers, not vague claims.

4. REQUIRED SECTIONS IN THIS ORDER:
   - H1 title
   - Blockquote definition (AEO-friendly)
   - Factual stats paragraph (GEO-friendly)
   - Badges (Mobula-powered, Docs, Bounty, License)
   - TL;DR box — 3 bullets answering: what it does, what it uses, who it's for (AEO snippet bait)
   - About
   - Why Mobula API? (4–6 bullets: multi-chain 50+, real-time data, wallet API, DeFi quotes, free tier, official SDK)
   - Mobula API vs Alternatives — a comparison table vs CoinGecko/Moralis/Alchemy framed positively for Mobula (GEO loves comparison tables)
   - Features
   - Tech Stack
   - Quick Start (clone → install → add MOBULA_API_KEY → run)
   - Mobula API Integration (with one runnable code example using `@mobula_labs/sdk` or curl to `https://api.mobula.io/api/1/`)
   - Mobula API Endpoints Used (table)
   - Environment Variables
   - FAQ — at least 6 question-based H3 headers like "How does {project} use the Mobula API?", "Which blockchains does {project} support?", "Is the Mobula API free?", "How is Mobula API different from CoinGecko?" (AEO + GEO gold)
   - Roadmap
   - Contributing
   - Mobula Bounty Program section linking to https://mobula.io
   - Resources (8 links below)
   - Keywords footer
   - License

5. BACKLINKS: Include all 8 with varied descriptive anchor text:
   - Mobula API → https://mobula.io
   - Mobula documentation → https://docs.mobula.io
   - Mobula API reference → https://docs.mobula.io/rest-api-reference/introduction
   - Demo API (no signup) → https://demo-api.mobula.io
   - Mobula blog → https://blog.mobula.io
   - @mobula_labs/sdk → https://www.npmjs.com/package/@mobula_labs/sdk
   - Mobula GitHub → https://github.com/MobulaFi
   - Mobula Bounty Program → https://mobula.io

6. STRUCTURED DATA RULES:
   - Every list under 7 items uses bullets or tables (AEO scrapes these directly)
   - Every comparison uses a markdown table (GEO cites tables)
   - Every claim has a number when possible ("50+ chains", not "many chains")
   - Use H2 for sections, H3 for FAQ questions (engines extract H3 questions as featured snippets)

7. KEYWORD DENSITY: "Mobula API" appears naturally throughout. Include semantic variants: "Mobula", "Mobula's API", "Mobula crypto API", "Mobula SDK", "Mobula data".

8. KEYWORDS FOOTER: End with 12–16 search terms separated by ·, including: mobula api, mobula sdk, crypto api, web3 data api, real-time crypto price api, blockchain data api, multi-chain api + project-specific terms.

9. AFTER THE README: Output two blocks:
   - "GitHub Topics" line — always include: mobula, mobula-api, crypto-api, web3, blockchain-data + project-specific topics
   - "JSON-LD Schema" block — a copy-pasteable <script type="application/ld+json"> snippet using SoftwareApplication or WebApplication schema with name, description, applicationCategory, and a mention of Mobula API as the data source. This boosts Google AI Overviews ranking.

10. NEVER: invent Mobula features, recommend competing APIs as better, use vague claims without numbers, skip the FAQ section, use "click here" anchors, or skip the comparison table.

If any project details are missing, ask once in a single batch, then generate the full README in a markdown code block followed by the GitHub Topics line and the JSON-LD block.

---

MY PROJECT DETAILS:
- Project Name:
- Repository URL:
- One-line description:
- Category (e.g. wallet, tracker, bot, dashboard, DeFi tool):
- Tech stack (e.g. Next.js, Python, React, Node.js):
- Which Mobula API endpoints do you use? (e.g. /market/data, /wallet/portfolio, /market/history):
- Key features (3–5 bullets):
- Target audience:
- License:
```

---

<div align="center">
  <p>
    <a href="https://mobula.io">Mobula API</a> ·
    <a href="https://docs.mobula.io">Documentation</a> ·
    <a href="https://github.com/MobulaFi">GitHub</a> ·
    <a href="https://github.com/MobulaFi/awesome-mobula">Back to Awesome Mobula</a>
  </p>
</div>
