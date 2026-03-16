# Kardia Digital — Curated AI Agents

Curated fork of [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) for Salesforce consulting and web development work.

## What's Here

22 agents across 5 categories, selected for relevance to Salesforce platform development, Next.js/LWC frontend work, and project delivery.

### Engineering (13)
| Agent | Focus |
|---|---|
| Software Architect | System design and architectural decisions |
| Backend Architect | Generic backend/cloud architecture (kept for upstream sync) |
| Code Reviewer | Code review focused on correctness, security, maintainability |
| DevOps Automator | CI/CD, deployment pipelines, infrastructure |
| Technical Writer | Documentation, wiki pages, API references |
| Senior Developer | Generic full-stack (kept for upstream sync) |
| Frontend Developer | Generic frontend (kept for upstream sync) |
| Git Workflow Master | Git branching, commits, PR management |
| **Salesforce Developer** | Apex implementation — triggers, batch, integrations, Kardia standards |
| **Salesforce Flow Developer** | Flow automation — record-triggered, screen flows, subflow patterns |
| **LWC Developer** | Lightning Web Components, SLDS, Jest testing |
| **Next.js Developer** | Next.js App Router, TypeScript, Tailwind CSS |

### Testing (4)
| Agent | Focus |
|---|---|
| API Tester | API validation and testing |
| Evidence Collector | Screenshot-based QA verification |
| Reality Checker | Production readiness validation |
| Test Results Analyzer | Test output analysis and insight |

### Specialized (3)
| Agent | Focus |
|---|---|
| Agents Orchestrator | Multi-agent pipeline coordination |
| Document Generator | PDF/PPTX/DOCX generation |
| **Salesforce Architect** | Platform architecture, governor limits, integration patterns |

### Project Management (1)
| Agent | Focus |
|---|---|
| Senior Project Manager | Task decomposition and scope management |

### Design (2)
| Agent | Focus |
|---|---|
| UI Designer | Visual design systems and components |
| UX Architect | Technical architecture and UX foundations |

## Upstream Sync

Original agents are kept untouched for clean upstream merges. Kardia-specific agents (marked **bold** above) are additions.

```bash
# Pull upstream updates
git fetch upstream
git merge upstream/main
# Resolve any conflicts in Kardia-added files
```

## Origin

Forked from [The Agency](https://github.com/msitarzewski/agency-agents) by msitarzewski.
