<div align="center">

# Gaurav Singh Tomar

**AI Product Engineer**

<img src="https://img.shields.io/badge/Indore,_India-3D5A50?style=flat-square" alt="Indore, India" />
<img src="https://img.shields.io/badge/Open_to_Remote-C0562A?style=flat-square" alt="Open to Remote" />
<a href="mailto:gstomar606@gmail.com"><img src="https://img.shields.io/badge/Email-D9A441?style=flat-square" alt="Email" /></a>
<a href="https://linkedin.com/in/gaurav-singh-tomar-046a6a26a"><img src="https://img.shields.io/badge/LinkedIn-0C0E0B?style=flat-square" alt="LinkedIn" /></a>

</div>

<br />

I build AI tooling that non-technical people actually use. I own whether its output is
right, not just whether it runs, and I stay on it until people use it without me. Most of
my work is production systems with a human in the loop: generation pipelines with enforced
quality gates, review stages a subject specialist can operate, and desktop software
distributed to non-technical users across Windows and macOS.

> **Now** · building an internal AI toolkit: **20+ agent tools used by 200+ staff**,
> covering spec authoring, analytics instrumentation, dashboard generation and content
> pipelines, distributed as a synced plugin so improvements reach everyone at once.
> Also running the AI video production platform that has shipped **800+ educational videos**
> across four state boards in Hindi and English medium.

<br />

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/tiger-dark.gif" />
    <img src="assets/tiger-roll.gif" alt="" width="440" />
  </picture>
</div>

<br />

## &nbsp;Timeline

### 2026 &nbsp;·&nbsp; AI systems and shipped products

#### [Design Automater](https://github.com/Tomar606/design-automater-releases) &nbsp;<sub>October</sub>

A desktop application that converts unstructured source material into finished,
design-consistent deliverables. A user selects a design, submits PDFs, Word files, scans,
Excel or PowerPoint, reviews the structure extracted by Claude against a live preview, and
exports print-ready PNG slides and PDFs. Built on a privacy-preserving architecture:
documents are processed on the user's own device and only extracted content reaches the
model provider. Distributed across Windows and macOS through a managed update channel, with
designs compiled from Figma source to within 0–4 px and extended without code changes.

#### Video pipeline, third generation &nbsp;<sub>October</sub>

Rewrote the production pipeline around a staged, resumable architecture where any stage
restarts without redoing upstream work, retiring the earlier animation-only and
generation-only tracks. Eight automated quality gates sit behind one command with a
non-zero exit and recorded waivers, so nothing reaches delivery unchecked. Skipped checks
are reported separately from passes, so a check that silently did nothing can never read
as a pass.

#### [AI video production platform](https://github.com/Tomar606/manim-video-solution-generator) &nbsp;<sub>August</sub>

One board-exam question becomes a finished vertical video: narration splicing, caption
generation, generated b-roll, exact subject diagrams, compositing and delivery. Generation
is used only where an approximation is acceptable: subject diagrams are built exactly
rather than generated, because in exam content the diagram is the answer and generated
video invents structure. Vision-model QC inspects rendered frames for layout, contrast and
geometry defects. A provider-agnostic LLM layer keeps model choice out of 50+ downstream
tools, so switching vendors is a configuration change. The review stage is an
auto-generated page showing every frame with its narration and audio, where a reviewer's
inline notes come back as one structured response the system consumes directly.

#### content-factory &nbsp;<sub>August</sub>

Deterministic document rendering at batch scale. Design source compiles once into a
versioned template, after which structured content renders to print-ready PDF and PNG with
reproducible, diffable output and no manual step per document.

#### PawDesk &nbsp;<sub>July</sub>

A macOS desktop companion in Swift. A click-through, always-on-top pet driven by a
weighted-random behaviour engine, with emotional state and three personalities that bias
its weights. Persisted with SwiftData, monetised with StoreKit 2, packaged for the Mac
App Store.

#### Joined Arivihan Technologies &nbsp;<sub>January</sub>

AI Product Engineer intern, full-time from April.

<br />

### 2025 &nbsp;·&nbsp; Python and AI systems

The year the focus moved out of full-stack web and into Python, LLM APIs and pipeline work:
from building web apps to building systems that produce things.

### 2023–2024 &nbsp;·&nbsp; Full-stack foundations

A run of full-stack projects in React, Next.js, TypeScript and Express (hiring platforms,
banking interfaces, publishing tools and document systems) that built the frontend stack
I still use today.

<br />

## &nbsp;Stack

| | |
|---|---|
| **AI** | Claude · OpenAI · Gemini · LangChain · LangGraph · tool calling · structured outputs · RAG · pgvector · multi-agent orchestration · vision-model QC · LLM-as-judge evals |
| **Backend** | Python · FastAPI · Pydantic · Node.js · Electron · PostgreSQL · token streaming |
| **Frontend** | Next.js · React · TypeScript · Tailwind · Swift / AppKit |
| **Media** | ffmpeg · Whisper · ElevenLabs · Google Veo / Flow · Manim · headless rendering |
| **Ops** | Docker · Git · GitHub Actions · Vercel · desktop packaging and auto-update channels |

<br />

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Tomar606&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&theme=graywhite" height="150" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=Tomar606&layout=compact&langs_count=6&hide_border=true&theme=graywhite" height="150" alt="Top languages" />
</div>
