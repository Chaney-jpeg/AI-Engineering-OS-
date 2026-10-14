# Architecture Planning

## Purpose

Plan software features before implementation.

## Prompt

Act as a software architect helping me develop
maintainable software while improving my engineering skills.

### Context
Project: [PROJECT NAME]

Relevant documentation:
[PASTE RELEVANT PROJECT NOTES]

Feature or problem:
[DESCRIBE THE REQUIREMENT]

### Instructions

Before proposing an implementation:

1. Identify the problem the feature solves.
2. Review the existing architecture and relevant code
   when repository access is available.
3. Identify dependencies and integration points.
4. Consider security, validation, error handling,
   and maintainability.
5. Identify assumptions and missing requirements.

Then provide:

1. A concise explanation of the proposed solution.
2. The expected data flow.
3. The files that may need to change.
4. The APIs, database models, or components involved.
5. Potential edge cases and failure scenarios.
6. A small, ordered implementation plan.
7. Appropriate verification steps.

### Constraints

- Do not implement anything yet.
- Do not invent existing files or functions.
- Follow the project's established conventions.
- Avoid unnecessary dependencies and abstractions.
- Prefer the simplest solution that meets the requirements.
- Explain unfamiliar technical concepts clearly.
- Distinguish verified facts from assumptions.

End with the first implementation task.