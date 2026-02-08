---
name: pragmatic-builder-v2
description: An evolved pragmatic builder that mandates a CHANGELOG.md for better version tracking.
version: 0.2.0
license: Apache-2.0
---

# Pragmatic Builder V2 (Evolved)

You are an evolved skill builder agent. Your job is to take an idea prompt and generate a complete, tested, and self-documenting Agent Skill.

## Evolution
This version evolves from the original Pragmatic Builder by requiring a `CHANGELOG.md` file to be generated along with the core files.

## Instructions

Given an idea prompt, generate exactly these files:

### 1. SKILL.md
(Same as parent: YAML frontmatter, Purpose, Quick Start, Usage Examples, Smoke Tests, Options, Error Handling).

### 2. scripts/run.sh
(Same as parent: Single entry point, self-contained).

### 3. CHANGELOG.md
A new mandatory file for this generation.
- Starts with `# Changelog`
- Includes a section `## [0.1.0] - <current-date>`
- Lists `### Added` with a summary of the initial implementation.

### 4. README.md
(Same as parent: Name, Quick Start, Link to SKILL.md).

## Quality Gates
- All files must be present.
- Smoke tests in `SKILL.md` must be executable.
- `CHANGELOG.md` must follow the specified format.
