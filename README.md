# Boutros Tawaifi

**Senior full-stack engineer.** TypeScript, Node.js, React, Angular · real-time data systems · AI-native development.

Since 2021 I've been the sole engineer at Orbit Sports Data, building and running a live sports-data platform: analysts report match events in real time, and customers receive them as feeds over WebSocket, RabbitMQ and REST. That work is private; the repos below are what I can show.

I care most about **correctness, maintainability, measurable performance, and taking projects all the way from idea to a usable release**.

## Selected engineering work

### [Codebase MCP Bridge](https://github.com/BTawaifi/codebase-mcp-bridge) [![CI](https://github.com/BTawaifi/codebase-mcp-bridge/actions/workflows/ci.yml/badge.svg)](https://github.com/BTawaifi/codebase-mcp-bridge/actions/workflows/ci.yml)
A Model Context Protocol server that gives AI coding tools controlled access to a repository: batched search and read, patches with rollback, Git, and allowlisted validation, over stdio or OAuth-protected HTTP. Built with AI agents under my direction; tested in CI on Node 22 and 24.

**Signals:** TypeScript · MCP · agent tooling · security boundaries · CI

### [Image moderation (university project)](https://github.com/BTawaifi/Affordable-Image-Moderation-CLIP-Model-with-FastAPI-Framework)
OpenAI CLIP zero-shot image classification on FastAPI workers, plus NestJS microservices (gateway, auth, upload, storage) over RabbitMQ.

**Signals:** NestJS · microservices · RabbitMQ · Python · FastAPI · ML integration

### [Audio DeSilencer](https://github.com/BTawaifi/Audio-DeSilencer)
Python audio-processing package and CLI for detecting and removing silence. Published for installation with `pip`, with configurable thresholds and FFmpeg-backed format support.

**Signals:** Python · package/CLI design · audio processing · open source · 28+ stars / 6+ forks

### [Time Master](https://github.com/BTawaifi/Time-Master)
Cross-platform Electron + React desktop application for structured deep-work sessions. Includes automated packaging/releases, persistent local data, multiple session engines, and a native desktop enforcement layer.

**Signals:** Electron · React · stateful desktop software · testing · CI/release engineering

### [PaneInk](https://github.com/BTawaifi/PaneInk-Releases)
Pressure-sensitive Windows drawing overlay for annotating any desktop app with a pen or mouse. Includes smooth vector ink, click-through overlay control, multi-monitor capture, clipboard integration, portable releases, and optional Windows auto-start.

**Signals:** C# · WPF · Win32 interop · pressure-sensitive input · desktop UX · CI/release engineering

### [FreeSpace RTS: Fleet Command](https://github.com/BTawaifi/RTS-fleet-command)
A real-time fleet-command mod for FreeSpace Open, written in Lua: up to 12 AI or player factions, capital-ship and fighter piloting, a station economy, and AI tuned from hundreds of headless replays. Released on GitHub with a large automated test suite.

**Signals:** Lua · game AI · simulation tooling · automated testing · release engineering

### [Hybrid Markdown Editor](https://github.com/BTawaifi/hybrid-markdown-editor) [![CI](https://github.com/BTawaifi/hybrid-markdown-editor/actions/workflows/ci.yml/badge.svg)](https://github.com/BTawaifi/hybrid-markdown-editor/actions/workflows/ci.yml)
Reusable React markdown editor that renders inactive lines while turning the focused line into an inline editor. Designed as a controlled component with styling hooks and an extensions API.

**Signals:** TypeScript · React library/API design · editor behavior · performance work

### [EventLogix](https://github.com/BTawaifi/EventLogix)
Full-stack event logging and monitoring application with filtering, live updates, pagination, exports, and containerized local deployment.

**Signals:** Next.js · TypeScript · PostgreSQL · Prisma · Docker · SWR

## Open-source contribution

### [FreeSpace Open engine: headless, reproducible batch simulation](https://github.com/scp-fs2open/fs2open.github.com/pull/7897)
Engine work on the FreeSpace Open C++ codebase that lets missions run unattended and repeatably, built to tune the AI and economy of my own RTS mod over hundreds of replayed matches:
- a headless fixed-step simulation mode: no window or audio, a virtual mission clock, and a JSON result per run;
- seeded RNG across every random family the simulation uses, so equal seeds reproduce;
- an On Ship Damage script hook;
- afterburner cooldowns that follow the mission clock;
- a parallel batch runner with unit tests.

## How I work

I use coding agents heavily, but I treat generated code the same way I would treat an untrusted patch from another engineer: **inspect it, test it, benchmark it when performance claims matter, and own the final result**.

The engineering work I find most interesting usually involves one or more of:

- tracing a bug to its actual root cause rather than patching symptoms;
- simplifying boundaries between components or services;
- hardening failure modes, retries, validation, and observability;
- improving performance from measurements rather than assumptions;
- turning one-off internal solutions into reusable tools.

## Smaller tools and experiments

I also publish focused utilities and experiments when they solve a concrete problem, including Windows tooling, scraping/automation helpers, desktop overlays, and AI-assisted development workflows.
