# Hiero GitHub Workflow App — LFX Mentorship Prototype

A config-driven GitHub App built with [Probot](https://github.com/probot/probot), 
developed as a prototype for the 
[LFDT – Hiero GitHub Workflow App](https://github.com/LF-Decentralized-Trust-Mentorships/mentorship-program/issues/73) 
mentorship project (Issue #73).

## What it does

This app implements per-repository automation for Hiero maintainer workflows:

- **PR lifecycle automation** — labels, review assignments, and stale detection triggered by PR events
- **Issue management** — auto-labeling, stale issue closure, difficulty tagging
- **Contributor onboarding** — welcome messages for first-time contributors, DCO reminders
- **Config-driven behavior** — each repository can enable/disable features via `hiero-workflow.yml`

## Architecture

The design follows the multi-repo, config-first pattern discussed in Issue #73:
