---
name: project-scaffolder
description: Generates markdown implementation plans (M*_IMPLEMENTATION_PLAN.md) for AI agents to implement projects.
---

- Generate a concise Markdown implementation plan under docs/ focused on objectives, scope, validation, and flexible implementation guidance.
- Prefer the simplest approach that satisfies the user’s goal and acceptance criteria.
- Ask clarifying questions only when missing requirements would materially affect scope or acceptance criteria.
- Break complex projects into feasible milestones.
- Validate core functionality first; defer polish and automation to later milestones.
- The Markdown file should follow this format:

1. Summary
- One sentence.

2. Project Requirements
- Only include non-negotiable requirements core to the project.

3. Assumptions
- Include only reasonable inferred defaults needed to make the plan actionable.
- Assumptions are not hard requirements and are for guidance.

4. In-scope/out-of-scope

5. Tech Stack/App Flow

6. Testing
- Define clear methods of gathering evidence.
- Test how the user would use the project, such as opening a web app locally in a browser.

7. Acceptance Criteria
- Define measurable completion criteria.