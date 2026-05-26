# BaseCode Skills

A set of AI skills and commands for applying [BaseCode](https://basecodefieldguide.com) practices — a focused, language-agnostic set of principles for writing human readable code.

## Installation

There are multiple ways to install these skills and commands.

If you primarily use Claude Code, we recommend installing the plugin. Otherwise, you may install through `npx`.

### Claude Code

Add the marketplace and install globally by running:

```
/plugin marketplace add jasonmccreary/basecode-skills
/plugin install basecode@jasonmccreary --scope user
```

The `--scope user` flag installs the plugin once for your entire system — no per-project setup needed.

### NPX Skills

You may also install via [Skills](https://www.skills.sh/) by running:

```sh
npx skills add jasonmccreary/basecode-skills
```

## Commands

- `/basecode` — review and refactor code to apply BaseCode practices for human readability

## What are BaseCode Practices?

BaseCode is a set of focused, language-agnostic principles for writing code that communicates clearly to the humans who read it. The practices cover naming, functions, conditionals, comments, and structure — the everyday decisions that make code a pleasure or a burden to work with.

Learn more at [basecodefieldguide.com](https://basecodefieldguide.com).
