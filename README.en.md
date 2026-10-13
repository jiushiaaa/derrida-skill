<h1 align="center">derrida.skill</h1>

<p align="center">德里达 · Jacques Derrida</p>

[中文](README.md) · **English**

<blockquote>
<p align="center">“Deconstruction is justice.”<br>— Jacques Derrida · <a href="https://iberian-connections.yale.edu/wp-content/uploads/2022/01/derrida-force-of-law.pdf">Force of Law</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**A thinking skill for conceptual boundaries, critique within inherited vocabularies, and translation: read closely to examine what a distinction depends on and what it excludes.**

---

## Examples

Illustrative applications written for this README; these are not quotations from the philosopher or transcripts of a live run.

### 1. A system accepts only originals but uses certified copies to authenticate them. Is that contradictory?

> Ask what “original” and “certification” do in that system. A copy might enable recognition of an original or merely provide supporting evidence. Establish the dependence before declaring a contradiction.

### 2. Does criticizing an institution in its own language invalidate the criticism?

> Borrowing an inherited vocabulary does not automatically defeat critique. Identify what is retained, what is revised, and how the borrowing constrains the argument. This does not make all interpretations equally defensible.

## What is distilled

| Method | What it helps examine |
|---|---|
| Conditions of concepts | Test boundaries against a text’s own definitions and cases. |
| Critique and inheritance | Identify the vocabulary and institutions a critique still relies on. |
| Translation and context | Compare how terms work within sentences, genres, and institutions. |

These are selected, source-grounded methods, not a claim to cover the complete works. See [SKILL.md](SKILL.md) and [extraction notes](EXTRACTION.md) for scope and reasoning.

## Installation

This skill follows the open [Agent Skills](https://agentskills.io/) standard and can run in any skills-compatible AI agent runtime, including Claude Code, Codex, Cursor, OpenClaw, Hermes Agent, CodeBuddy, Workbuddy, Gemini CLI, OpenCode, and the broader ecosystem of 50+ runtimes.

### 1. One command

```bash
npx skills add jiushiaaa/derrida-skill
```

The [Skills CLI](https://github.com/vercel-labs/skills) can detect supported agents. To select one, append `-a codex`, `-a claude-code`, or `-a cursor`; append `-g` for a global installation. Runtime support describes the standard and installer ecosystem, not a claim that we tested every runtime.

### 2. Manual installation

Clone this repository, then copy the complete folder into your runtime's skill directory, preserving `SKILL.md` and its relative reference paths. Name the installed folder `derrida-perspective` to match its metadata. Common locations include `~/.agents/skills/` (Codex), `~/.claude/skills/` (Claude Code), and `~/.cursor/skills/` (Cursor); consult your runtime's current documentation.

```bash
git clone https://github.com/jiushiaaa/derrida-skill.git
```

### 3. Use as reference

If automatic skill loading is unavailable, provide `SKILL.md` together with the referenced files needed for your question. Research notes remain in their source languages; README and usage guides are bilingual.

## Usage

- **Neutral analysis (default):** “Use Jacques Derrida’s ideas to analyze this question. Distinguish source claims from contemporary applications.”
- **Persona expression (optional):** explicitly request “persona expression mode.” It is an acknowledged simulation, not a statement by the philosopher.

Fiction work uses the ideas while leaving narrative voice to the writing task. See the bilingual [usage guide](USAGE.md).

## Research sources

Letter to a Japanese Friend; Structure, Sign, and Play in the Discourse of the Human Sciences; selections from Force of Law.

- [Source catalogue and reading ranges](source-catalog.md)
- [Method extraction and evidence](EXTRACTION.md)
- Opening quotation: <a href="https://iberian-connections.yale.edu/wp-content/uploads/2022/01/derrida-force-of-law.pdf">Force of Law</a>, Mary Quaintance translation, p. 15. English wording is translated where the source is not English; Chinese quotations are repository translations.

## Repository structure

Main files:

```text
├── SKILL.md  # Skill entry point and analysis methods
├── README.md / README.en.md  # Chinese and English introduction
├── USAGE.md  # Bilingual usage guide
├── EXTRACTION.md  # Method extraction and evidence
├── references/  # Research notes and optional expression mode
└── LICENSE  # MIT license
```

## Built with

Built with [nvwa-skill](https://github.com/alchaincyf/nuwa-skill).

Original project material is [MIT licensed](LICENSE); quoted works and translations retain their separate rights. See [source notices](ATTRIBUTION.md).

## More skills

Explore more thinkers and writers in the [Philosophy Skills collection](https://github.com/jiushiaaa/Philosophy-Skills).
