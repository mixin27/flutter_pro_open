# Team and Release Management Guide

## Automated Releases

- [Release Drafter](https://github.com/release-drafter/release-drafter) automatically updates draft release notes based on PRs and their labels.
- When ready for a release:
  1. Go to the "Releases" tab.
  2. Click “Edit” on the draft.
  3. Finalize the release/tag.

## Code Ownership

- The `.github/CODEOWNERS` file means PRs touching key folders request review automatically from the listed maintainers/teams.
- You can replace usernames with your GitHub org/team, e.g. `@yourorg/feature-x-owners`.
- CODEOWNERS also works with branch protections (“Require code owner review” in Settings > Branches).

## Auto-Labeling

- PRs are automatically labeled by folder/content using `.github/labeler.yml` and the labeler action.
- You can further extend these with labels for platform, priority, or product area.

## Boards and Branch Protection (Recommended)

- Use GitHub Projects (Beta) for kanban/roadmap boards.
- Enable branch protection on `main`: require PR, required status checks, and code owner approvals.

## Changelog

- CHANGELOG.md can be maintained manually, or generated/refined at release time via Release Drafter.

## Examples

- Edit `.github/CODEOWNERS` to fit your team.
- Extend `.github/labeler.yml` for more folders, modules, or domain-specific labels.
- Update `release-drafter.yml` for more customization of changelog templates.

---

Happy collaborating!
