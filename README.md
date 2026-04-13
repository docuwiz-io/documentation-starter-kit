# docuwiz-templates

> Write and ship docs the same way you write and ship code. These are Markdown templates for the most common doc types in a software project — versioned, forkable, and ready to drop into any repo.

If you're a developer, Docuwiz fits into how you already work. Write docs in Markdown, version them in Git, review them in PRs, and publish to a hosted portal in one click. No CMS. No "who has edit access" conversations.

---

## File structure

```
docuwiz-templates/
├── Architecture Overview_template_byDocuwiz.md
├── Best Practices & Guidelines_template_byDocuwiz.md
├── Changelog_template_byDocuwiz.md
├── Explanation_ Conceptual Guide_template_byDocuwiz.md
├── How-to Guide_ Task-Based_template_byDocuwiz.md
├── Reference_ Technical Lookup_template_byDocuwiz.md
├── Release Notes_template_byDocuwiz.md
├── Troubleshooting & FAQs_template_byDocuwiz.md
├── Tutorial_ Getting Started _template_byDocuwiz.md
└── README.md
```

---

## Templates at a glance

| Template | What it is |
|---|---|
| **Architecture Overview** | High-level map of system components, data flow, and security boundaries. Structural picture, no step-by-step. |
| **Best Practices & Guidelines** | Team-accumulated conventions — naming, config patterns, security hygiene, and things to avoid. Opinionated but not mandatory. |
| **Changelog** | Versioned, chronological log of changes grouped into Added, Changed, and Fixed. Developer-facing and diff-friendly. |
| **Conceptual Guide** | Answers "why does this work this way?" — builds a mental model before the reader touches anything. |
| **How-to Guide** | Task-based recipe for existing users. Clear steps, specific outcome, no background explanation needed. |
| **Reference** | Dense technical lookup — field definitions, allowed values, parameter types, defaults, validation rules. |
| **Release Notes** | Customer- and stakeholder-facing release communication. Covers new features, enhancements, fixes, and known issues. |
| **Troubleshooting & FAQs** | Structured problem-solving guide for when something breaks. Reduces support load, most-visited page in any dev portal. |
| **Getting Started Tutorial** | Hands-on onboarding for new users. Ends with a working setup, not just a feature tour. |

---

## When to use each template

| Template | Reach for it when... |
|---|---|
| **Architecture Overview** | Onboarding a new engineer, kicking off an integration, or documenting design decisions before a refactor |
| **Best Practices & Guidelines** | You want to raise the floor on how your team or users work with a system — before the mistakes happen |
| **Changelog** | You're shipping a release and need a scannable, versioned log that lives in the repo alongside the code |
| **Conceptual Guide** | A feature is abstract or non-obvious and how-to guides alone aren't sticking — readers need the "why" first |
| **How-to Guide** | A user knows what they want to do but not the exact sequence — config tasks, migrations, integrations |
| **Reference** | Someone is actively building or debugging and needs exact values, fast — this lives in a second tab |
| **Release Notes** | Announcing a version to customers, stakeholders, or a public audience beyond just your engineering team |
| **Troubleshooting & FAQs** | Shipping a feature with non-obvious failure modes, or deflecting repeat support questions proactively |
| **Getting Started Tutorial** | A user is touching your product for the first time and needs a guided path to a real, working outcome |

---

## Start from a template — in one click

Every template here is available directly inside the Docuwiz UI. Pick a doc type, hit **"Use Template"**, and you land in a pre-structured document ready to fill in — no blank page, no debating what sections to include.

Templates are opinionated by design. Each one is built around a specific reader, a specific goal, and a specific moment in the product lifecycle.

---

## Docuwiz for developers

**Docs as code.** Markdown files, Git versioning, PR reviews. Your docs live where your code lives.

**OAS linting.** Drop in an OpenAPI Specification file and get schema errors and warnings surfaced immediately — catch malformed specs before they hit your API consumers.

**AI-powered OAS enhancement.** Paste in a bare spec and Docuwiz enriches it with field descriptions, usage examples, parameter constraints, and enum values. From a functional file to production-quality API docs without the manual grind. [See a real example →](https://blog.docuwiz.io/p/case-study-transforming-specs-to)

**One-click publish.** Push docs to a hosted developer portal straight from the Docuwiz UI. No build pipeline, no deployment scripts.

---

## Resources

- [Cheatsheets](https://blog.docuwiz.io/s/cheatsheets) — quick reference guides for common doc patterns
- [Podcast](https://blog.docuwiz.io/podcast) — conversations on developer documentation, API design, and docs-as-code workflows
- [Docuwiz.io →](https://docuwiz.io)
