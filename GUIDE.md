# Flutter Pro Open Source Project Guide

Welcome! This project template includes a complete, advanced setup for open source Flutter apps or packages.
It is modeled after top open source standards. This document explains every automation, template, and workflow you see here.

---

## 🗂️ Directory Overview

- `.github/`
  Contains issue templates (for bugs, features, docs, questions, tasks), a Pull Request template, workflows like automated CI and labeling.
- `lib/`
  Your Dart/Flutter code.
- `test/`
  Unit & widget tests.
- `example/`
  Example app for packages.
- Project root
  Docs, pubspec, code of conduct, license, and this guide.

---

## 🚦 CI & Automation

- **CI**: All pushes and PRs run formatting, analysis, and tests via GitHub Actions (`flutter_ci.yml`).
- **Auto-label**: All new issues auto-label with `triage` (see `auto_label.yml`). Customize as needed.
- **Issue/PR templates**: Standardizes information and process for contributors.

---

## 🛠️ Issue & PR Management

- Five issue templates: bug, feature, question, docs, task (see `.github/ISSUE_TEMPLATE/`)
- Blank issues are disabled; users are guided to use the right template or Discussions.
- PR template enforces standards for code, docs, and reviewer clarity.

---

## 🧑‍💻 Contribution Guide

- **See `CONTRIBUTING.md`** for step-by-step contribution flow!
- Issues are always created first (except trivial docs/typo PRs).
- PRs should reference and close the issue they address.
- Code formatting and tests must pass before merging.
- Be courteous: all contributors follow the [Code of Conduct](CODE_OF_CONDUCT.md).

---

## 🔖 Labels & Boards

- Issues are auto-labeled `triage` for maintainers to quickly review/route.
- Maintainers can add: `help wanted`, `good first issue`, `high priority`, `platform: ios`, etc.
- Consider using GitHub Projects for Kanban-style tracking.

---

## 🔒 Security & Stability

- Enable [Dependabot](https://github.com/dependabot) for dependency updates.
- Consider setting branch protection: Require PR, passing CI, and code review for main branches.

---

## 🎯 Customization

- Update Contact Links/Discussions URL in `.github/ISSUE_TEMPLATE/config.yml`.
- Customize workflow versions, Dart/Flutter versions, and pubspec as needed.

---

Happy Coding!
