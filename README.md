<div align="center">

# 🧠 Baitermin Mission Control

### BAITERMIN AI HQ

A sci-fi inspired visual command center for **multi-HQ AI content workflows**.

![Repository](https://img.shields.io/badge/Source-Private-6e7681?style=flat-square&logo=github)
![Status](https://img.shields.io/badge/Status-Active_Development-f59e0b?style=flat-square)
![React](https://img.shields.io/badge/React-19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-6-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-8-646CFF?style=flat-square&logo=vite&logoColor=white)
![PixiJS](https://img.shields.io/badge/PixiJS-8-E91E63?style=flat-square)
![Zustand](https://img.shields.io/badge/Zustand-State-orange?style=flat-square)

</div>

---

## Overview

Baitermin Mission Control is a personal AI content platform designed as an interactive space-station command interface rather than a conventional SaaS dashboard.

Each future **HQ** represents an independent brand or channel identity. AI agents will work through repeatable content workflows inside that HQ:

> **Research → Create → Publish → Analyze → Learn → Repeat**

The production source repository is private while the system is under active development. This repository is the public showcase for the concept, current implementation and roadmap.

---

## Current Status

**Phase 1 — Mission Control Foundation is complete.**  
**Phase 2 — Multi-HQ & Mission Architecture is in progress.**

The current implementation proves the visual and interaction model with a local mock mission and deterministic mock workflow. Real AI agents, durable backend execution and publishing integrations arrive in later phases.

### Phase 1 delivered

- Interactive **2400 × 1600** virtual station world
- Eight themed agent rooms
- PixiJS-based station rendering
- Drag-to-pan and wheel-to-zoom viewport
- Interactive agent tokens
- Hover and selection states
- Five visually distinct runtime statuses
- React agent-detail overlay
- Deterministic multi-stage mock mission workflow
- Start / cancel / reset mission controls
- Historical analytics panel
- Cinematic station atmosphere and visual polish
- Race-safe workflow cancellation and UI interaction handling
- Automated headless and browser-level verification during development

### Phase 2 started

The project is now moving from one hardcoded station toward a reusable domain model for:

- Multiple HQs
- Agent archetypes and instances
- Durable missions
- HQ identity and language
- Generic research workflows
- Content modes and content streams
- Mission composition
- Safety and settings foundations

---

## Product Vision

Mission Control is intended to become a system where multiple specialized AI agents can cooperate around a brand's complete content lifecycle while keeping the user in control.

Examples of future responsibilities include:

- Trend and subject research
- Content ideation
- Script and copy generation
- Visual production
- Narration and media assembly
- Quality control
- Publishing
- Analytics and learning
- Community intelligence

The visual HQ is not only decoration: rooms, agents, mission states and activity are intended to make an otherwise invisible AI workflow understandable at a glance.

---

## Roadmap

| Phase | Scope | Status |
| --- | --- | --- |
| 1 | Mission Control visual foundation & mock workflow | ✅ Complete |
| 2 | Multi-HQ & mission architecture | 🟡 In progress |
| 3 | Durable real AI agent runtime | ⬜ Planned |
| 4 | AI content factory | ⬜ Planned |
| 5 | Knowledge, assets & community intelligence | ⬜ Planned |
| 6 | Platform intelligence & publishing | ⬜ Planned |
| 7 | Autonomous AI HQ | ⬜ Planned |

---

## Architecture

### Interface

- **React 19**
- **TypeScript 6**
- **Vite 8**

### Visual World

- **PixiJS 8** for rendering
- **pixi-viewport** for world navigation
- Fixed world-coordinate station model
- DOM overlays separated from the Pixi world transform

### State

- **Zustand** for agent and mission runtime state
- Domain configuration separated from rendering layers
- Deterministic workflow simulation for the current foundation phase

### Quality

- **Vitest**
- **oxlint**
- TypeScript production builds
- Browser-level interaction verification used throughout Phase 1

---

## Design Principles

- **Visual first:** complex AI workflows should be understandable without reading logs.
- **Multi-HQ by design:** one HQ represents one brand, while the architecture remains reusable.
- **Human control:** autonomy should increase gradually rather than hiding important decisions.
- **Provider independence:** future AI runtime layers should not lock the system to a single model provider.
- **Deterministic foundations:** workflow durability, safety and state transitions should not depend on an LLM making infrastructure decisions.

---

## Privacy & Source Code

The production Mission Control repository is private while the architecture and product are still evolving.

This public showcase intentionally contains **no credentials, private configuration or proprietary implementation source code**.

---

<div align="center">

**Built by [Baitermin](https://github.com/Baitermin)**

🚧 Baitermin Mission Control is actively being developed.

</div>
