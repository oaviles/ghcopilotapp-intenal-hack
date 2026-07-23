# GitHub Copilot App Mini-Hackathon

Welcome to the **GitHub Copilot App** Mini-Hackathon. This event is designed to give you hands-on experience with the power of the GitHub Copilot desktop application (built on Copilot CLI), exploring features such as parallel agent sessions, custom instructions, Model Context Protocol (MCP) server integration, and automated pull request merging using Agent Merge.

---

## Challenge 1: Environment Setup and GitHub Copilot App Installation

* **Title**: Installation, Workspace Connection, and Exploration
* **Challenge Description**: 
  Set up your local environment by cloning the Tailspin Toys sample repository and installing the GitHub Copilot desktop application. Connect your repository to the app's workspace to enable agent interactions, review the initial backlog, and prepare for task execution.
* **Challenge Scenario**: 
  You are a software developer joining the Tailspin Toys e-commerce team. The team has just adopted the new **GitHub Copilot App** to accelerate delivery through agent-driven development. Your first mission is to set up your local workspace, link the project, and take a tour of the application interface to understand session structures and integrated issue/PR management.
* **Suggested time to solve**: 20 minutes
* **Resources**:
  * [Prerequisites - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/0-prerequisites/)
  * [Install the Copilot App - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/1-install-copilot-app/)
  * [GitHub Copilot App Overview Documentation](https://docs.github.com/copilot/concepts/agents/github-copilot-app)

---

## Challenge 2: Your First Agent Session and Quick Change

* **Title**: Implementing Star Ratings and Submitting Your First Pull Request
* **Challenge Description**: 
  Start an autonomous agent session inside the GitHub Copilot App to request the addition of a star rating component to the Tailspin Toys product view. Allow the agent to generate the necessary code changes and submit your first Pull Request directly from the app.
* **Challenge Scenario**: 
  The product team requested a visual star rating display on the product list page. Instead of writing the component from scratch, you will use an agent session in the GitHub Copilot App to delegate the implementation, review the proposed diffs directly within the workspace, and submit the corresponding Pull Request.
* **Suggested time to solve**: 20 minutes
* **Resources**:
  * [Running your first agent session - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/2-add-star-rating/)
  * [GitHub Copilot App Documentation](https://docs.github.com/copilot/concepts/agents/github-copilot-app)

---

## Challenge 3: Guiding the Agent with Custom Instructions

* **Title**: Standardizing Documentation and Code with Custom Instructions
* **Challenge Description**: 
  Enforce code and documentation standards across the project using custom instructions (`.github/copilot-instructions.md` or repository instruction settings). Configure the agent to follow these rules when resolving a backlog issue, and verify that the generated code and responses strictly adhere to the defined standards.
* **Challenge Scenario**: 
  The lead architect defined new organizational standards for documentation and TypeScript/React code style. To avoid repetitive manual code reviews, you must instruct Copilot on these rules via a *Custom Instructions* file so that any future task executed by the agent automatically aligns with the project guidelines.
* **Suggested time to solve**: 20 minutes
* **Resources**:
  * [Guiding Copilot with custom instructions - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/3-custom-instructions/)
  * [Adding custom instructions for GitHub Copilot](https://docs.github.com/copilot/customizing-copilot/adding-custom-instructions-for-github-copilot)

---

## Challenge 4: Full Feature Development and Validation with Playwright MCP

* **Title**: Autonomous Product Filtering Development and Testing with MCP
* **Challenge Description**: 
  Use the Plan and Autopilot modes within the app to build a full product filtering system. Next, connect the Playwright MCP (Model Context Protocol) server to the application to allow the agent to launch a real browser and run end-to-end verification tests against the newly built feature.
* **Challenge Scenario**: 
  Tailspin Toys customers need to filter products by category and price range. Because this feature spans multiple components, you will leverage the planning capabilities of the GitHub Copilot App to breakdown and develop the feature seamlessly. Once implemented, you will use the integrated Playwright MCP server to let the agent launch the browser, interact with the web app, and verify that the filter functions as expected.
* **Suggested time to solve**: 30 minutes
* **Resources**:
  * [Building a feature with Autopilot - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/4-build-filtering/)
  * [Testing with Playwright MCP - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/5-mcp-playwright/)
  * [GitHub Copilot & Model Context Protocol (MCP)](https://docs.github.com/copilot/concepts/agents/github-copilot-app)

---

## Challenge 5: Continuous Integration with Agent Merge and Work Canvases

* **Title**: Automated PR Integration via Agent Merge and Planning with Canvases
* **Challenge Description**: 
  Leverage the **Agent Merge** feature in the GitHub Copilot App to handle merge conflicts, run rebases, fix CI failures, and merge the product filtering Pull Request without manual intervention. Finally, create a shared Canvas to map out future iteration steps and recurring automation tasks.
* **Challenge Scenario**: 
  Your product filtering PR has conflicts with the main branch and requires updating integration tests due to recent team updates. Instead of manually resolving rebases and fixing tests, assign **Agent Merge** to shepherd the PR through review, fix CI issues, and merge it. Wrap up by organizing your team's workflow using an interactive Canvas workspace.
* **Suggested time to solve**: 20 minutes
* **Resources**:
  * [Merging with Agent Merge - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/6-agent-merge/)
  * [Planning with canvases - Copilot Workshops](https://github-samples.github.io/copilot-workshops/app/7-canvases/)
  * [GitHub Copilot App Review & Next Steps](https://github-samples.github.io/copilot-workshops/app/8-review/)
