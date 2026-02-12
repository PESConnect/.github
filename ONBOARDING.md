# PES Global Developer Onboarding Guide

Welcome to PES Global Group / CassillyCapital Enterprise! This guide will help you get started with our development workflow and project management standards.

## Quick Links

| Resource | Link |
|----------|------|
| ERP Project Board | [View Roadmap](https://github.com/orgs/PESConnect/projects/4) |
| BSDYNO Infrastructure | [View Board](https://github.com/orgs/PESConnect/projects/2) |
| Odoo Migration Tracker | [View Progress](https://github.com/orgs/PESConnect/projects/3) |
| Contributing Guidelines | [CONTRIBUTING.md](./CONTRIBUTING.md) |
| Security Policy | [SECURITY.md](./SECURITY.md) |

## Project Management Methodology

We use **GitHub Projects** as our single source of truth for all project management. This follows Fortune 50 enterprise standards.

### Key Principles

1. **Every task is an issue** - No work happens without a tracked issue
2. **Every issue has dates** - Start Date and Target Date are required
3. **Every PR links to an issue** - Use "Closes #XX" in PR descriptions
4. **Views are standardized** - Roadmap (timeline) + Sprint Board (kanban)

### Required Project Fields

| Field | Purpose | Format |
|-------|---------|--------|
| Status | Track progress | Todo/In Progress/Done |
| Start Date | When work begins | YYYY-MM-DD |
| Target Date | Deadline | YYYY-MM-DD |
| Priority | Urgency level | Critical/High/Medium/Low |

## Development Workflow

### 1. Starting New Work

```
1. Check the project board for assigned issues
2. Move issue to "In Progress"
3. Create a feature branch: feature/issue-XX-description
4. Set Start Date on the issue
```

### 2. Creating Pull Requests

- Use the PR template (auto-applied)
- Fill out ALL sections
- Link to issue with "Closes #XX"
- Request review from team lead

### 3. Code Review Standards

- All PRs require at least 1 approval
- CI checks must pass
- No secrets in code
- Documentation updated if needed

## Repository Structure

| Repo | Purpose |
|------|---------|
| pes-odoo-erp-infrastructure | Main ERP implementation |
| bsdyno | Infrastructure and servers |
| .github | Org-wide templates (this repo) |

## Infrastructure Overview

### Architecture

- **Primary**: On-premises server (BSDYNO)
- **Secondary**: Azure hybrid cloud
- **Integration**: n8n automation workflows

### Key Technologies

- Odoo 19 Enterprise
- PostgreSQL database
- Docker containers
- Cloudflare tunnels

## Getting Help

1. Check existing issues and documentation
2. Ask in team Slack channel
3. Create a new issue using templates
4. Tag @ACassilly for urgent matters

## First Week Checklist

- [ ] Get GitHub organization access
- [ ] Review all project boards
- [ ] Read CONTRIBUTING.md
- [ ] Set up local development environment
- [ ] Clone key repositories
- [ ] Join team communication channels
- [ ] Complete first assigned issue

---

*Last updated: Auto-generated from .github repository*
