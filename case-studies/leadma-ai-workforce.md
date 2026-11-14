# Case Study: Leadma AI Workforce

## Overview
Leadma AI Workforce is an enterprise-oriented Agentic AI platform intended to coordinate AI-assisted delivery work across multiple projects. Its design focuses on controlled execution rather than unrestricted autonomous actions.

## Business problem
Multi-project software delivery requires clear project boundaries, task ownership, approvals, traceable changes, access to project knowledge, and visibility into operational cost and progress. The platform is designed to bring these controls into one delivery environment.

## Capabilities documented
- Project provisioning and project-level isolation.
- Agent registry and orchestration workflows.
- Task planning, assignment, dependencies, retries and recovery.
- Human approval gates for change requests and controlled actions.
- Document ingestion and hybrid knowledge retrieval.
- Support and issue workflows with escalation.
- Audit history, cost/budget controls, metrics and operational reports.
- Local Git worktree and pull-request workflow simulation.

## Technology
NestJS API, Next.js web application, TypeScript, Prisma and PostgreSQL. The repository's Docker Compose configuration describes PostgreSQL with pgvector, Redis and MinIO.

## Verification evidence and limitations
The repository's UAT report dated 10 November 2026 records 130 automated tests across five suites. It also explicitly records important limitations:
- The planner and agents use deterministic mock implementations; the Claude adapter is unverified.
- No external GitHub/CI integration is implemented.
- Release is recorded by the platform and is not a deployment to infrastructure.
- Containers had not been built at the time of the report.
- External penetration testing, dependency audit, DAST, disaster recovery on separate infrastructure, and realistic-scale load/soak testing were not completed.
- Agent evaluation coverage is limited and uses a mock provider baseline.

These qualifications are essential: this is not presented as a fully production-validated autonomous AI platform.

## Portfolio relevance
This project demonstrates system-level thinking around agent orchestration, human-in-the-loop controls, project isolation, auditability, budget governance and testable workflows.

Private repository: https://github.com/akjayakody/Leadma_AI_Agents
