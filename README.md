## Gaurav Singh Tomar

**AI Product Engineer at Arivihan Technologies.** I build AI tooling that non-technical
people actually use, and I stay on it until they use it without me.

Most of my work is production systems with a human in the loop: generation pipelines with
enforced quality gates, review stages a subject specialist can operate, and desktop software
distributed to non-technical users across Windows and macOS. Based in Indore, India.
Open to remote.

---

### Now

Building the internal AI toolkit at Arivihan: **20+ agent tools used by 200+ staff**,
covering spec authoring, analytics instrumentation, dashboard generation and content
pipelines, distributed as a synced plugin so improvements reach everyone at once.

Also running the AI video production platform that has shipped **800+ educational videos**
across four state boards in Hindi and English medium.

---

## Timeline

### 2026 — AI systems and shipped products

**October — [Design Automater](https://github.com/Tomar606/design-automater-releases)**
A desktop application that converts unstructured source material into finished,
design-consistent deliverables. A user selects a design, submits PDFs, Word files, scans,
Excel or PowerPoint, reviews the structure extracted by Claude against a live preview, and
exports print-ready PNG slides and PDFs. Built on a privacy-preserving architecture:
documents are processed on the user's own device and only extracted content reaches the
model provider. Distributed across Windows and macOS through a managed update channel, with
designs compiled from Figma source to within 0–4 px and extended without code changes.

**October — video pipeline, third generation**
Rewrote the production pipeline around a staged, resumable architecture where any stage
restarts without redoing upstream work, retiring the earlier animation-only and
generation-only tracks. Eight automated quality gates sit behind one command with a
non-zero exit and auditable waivers, so nothing reaches delivery unchecked.

**August — [AI video production platform](https://github.com/Tomar606/manim-video-solution-generator)**
One board-exam question becomes a finished vertical video: narration splicing, caption
generation, generated b-roll, exact subject diagrams, compositing and delivery. Vision-model
QC inspects rendered frames for layout, contrast and geometry defects. A provider-agnostic
LLM layer keeps model choice out of 50+ downstream tools. The review stage is an
auto-generated page showing every frame with its narration and audio, where a reviewer's
inline notes come back as one structured response the system consumes directly.

**August — content-factory**
Deterministic document rendering at batch scale. Design source compiles once into a
versioned template, after which structured content renders to print-ready PDF and PNG with
reproducible, diffable output and no manual step per document.

**July — PawDesk**
A macOS desktop companion in Swift. A click-through, always-on-top pet driven by a
weighted-random behaviour engine, with emotional state and three personalities that bias
its weights. Persisted with SwiftData, monetised with StoreKit 2, packaged for the Mac
App Store.

**January — joined Arivihan Technologies** as an AI Product Engineer intern; full-time
from April.

### 2025 — moving to Python and AI

**OnTry** and a shift out of full-stack web into Python, LLM APIs and pipeline work. This
is the year the focus changed from building web apps to building systems that produce
things.

### 2023–2024 — full-stack foundations

A run of full-stack projects in React, Next.js, TypeScript and Express — hiring platforms,
banking interfaces, publishing tools and document systems — that built the frontend stack
I still use today.

---

## Stack

| | |
|---|---|
| **AI** | Claude · OpenAI · Gemini · LangChain · LangGraph · tool calling · structured outputs · RAG · pgvector · multi-agent orchestration · vision-model QC · LLM-as-judge evals |
| **Backend** | Python · FastAPI · Pydantic · Node.js · Electron · PostgreSQL · Redis · SSE streaming |
| **Frontend** | Next.js · React · TypeScript · Tailwind · Swift / AppKit |
| **Media** | ffmpeg · Whisper · ElevenLabs · Google Veo / Flow · Manim · headless rendering |
| **Ops** | Docker · Git · GitHub Actions · Vercel · desktop packaging and auto-update channels |

---

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Tomar606&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&theme=graywhite" height="150" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=Tomar606&layout=compact&langs_count=6&hide_border=true&theme=graywhite" height="150" alt="Top languages" />
</div>

<div align="center">
  <a href="mailto:gstomar606@gmail.com">gstomar606@gmail.com</a> ·
  <a href="https://linkedin.com/in/gaurav-singh-tomar-046a6a26a">LinkedIn</a>
</div>
