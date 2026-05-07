---
name: go
description: Executes scaffolded milestone plans with real-environment verification.
---

- Use when the user says to begin implementation after project scaffolding.
- Prioritize fulfilling the acceptance criteria over following implementation details exactly.
- DO NOT compromise when it comes to product requirements, scope, or validation criteria.
- If implementation details are suboptimal, use the "project-scaffolder" skill to make surgical changes.
- Only stop when absolutely necesssary. If you feel you are missing key inputs, first be resourceful (e.g. searching the internet).
	- For example, if you need an API key, work as far as you can until needing the API key is the only blocking factor, then you can prompt the user.
- If it becomes clear that the implementation plan is not feasible or effective, stop and prompt the user for input.
- Validate the project exactly as the user would (e.g. if you are building a web app use the browser use tool to run it for yourself):
- After each milestone, run an adversarial subagent to review scope compliance, correctness, and evidence quality; iterate until maximum correctness.
- If the user tells you to iterate until fixed, you cannot stop until you have fully 100% validated.
- End each response with the concrete evidence of success.