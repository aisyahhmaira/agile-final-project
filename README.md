# Agile Final Project — E-Commerce Product Catalog

## Project Overview

This repository documents my Agile Planning Final Project, completed as part of the **IBM DevOps and Software Engineering Professional Certificate** on Coursera.

The project applies Agile and Scrum practices to planning a back-end product catalog for an e-commerce website. Using GitHub Issues and GitHub Projects, I created user stories, organized and prioritized a product backlog, planned a sprint, and simulated a development workflow using a Kanban board.

## Project Objectives

- Create user stories based on stakeholder requirements.
- Organize and prioritize a product backlog.
- Refine stories and define acceptance criteria using Gherkin syntax.
- Estimate work using story points.
- Plan and manage a two-week sprint.
- Track work through a Kanban workflow.
- Review sprint progress using GitHub Projects Insights.

## Stakeholder Requirements

| Issue | Requirement | Category |
|---|---|---|
| 1 | Create a product in the catalog | Enhancement |
| 2 | Retrieve a product from the catalog | Enhancement |
| 3 | Update a product in the catalog | Enhancement |
| 4 | Delete a product from the catalog | Enhancement |
| 5 | Like a product in the catalog | Enhancement |
| 6 | Dislike a product in the catalog | Enhancement |
| 7 | List all products in the catalog | Enhancement |
| 8 | Query a subset of products in the catalog | Enhancement |
| 9 | Host the service in the cloud | Technical Debt |
| 10 | Automate deployment of changes to the cloud | Technical Debt |

## Agile Planning Process

### 1. User Stories

Created **10 GitHub Issues**, one for each stakeholder requirement. Each issue follows the format:

> As a **[role]**, I need **[function]**, so that **[benefit]**.

Stories include details and assumptions and acceptance criteria expressed in **Given / When / Then** (Gherkin) syntax.

See the [reusable user story issue template](.github/ISSUE_TEMPLATE/user-story.md) and the [project issues](../../issues).

### 2. Product Backlog

Initially organized the work as follows:

- **8 stories** in Product Backlog.
- **2 stories** (listing all products and querying a subset) in Icebox.
- Stories prioritized according to the stakeholder requirement order.
- **Enhancement** and **technical debt** labels used to classify work.

The Kanban workflow includes **New Issues → Icebox → Product Backlog → Sprint Backlog → In Progress → Review/QA → Done**.

### 3. Backlog Refinement

Reviewed and prioritized the stories, clarified assumptions, and prepared the highest-priority items for sprint planning.

### 4. Sprint Planning

Created a two-week iteration called **Sprint 1**, scheduled for **November 9–22, 2026**. Selected the four highest-priority stories:

| GitHub Issue | User Story | Estimate |
|---|---|---:|
| #1 | Create a product | 3 points |
| #2 | Retrieve a product | 2 points |
| #3 | Update a product | 5 points |
| #4 | Delete a product | 3 points |
| **Total** | | **13 points** |

### 5. Sprint Simulation

Simulated a sprint by assigning stories and moving them through the Kanban board. The final simulated status was:

| GitHub Issue | Story | Points | Final Status |
|---|---|---:|---|
| #1 | Create a product | 3 | Done |
| #2 | Retrieve a product | 2 | Done |
| #3 | Update a product | 5 | In Progress |
| #4 | Delete a product | 3 | Sprint Backlog |

**Sprint results:** 13 points planned, 5 points completed, and 8 points remaining.

### 6. Sprint Progress Chart

Configured a custom GitHub Projects Insights chart named **BurnDown Chart** using:

- **Layout:** Stacked Area
- **X-axis:** Sprint
- **Group by:** Status
- **Y-axis:** Sum of a field
- **Y-axis field:** Estimate

## Tools and Concepts

| Tool or Concept | Use in This Project |
|---|---|
| GitHub | Repository and version control |
| GitHub Issues | User stories and labels |
| GitHub Projects | Kanban board, sprint iteration, estimates, and insights |
| Markdown | Issue template and project documentation |
| Gherkin | Acceptance criteria using Given / When / Then |
| Agile and Scrum | Backlog refinement and sprint planning |
| Kanban | Visual workflow tracking |

## Skills Practiced

- Writing and refining user stories.
- Prioritizing work by stakeholder requirements.
- Defining testable acceptance criteria.
- Estimating work with story points.
- Planning a sprint and tracking its progress.
- Moving work through development and review stages.
- Documenting an Agile workflow in GitHub.

## Project Resources

- [All GitHub Issues](../../issues)
- [User Story Issue Template](.github/ISSUE_TEMPLATE/user-story.md)
- [GitHub Repository](https://github.com/aisyahhmaira/agile-final-project)
- [GitHub Kanban Board](https://github.com/users/aisyahhmaira/projects/8)
