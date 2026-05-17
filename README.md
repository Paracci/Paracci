# Hi, I'm Paracci 👋

I build tools that fix annoying things: browser extensions, automation systems, and large-scale translation infrastructure. Most of what I make started as a personal itch I couldn't stop scratching. A lot of it ended up as open source.

### 🛠️ Featured Projects

* [**Paracci Secure Messaging**](https://github.com/Paracci/paracci-msg) A 100% offline, AI-resistant secure messaging application built around `.paracci` envelope files, hardware-calibrated Argon2id time-locks, and cryptographic sovereignty. Features a native desktop UI via Flask + pywebview, a self-inspecting integrity sentinel that triggers an automatic shutdown on tampering, native OS-level anti-screenshot protection, single-use burn tracking, and RAM-safe decrypted message handling. Source-available for independent security auditing.
  *Stack: Python, Flask, pywebview, Cryptography (Ed25519, XChaCha20-Poly1305, Argon2id), Windows/Linux/macOS Native APIs*

* [**YouTube Shorts Channel Blocker & Ultimate Downloader**](https://github.com/paracci/youtube-shorts-blocker) A full-featured quality-of-life extension I use daily. One-click channel blocking, automatic ad muting and skipping, Shorts shelf removal, and a dual-mode video downloader with a native yt-dlp companion app for 4K/1080p and MP3 downloads. Fully wired settings panel, real-time toggle integration, a native host setup page, and full 11-language UI support, all styled to match YouTube's exact design language.
  *Stack: JavaScript, CSS, Chrome Extension V3 (MutationObserver, IntersectionObserver, Native Messaging)*

* [**X (Twitter) Auto Ad Blocker**](https://github.com/paracci/x-auto-ad-blocker) A lightweight Chrome extension I built for my daily browsing. Unlike traditional blockers that just hide elements with CSS, this extension mimics user interaction to permanently block the advertiser's account in the background. Because the account itself is blocked, your feed stays ad-free across all your devices. Also includes a media downloader for videos, GIFs, and images, and full 11-language UI support.
  *Stack: JavaScript, CSS, Chrome Extension V3 (MutationObserver)*

* [**AITree - Project File Map Generator**](https://github.com/paracci/aitree) Scans any directory (or GitHub repo — no cloning required) and prints a clean, annotated file tree you can paste straight into any AI chat. Comes with a web UI, a live-watch mode, and a full [MCP server](https://modelcontextprotocol.io) so AI assistants like Claude can call it as a tool and read your files directly — without leaving the conversation.
  *Stack: Python, MCP (Model Context Protocol), watchdog, tiktoken, gitpython*

* [**LDR - Logo Dynamic Redirect**](https://github.com/paracci/ldr) An open standard for turning any brand logo into a smart, context-aware gateway. Like QR - but branded, intelligent, and updatable. Same logo, different people, different destinations. Includes a perceptual hashing engine, registry mock server, Web SDK, Node.js SDK, and an interactive demo. 68 tests, 0 failures.
  *Stack: JavaScript, Node.js, Perceptual Hashing (pHash/aHash/dHash), Open Standard (MIT)*

* [**Facepunch Wiki Turkish Translation Project**](https://github.com/Paracci/facepunch-wiki-tr) A massive automated translation system that keeps Facepunch (Garry's Mod, Rust, Steamworks) wikis up to date in Turkish. Uses a triple-layer hybrid AI model (Google Gemini, DeepL, and local nllb-200) to process 8,000+ pages while protecting technical elements like code blocks, function names, and HTML structures during translation.
  *Stack: Python, Node.js, Vanilla JS, Custom AI Validation*

### 🔒 In Development

* **AutoStudio** *(private)* A visual Chrome extension for building, editing, and testing web automation flows without writing code. Record browser interactions, edit them in a node-based flow canvas, and export to Playwright or Selenium.
  *Stack: TypeScript, React 18, Vite, React Flow, Vitest*

* **Deep-Angler-Fish** *(private)* A Shodan-style internet scanning and vulnerability analysis engine. Distributed microservices architecture with multi-protocol support (HTTP, SSH, RDP, SCADA/ICS), Nuclei/ZAP integration, CVE matching via NVD, and OCR on captured screenshots.
  *Stack: Python, Go, Elasticsearch, RabbitMQ, Docker*

### 💻 Tech Stack & Interests

* **Languages:** JavaScript, TypeScript, Python, Go, HTML/CSS
* **Backend & Tools:** Node.js, Express, FastAPI, Docker
* **Focus Areas:** Browser Extensions, DOM Manipulation, AI Automation & Translation Systems, Web Security Research, SPA Development, Open Standards
