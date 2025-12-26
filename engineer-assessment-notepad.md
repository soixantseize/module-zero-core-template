# Software Engineer Skill Assessment

## Candidate Responses

| # | Category | Response Summary |
|---|----------|------------------|
| 1 | Background | 10+ years professional experience, .NET/C# focus, large codebase maintenance, feature development, defect resolution. Currently expanding into AWS (ECS, CodePipeline, Secrets Manager, Lambda) |
| 2 | Architecture & Patterns | Approaches unfamiliar code by understanding data flow (DB, controllers, APIs). Familiar with patterns but some conceptual gaps: DI described as singleton-based injection (partially correct - DI is broader). Repository Pattern confused with git repos (actually an abstraction layer for data access). Uses patterns in practice. |
| 3 | Debugging | Practical hands-on approach: connects local debugger to prod DB, steps through code as user, analyzes data flow and DB writes, checks DB logs and exceptions. Solid but relies on direct access. Didn't mention observability tools (APM, log aggregation, CloudWatch, distributed tracing). |
| 4 | Testing | Strong testing experience. Uses XUnit for unit tests, Postman for API tests with email alerting. Impressive modern E2E setup: TestContainers + Playwright + PostgreSQL running in CodePipeline. Spins up isolated containers (DB, API, frontend, Playwright) for real regression tests. Shows understanding of testing pyramid and CI/CD integration. |

## Assessment Summary

- **Overall Level**: TBD
- **Strengths**: TBD
- **Areas for Growth**: TBD

---

## Categories Evaluated
- [ ] Programming Fundamentals
- [ ] Data Structures & Algorithms
- [ ] System Design
- [ ] Software Architecture
- [ ] Testing & Quality
- [ ] DevOps & Tooling
- [ ] Problem Solving
