<div align="center">
  <img src="velora-jobbook-logo.png" alt="Velora JobBook" width="150" />

  # Velora JobBook

  **Offline job tracking, money management, and invoicing for skilled professionals.**

  Flutter · Dart · SQLite · Android · AI-assisted development
</div>

> **Showcase repository:** The production source code is private because Velora JobBook is a commercial product. This public repository documents the problem, product decisions, working features, and development process.

## The problem

Independent technicians and contractors often manage jobs, customer details, payments, expenses, and outstanding balances across notebooks, messaging apps, and scattered files. That makes it difficult to see what work is active, what money is due, and what happened on a completed job.

Velora JobBook brings those daily workflows into one offline-first Android application designed for practical use in the field.

## Target users

- Independent technicians and service professionals
- Small contractors and trade businesses
- People who need simple job and money records without depending on a constant internet connection

## My role

**Founder, Product Builder, and AI-Assisted App Developer**

I identified the problem, defined the product scope and business rules, designed the user flows and interface direction, prioritized the Beta/V1 roadmap, directed AI-assisted implementation, tested complete workflows, reviewed fixes, and prepared Beta releases.

I used ChatGPT, Claude, and Codex as development partners. I do not present myself as having manually written every line of the application. My contribution is turning a real user problem into detailed product decisions, evaluating the generated implementation, testing it, and iterating until the workflows work as intended.

## Key features

- Dashboard with job and financial summaries
- Job creation, editing, status tracking, and searchable records
- Customer, worker, and supplier management
- Income and expense tracking linked to jobs and accounts
- Receivables, payables, and partial-settlement tracking
- Invoice review, signatures, PDF generation, and a saved invoice library
- Business reports with PDF preview and export
- Business profile and category configuration
- Local backup and restore with integrity validation
- Offline-first local storage

## Product workflow

```text
Business setup
      ↓
Create customer and job
      ↓
Track progress and job-related money
      ↓
Review and finalize invoice
      ↓
Capture signatures and generate PDF
      ↓
Review reports, receivables, and payables
```

## AI-assisted development workflow

1. Start with the user problem and define the intended outcome.
2. Break the product into workflows, business rules, and acceptance criteria.
3. Give AI coding tools scoped implementation tasks with relevant context.
4. Review the result against the product requirements and existing architecture.
5. Run automated tests and manually test complete user journeys.
6. Report failures precisely, refine the specification, and iterate.
7. Keep releases controlled through Beta milestones and regression checks.

AI accelerated implementation, but product judgment, scope, prioritization, review, and final acceptance remained human-led.

## Tech stack

| Area | Technology |
|---|---|
| Application | Flutter and Dart |
| Platform | Android (with a cross-platform Flutter codebase) |
| Local data | SQLite via `sqflite` |
| State management | Provider |
| Documents | PDF generation, preview, printing, and sharing |
| Signatures | In-app signature capture |
| Backup | Portable archive with manifest and SHA-256 integrity validation |
| Quality | Flutter unit, widget, repository, migration, and integration tests |
| Development support | ChatGPT, Claude, and Codex |

## Screenshots

Clean product screenshots are being prepared for this section.

| Dashboard | Job workflow | Invoice and reports |
|---|---|---|
| _Screenshot coming soon_ | _Screenshot coming soon_ | _Screenshot coming soon_ |

## Demo

A short product walkthrough is being prepared. It will cover:

`Dashboard → create a job → record work and money → finalize an invoice → review reports`

## Current status

**Version 0.9.0-beta.2**

The product is in Beta and is being refined through workflow testing, regression testing, and user feedback before a stable V1 release. This repository intentionally avoids claiming production-scale adoption or results that have not yet been measured.

## What this project demonstrates

- Turning an unstructured business problem into a scoped product
- Designing connected workflows rather than isolated screens
- Managing complex rules across jobs, money, invoices, and reports
- Working effectively with AI coding agents while keeping ownership of product decisions
- Testing and iterating toward a usable release
- Communicating honestly about both the work completed and the role AI played

## Contact

**Amith Baiju E**  
Founder & AI-Assisted Product Builder  
Email: [amithbaijuedakkalathur@gmail.com](mailto:amithbaijuedakkalathur@gmail.com)  
LinkedIn: [linkedin.com/in/amith-baiju](https://www.linkedin.com/in/amith-baiju/)

A demo link will be added after the walkthrough is ready.

---

© 2026 Amith Baiju E. Product identity and showcase content are shared for portfolio review. Production source code is not included.
