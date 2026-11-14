# Leadma — Engineering Capabilities

This capability summary is grounded in the selected project repositories and their documented scope. It distinguishes demonstrated application domains from broader areas that would require additional evidence.

## Demonstrated through selected projects

| Capability | Project evidence |
|---|---|
| Enterprise workflow modelling | Romaca ERP business flow; Leadma Audit engagement lifecycle |
| Full-stack application engineering | React/Next.js front ends and Express/NestJS back ends documented across projects |
| API and service-layer design | Express and NestJS service architectures |
| Relational data modelling | PostgreSQL and Prisma documented in multiple projects |
| Role-based access control | Leadma Audit, LeadmaIE and Leadma AI Workforce documentation |
| Approval workflows and auditability | Leadma AI Workforce, Romaca ERP and Leadma Audit |
| Manufacturing and industrial domain systems | Romaca ERP and LeadmaIE |
| Risk and assessment workflows | Leadma Audit |
| AI orchestration concepts and controls | Leadma AI Workforce: agent registry/orchestration, human approvals, budget controls and knowledge retrieval |
| Automated testing | Test suites documented for Leadma AI Workforce and Romaca ERP |

## AI and data engineering direction

The Leadma AI Workforce project documents work on agent orchestration, retrieval-oriented knowledge workflows, human-in-the-loop approvals, project isolation, cost controls and operational auditability.

This portfolio does **not** claim verified production integration with H2O.ai, model training at scale, model serving, or a completed MLOps lifecycle. Those capabilities should be added only when there is a concrete implementation, benchmark, deployment or demonstrable project artifact.

## Engineering principles

1. **Business-first design:** model the operational workflow and control points before implementing screens.
2. **Server-side enforcement:** protect important business rules at the API and data layer.
3. **Controlled execution:** use roles, approvals and explicit state transitions for consequential actions.
4. **Traceability:** preserve meaningful audit history for important transactions.
5. **Data boundaries:** separate projects, customers and roles where the application requires it.
6. **Verification:** document automated tests and state clearly what has not yet been tested.
7. **Deployment honesty:** distinguish a working prototype, a tested implementation and a production service.

## How to present this portfolio

For a technical discussion, choose one project and be ready to explain:
- the business problem and user roles;
- the architecture and key data entities;
- one end-to-end workflow;
- a difficult engineering decision and its trade-off;
- how access, approvals and auditability are enforced;
- what tests were run and what remains unverified.

