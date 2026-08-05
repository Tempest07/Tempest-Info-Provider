# Tempest Info Provider Skills

A small, public catalog of reviewed `SKILL.md` files for the Tempest WeCom assistant.

## Repository policy

- This repository contains skill documents only. Bot source code, credentials, local databases, and logs do not belong here.
- Every imported skill must be pinned to a full 40-character Git commit SHA.
- Importing creates a pending record; approval and activation are separate administrator actions.
- Group activation requires the exact 64-character SHA-256 hash and is scoped to that WeCom group.
- A skill runs only through an explicit `/skill use <name> <question>` command.
- Skill calls receive no ordinary chat history, do not write to ordinary chat history, and receive no tool permissions.
- Risk-flagged or integrity-invalid skill content is blocked before a model request.

## Layout

Each skill lives at:

```text
skills/<skill-name>/SKILL.md
```

The first example is `skills/source-triangulation/SKILL.md`.
