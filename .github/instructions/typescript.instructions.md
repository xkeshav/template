---
applyTo: "**/*.ts, **/*.tsx"
name: "Typescript Instructions"
description: : "general instructions to writer typescript file"
---

# Project standards

Apply the [general coding guidelines](../copilot.instructions.md) to all code.

## Typescript guidelines

- use typescript for all new code
- Always use `type` alias instead of `interface`
- Name type aliased in PascalCase
- Avoid using `any`; use specific types or `unknown`
- Use optional chaining (?.) and nullish coalescing ( ?? ) operators.
- Prefer union and intersections types for complex structure.
- Use explicit types for function parameters and return values.