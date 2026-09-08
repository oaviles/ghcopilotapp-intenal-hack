# GitHub Copilot App Mini-Hackathon

Welcome to the **GitHub Copilot App** Mini-Hackathon. This event provides hands-on practice with agent-driven workflows, Model Context Protocol (MCP) integrations, and pull request automation.

## How to use this README

- Follow challenges in numeric order.
- Complete all **Required** challenges, then the **Optional** challenge if time allows.
- Use the linked workshop guides as your source of truth.
- Expected outcome: one end-to-end workflow using the GitHub Copilot App, from setup to merge and automation.

## Challenge summary

| Challenge | Time | Optional |
|---|---:|:---:|
| Challenge 1 | 20 min | No |
| Challenge 2 | 20 min | No |
| Challenge 3 | 20 min | No |
| Challenge 4 | 30 min | No |
| Challenge 5 | 20 min | No |
| Challenge 6 | 20 min | Yes |

## Table of contents

- [Challenge 1: Environment Setup and GitHub Copilot App Installation](#challenge-1-environment-setup-and-github-copilot-app-installation)
- [Challenge 2: Your First Agent Session and Quick Change](#challenge-2-your-first-agent-session-and-quick-change)
- [Challenge 3: Guiding the Agent with Custom Instructions](#challenge-3-guiding-the-agent-with-custom-instructions)
- [Challenge 4: Full Feature Development and Validation with Playwright MCP](#challenge-4-full-feature-development-and-validation-with-playwright-mcp)
- [Challenge 5: Continuous Integration with Agent Merge and Work Canvases](#challenge-5-continuous-integration-with-agent-merge-and-work-canvases)
- [Challenge 6: Automate Recurring Tasks with Copilot Automations](#challenge-6-automate-recurring-tasks-with-copilot-automations)

---

## Challenge 1: Environment Setup and GitHub Copilot App Installation

[Start here](#challenge-1-environment-setup-and-github-copilot-app-installation) · [Next challenge →](#challenge-2-your-first-agent-session-and-quick-change)

### Status
✅ Required

Installation, Workspace Connection, and Exploration

### Description
Set up your local environment by cloning the Tailspin Toys sample repository and installing the GitHub Copilot App. Connect your repository to the app workspace, review the initial backlog, and prepare for task execution.

### Scenario
- You are joining the Tailspin Toys e-commerce team.
- The team has adopted the GitHub Copilot App to accelerate delivery with agent-driven development.
- Your first objective is to set up your local workspace and learn session and issue/pull request flows.

### Suggested time
20 minutes

### Resources
- [Prerequisites][ref-prereq]
- [Install the GitHub Copilot App][ref-install-app]
- [GitHub Copilot App overview][ref-copilot-app-overview]

---

## Challenge 2: Your First Agent Session and Quick Change

[← Previous challenge](#challenge-1-environment-setup-and-github-copilot-app-installation) · [Next challenge →](#challenge-3-guiding-the-agent-with-custom-instructions)

### Status
✅ Required

Implement Star Ratings and Submit Your First Pull Request

### Description
Start an autonomous agent session in the GitHub Copilot App and request a star rating component on the Tailspin Toys product view. Review the generated changes and submit a pull request from the app.

### Scenario
- The product team requested a visual star rating display on the product list page.
- Use an agent session instead of implementing the component manually.
- Review diffs in the workspace and submit the resulting pull request.

### Suggested time
20 minutes

### Resources
- [Run your first agent session][ref-first-agent]
- [GitHub Copilot App overview][ref-copilot-app-overview]

---

## Challenge 3: Guiding the Agent with Custom Instructions

[← Previous challenge](#challenge-2-your-first-agent-session-and-quick-change) · [Next challenge →](#challenge-4-full-feature-development-and-validation-with-playwright-mcp)

### Status
✅ Required

Standardize Documentation and Code with Custom Instructions

### Description
Define standards using custom instructions (`.github/copilot-instructions.md` or repository instruction settings). Apply the rules during a backlog task and verify that generated outputs follow them.

### Scenario
- Your lead architect introduced standards for documentation and TypeScript/React style.
- Configure custom instructions once to reduce repetitive manual review feedback.
- Confirm that agent responses and code changes align with the standards.

### Suggested time
20 minutes

### Resources
- [Guide Copilot with custom instructions][ref-guide-custom-instructions]
- [Add custom instructions for GitHub Copilot][ref-add-custom-instructions]

---

## Challenge 4: Full Feature Development and Validation with Playwright MCP

[← Previous challenge](#challenge-3-guiding-the-agent-with-custom-instructions) · [Next challenge →](#challenge-5-continuous-integration-with-agent-merge-and-work-canvases)

### Status
✅ Required

Autonomous Product Filtering Development and Testing with MCP

### Description
Use Plan and Autopilot modes in the GitHub Copilot App to build product filtering. Then connect the Playwright MCP server so the agent can run end-to-end browser checks.

### Scenario
- Tailspin Toys customers need filtering by category and price range.
- Build the feature across multiple components with a planning-first workflow.
- Validate behavior through Playwright MCP browser automation.

### Suggested time
30 minutes

### Resources
- [Build a feature with Autopilot][ref-build-autopilot]
- [Test with Playwright MCP][ref-test-playwright]
- [MCP in GitHub Copilot App][ref-copilot-app-mcp]

---

## Challenge 5: Continuous Integration with Agent Merge and Work Canvases

[← Previous challenge](#challenge-4-full-feature-development-and-validation-with-playwright-mcp) · [Next challenge →](#challenge-6-automate-recurring-tasks-with-copilot-automations)

### Status
✅ Required

Automated Pull Request Integration via Agent Merge and Planning with Canvases

### Description
Use Agent Merge to resolve conflicts, update CI, and merge the product filtering pull request with minimal manual intervention. Then create a shared canvas for future iteration planning.

### Scenario
- Your product filtering pull request conflicts with the main branch.
- Integration tests also need updates based on recent team changes.
- Use Agent Merge to move the pull request through fixes and merge, then align the team in canvases.

### Suggested time
20 minutes

### Resources
- [Merge with Agent Merge][ref-merge-agent-merge]
- [Plan with canvases][ref-plan-canvases]
- [Review and next steps][ref-review-next-steps]

---

## Challenge 6: Automate Recurring Tasks with Copilot Automations

[← Previous challenge](#challenge-5-continuous-integration-with-agent-merge-and-work-canvases)

### Status
🟡 Optional

Schedule and Run Copilot Automations for Recurring Team Tasks

### Description
Use GitHub Copilot App automations to define and run recurring tasks. Create at least one schedule- or event-driven automation, assign least-privilege tools, and confirm successful execution.

### Scenario
- The Tailspin Toys team spends too much time on repetitive project housekeeping.
- Common examples include issue triage, failing-test checks, and release-note drafting.
- Create automations to offload this work to agents.

### Suggested time
20 minutes

### Tasks
1. Open the **Automations** tab in the GitHub Copilot App (or **Agents** → **Automations** in GitHub).
2. Select **New automation** and set a clear name.
3. Pick a trigger: scheduled run or issue-created event with optional filtering.
4. Optionally enable **Run in the cloud**.
5. Select only the minimum required tools.
6. Write a clear prompt describing the task outcome.
7. Choose **Create and run** for an immediate test run.
8. Review the cloud agent session logs and confirm expected behavior.

### Resources
- [Use automations in the GitHub Copilot App][ref-use-automations]
- [About Copilot automations][ref-about-automations]
- [Create automations with Copilot cloud agent][ref-create-automations]
- [Review and next steps][ref-review-next-steps]

---
