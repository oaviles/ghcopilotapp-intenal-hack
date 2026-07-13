# GitHub Copilot App Mini-Hackathon 🚀

Welcome to the **GitHub Copilot App Mini-Hackathon**! This hands-on hackathon is designed to introduce you to the standalone **GitHub Copilot App**, moving beyond simple inline completions to orchestrating advanced multi-agent workflows. 

Through these 5 challenges, you will explore the app's native task-assignment ecosystem, leverage isolated environments, use interactive visualization planes, and execute parallel development workloads.

---

## 📅 Hackathon Overview
* **Target Audience:** Developers, Cloud Architects, and Technical Team Leads.
* **Objective:** Gain practical proficiency with the standalone GitHub Copilot App features, including the Dashboard, Canvases, Parallel Agent Sessions, Isolated Git Worktrees, Automations, and the Rubber Duck Agent.

---

## ⚔️ The Challenges

### Challenge 1: The Conceptual Brainstorm & Command Center Orientation
* **Title:** Orienting the Command Center with the Rubber Duck Agent
* **Suggested Time to Solve:** 15 minutes
* **Challenge Description:** Initialize your hackathon workspace inside the standalone GitHub Copilot App. Before writing any code, you must architect a high-level plan for a multi-tenant microservice using the built-in Rubber Duck debugging and reasoning framework, managing this session from your central operational panel.
* **Challenge Scenario:** You are tasked with adding an event-driven notification service to an existing repository. Open the GitHub Copilot App and navigate the **Dashboard ("My Work" view)** to select your repository. Spin up a specialized **Rubber Duck Agent** session to discuss the optimal architectural pattern (e.g., Webhooks vs. Polling) without generating code files yet. The goal is to obtain a clean, structured architectural recommendation checklist.
* **Resources:**
  * [About the GitHub Copilot App](https://docs.github.com/copilot/concepts/agents/github-copilot-app)
  * [Working with Agent Sessions in the GitHub Copilot App](https://docs.github.com/en/copilot/how-tos/github-copilot-app/agent-sessions)

---

### Challenge 2: Visualizing Intent & Scaffolding Code
* **Title:** Designing and Generating via Interactive Canvases
* **Suggested Time to Solve:** 20 minutes
* **Challenge Description:** Transform your conceptual architecture checklist into a physical layout and codebase boilerplate using the interactive, bidirectional workflow canvas.
* **Challenge Scenario:** Using the prompt interface, instruct Copilot to scaffold the notification service discussed in Challenge 1. Instead of viewing plain terminal code output, force the agent to render its execution plan, file trees, and endpoint flows inside a **Canvas**. Review the generated Canvas, modify the plan mid-execution directly on the visual surface to add an authentication middleware file, and approve the step-by-step layout generation.
* **Resources:**
  * [GitHub Copilot Gets Its Own App — and Agents Are the Reason Why](https://devops.com/github-copilot-gets-its-own-app-and-agents-are-the-reason-why/)
  * [Researching, Planning, and Iterating with Copilot Agents](https://docs.github.com/en/copilot/how-tos/copilot-on-github/use-copilot-agents/research-plan-iterate)

---

### Challenge 3: High-Concurrency Feature Engineering
* **Title:** Parallel Execution across Isolated Git Worktrees
* **Suggested Time to Solve:** 30 minutes
* **Challenge Description:** Execute multiple development tasks simultaneously on the same repository without causing local directory conflicts or file corruption.
* **Challenge Scenario:** Your repository requires three concurrent updates: fixing a broken test suite, optimizing a database index, and writing API documentation. In the GitHub Copilot App, spin up three **Parallel Agent Sessions** at the same time. Observe how the app automatically assigns each session to its own **Isolated Git Worktree** in the background. Verify that you can review progress across all three threads concurrently without manual branch switching or stashing.
* **Resources:**
  * [GitHub Copilot App: Parallel Agents via Git Worktrees](https://byteiota.com/github-copilot-app-parallel-agents-git-worktrees/)
  * [Workspace vs Worktree Isolation in Copilot CLI](https://www.kenmuse.com/blog/workspace-vs-worktree-isolation-in-copilot-cli/)

---

### Challenge 4: Hands-Off Governance & Background Workloads
* **Title:** Configuring Autonomous Cloud Automations
* **Suggested Time to Solve:** 20 minutes
* **Challenge Description:** Configure a fire-and-forget background agent execution policy to automate recurring tasks such as dependency maintenance and PR triage.
* **Challenge Scenario:** To ensure continuous code health, set up a **Cloud Automation** rule inside your Copilot workspace configuration. Configure the agent to autonomously wake up when a new issue labeled `bug` is opened, pull down repository context, create a diagnostic plan, and stage a fix directly as a draft Pull Request on a scheduled runner, all without tying up your local laptop resources.
* **Resources:**
  * [Managing and Tracking Copilot Agents](https://docs.github.com/en/copilot/how-tos/copilot-on-github/use-copilot-agents/manage-and-track-agents)
  * [GitHub Desktop: Worktrees and Deeper Copilot Integration](https://github.blog/changelog/2026-06-26-github-desktop-3-6-worktrees-and-deeper-copilot-integration/)

---

### Challenge 5: The Synchronization & Agent Merge
* **Title:** Consolidating Multi-Agent Outputs into Production
* **Suggested Time to Solve:** 30 minutes
* **Challenge Description:** Bring your parallel streams together by resolving merge conflicts, completing code reviews, and executing an enterprise-compliant Agent Merge.
* **Challenge Scenario:** Go back to your central **Dashboard ("My Work")** view. You will find the completed features from Challenge 3 and the draft PR from Challenge 4. Bring up the conflict resolution Canvas to allow Copilot to explain cross-cutting updates. Use the **Agent Merge** control feature to validate that all mandatory branch protection rules and CI checks pass before safely landing your AI-authored branches into `main`.
* **Resources:**
  * [GitHub Copilot App Hits General Availability With Parallel Agents and Canvases](https://webdeveloper.com/news/github-copilot-app-generally-available/)
  * [Reviewing Copilot Output and Code Review Capabilities](https://docs.github.com/en/copilot/how-tos/copilot-on-github/use-copilot-agents/review-copilot-output)

---

## 🛠️ Verification Checklist
To successfully pass the hackathon, ensure you can demonstrate the following components to your proctor:
1. [ ] An active **My Work** dashboard view with historical sessions tracking.
2. [ ] A custom interactive **Canvas** showing customized modifications to the scaffolding plan.
3. [ ] Evidence of active **Parallel Sessions** running inside independent background directory trees.
4. [ ] A valid JSON configuration file or automation dashboard schedule for **Cloud Automations**.
5. [ ] A successfully executed **Agent Merge** showing compliant code tracking.
