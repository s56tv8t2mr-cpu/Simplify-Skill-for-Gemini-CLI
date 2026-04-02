# Gemini Code Simplifier

A code simplification agent skill for [Gemini CLI](https://github.com/google-gemini/gemini-cli), adapted from [Anthropic's Claude Code Simplifier plugin](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/code-simplifier).

---

## What It Does

This skill helps Gemini CLI reduce code complexity without changing what the code actually does. It simplifies structure, removes redundant logic, improves readability, and keeps changes consistent with your project's coding standards.

---

## Usage

Copy `gemini-code-simplifier.md` into your Gemini CLI skills or agents directory and invoke it when you want to refactor or clean up code.

---

## Key Behaviors

- **Preserves functionality** — never changes what the code does, only how it does it
- **Reduces nesting and redundancy** — flattens unnecessary complexity
- **Follows project standards** — respects conventions found in your `GEMINI.md`
- **Avoids over-simplification** — clarity and maintainability take priority over fewer lines
- **Prefers explicit code** — uses `if/else` or `switch` over nested ternary operators

---

## Differences from the Original Claude Version

This skill has been adapted for Gemini CLI from the original Claude Code Simplifier:

- Removed Claude Code–specific instructions (e.g., references to `CLAUDE.md`, Claude's autonomous behavior model, and Claude-specific coding conventions)
- Streamlined the workflow for Gemini CLI's agent format
- Scope references updated to reflect Gemini CLI conventions (e.g., `GEMINI.md`)
- Simplified the prompt structure for compatibility with Gemini's instruction format

---

## Attribution & License

This project is derived from the **Claude Code Simplifier** plugin by **Anthropic, Inc.**,  
available at: https://github.com/anthropics/claude-plugins-official/tree/main/plugins/code-simplifier  
Licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).

Modifications copyright 2026 Daniel Babbitt.

This project is also distributed under the [Apache License 2.0](LICENSE).

---

## Contributing

Issues and pull requests are welcome.
