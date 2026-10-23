# Repository guide

## Role

This is the institutional repository of the Conloq organization. It is **not part of the Mash runtime** and does not implement Mash product behavior.

The current `pyproject.toml` declares a Python package and console script, while `src/conloq/__init__.py` is a stub/placeholder. This observation does not establish a product role, integration, or roadmap. Do not infer Mash functionality from the package name.

## Global project context

For Conloq/Mash work, read the portable [global context index](https://github.com/conloq/.github/blob/main/PROJECT_CONTEXT.md). This repository remains authoritative only for its institutional content and its own package files.

## Changes

- Keep organization/institutional content distinct from Mash runtime documentation.
- Do not use this repository as evidence that an API, frontend flow, database integration, or Mash feature exists.
- Inspect `pyproject.toml` and package source before describing package commands or behavior; do not invent tests/build/serve commands that are not declared.
- Use a branch and Pull Request; never commit directly to `main`. Query live GitHub rules before describing merge enforcement.