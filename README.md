## Gaurav Singh Tomar

**AI Product Engineer at Arivihan Technologies.** I build AI tooling that non-technical
people actually use, and I stay on it until they use it without me.

Most of my work is production systems with a human in the loop: generation pipelines with
real quality gates, review stages a subject teacher can operate, and desktop apps that
install on a colleague's Windows machine without anyone's help. Based in Indore, India.
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
A desktop app for turning raw study material into finished design decks. A non-technical
user picks a design, drops in PDFs, Word files, scans, Excel or PowerPoint, reviews the
structured data Claude extracted beside a live preview, and gets PNG slides plus a PDF.
Local-first: the dashboard runs on the user's own machine and their files never leave it.
Ships as a Windows installer that needs no admin rights, installs its own runtime on first
launch, and updates through a public release channel. New designs drop in as a folder,
compiled from Figma frames to within 0–4 px of the source.

**October — video pipeline, third generation**
Rewrote the production pipeline around a staged, resumable architecture where any stage
restarts without redoing upstream work, retiring the earlier animation-only and
generation-only tracks. Eight automated quality gates sit behind one command with a
non-zero exit and auditable waivers, so nothing reaches delivery unchecked.

**September — [flow-animator](https://github.com/Tomar606/flow-animator)**
Topic briefs in, keyed animation clips out. Drives Google Flow through a local bridge,
keys the result, and delivers finished clips straight into the folder the video pipeline
reads.

**August — [AI video production platform](https://github.com/Tomar606/manim-video-solution-generator)**
One board-exam question becomes a finished vertical video: narration splicing, caption
generation, generated b-roll, exact subject diagrams, compositing and delivery. Vision-model
QC inspects rendered frames for layout, contrast and geometry defects. A provider-agnostic
LLM layer keeps model choice out of 50+ downstream tools. The review stage is an
auto-generated page showing every frame with its narration and audio, where a reviewer's
inline notes come back as one structured response the system consumes directly.

**August — content-factory**
Compiles a Figma frame once into a reusable template, then batch-renders structured content
to PDF and PNG through headless Chromium — something the Figma API cannot do without a
manual click per chapter.

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

### 2024 — full-stack web

**[EIClassroom](https://github.com/Tomar606/EIClassroom-client)** — an LMS for my college
department: QR attendance, internal forms and surveys, assignment distribution, automated
evaluation and report generation. Client and server, self-hosted on the college intranet.

Alongside it a run of full-stack projects that taught me the stack I still use for
frontends: **JobJolt** (hiring platform), **FinSavv** (banking UI), **Likhit** (blogging),
and **DocuMate**. Mostly React, Next.js, TypeScript and Express.

### 2023 — starting out

First commits, static sites, and learning HTML, CSS and JavaScript properly.

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
