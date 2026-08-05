# Tempest Info Provider Skills

A small, public catalog of reviewed `SKILL.md` files for the Tempest WeCom assistant.

## Repository policy

- This repository contains skill documents only. Bot source code, credentials, local databases, and logs do not belong here.
- Every imported skill must be pinned to a full 40-character Git commit SHA.
- Importing creates a pending review record. It does not activate or execute the skill.
- A WeCom administrator must inspect the exact pinned file and approve its SHA-256 hash.
- Approved skills still remain non-executable until a separate activation sandbox is implemented.

## Layout

Each skill lives at:

```text
skills/<skill-name>/SKILL.md
```

The first example is `skills/source-triangulation/SKILL.md`.
