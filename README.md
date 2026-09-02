# StoryForge Studio

StoryForge Studio is a production-operations cockpit for creative teams. It turns a messy production brief into a review-ready sequence of scene beats, dependencies, risk flags, and an auditable handoff.

## Why this exists

Creative and marketing teams lose time translating a brief into a workable plan. StoryForge makes that translation visible: every scene has a purpose, every constraint is carried forward, and unresolved items are shown instead of silently guessed.

## Current prototype

This repository contains a self-contained browser prototype using synthetic data. Click **Run agent crew** to see a deterministic dry run of the workflow. No user data is transmitted and no external service is claimed by this prototype.

## Intended hackathon architecture

The final Agentic Cinema version is intended to use Google Cloud Agent Builder as the orchestration layer and one partner track service for the handoff. The adapter boundary is deliberately isolated so the same workflow can connect to a partner workspace without changing the review experience.

Before final submission, the following must be completed and verified:

1. Deploy the orchestration workflow in Google Cloud Agent Builder.
2. Connect exactly one listed partner service and document the real request/response path.
3. Deploy this UI at a public URL.
4. Record and publish the required 3-minute English, subtitled demo.
5. Replace the local dry-run claim with evidence from the live integration.

Until those steps are verified, this README does not claim hackathon compliance.

## Run locally

Open `index.html` in a browser. No build step is required.

## License

MIT
