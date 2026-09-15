# Cloud Infrastructure Patterns

Practical platform engineering and cloud infrastructure patterns using Terraform, Kubernetes, Ansible, policy-as-code and CI/CD.

## Purpose

This repository is a hands-on engineering lab for exploring reusable cloud infrastructure and platform engineering patterns.

It serves three complementary purposes:

- **Public portfolio** — demonstrate practical platform engineering, infrastructure-as-code, Kubernetes, automation, policy-as-code and CI/CD patterns.
- **Practical engineering lab** — provide a space for hands-on experimentation with cloud infrastructure, GitHub, GitLab, artifact management, automation and platform tooling.
- **Migration specimen** — provide a controlled repository for exploring GitHub-to-GitLab migration, including source code, branches, CI/CD workflows, governance controls, metadata and documentation.

## Repository Organisation

The repository is organised by **engineering responsibility rather than individual tooling**.

| Directory | Responsibility | Typical content |
| --- | --- | --- |
| `infrastructure/` | Declarative infrastructure definitions | Terraform modules and cloud/platform configurations |
| `automation/` | Operational and orchestration tooling around infrastructure | Python automation, Ansible playbooks and operational scripts |
| `policy/` | Policy-as-code and governance controls | OPA/Rego, Sentinel and compliance policies |
| `catalog/` | Enterprise and platform metadata | Teams, business units, services and environments |
| `docs/` | Docs-as-code | Architecture, patterns, runbooks and migration guides |
| `tests/` | Validation and automated testing | Unit, integration, functional and BDD tests |

> **Tooling follows responsibility.** Terraform definitions belong with the infrastructure they describe, while operational automation belongs under `automation/`.

## Repository Structure

```text
.
├── .github/
│   └── workflows/
├── infrastructure/
│   ├── aws/
│   ├── azure/
│   ├── gcp/
│   └── oci/
├── automation/
│   ├── ansible/
│   └── python/
├── policy/
│   ├── opa/
│   └── sentinel/
├── catalog/
│   ├── business-units/
│   ├── environments/
│   ├── services/
│   └── teams/
├── docs/
│   ├── architecture/
│   ├── patterns/
│   └── runbooks/
└── tests/
    ├── bdd/
    ├── integration/
    └── unit/
