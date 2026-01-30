# Agent Skills

This repository contains agent skills used by Claude Code and compatible tools.

## Available Skills

### project-starter

**Purpose:** Analyze projects and explain how to start them.  
**Use when:** The user asks how to initialize, set up, or run a project for the first time.

**Triggers:**

- "cómo inicializo el proyecto"
- "setup"
- "cómo inicio"
- "qué necesito para levantar"

📍 Source: [`skills/project-starter/SKILL.md`](skills/project-starter/SKILL.md)

---

## Usage Notes

- Skills are Markdown-only.
- No build or install step required.
- Each skill directory name must match the `name` field in its `SKILL.md`.
- Claude should load the appropriate skill based on trigger intent.
