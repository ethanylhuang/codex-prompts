---
name: project-scaffolder
description: Generates markdown implementation plans (M*_IMPLEMENTATION_PLAN.md) for AI agents to implement projects.
---

- Generate a concise Markdown implementation plan under docs/.
- Prefer the simplest path that satisfies the goal.
- Ask clarifying questions if the scope is unclear.
- Keep plans specific, high-level, and flexible.
- Validate the core user flow first.
- Defer polish and automation.
- The Markdown file should follow this format:

1. Summary
- One sentence.

2. Project Requirements
- Only include non-negotiable requirements core to the project.

3. Assumptions
- Optional.
- Include only inferred defaults that affect scope.
- Do not treat assumptions as hard requirements.

4. In-scope/out-of-scope

5. General Approach
- Start with the smallest working user flow.
- Name key screens, models, integrations, and workflows when known.
- Sequence core behavior, persistence/integration, then polish.
- Avoid exact files/classes unless required.

6. Testing
- Define concrete evidence.
- Test as the user would.

7. Acceptance Criteria
- Define measurable completion criteria.
