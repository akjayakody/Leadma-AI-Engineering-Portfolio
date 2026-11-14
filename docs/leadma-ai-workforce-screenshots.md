# Leadma AI Workforce — Application Screenshots

These screenshots were selected from the private Leadma AI Workforce repository's live-command-centre evidence folder and reviewed before publication. They show interface states and workflow controls; they are not independent proof of production deployment or external model-provider integration.

## 1. Agent Workforce Command Centre

![Command Centre showing the Main Orchestrator and specialist-agent status](../screenshots/ai-workforce-command-centre.jpg)

The dashboard presents the Main Orchestrator and the availability/status of specialist agents.

## 2. Dependency-aware workflow

![Workflow waiting on a dependency](../screenshots/ai-workforce-dependency-state.jpg)

Shows a workflow state in which an agent is waiting on a dependency.

## 3. Human approval gate

![High-risk task paused pending approval](../screenshots/ai-workforce-human-approval.jpg)

The task detail shows an approval-required state and explicitly indicates that execution has not occurred. This illustrates a human-in-the-loop control.

## 4. Completed orchestration state

![Completed orchestration run](../screenshots/ai-workforce-completed-run.jpg)

Shows the completed state and specialist-agent status indicators.

## 5. Project context selection

![Project B selected in the workspace](../screenshots/ai-workforce-project-isolation.jpg)

Shows Project B selected in the workspace. The repository's UAT documentation separately describes project-isolation tests; this screenshot alone should not be treated as a security certification.

## 6. Mobile-width interface

![Agent Workforce Management at mobile width](../screenshots/ai-workforce-mobile-view.jpg)

A mobile-width view of the Agent Workforce Management screen.

## Publication and evidence notes

- These images contain demo project labels and workflow data, not identified client records.
- No credentials, API keys or real customer personal information were visible in the selected images during review.
- The screenshots were copied from the private repository's `docs/evidence/live-command-centre/` folder.
- The UAT report records deterministic mock planner/agent implementations and says the Claude adapter is unverified. These visuals therefore demonstrate UI and workflow states, not verified autonomous execution by an external AI model.
- The UAT report also records that release is logged by the platform rather than deployed to infrastructure. Do not present these screenshots as proof of production deployment.
