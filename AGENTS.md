## Agents

108 specialized AI agents for OpenCode. Agents are stored in `.opencode/agents/` as Markdown files with YAML frontmatter.

**Using Agents:** Agents are automatically discovered. Invoke any agent with `@agent-name` in your message. Example: `@python-pro optimize this function`.

**Discovery:** Consult `INDEX.md` at repo root for the full categorized agent directory (108 agents grouped by domain). Pick the MOST specialized agent — domain-specific checklists and anti-patterns only work when the agent matches the domain.

### Agent Categories

| Category | Count | Examples |
|----------|-------|----------|
| Language Implementation | 22 | python-pro, golang-pro, rust-pro, typescript-pro |
| Web Frameworks | 10 | react-pro, nextjs-pro, django-pro, fastapi-pro |
| Architecture & Design | 9 | backend-architect, api-designer, microservices-architect |
| DevOps & Infrastructure | 11 | devops-engineer, kubernetes-architect, cloud-architect |
| Security | 6 | security-reviewer, penetration-tester, threat-modeling-pro |
| Database | 5 | postgres-pro, sql-pro, database-architect |
| Testing & Quality | 5 | code-reviewer, tdd-guide, test-automator |
| AI & ML | 5 | ai-engineer, ml-engineer, prompt-engineer |
| Frontend & Mobile | 5 | frontend-developer, ios-pro, ui-designer |
| Documentation | 7 | documentation-pro, technical-writer, docs-architect |
| Incident & Troubleshooting | 4 | incident-responder, debugger, devops-troubleshooter |
| Specialized | 19 | build-engineer, cli-developer, product-manager, etc. |

### Agent Selection

Most specialized wins (e.g., postgres-pro over database-optimizer). Split hybrid tasks into subtasks with different agents.
