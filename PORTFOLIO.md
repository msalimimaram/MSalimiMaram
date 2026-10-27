# Project Portfolio

A concise review of selected software projects, their problem spaces, intended value, technical direction, and current limitations.

> **How to read this portfolio:** descriptions of goals and intended value are not claims of measured business impact. Project maturity is stated explicitly where known. No customer outcomes, revenue figures, adoption metrics, or production-readiness claims are asserted without evidence.

## 1. GAMva — OctoLife personal-growth platform

**Public preview:** https://gamva-preview.vercel.app/  
**Public source:** https://github.com/msalimimaram/gamva-preview  
**Related application repositories:** Django backend and Flutter mobile client are private.

### Problem space

Personal-development activities are often split across disconnected tools: habit tracking, goals, learning, challenges, wellbeing, and community. GAMva explores a more connected experience that helps users work across these areas without reducing progress to a public ranking.

### Product direction

The concept is organized around eight dimensions: Health, Learning, Financial wellbeing, Personal development, Career, Mental and emotional wellbeing, Challenge and entertainment, and Overcoming fears.

The wider product direction includes an OctoLife overview, goals and routines, challenges, progress reporting, social connections, content, profile controls, and a future coach/commerce ecosystem.

### Technical direction

- Public web preview: React, TypeScript, Vite, Tailwind CSS.
- Mobile client: Flutter and Dart (private repository).
- Backend: Django/Python (private repository).
- Product focus: mobile-first experience, coherent journeys, clear user control, and sustainable engagement.

### Intended business and user value

- Give users one coherent entry point for multiple personal-growth activities.
- Make progress and next actions easier to understand.
- Encourage consistency without punitive resets or shame-based motivation.
- Create a product foundation that can evolve across web preview, mobile, and backend services.

These are design goals, not measured outcomes.

### Current status and evidence

The public repository is a **product/UI preview**. Its README explicitly warns that not every screen or workflow should be assumed to be connected to production services or production-ready. The backend and mobile source are private and cannot be independently reviewed from the public preview alone.

**Review links:** [Live preview](https://gamva-preview.vercel.app/) · [Public repository](https://github.com/msalimimaram/gamva-preview)

---

## 2. Office KMC — insurance operations system

**Public source:** https://github.com/msalimimaram/office_kmc

### Problem space

Insurance operations involve related organizational records, policies, claims, requests, tasks, documents, imports, and correspondence. A workflow-oriented internal system can help structure these activities and make responsibilities and records easier to manage.

### Functional scope described in the repository

- Accounts, organizational structures, and people records.
- Insurance providers, insurance lines, contracts, and amendments.
- Claims registration and tracking.
- Requests and status workflows.
- Tasks, deadlines, documents, bulk Excel imports, and audit-related records.
- A Persian, right-to-left interface.

### Technical direction

- Python and Django.
- Django ORM and server-rendered templates.
- SQLite for local development and PostgreSQL as the intended non-development database.
- Role-oriented access patterns and supporting documentation for deployment, testing, and security review.

### Intended business value

- Structure recurring insurance-administration workflows.
- Keep related records in one domain-specific application.
- Support traceability and role-aware handling of operational data.
- Provide a Persian/RTL interface aligned with the intended users.

These are intended benefits; no quantified time savings, cost reductions, or adoption results are claimed.

### Current status and operational caution

The repository README identifies the system as **under development and suitable for controlled evaluation with synthetic data**. It explicitly says not to use real employee or insured-person data before required security and deployment work is complete. It also lists remaining release considerations, including permission testing, authentication hardening, file security, backups, deployment controls, and responsive testing.

**Review link:** [Office KMC source repository](https://github.com/msalimimaram/office_kmc)

---

## Working principles

Across projects, I aim to:

1. Understand the workflow and the people who depend on it.
2. Make product scope, technical boundaries, and assumptions explicit.
3. Prefer maintainable structures and useful documentation over unnecessary complexity.
4. Treat authorization, privacy, error handling, and testing as product requirements.
5. Report status honestly and separate implemented behavior from intended direction.

## Technical areas

- **Backend:** Python, Django, REST API design.
- **Mobile:** Flutter, Dart.
- **Web:** React, TypeScript, Vite, Tailwind CSS.
- **Engineering practices:** architecture, integration, testing, documentation, version control, and release planning.

## Collaboration

For the fastest assessment, start with the linked public repositories and their READMEs. Focused feedback, code review, and conversations about practical software problems are welcome.
