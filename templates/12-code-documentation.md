# Code Documentation Standards
**Save as:** `templates/12-code-documentation.md`
**Purpose:** Ensures every codebase, function, and project is documented clearly and maintainably.

---

## MY DOCUMENTATION PRINCIPLES
1. Document the WHY, not just the WHAT — the code shows what it does
2. Write for the next person in 12 months, who may be you
3. Keep docs close to the code — outdated docs are worse than none
4. Good naming reduces the need for comments

---

## README TEMPLATE

```
# [Project Name]

[One sentence describing what this does.]

## What It Does
[2-3 sentences. What problem does this solve? Who uses it?]

## Quick Start
```bash
[Installation command]
[Run command]
```

## Requirements
- [Requirement 1]
- [Requirement 2]

## Configuration
| Variable | Description | Default |
|----------|-------------|---------|
| [VAR_NAME] | [What it does] | [value] |

## Usage
[The most common use case with a real example.]

## API Reference
[Link to full docs or paste key methods here]

## Contributing
[How to contribute, if applicable]

## License
[License name]
```

---

## FUNCTION COMMENT TEMPLATE

```
/**
 * [What this function does in one clear sentence.]
 *
 * @param {type} paramName - [What this parameter is]
 * @returns {type} - [What is returned]
 * @throws {ErrorType} - [When this throws an error]
 *
 * Why this exists: [The reason this was written this way]
 * Known limitations: [What it cannot handle]
 */
```

---

## COMMIT MESSAGE TEMPLATE
```
[type]: [short description in present tense]

Why: [the reason for this change]
What changed: [what specifically was modified]
Impact: [any side effects or things to watch]
```

Types: `feat` `fix` `docs` `refactor` `test` `chore`

---

## AI PROMPTS FOR CODE DOCUMENTATION
- "Write a README for this project: [paste code or description]. Include quick start, requirements, and a usage example."
- "Add comments to this code explaining the WHY, not just the what: [paste code]"
- "Write a clear docstring for this function: [paste function]"
- "Review this README and tell me what a new developer would find confusing: [paste README]"
