# Undercover Employee: The Secret-Shopper Audit Protocol

> **An open-source AI engineering protocol from [We Build for Good](https://webuildforgood.com)**  
> *Cut through AI flattery. See your product through unvarnished eyes.*

---

## Overview

`undercover-employee` is an adversarial audit protocol for AI assistants (Claude Code, Cursor, Antigravity, OpenAI Codex).

It instructs an AI model to drop its default sycophantic persona and walk through a product, codebase, or onboarding flow as an undercover first-time user, skeptical buyer, or new junior engineer.

---

## Why This Exists

Most AI product audits are useless because LLMs are trained to be polite and agreeable. When you ask an AI to evaluate your website or application, it generates flattering platitudes while completely missing the fact that:
* The primary call-to-action is buried below the fold.
* The signup form demands irrelevant information.
* The documentation assumes tribal knowledge that newcomers do not possess.
* The copy sounds defensive, confusing, or buzzword-heavy.

`undercover-employee` gives your AI collaborator a mandate for radical candor grounded in user friction.

---

## Installation

### For Claude Code
```bash
git clone https://github.com/We-Build-For-Good/skill-undercover-employee.git ~/.claude/skills/undercover-employee
```

### For Cursor
```bash
mkdir -p .cursor/skills
git clone https://github.com/We-Build-For-Good/skill-undercover-employee.git .cursor/skills/undercover-employee
```

### For Antigravity / Open Agent Skills
```bash
mkdir -p .agents/skills
git clone https://github.com/We-Build-For-Good/skill-undercover-employee.git .agents/skills/undercover-employee
```

---

## How to Use It

Invoke the skill by pointing it at a URL, a repository, or a staging branch:
* *"Run an undercover-employee audit on our landing page as a skeptical first-time visitor."*
* *"Act as an undercover junior developer trying to run our local setup script from scratch."*
* *"Perform a secret-shopper review of our checkout and onboarding flow."*

The AI will execute the four-stage audit and return a grounded, zero-flattery dispatch identifying exact points of friction.

---

## License

MIT License. Developed and maintained by [We Build for Good](https://webuildforgood.com).
