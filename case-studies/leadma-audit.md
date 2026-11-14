# Case Study: Leadma Audit

## Overview
Leadma Audit is a web application for managing ergonomic audit engagements, from assigning auditors to recording field observations, issuing reports and managing certificates.

## Workflow
1. Administrator creates an audit and assigns an auditor.
2. Auditor records a location-based observation with a photo and comment.
3. The observation is classified and risk-scored.
4. Recommended controls are mapped to the ISO hierarchy and relevant ISO 45001 clauses.
5. Auditor prepares and signs the report.
6. Client reviews findings and manages corrective actions.
7. The platform manages invoices, certificates and certificate verification.

## Technology
React, Vite, Express, Prisma and PostgreSQL.

## Controls documented
- Server-side role enforcement.
- Password hashing, database-backed revocable sessions and account lockout.
- Two-step sign-in.
- Signed reports and certified audit records are locked against silent changes.
- Sequential document numbering.
- Client data separation and controlled invitations.

## Portfolio relevance
This project demonstrates workflow digitisation for industrial assessments, risk-data capture, controlled document lifecycles, role-based access and auditable business processes.

Private repository: https://github.com/akjayakody/leadma-audit-platform
