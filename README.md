# GitHub Copilot App Mini-Hackathon

Welcome to the **GitHub Copilot App** Mini-Hackathon. This event gives you hands-on experience with the GitHub Copilot desktop application (built on Copilot CLI), exploring features such as parallel agent sessions, custom instructions, Model Context Protocol (MCP) server integration, and automated pull request merging using Agent Merge.

## What you'll learn

- How to install the GitHub Copilot App and connect a repository to its workspace.
- How to delegate work to autonomous agent sessions and open pull requests from the app.
- How to steer agents with custom instructions so generated code follows your standards.
- How to combine Plan/Autopilot modes with an MCP server for end-to-end verification.
- How to automate PR integration with Agent Merge, and recurring work with Automations.

## Table of contents

- [Prerequisites](#prerequisites)
- [Challenges at a glance](#challenges-at-a-glance)
- [Challenge 1: Environment setup and GitHub Copilot App installation](#challenge-1-environment-setup-and-github-copilot-app-installation)
- [Challenge 2: Your first agent session and quick change](#challenge-2-your-first-agent-session-and-quick-change)
- [Challenge 3: Guiding the agent with custom instructions](#challenge-3-guiding-the-agent-with-custom-instructions)
- [Challenge 4: Full feature development and validation with Playwright MCP](#challenge-4-full-feature-development-and-validation-with-playwright-mcp)
- [Challenge 5: Continuous integration with Agent Merge and work canvases](#challenge-5-continuous-integration-with-agent-merge-and-work-canvases)
- [Challenge 6 (optional): Automate recurring tasks with Copilot Automations](#challenge-6-optional-automate-recurring-tasks-with-copilot-automations)
- [Wrap-up and next steps](#wrap-up-and-next-steps)

## Prerequisites

Before you start, make sure you have:

- A GitHub account with an active GitHub Copilot license.
- The GitHub Copilot desktop application installed on your machine.
- Git installed locally, plus a clone of the Tailspin Toys sample repository used throughout the challenges.

> [!TIP]
> Work through the [Prerequisites](https://github-samples.github.io/copilot-workshops/app/0-prerequisites/) page first — it lists the exact tooling and versions each challenge expects.

## Challenges at a glance

| # | Challenge | Focus | Suggested time |
| --- | --- | --- | --- |
| 1 | Environment setup and GitHub Copilot App installation | Installation, workspace connection, exploration | 20 min |
| 2 | Your first agent session and quick change | Star ratings and your first pull request | 20 min |
| 3 | Guiding the agent with custom instructions | Standardizing documentation and code | 20 min |
| 4 | Full feature development and validation with Playwright MCP | Autonomous product filtering and MCP testing | 30 min |
| 5 | Continuous integration with Agent Merge and work canvases | Automated PR integration and planning | 20 min |
| 6 | *(Optional)* Automate recurring tasks with Copilot Automations | Scheduling and running automations | 20 min |

---

## Challenge 1: Environment setup and GitHub Copilot App installation

⏱️ **Suggested time:** 20 minutes

### Description

Set up your local environment by cloning the Tailspin Toys sample repository and installing the GitHub Copilot desktop application. Connect your repository to the app's workspace to enable agent interactions, review the initial backlog, and prepare for task execution.

### Scenario

You are a software developer joining the Tailspin Toys e-commerce team. The team has just adopted the new **GitHub Copilot App** to accelerate delivery through agent-driven development. Your first mission is to set up your local workspace, link the project, and take a tour of the application interface to understand session structures and integrated issue/PR management.

### Resources

- [Prerequisites - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/0-prerequisites/)
- [Install the Copilot App - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/1-install-copilot-app/)
- [GitHub Copilot App overview documentation](https://docs.github.com/copilot/concepts/agents/github-copilot-app)

---

## Challenge 2: Your first agent session and quick change

⏱️ **Suggested time:** 20 minutes

### Description

Start an autonomous agent session inside the GitHub Copilot App to request the addition of a star rating component to the Tailspin Toys product view. Allow the agent to generate the necessary code changes and submit your first pull request directly from the app.

### Scenario

The product team requested a visual star rating display on the product list page. Instead of writing the component from scratch, you will use an agent session in the GitHub Copilot App to delegate the implementation, review the proposed diffs directly within the workspace, and submit the corresponding pull request.

### Resources

- [Running your first agent session - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/2-add-star-rating/)
- [GitHub Copilot App documentation](https://docs.github.com/copilot/concepts/agents/github-copilot-app)

---

## Challenge 3: Guiding the agent with custom instructions

⏱️ **Suggested time:** 20 minutes

### Description

Enforce code and documentation standards across the project using custom instructions (`.github/copilot-instructions.md` or repository instruction settings). Configure the agent to follow these rules when resolving a backlog issue, and verify that the generated code and responses strictly adhere to the defined standards.

### Scenario

The lead architect defined new organizational standards for documentation and TypeScript/React code style. To avoid repetitive manual code reviews, you must instruct Copilot on these rules via a *custom instructions* file so that any future task executed by the agent automatically aligns with the project guidelines.

### Resources

- [Guiding Copilot with custom instructions - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/3-custom-instructions/)
- [Adding custom instructions for GitHub Copilot](https://docs.github.com/copilot/customizing-copilot/adding-custom-instructions-for-github-copilot)

---

## Challenge 4: Full feature development and validation with Playwright MCP

⏱️ **Suggested time:** 30 minutes

### Description

Use the Plan and Autopilot modes within the app to build a full product filtering system. Next, connect the Playwright MCP (Model Context Protocol) server to the application so the agent can launch a real browser and run end-to-end verification tests against the newly built feature.

### Scenario

Tailspin Toys customers need to filter products by category and price range. Because this feature spans multiple components, you will leverage the planning capabilities of the GitHub Copilot App to break down and develop the feature seamlessly. Once implemented, you will use the integrated Playwright MCP server to let the agent launch the browser, interact with the web app, and verify that the filter functions as expected.

### Resources

- [Building a feature with Autopilot - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/4-build-filtering/)
- [Testing with Playwright MCP - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/5-mcp-playwright/)
- [About Model Context Protocol (MCP)](https://docs.github.com/copilot/concepts/about-mcp)

---

## Challenge 5: Continuous integration with Agent Merge and work canvases

⏱️ **Suggested time:** 20 minutes

### Description

Leverage the **Agent Merge** feature in the GitHub Copilot App to handle merge conflicts, run rebases, fix CI failures, and merge the product filtering pull request without manual intervention. Finally, create a shared canvas to map out future iteration steps and recurring automation tasks.

### Scenario

Your product filtering PR has conflicts with the main branch and requires updating integration tests due to recent team updates. Instead of manually resolving rebases and fixing tests, assign **Agent Merge** to shepherd the PR through review, fix CI issues, and merge it. Wrap up by organizing your team's workflow using an interactive canvas workspace.

### Resources

- [Merging with Agent Merge - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/6-agent-merge/)
- [Planning with canvases - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/7-canvases/)

---

## Challenge 6 *(Optional)*: Automate recurring tasks with Copilot Automations

⏱️ **Suggested time:** 20 minutes

### Description

Use the **Automations** feature in the GitHub Copilot App to define, schedule, and run recurring agent tasks without manual intervention. Create at least one automation that triggers on a schedule or in response to a repository event, configure the tools it may use, and verify it executes correctly — either on demand or at its next scheduled interval.

### Scenario

The Tailspin Toys team is growing and manual housekeeping tasks — such as triaging new issues, checking for failing tests, and drafting weekly release notes — are taking up valuable developer time. As the team's DevOps lead, your mission is to offload these recurring tasks to Copilot by creating automations. You will define the prompt, choose the right trigger (schedule or event), select the minimum required tools following a least-privilege approach, and optionally enable cloud execution so the automation runs even when your laptop is off.


> [!IMPORTANT]
> Apply the principle of least privilege when selecting tools: grant an automation only the permissions it needs to complete its task.

### Resources

- [Using automations in the GitHub Copilot app](https://docs.github.com/copilot/how-tos/github-copilot-app/using-automations)
- [About Copilot automations](https://docs.github.com/copilot/concepts/agents/cloud-agent/about-automations)
- [Creating automations with Copilot cloud agent](https://docs.github.com/copilot/how-tos/use-copilot-agents/cloud-agent/create-automations)

---

## Wrap-up and next steps

Once you have finished the challenges, review what you built and explore where to go next:

- [GitHub Copilot App review and next steps - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/8-review/)
- [GitHub Copilot App documentation](https://docs.github.com/copilot/concepts/agents/github-copilot-app)
