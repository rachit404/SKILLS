# Personal Agent Skills

A repository-local collection of portable Markdown agent skills.

## Structure
All skills are stored under `.agents/skills/`. The `knowledge-academy` skill coordinates learning and delegates domain-specific work to specialist skills.

## Skills
- knowledge-academy
- medicine
- law
- finance
- trading
- economics
- politics
- science
- arts-humanities
- business

## Usage
Use this repository as the source of truth. Agent clients may require their own project-level discovery paths; consult each client's current documentation. No global installation is required.

## Format
Each skill is a directory containing a `SKILL.md` with YAML frontmatter (`name`, `description`) followed by Markdown instructions.
