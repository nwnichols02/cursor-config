# cursor-config

Cursor-oriented agent workflow: skills, conventions, and planner tooling.

## Files

| File / directory | What                                      | When to read                          |
| ---------------- | ----------------------------------------- | ------------------------------------- |
| `README.md`      | Philosophy, quick start, usage            | Installing or explaining this repo    |
| `conventions/`   | Shared docs (AGENTS.md/README patterns)   | Writing project docs, running doc-sync |
| `skills/`        | Skill definitions (`SKILL.md`) + scripts  | Invoking skills, changing behavior    |
| `agents/`        | Role prompts (planner sub-agents)         | Editing technical writer / QR prompts |
| `skills/scripts/`| Python implementations (`python3 -m …`)  | Developing or debugging skill code  |

## Subdirectories

| Directory        | What                         | When to read                    |
| ---------------- | ---------------------------- | ------------------------------- |
| `skills/scripts/`| Package root for `skills.*`  | Running skills from `.cursor`   |

Install tracked folders under your Cursor config root so paths like
`.cursor/skills/scripts` resolve correctly (see `README.md` Quick Start).
