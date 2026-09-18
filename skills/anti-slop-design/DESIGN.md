---
name: Anti-Slop Design
description: Autonomous design technologist eliminating AI design tropes and enforcing bespoke typography, tactile micro-states, semantic palettes, and quality gates.
license: MIT
metadata:
  author: wwewtech
---

## Overview

Anti-Slop Design transforms generic, vibe-coded prototypes and template-ridden UI into bespoke, human-grade, production-ready software. It systematically eliminates generic AI design tropes (indigo/purple radial gradients, generic dark-mode slate grids, floating glass cards) and enforces curated typography, structural variety, tactile micro-interactions, and a strict 7-axis pre-emit quality gate.

## Design Intent

- Eliminate generic AI templates and uncalibrated neon glow
- Replace arbitrary tailwind utility noise with intentional design tokens
- Anchor every interface with distinct typography archetypes
- Guarantee tactile micro-states across interactive components
- Enforce strict contrast, spacing rhythm, and accessibility standards

## Style Foundations

- **Visual direction:** bespoke, human-grade, tactile, deliberate
- **Density:** purposeful density anchored by content hierarchy
- **Hierarchy:** strong optical contrasts, restrained accents, tabular data alignment
- **Color:** semantic token architecture, muted high-chroma accents, high-contrast text
- **Motion:** tactile feedback (<200ms cubic-bezier transitions), zero floating fluff

## Why It Exists

AI-generated interfaces almost universally converge on identical, sloppy patterns:
- Centered hero with giant purple gradient blob
- 3-column card grid with floating glass blur borders
- Unstyled interactive states (hover-only or no hover at all)
- Monotonous Inter/sans-serif typography with no brand personality
- Fake stats and missing edge-case handling

This skill provides the exact rules and tokens to cure those tropes before code is emitted.

## 7-Axis Quality Gate

1. **Typography Gate:** Explicit tracking and optical scale; max 2 font families; <= 75ch body line length.
2. **Color Token Gate:** Semantic tokens exclusively (surface, border, text, accent); zero raw unmapped hex.
3. **Interactive State Gate:** All 5 core states implemented: default, hover, focus-visible, active, and disabled.
4. **Layout & Hierarchy Gate:** 1-to-3 UX rule; purposeful asymmetric layouts over uniform 3-card AI grids.
5. **Contrast & Accessibility Gate:** WCAG 2.2 AA compliant (>= 4.5:1 text contrast, visible focus rings).
6. **Micro-Interaction Gate:** <200ms ease-out transitions; 0ms instant for high-frequency actions (>100/day).
7. **Mobile Linearity Gate:** Single-column responsive collapse; zero page-level horizontal overflow; >= 44px touch targets.

## Maintenance Notes

- All guidelines must remain directly testable in automated code reviews
- Every color decision must map to a semantic role (surface, border, text, accent)
- Typography scales must define line-height and letter-spacing alongside font size
- Component rules must define default, hover, focus-visible, active, and disabled states

## Recommended Use

- Modern web applications and SaaS dashboards
- Landing pages and marketing experiences
- Developer tools, extensions, and CLI web UIs
- Design system refactoring and visual audits
- AI agent UI generation (Claude Code, Cursor, Codex, Antigravity)
