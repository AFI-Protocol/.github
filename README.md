# .github

**Organization-wide GitHub configuration for AFI Protocol**

## Purpose

Centralized GitHub configuration, workflows, and templates for all AFI Protocol repositories.

## Contents

- **workflows/** - Reusable GitHub Actions workflows
- **ISSUE_TEMPLATE/** - Issue templates
- **PULL_REQUEST_TEMPLATE.md** - PR template
- **profile/README.md** - Organization profile
- **CONTRIBUTING.md** - Contribution guidelines
- **CODE_OF_CONDUCT.md** - Code of conduct
- **SECURITY.md** - Security policy

## Reusable Workflows

- `validate-typescript.yml` - TypeScript validation
- `validate-python.yml` - Python validation
- `validate-solidity.yml` - Solidity contract validation
- `deploy-docs.yml` - Documentation deployment
- `security-scan.yml` - Security scanning

## Usage

Repositories can reference these workflows:

```yaml
name: Validate
on: [push, pull_request]
jobs:
  validate:
    uses: AFI-Protocol/.github/.github/workflows/validate-typescript.yml@main
```

## Status

🚧 **New repository created during multi-repo reorganization (2025-11-14)**

This repo is part of the final AFI Protocol organization structure.

