# PES Global Contributing Guidelines

> **This document establishes the standard project management methodology for all PESConnect repositories.**

---

## Project Management Standards

### Every New Project MUST Have:

1. **GitHub Project** with:
   - Roadmap view (Gantt-style timeline)
   - Sprint Board view (Kanban: Todo / In Progress / Done)
   - Start Date and Target Date fields configured

2. **Milestones** for phase tracking:
   - Create milestones for each major phase
   - Assign due dates to milestones
   - Link all issues to appropriate milestones

3. **Issues** for all trackable work:
   - Use issue templates (see below)
   - Always assign to a Project
   - Always assign to a Milestone
   - Set Start Date and Target Date

---

## Issue Creation Checklist

Before creating an issue, ensure:

- [ ] Title follows format: `[Phase/Area] Brief Description`
- [ ] Description includes Objective, Tasks (with checkboxes), and Acceptance Criteria
- [ ] Assigned to appropriate GitHub Project
- [ ] Assigned to correct Milestone
- [ ] Start Date and Target Date set
- [ ] Appropriate labels applied

---

## Standard Issue Structure

```markdown
## Objective
Brief description of what this issue accomplishes.

## Tasks
- [ ] Task 1
- [ ] Task 2
- [ ] Task 3

## Acceptance Criteria
- Criterion 1
- Criterion 2

## Dependencies
- List any blocking issues or prerequisites
```

---

## Branch Naming Convention

| Type | Format | Example |
|------|--------|--------|
| Feature | `feat/description` | `feat/shopify-connector` |
| Bugfix | `fix/description` | `fix/login-error` |
| Cursor AI | `cursor/description-id` | `cursor/pricing-engine-973e` |
| Hotfix | `hotfix/description` | `hotfix/critical-patch` |

---

## Pull Request Standards

1. **Link to Issue**: Every PR must reference the issue it resolves
2. **Description**: Explain what changed and why
3. **Checklist**: Complete the PR template checklist
4. **Review**: Request review from at least one team member

---

## Active GitHub Projects

| Project | Purpose | Link |
|---------|---------|------|
| PES Global Odoo 19 ERP Implementation | ERP deployment across 23 entities | [Project #4](https://github.com/orgs/PESConnect/projects/4) |
| BSDYNO Webshop - Launch Roadmap Q1 2026 | Big Sky Dynamics webshop launch | [Project #3](https://github.com/orgs/PESConnect/projects/3) |
| Odoo 18 to 19 Enterprise Migration | Version migration tracking | [Project #2](https://github.com/orgs/PESConnect/projects/2) |

---

## Quick Start for New Team Members

1. **View all projects**: [PESConnect Projects](https://github.com/orgs/PESConnect/projects)
2. **Check your assigned issues**: Filter by assignee in any project
3. **Update status**: Drag cards on Sprint Board as you progress
4. **Set dates**: Click issue -> Set Start Date and Target Date for roadmap visibility

---

## Questions?

Reach out via the [Support](./SUPPORT.md) channels.
