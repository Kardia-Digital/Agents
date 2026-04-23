# Kardia Digital — Curated AI Agents

Curated fork of [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) for Salesforce consulting and web development work.

## What's Here

32 agents across 5 categories, selected for relevance to Salesforce platform development, Next.js/LWC frontend work, and project delivery. All retained agents follow the Kardia slim pattern: YAML frontmatter + Identity + Mission + Critical Rules + Standards (with wiki pointers rather than inlined methodology).

### Engineering (17)
| Agent | Focus |
|---|---|
| Software Architect | System design and architectural decisions |
| Backend Architect | Generic backend/cloud architecture |
| Code Reviewer | Code review focused on correctness, security, maintainability |
| DevOps Automator | CI/CD, deployment pipelines, infrastructure |
| Technical Writer | Documentation, wiki pages, API references |
| Senior Developer | Generic full-stack |
| Frontend Developer | Generic frontend |
| Git Workflow Master | Git branching, commits, PR management |
| AI Engineer | Agentforce, prompt builder, model configuration |
| Security Engineer | Salesforce + web application security |
| Database Optimizer | SOQL selectivity, governor budgets, RDBMS tuning |
| Minimal Change Engineer | Surgical implementation — smallest diff that solves the problem |
| Codebase Onboarding Engineer | Org / repo exploration and onboarding for new engineers |
| **Salesforce Developer** | Apex implementation — triggers, batch, integrations, Kardia standards |
| **Salesforce Flow Developer** | Flow automation — record-triggered, screen flows, subflow patterns |
| **LWC Developer** | Lightning Web Components, SLDS, Jest testing |
| **Next.js Developer** | Next.js App Router, TypeScript, Tailwind CSS |

### Testing (6)
| Agent | Focus |
|---|---|
| API Tester | API validation and testing |
| Evidence Collector | Screenshot-based QA verification |
| Reality Checker | Production readiness validation |
| Test Results Analyzer | Test output analysis and insight |
| Accessibility Auditor | WCAG 2.1 AA audits on LWC + Next.js with screen-reader traces |
| Performance Benchmarker | Salesforce governor limits + Next.js Core Web Vitals |

### Specialized (5)
| Agent | Focus |
|---|---|
| Agents Orchestrator | Multi-agent pipeline coordination |
| Document Generator | PDF/PPTX/DOCX generation |
| Compliance Auditor | SOC 2 / HIPAA-aligned audit readiness and evidence |
| Automation Governance Architect | n8n governance + Salesforce integration patterns |
| **Salesforce Architect** | Platform architecture, governor limits, integration patterns |

### Project Management (1)
| Agent | Focus |
|---|---|
| Senior Project Manager | Task decomposition and scope management |

### Design (3)
| Agent | Focus |
|---|---|
| UI Designer | Visual design systems and components |
| UX Architect | Technical architecture and UX foundations |
| UX Researcher | Small-sample qualitative + behavioural-analytics research |

## Upstream Sync Policy

Origin: forked from [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents). Upstream adds marketing, gaming, content-creation, and similar agents that Kardia does not use — those categories are intentionally skipped during merges.

**Retained categories** (merge-tracked): `engineering/`, `testing/`, `design/`, `specialized/`, `project-management/`.

**Skipped categories** (do not merge from upstream): `marketing/`, `gaming/`, `content-creation/`, `legacy/`, plus any new top-level category that isn't on the retained list.

**Before merging upstream:**
1. Review new agents against the retained-categories list — don't blanket-merge
2. Adopt only agents that fit Kardia's Salesforce + web delivery surface
3. Slim any adopted agent to the Kardia pattern (see existing agents for structure) *before* committing
4. Update this README's count and tables
5. Check if the upstream changed a Kardia-retained agent — if yes, reconcile manually rather than accepting upstream wholesale (our slims diverge from upstream content)

Kardia-specific agents (marked **bold** in tables above) are additions — never pushed upstream, never overwritten by upstream merges.

```bash
# Pull upstream updates — review before merging
git fetch upstream
git log upstream/main --oneline --name-only | head -50   # see what changed
# Cherry-pick category-by-category instead of blanket merge
```

## Origin

Forked from [The Agency](https://github.com/msitarzewski/agency-agents) by msitarzewski.
