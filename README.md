<div align="center">

# Hi, I'm Paracci 👋

### I build practical software for real-world problems.

**Developer Tools** · **AI Systems** · **Security** · **Browser Extensions** · **Automation**

<br>

[![GitHub](https://img.shields.io/badge/GitHub-Paracci-181717?style=for-the-badge&logo=github)](https://github.com/Paracci)
![Status](https://img.shields.io/badge/Status-Actively%20Building-2ea44f?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-Useful%20Software-0969da?style=for-the-badge)

</div>

---

## 👨‍💻 About Me

I build software around problems that are **repetitive, difficult, or poorly solved**.

My work spans **developer tooling, browser extensions, automation systems, security-focused software, and AI-assisted infrastructure**. Most projects begin as something I personally want solved properly, then evolve into reusable tools with a strong focus on clarity, reliability, operator control, and practical value.

I am especially interested in systems where AI can assist decision-making **without replacing deterministic policy, explicit configuration, or human oversight**.

<br>

**What matters to me**

`Clarity` · `Reliability` · `Operator Control` · `Secure Defaults` · `Practical Value`

---

## 🚧 What I'm Building Now

### Paracci Moderation

![Status](https://img.shields.io/badge/status-in%20development-f59e0b?style=flat-square)
![Visibility](https://img.shields.io/badge/visibility-private-6e7681?style=flat-square)
![Type](https://img.shields.io/badge/type-hosted%20moderation%20platform-8250df?style=flat-square)

**Hosted moderation infrastructure for games, communities, forums, chat systems, and other user-generated-content products.**

The project is developed internally under the codename **JevSentinel** while transitioning from its original self-hosted API concept into the broader **Paracci Moderation** platform.

The platform is designed to combine semantic moderation, deterministic policy, trusted subject history, review workflows, analytics, maintained integrations, and a developer API without handing enforcement authority directly to the underlying semantic provider.

```text
Contextual Language Understanding
              ↓
Structured Moderation Signals
              ↓
Deterministic Policy + Trusted History
              ↓
Review / Decision / Integration Enforcement
```

Paracci Moderation uses TypeSafe Jev as an underlying semantic decision provider. Customer-facing moderation behavior remains operator-controlled.

**Current foundation**

`TypeScript` · `Node.js 24` · `Fastify` · `Next.js` · `React`  
`PostgreSQL` · `Zod` · `OpenAPI 3.1` · `TypeSafe Jev`

<sub>Private development · Hosted moderation infrastructure · Provider-neutral customer-facing design</sub>

---

## ✨ Featured Projects

<p align="center">
  A selection of tools and systems I've designed, built, and actively developed.
</p>

### Primary Work

<table>
<tr>
<td width="50%" valign="top">

### 🔐 [Paracci Secure Messaging](https://github.com/Paracci/paracci-msg)

<sub>OFFLINE SECURITY SOFTWARE</sub>

<br>

Serverless, offline-first desktop software for secure two-party encrypted file exchange without external network or account dependencies.

It uses authenticated `.paracci` envelopes, local replay protection, hybrid post-quantum key exchange, and platform-native credential protection.

<br>

`Python` · `Flask` · `pywebview`  
`X25519` · `ML-KEM-768` · `Ed25519`  
`ChaCha20-Poly1305` · `HKDF` · `Argon2id`

<br>

[**Explore project →**](https://github.com/Paracci/paracci-msg)

</td>
<td width="50%" valign="top">

### 🌳 [AITree](https://github.com/Paracci/aitree)

<sub>DEVELOPER TOOL</sub>

<br>

Generate clean, AI-friendly project maps from local directories or GitHub repositories, with live watching, a web UI, and native MCP integration.

<br><br><br><br>

`Python` · `MCP` · `watchdog`  
`tiktoken` · `gitpython`

<br><br>

[**Explore project →**](https://github.com/Paracci/aitree)

</td>
</tr>
</table>

<br>

### Browser Tools

<table>
<tr>
<td width="50%" valign="top">

### ▶️ [YouTube Shorts Channel Blocker & Ultimate Downloader](https://github.com/Paracci/youtube-shorts-blocker)

<sub>PRIVACY-FOCUSED BROWSER EXTENSION</sub>

<br>

A Chrome MV3 extension for local channel filtering, Shorts cleanup, best-effort ad handling, and high-quality media downloads through an optional native `yt-dlp` + verified `ffmpeg` companion workflow.

<br>

`JavaScript` · `CSS` · `Chrome Extension MV3`  
`Native Messaging` · `yt-dlp` · `ffmpeg`

<br>

[**Explore project →**](https://github.com/Paracci/youtube-shorts-blocker)

</td>
<td width="50%" valign="top">

### 𝕏 [X (Twitter) Auto Ad Blocker](https://github.com/Paracci/x-auto-ad-blocker)

<sub>BROWSER AUTOMATION</sub>

<br>

Detects sponsored posts in real time and lets users either hide them locally or automatically block the advertiser's account on X, with built-in media downloads and multilingual UI support.

<br><br>

`JavaScript` · `CSS` · `Chrome Extension MV3`

<br>

[**Explore project →**](https://github.com/Paracci/x-auto-ad-blocker)

</td>
</tr>
</table>

<br>

### Automation & Localization

<table>
<tr>
<td valign="top">

### 🇹🇷 [Facepunch Wiki Turkish Translation Project](https://github.com/Paracci/facepunch-wiki-tr)

<sub>AUTOMATION · AI · DOCUMENTATION</sub>

<br>

An automated translation and update system for Facepunch documentation covering **Garry's Mod, Rust, Steamworks, and the general Facepunch wiki**, while protecting code blocks, function names, API parameters, HTML structures, and other technical content during translation.

<br>

`Python` · `Node.js` · `Gemini` · `DeepL` · `NLLB-200` · `CTranslate2`

<br>

[**Explore project →**](https://github.com/Paracci/facepunch-wiki-tr)

</td>
</tr>
</table>

---

## 🧪 In Development

### Deep-Angler-Fish V2

**Security research platform for internet asset discovery and external attack-surface observation.**

![Status](https://img.shields.io/badge/status-private%20development-f59e0b?style=flat-square)
![Launch](https://img.shields.io/badge/public%20launch-not%20enabled-6e7681?style=flat-square)
![Area](https://img.shields.io/badge/area-security%20research-d1242f?style=flat-square)

V2 is under private development with public launch kept explicitly disabled while engineering, validation, and readiness work continues.

Its architecture emphasizes authoritative state, bounded distributed processing, disposable search projections, fail-closed rate control, and explicit operational guardrails.

### Architecture Direction

`Authoritative state` · `Bounded delivery` · `Disposable projections` · `Fail-closed rate control` · `Explicit control-plane boundaries`

### Research & Observation Scope

`Certificate Transparency` · `DNS` · `TCP` · `TLS` · `HTTP`  
`Change Detection` · `Alerts` · `Network-Location Intelligence`

### Architecture Priorities

`Tenant Isolation` · `RBAC/RLS` · `Auditability` · `Idempotency` · `Bounded Retries` · `Cancellation` · `Fail-Closed Behavior`

<sub>Private development · Public launch not enabled</sub>

---

## 🧰 Tech I Work With

| Area | Technologies |
| --- | --- |
| **Languages** | TypeScript · JavaScript · Python · Go |
| **Backend & Web** | Node.js · Fastify · FastAPI · Next.js · React |
| **Data & Infrastructure** | PostgreSQL · Redis · RabbitMQ · OpenSearch · Docker |
| **APIs & Standards** | OpenAPI 3.1 · JSON Schema · MCP |
| **Security & Crypto** | Ed25519 · X25519 · ML-KEM-768 · ChaCha20-Poly1305 · Argon2id |
| **Browser Tooling** | Chrome Extension MV3 · Native Messaging |
| **Developer Workflow** | Git · GitHub · Automation tooling |

---

## 🔎 Areas of Interest

### 🧠 AI & Decision Systems
Context-aware moderation · structured AI outputs · evaluation · guardrails · human-review workflows · deterministic policy layers

### 🛠 Developer Tooling
Developer experience · project automation · AI-assisted workflows · MCP · open standards · interoperable systems

### 🛡 Security & Resilient Systems
Secure defaults · auditability · attack-surface research · predictable failure modes · operator control

### 🌐 Browser & Web Automation
Browser extensions · native integrations · content workflows · quality-of-life tooling · user-controlled automation

---

## 🧭 How I Build

> **Practical over ornamental.**  
> Solve the real problem first.

> **Explicit over implicit.**  
> Configuration and behavior should be understandable.

> **Operator control over black-box automation.**  
> Especially for high-impact decisions.

> **Secure defaults.**  
> Systems should fail safely where possible.

> **Reusable by design.**  
> Personal tools should be able to grow into dependable software.

---

## 🤝 Connect

<div align="center">

The best place to follow my work, explore source code, report issues, or start a technical discussion is GitHub.

<br><br>

[![Visit GitHub](https://img.shields.io/badge/Visit%20GitHub-Paracci-181717?style=for-the-badge&logo=github)](https://github.com/Paracci)

<br><br>

**Build useful things. Keep them understandable.**

<sub>Developer Tools · AI Systems · Security · Automation</sub>

</div>
