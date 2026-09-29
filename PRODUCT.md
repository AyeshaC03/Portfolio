# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Scrum Masters, Release Train Engineers, and pre-PI Planning facilitators checking team capacity, prioritized backlog, cross-team dependencies, overcommitment, and timing or commitment mismatches before PI Planning.

## Product Purpose

The PI Planning Capacity & Conflict Pre-Check helps surface planning conflicts before Day 1 so the room can spend its time resolving known issues rather than discovering them. It is a pre-check aid, not a PI commitment oracle or a replacement for PI Planning.

## Positioning

It uses explicit, deterministic capacity and dependency checks over a browser-local scenario, rather than AI interpretation or shared backend data.

## Operating Context

Facilitators review planned work and capacity across five PI iterations (I1–I4 and IP), then inspect linked cross-team dependencies, readiness findings, and suggested pre-Day-1 actions.

## Capabilities and Constraints

The standalone tool is a static web page with no service, external API, or authentication. It includes synthetic illustrative sample data, deterministic checks, JSON import/export, and localStorage persistence. Edited data is local to the current browser and device, not shared with other viewers. Capacity and planned effort use team-specific capacity-days and may only be compared within the same team; story points or other estimates must not be summed or compared across teams.

## Brand Commitments

The portfolio's existing identity is charcoal/near-black, high-contrast typography, and a single lime accent. The tool is an Operate surface and should keep the portfolio's established visual world.

## Evidence on Hand

The supplied source prototype and README describe the pre-PI conflict-discovery goal and the limitation of its Claude-only database and AI calls on GitHub Pages. The existing portfolio at `index.html` contains public artifact links and the established visual identity. No real team data, customer results, or measured savings are provided; all example planning data must be labeled fictional and illustrative.

## Product Principles

- Surface conflicts before PI Planning, not during it.
- Show rule-based findings with explicit evidence and actionable next steps.
- Keep team-specific effort units separate across teams.
- Treat all seeded planning data as fictional and illustrative.
- Preserve local edits without implying cross-viewer sharing.
