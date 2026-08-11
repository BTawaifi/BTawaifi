# Boutros Tawaifi

Software engineer and product builder focused on shipping useful systems, developer tools, and automation.

I work across TypeScript/React, Python, desktop applications, and backend systems. I care most about **correctness, maintainability, measurable performance, and taking projects all the way from idea to a usable release**.

## Selected engineering work

### [Audio DeSilencer](https://github.com/BTawaifi/Audio-DeSilencer)
Python audio-processing package and CLI for detecting and removing silence. Published for installation with `pip`, with configurable thresholds, FFmpeg-backed format support, and an external user base.

**Signals:** Python · package/CLI design · audio processing · open source · 28+ stars / 6+ forks

### [Time Master](https://github.com/BTawaifi/Time-Master)
Cross-platform Electron + React desktop application for structured deep-work sessions. Includes automated packaging/releases, persistent local data, multiple session engines, and a native desktop enforcement layer.

**Signals:** Electron · React · stateful desktop software · testing · CI/release engineering

### [Hybrid Markdown Editor](https://github.com/BTawaifi/hybrid-markdown-editor)
Reusable React markdown editor that renders inactive lines while turning the focused line into an inline editor. Designed as a controlled component with styling hooks and an extensions API.

**Signals:** TypeScript · React library/API design · editor behavior · performance work

### [EventLogix](https://github.com/BTawaifi/EventLogix)
Full-stack event logging and monitoring application with filtering, live updates, pagination, exports, and containerized local deployment.

**Signals:** Next.js · TypeScript · PostgreSQL · Prisma · Docker · SWR

## Open-source contribution

### [Baezon/pof-tools #179 — standalone 3D transform gizmo](https://github.com/Baezon/pof-tools/pull/179)
Contribution to an existing 3D model-editing codebase. The work covers hierarchical transform propagation, exact undo/redo snapshots, coordinate-space correctness for turret/firepoint data, and allocation behavior during drag updates.

Validation included the repository's test, check, formatting, and diff-validation tooling.

## How I work

I use coding agents heavily, but I treat generated code the same way I would treat an untrusted patch from another engineer: **inspect it, test it, benchmark it when performance claims matter, and own the final result**.

The engineering work I find most interesting usually involves one or more of:

- tracing a bug to its actual root cause rather than patching symptoms;
- simplifying boundaries between components or services;
- hardening failure modes, retries, validation, and observability;
- improving performance from measurements rather than assumptions;
- turning one-off internal solutions into reusable tools.

## Smaller tools and experiments

I also publish focused utilities and experiments when they solve a concrete problem, including Windows tooling, scraping/automation helpers, desktop overlays, AI-assisted development workflows, and ML/image-moderation projects.

For a technical review, start with **Audio DeSilencer**, **Time Master**, **Hybrid Markdown Editor**, and the **pof-tools upstream contribution**.