# Odin‑Recipes

A small collection of cooking recipes and companion example code used to learn and demonstrate concepts with the Odin language and simple tooling. The repository collects recipe data, example programs that operate on that data, and documentation to explain goals and implementation.

## Project goals
- Store a set of human‑readable recipes.
- Provide example code that parses, formats or manipulates recipe data.
- Show basic project structure, build/run examples, and tests for learning purposes.

## What was done
- Initialized project structure and README.
- Added example recipe files (YAML/JSON/markdown).
- Implemented example programs that load and render recipes.
- Wrote basic tests or examples to validate parsing and formatting.
- Documented how to run examples and the repository layout.

## Repository layout (example)
- /recipes — recipe files (markdown, YAML, JSON)
- /examples — small Odin programs or scripts that process recipes
- /docs — notes and design decisions
- readme.md — this file

## How to use
1. Inspect recipes in the `recipes/` directory.
2. Run examples (if you have the Odin toolchain or relevant runtime):
    - Build: `odin build ./examples/...` (adjust for your environment)
    - Run: `odin run ./examples/<example>.odin` or run provided scripts.
3. Read `docs/` for implementation notes and testing instructions.

## Notes
- Keep recipe files human‑readable and consistent (choose one format: markdown/YAML/JSON).
- Use examples to experiment with parsing, formatting, or generating outputs (CLI, HTML, etc.).

## License
Add a LICENSE file or choose a license (MIT, Apache‑2.0, etc.) as appropriate.

If you want, provide more details about the actual files you added and I will update this README to reflect them precisely.