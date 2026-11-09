# Project Template

This repository is a starting point for a project. Fill in your own case, produce the analysis/design products, and build the implementation — all tracked through GitHub issues and pull requests.

## Getting started

1. Create your own repository from this template.
2. Describe your case in [assignment/assignment.md](assignment/assignment.md) and add your stakeholder interviews to [assignment/interviews.md](assignment/interviews.md). Both files contain placeholders (`[...]`) to replace.
3. Read [ISSUES_CREATION.md](ISSUES_CREATION.md) and open your first issues.

## Folders

1. [assignment/](assignment/) — the case brief and interview material (templates to fill in)
2. [products/](products/) — your analysis/design deliverables (persona, diagrams, specs, prototype, test plan)
3. [code/](code/) — the implementation

## Process

All work — analysis/design products and code alike — must be tracked through GitHub issues and resolved through pull requests. This is not optional: it's how you and your teammates stay able to follow what changed, why, and who reviewed it.

1. **Every piece of work starts as an issue.** Before you touch `products/` or `code/`, open an issue using one of the templates under **Issues → New issue**:
   - **Product Issue** — for analysis/design work (persona, diagrams, specs, prototype, UXD test plan, ...). One issue per deliverable, or per slice of a deliverable — see [ISSUES_CREATION.md](ISSUES_CREATION.md), Part A.
   - **Coding Issue** — for implementation work. One issue per acceptance criterion (vertical slice), or per sequence-diagram step/branch for cross-cutting concerns — see [ISSUES_CREATION.md](ISSUES_CREATION.md), Part B.

   Read [ISSUES_CREATION.md](ISSUES_CREATION.md) before opening issues — it explains how to split a story or product into issues that are small enough to review in one PR, and the size checks both templates ask you to confirm.

2. **No direct commits to the main branch.** All changes — product documents and code — are made on a branch and merged via a pull request. Never push straight to the main branch, even for "small" fixes.

3. **One issue → one branch → one pull request.** Name the branch after the issue, and reference the issue in the PR description with `Closes #<issue-number>` so the link shows up automatically and the issue closes on merge.

4. **Every pull request gets reviewed before merging.** A teammate (or, for product PRs, the reviewing pair using the **Peer Feedback** template) reviews the diff and leaves feedback on the issue/PR before it's merged. Don't merge your own PR without a review.

5. **Traceability is the point.** Because every change is: issue → branch → PR → review → merge, anyone (a teammate or us) can look at the issue tracker and reconstruct what was built, in what order, and who signed off on it. Skipping the process breaks that chain — it's the first thing we check when a milestone looks unclear.

## Case

See [assignment/assignment.md](assignment/assignment.md) for the case brief and [assignment/interviews.md](assignment/interviews.md) for the interview material it's based on.

## Products

See [products/products.md](products/products.md) for the list of analysis/design deliverables you need to produce, and [ISSUES_CREATION.md](ISSUES_CREATION.md) for how to turn each one into issues.

## Code

- [code/backend/](code/backend/) — an **example** microservice backend (auth service, catalog service and API gateway). It shows the expected setup and conventions; adapt, rename or replace the services to fit your own case. See [code/backend/README.md](code/backend/README.md) for how to run it.
- [code/frontend/](code/frontend/) — empty; add your frontend here.
