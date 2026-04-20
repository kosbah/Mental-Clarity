# Mental Clarity — BMad Skill Menu

> **Rules for Claude:**
> - If the user types just **"help"**, immediately read and follow `.claude/skills/bmad-help/SKILL.md`
> - Whenever you reference a skill path or file name in any response, always wrap it in a code block for easy copy/paste

To run any skill, say: **"Read and follow `.claude/skills/<skill-name>/SKILL.md`"**

---

## Where am I in the workflow?

Type **"help"** — Claude will run BMad Help automatically.

---

## Phase 1 — Analysis & Research

| Code | What to say | What it does |
|------|-------------|--------------|
| BP | `bmad-brainstorming` | Brainstorm ideas with expert facilitation |
| CB | `bmad-product-brief` | Nail down your product idea in a brief |
| WB | `bmad-prfaq` | Stress-test your concept with Working Backwards |
| DR | `bmad-domain-research` | Deep dive into industry domain & terminology |
| MR | `bmad-market-research` | Market analysis, competitors, customer needs |
| TR | `bmad-technical-research` | Technical feasibility & architecture options |

## Phase 2 — Planning

| Code | What to say | What it does |
|------|-------------|--------------|
| CP | `bmad-create-prd` | Create your Product Requirements Document |
| VP | `bmad-validate-prd` | Validate your PRD |
| EP | `bmad-edit-prd` | Edit an existing PRD |
| CU | `bmad-create-ux-design` | Plan UX patterns and design specs |

## Phase 3 — Solutioning

| Code | What to say | What it does |
|------|-------------|--------------|
| CA | `bmad-create-architecture` | Document technical decisions (required) |
| CE | `bmad-create-epics-and-stories` | Break requirements into epics & stories (required) |
| IR | `bmad-check-implementation-readiness` | Verify PRD + UX + Architecture are aligned |
| TF | `bmad-testarch-framework` | Initialize test framework (Playwright/Cypress) |
| TD | `bmad-testarch-test-design` | Risk-based test planning |
| CI | `bmad-testarch-ci` | Configure CI/CD quality pipeline |

## Phase 4 — Implementation

| Code | What to say | What it does |
|------|-------------|--------------|
| SP | `bmad-sprint-planning` | Kick off sprint — produces story sequence plan |
| SS | `bmad-sprint-status` | Summarize sprint status & route to next step |
| CS | `bmad-create-story` | Prepare next story for development |
| VS | `bmad-create-story` (validate action) | Validate story readiness before coding |
| DS | `bmad-dev-story` | Execute story implementation |
| CR | `bmad-code-review` | Review code after dev story |
| QA | `bmad-qa-generate-e2e-tests` | Generate automated E2E/API tests |
| AT | `bmad-testarch-atdd` | ATDD — red-phase acceptance tests |
| TA | `bmad-testarch-automate` | Expand test coverage |
| CK | `bmad-checkpoint-preview` | Human review of commits/branches/PRs |
| ER | `bmad-retrospective` | Epic retrospective — lessons learned |

## Anytime

| Code | What to say | What it does |
|------|-------------|--------------|
| QQ | `bmad-quick-dev` | Quick intent-to-code workflow |
| CC | `bmad-correct-course` | Navigate significant changes or pivots |
| DP | `bmad-document-project` | Document existing project for AI context |
| GPC | `bmad-generate-project-context` | Generate lean LLM-optimized project context |
| AR | `bmad-review-adversarial-general` | Adversarial quality review of any document |
| ECH | `bmad-review-edge-case-hunter` | Edge case & boundary condition review |
| DT | `bmad-cis-design-thinking` | Human-centered design thinking |
| IS | `bmad-cis-innovation-strategy` | Innovation & disruption strategy |
| PS | `bmad-cis-problem-solving` | Systematic problem solving |
| ST | `bmad-cis-storytelling` | Craft compelling narratives |
| PM | `bmad-party-mode` | Multi-agent discussion / collaboration |
| SD | `bmad-shard-doc` | Split large docs (>500 lines) |

## Agents (specialist personas)

| What to say | Role |
|-------------|------|
| `bmad-agent-analyst` | Business analyst & requirements |
| `bmad-agent-architect` | System architect & technical design |
| `bmad-agent-dev` | Senior software engineer |
| `bmad-agent-pm` | Product manager |
| `bmad-agent-ux-designer` | UX designer & UI specialist |
| `bmad-agent-tech-writer` | Technical documentation |

## BMad Builder (build/edit skills & modules)

| Code | What to say | What it does |
|------|-------------|--------------|
| BA | `bmad-agent-builder` | Build or edit an agent skill |
| AA | `bmad-agent-builder` (analyze) | Quality analysis on an agent |
| BW | `bmad-workflow-builder` | Build or edit a workflow skill |
| AW | `bmad-workflow-builder` (analyze) | Quality analysis on a workflow |
| IM | `bmad-module-builder` | Ideate a new BMad module |
| CM | `bmad-module-builder` (create) | Scaffold a module |

---

## Mobile usage tip

On Claude Code Mobile, invoke any skill by saying:
> "Read and follow `.claude/skills/bmad-create-prd/SKILL.md`"

Replace `bmad-create-prd` with any skill name from the tables above.
