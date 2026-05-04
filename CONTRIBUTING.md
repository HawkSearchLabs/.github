# Contributing to HawkSearch Developer Resources

Welcome! This GitHub organization hosts **examples, tools, and guides**
to help developers integrate with HawkSearch APIs.

**Note:** HawkSearch is a proprietary SaaS product.  
This repository does not contain internal HawkSearch source code.

---

## What You Can Contribute

We welcome contributions that help others use HawkSearch effectively:

- Code examples using public HawkSearch APIs
- Sample applications and UI integrations
- Developer tools (CLI helpers, Postman collections, Terraform modules)
- How-to guides and best practices

---

## Repository Structure

Each project or experiment lives in its **own dedicated repository** within the HawkSearch Labs organization. When submitting or proposing a new repository, please follow this structure:

```
your-project-name/
├── README.md               # Overview of the project
├── LICENSE                 # License for the project
├── CONTRIBUTING.md         # Contribution guidelines (this file)
├── OWNERS                  # Maintainers and owners of the repository
├── docs/                   # Project-level documentation
│
├── experiment_name/        # The core experiment or project folder
│   ├── README.md           # Explains this specific experiment
│   ├── src/                # Source code
│   └── results/            # Output, findings, or generated artifacts
│
└── shared/                 # Reusable resources across experiments
├── utils/              # Shared utility functions or scripts
├── libraries/          # Common libraries or dependencies
└── common-config/      # Shared configuration files
```

### Folder Guidelines

- **`experiment_name/`** — Rename this to reflect your actual project (e.g., `search-ranking-test/`). Each experiment should be self-contained with its own README and results.
- **`shared/`** — Place anything reusable here that isn't specific to one experiment. Avoid duplicating utilities across experiment folders.
- **`docs/`** — Use this for higher-level documentation: architecture decisions, API references, setup guides, etc.
- **`OWNERS`** — List the GitHub handles of the people responsible for maintaining this repo.

---

## Contribution Guidelines

### Starting a New Repository

1. Propose the repository in the [community discussions](https://github.com/HawkSearchLabs/community) before creating it
2. Use the structure above from the start — retrofitting structure later is harder
3. Name the repository clearly and consistently (kebab-case, e.g., `postman-collections`, `storefront-search-example`)

### Code Examples

- Must use **publicly documented APIs**
- Must not include API keys or credentials
- Should be minimal, readable, and runnable
- Each experiment folder must include a `README.md` explaining:
  - Use case
  - Prerequisites
  - How to run
  - Expected results

### Guides & Articles

- Place written guides in the `docs/` folder
- Focus on real-world use cases
- Prefer patterns and tradeoffs over marketing language
- Clearly label assumptions and limitations

---

## Review & Support Levels

Contributions may be labeled as:

- **Official Example** – reviewed and maintained by HawkSearch
- **Community Example** – contributed by users, lightly reviewed
- **Experimental** – not production-ready

---

## Code of Conduct

All contributors must follow our [Code of Conduct](./CODE_OF_CONDUCT.md).

Thank you for helping make HawkSearch easier to build with.
