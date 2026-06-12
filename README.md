# Memory Palace

<p align="center">
  <a href="https://github.com/alphatech-vn"><img src="https://img.shields.io/badge/Back%20to-AlphaTech%20Hub-1b1713?style=for-the-badge&logo=github&logoColor=white" alt="Back to AlphaTech Hub"></a>
</p>

<p align="center">
  <a href="https://memorypalace.alphatech.ai.vn/"><img src="assets/screenshots/01-dashboard.png" alt="Memory Palace dashboard" width="100%"></a>
</p>

<p align="center">
  <strong>Turn scattered files into a knowledge base you can actually reuse.</strong>
</p>

<p align="center">
  Memory Palace is a local-first AI knowledge workspace for people who read a lot, collect a lot,
  and are tired of starting from a blank prompt every time.
</p>

<p align="center">
  <img alt="Platform" src="https://img.shields.io/badge/Platform-Windows%2010%2F11-0F766E?style=flat-square">
  <img alt="Workflow" src="https://img.shields.io/badge/Workflow-Local--first%20Markdown-1D4ED8?style=flat-square">
  <img alt="Trial" src="https://img.shields.io/badge/Trial-15%20days-F59E0B?style=flat-square">
  <img alt="License" src="https://img.shields.io/badge/License-Commercial-7C3AED?style=flat-square">
</p>

<p align="center">
  <strong>Read in English</strong> |
  <a href="README.vi.md"><strong>Đọc bằng tiếng Việt</strong></a>
</p>

<p align="center">
  <a href="https://memorypalace.alphatech.ai.vn/"><strong>Landing Page</strong></a>
  |
  <a href="SUPPORT.md"><strong>Support</strong></a>
  |
  <a href="docs/FAQ.md"><strong>FAQ</strong></a>
</p>

## The Big Shift

Most AI tools still begin with the same ritual:

- Open a chat box,
- Paste messy source material,
- Get a decent answer once,
- Lose the structure,
- Repeat the work next week.

Memory Palace changes that loop.

You drop in documents, web pages, videos, repositories, and scans. The app compiles them into a clean Markdown wiki on your own machine. Then you can query it, review it, and generate outputs from it again and again.

The "wow" is not just that AI answers you.  
The "wow" is that your source material becomes a reusable workspace instead of a one-off conversation.

> From one-off prompting to a repeatable knowledge engine.

## Why It Feels Different

1. **Collect** messy source material.
2. **Compile** it into linked knowledge.
3. **Reuse** that knowledge for reports, slides, charts, canvases, and Q&A.

This repository is a public product-information and support hub for the commercial Windows desktop app by AlphaTech. It does not contain the application source code.

## What You Get

- `📥` Ingest PDFs, DOCX, TXT/Markdown, websites, YouTube, GitHub repositories, and scanned documents
- `🧠` Compile raw material into structured Markdown notes with concepts, topics, summaries, and links
- `💬` Ask questions against your compiled knowledge instead of rebuilding context every time
- `🪄` Generate reports, slide decks, PPTX, charts, and Canvas boards from the same knowledge base
- `📂` Keep outputs as portable files you can still use outside the app

## At A Glance

- `🏠` Local-first knowledge workspace on Windows
- `📝` Plain Markdown outputs you can keep and reuse
- `🔗` Obsidian-friendly workflow
- `🔍` OCR for PDFs, images, and scanned documents
- `🎬` YouTube ingest with robust caption retrieval
- `🗣️` Optional speech-to-text fallback for videos without usable captions
- `🧩` AI Skills for reports, slide decks, PPTX, charts, Canvas boards, research, review, and query workflows

## Visual Tour

<p align="center">
  <img src="assets/screenshots/02-chat.png" alt="Chat workspace" width="32%">
  <img src="assets/screenshots/03-wiki-graph.png" alt="Knowledge graph" width="32%">
  <img src="assets/screenshots/06-report.png" alt="Report output" width="32%">
</p>

<p align="center">
  <img src="assets/screenshots/07-slides.png" alt="Slides output" width="32%">
  <img src="assets/screenshots/08-chart.png" alt="Chart output" width="32%">
  <img src="assets/screenshots/09-canvas.png" alt="Canvas output" width="32%">
</p>

## Who It Is For

- `🎓` Students and researchers who accumulate messy source material
- `🧑‍💼` Analysts, consultants, and knowledge workers who need repeatable output
- `✍️` Writers and creators who want durable context, not disposable chat threads
- `📚` Obsidian users who want a stronger ingest-and-structure layer

## What Memory Palace Does

