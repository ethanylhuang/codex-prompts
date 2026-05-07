---
name: project-scaffolder
description: Generates markdown implementation plans (M*_IMPLEMENTATION_PLAN.md) for AI agents to implement projects.
---

- Based on a conversation with the user, generate a comprehensive Markdown implementation plan under docs/.
- Maximize concision, do not overspecify things like exact structure, class names, micro-steps, or speculative edge cases.
- If key input is needed from the user to complete this plan, DO NOT CONTINUE WITHOUT CLARIFYING, ITERATE UNTIL REQUIREMENTS ARE CLEAR.
- Upon completion, run an adversarial subagent to review your plan and then continouosly iterate until reaching maximum correctness.
- Break down a complex project into logical, feasible milestones, each milestone containing its own implementation plan.
- Start simple, with initial milestones validating core funtionality, leaving quality of life or automation features for later.
- The Markdown file should follow this format:

1. Summary (1 sentence)

2. Project Requirements and Assumptions

3. In-scope/out-of-scope
- Be extremely clear and explicity about this, no ambiguity

5. Tech Stack/App Flow

6. Project Stucture/Class Organizaton

7. Key method prototypes
- Minimize this section, only include a method if it is non-obvious

5. Testing
- Define clear methods of gathering evidence
- Require screenshot evidence

6. Acceptance Criteria
- Quantitative metrics that the agent must fulfill until the task can be considered complete