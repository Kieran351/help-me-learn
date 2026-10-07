# help-me-learn

English | [简体中文](README.zh-CN.md)

Learn a concept by reasoning it out yourself. The agent guides you with Socratic questions instead of handing over the answer.

## Features

- Probes what you already know, then advances one small question at a time.
- Surfaces contradictions instead of saying "wrong", and checks real understanding with follow-up variants.
- Gives hints after you get stuck, and explains directly after repeated attempts — no withholding for its own sake.
- Switches to plain explanation whenever you say "just tell me".
- Optionally updates a topic map (`topics/<topic>/map.md`) with what you've mastered.

Triggers on phrases like "quiz me", "do I understand this right", "don't just tell me", or invoke it with `$help-me-learn`.

## Install

Requires Node.js and npm. Use the [Skills CLI](https://github.com/vercel-labs/skills):

```bash
npx skills add Kieran351/help-me-learn
```

Choose your agent and installation scope when prompted. Add `-g` for a global installation.

## Update

```bash
npx skills update help-me-learn
```

Choose the scope when prompted, or add `-g` for global / `-p` for project. Run project updates from the project directory.

## Uninstall

Project installation — run from the project directory:

```bash
npx skills remove help-me-learn
```

Global installation:

```bash
npx skills remove help-me-learn -g
```