- Ingests PDFs, DOCX, TXT/Markdown, web pages, YouTube videos, GitHub repositories, and scanned documents
- Compiles raw material into structured Markdown notes with links, summaries, concepts, and topics
- Lets you ask questions against that compiled knowledge instead of prompting from scratch every time
- Generates outputs from the curated wiki: reports, slide decks, PPTX, charts, and Canvas boards
- Saves outputs as files you can open outside the app: Markdown, HTML, PPTX, `.canvas`, and images

## Why It Exists

Memory Palace is not trying to replace ChatGPT, Claude, Obsidian, or Notion.

It exists for a narrower and more practical problem:

> "I already have the source material. I want a reliable way to turn it into structured knowledge and useful outputs without rebuilding context every time."

If that sounds familiar, this product will feel immediately different from a general chat app.

## Why People Remember It

- `✨` It makes AI feel less disposable
- `🧭` It turns source chaos into a repeatable workflow
- `🏗️` It gives you structure before generation, not after
- `💡` It creates an "I can build on this later" feeling instead of "I need to redo this tomorrow"

## Product Boundaries

### Shipped now

- Windows 10/11 desktop app
- Local-first vault with standard Markdown outputs
- Obsidian-friendly workflow
- PDF/image OCR pipeline
- YouTube ingest with robust caption retrieval
- Optional speech-to-text fallback for videos without captions
- AI Skills for reports, slides, PPTX, charts, Canvas, research, review, and query workflows

### Important caveats

- Memory Palace is not a cloud note app
- Memory Palace is not a team collaboration or cloud sync product
- The app can call external AI providers that you configure
- Some network activity is expected for source fetching, license/update checks, and provider API calls
- macOS is not public-ready yet

## Privacy Model

Memory Palace is local-first:

- Your raw files, compiled wiki, and generated outputs live on your machine
- Notes are plain files, not locked into a proprietary database
- The app does not upload your document library to AlphaTech servers

What may leave your machine:

- Prompts/content sent to the LLM provider you choose
- Source fetching from websites, YouTube, or GitHub when you ingest remote content
- License/update traffic required to run the desktop product

See [docs/PRIVACY.md](docs/PRIVACY.md) for the short public privacy summary.

## Obsidian Relationship

Memory Palace works well with Obsidian, but it does not try to replace it.

- Memory Palace: ingest, compile, structure, generate
- Obsidian: read, edit, link, sync, and continue working with the resulting files

Outputs are Markdown and Canvas artifacts that stay useful even if you stop using the app.

## Availability

- Platform: Windows 10/11 x64
- Trial: 15 days, full features
- Current public offer: Lifetime Personal - `1,250,000 VND`
- Refund: 30 days
- Purchase/support path: direct contact via landing page, Zalo, Telegram, or email

Landing page:

- https://memorypalace.alphatech.ai.vn/

## 3-Step Getting Started

1. **Collect** your source material: documents, links, videos, repositories, or scans.
2. **Compile** it into a structured local Markdown knowledge base.
3. **Generate** reports, slides, charts, canvases, or answers from that reusable knowledge.

## Start Here

- `🌐` Landing page: https://memorypalace.alphatech.ai.vn/
- `🛟` Support guide: [SUPPORT.md](SUPPORT.md)
- `❓` FAQ: [docs/FAQ.md](docs/FAQ.md)
- `🗺️` Roadmap: [docs/ROADMAP.md](docs/ROADMAP.md)

## Support

- Email: `alphatech.digitolead@gmail.com`
- Zalo: `https://zalo.me/0908695494`
- Telegram: `https://t.me/84908695494`

## Start Your Trial

<p align="center">
  <strong>Ready to turn scattered files into a reusable knowledge engine?</strong><br>
  Start with the 15-day full-feature trial, or contact AlphaTech directly for purchase and support.
</p>

<p align="center">
  <a href="https://memorypalace.alphatech.ai.vn/"><strong>Open Landing Page</strong></a>
  |
  <a href="SUPPORT.md"><strong>Contact Support</strong></a>
</p>

## Closed-Source Notice

Memory Palace is a commercial closed-source desktop product by AlphaTech.

This repository exists to:

- explain the product
- show current capabilities
- publish screenshots and public docs
- provide support and security contact paths

It does not include:

- application source code
- installer binaries
- private infrastructure
- license secrets
- customer data

## Repository Scope

This repo should stay limited to public-facing material:

- product overview
- FAQ
- privacy summary
- roadmap
- support/security contacts
- screenshots

If a future release flow uses GitHub Releases, that decision should be explicit and documented separately.
