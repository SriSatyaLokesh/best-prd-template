# PRD: [Feature/Product Name]

**Author:** [Name]
**Date:** [YYYY-MM-DD]
**Status:** Draft | In Review | Approved
**Version:** 1.0

---

## Table of Contents

1. [Executive Summary](#executive-summary)
2. [Problem Statement](#problem-statement)
3. [Goals & Success Metrics](#goals--success-metrics)
4. [User Stories](#user-stories)
5. [Functional Requirements](#functional-requirements)
6. [Non-Functional Requirements](#non-functional-requirements)
7. [Technical Considerations](#technical-considerations)
8. [Implementation Roadmap](#implementation-roadmap)
9. [Out of Scope](#out-of-scope)
10. [Open Questions & Risks](#open-questions--risks)
11. [Validation Checkpoints](#validation-checkpoints)
12. [Appendix: Task Breakdown Hints](#appendix-task-breakdown-hints)

---

## Executive Summary

[2-3 sentences: What problem are we solving + proposed solution + expected impact]

---

## Problem Statement

### Current Situation
[Describe what exists today and what's wrong with it]

### User Impact
- **Who is affected:** [User segment(s)]
- **How they're affected:** [Specific pain points]
- **Severity:** [Critical/High/Medium - with evidence/data]

### Business Impact
- **Cost of problem:** [Quantify: lost revenue, support tickets, churn]
- **Opportunity cost:** [What we're missing by not solving this]
- **Strategic importance:** [How this aligns with company goals]

### Why Solve This Now?
[Timing, market conditions, competitive pressure, technical readiness]

---

## Goals & Success Metrics

### Goal 1: [Primary Goal]
- **Description:** [What we're trying to achieve]
- **Metric:** [How we measure success]
- **Baseline:** [Current value with source]
- **Target:** [Goal value]
- **Timeframe:** [When we expect to achieve this]
- **Measurement Method:** [How we'll track: analytics, surveys, logs]

### Goal 2: [Secondary Goal]
- **Description:** [What we're trying to achieve]
- **Metric:** [How we measure success]
- **Baseline:** [Current value]
- **Target:** [Goal value]
- **Timeframe:** [When]
- **Measurement Method:** [How]

---

## User Stories

### Story 1: [Feature Name]

**As a** [user type],
**I want to** [action],
**So that I can** [benefit/outcome].

**Acceptance Criteria:**
- [ ] [Specific, testable criterion 1]
- [ ] [Specific, testable criterion 2]
- [ ] [Specific, testable criterion 3]
- [ ] [Edge case criterion]
- [ ] [Error handling criterion]

**Task Breakdown Hint:**
- Task 1.1: [Implementation step] (~4 hours)
- Task 1.2: [Implementation step] (~6 hours)
- Task 1.3: [Testing] (~2 hours)

**Dependencies:** [None | REQ-XXX | Story Y]

---

## Functional Requirements

### Must Have (P0) - Critical for Launch

#### REQ-001: [Requirement Title]
**Description:** [Detailed description of what the system must do]

**Acceptance Criteria:**
- [ ] [Specific, testable criterion]
- [ ] [Specific, testable criterion]

**Technical Specification:**
```
[Code example, API spec, or detailed technical description]
```

**Task Breakdown:**
- Implement [component]: Small (2-4h)
- Add [functionality]: Medium (4-8h)
- Test [feature]: Small (2-4h)

**Dependencies:** [None | REQ-XXX | External service Y]

---

### Should Have (P1) - Important but Not Blocking

#### REQ-002: [Requirement Title]
[Repeat structure]

---

## Non-Functional Requirements

### Performance
- **Response Time:** API endpoints < 200ms
- **Throughput:** Handle 1,000 req/sec normal load
- **Resource Usage:** Memory < 512MB per instance

### Security
- **Authentication:** JWT tokens
- **Data Protection:** TLS 1.3, encrypted PII
- **Compliance:** GDPR, CCPA

### Scalability
- **User Load:** 100k initial, scale to 1M

### Reliability
- **Uptime:** SLA 99.9%
- **Error Handling:** < 0.1% rate

### Accessibility
- **Standards:** WCAG 2.1 Level AA

### Compatibility
- **Browsers:** Current Chrome, Firefox, Safari, Edge
- **Devices:** Desktop, Mobile, Tablet responsive design

---

## Technical Considerations

### System Architecture
**Current & Proposed Integration Diagram:**
[Add ASCII/mermaid diagram or description]

### API Specifications
[Examples of primary API endpoints with requests/responses]

### Database Schema
[New/modified tables & indexes needed]

### Technology Stack
[Frontend, Backend, DB, Infrastructure tools]

### External Dependencies
[Third-party services and APIs utilized]

### Migration Strategy
[Database migrations, feature flag rollout, rollback plan]

### Testing Strategy
[Unit tests, E2E flows, coverage required]

---

## Implementation Roadmap

### Phase 1: Foundation (Week 1-x)
**Goal:** [Primary structural task]
- [ ] Task 1: [Create schema/base code]

### Phase 2: Core Features
**Goal:** [Main functional requirements]
- [ ] Task 2: [Build primary endpoints/UI]

### Phase 3: Polish & Deployment
**Goal:** [Testing & rollout]
- [ ] Task 3: [E2E test, production deploy]

---

## Out of Scope
[Explicitly call out features excluded from this release]

---

## Open Questions & Risks

### Open Questions
- **Q1:** [Question] | Status, Owner, Impact

### Risks & Mitigation
- **Risk 1:** [Risk] | Likelihood, Severity, Mitigation

---

## Validation Checkpoints

### Checkpoint 1: [Phase boundary]
**Criteria:**
- [ ] [Validation criteria 1]
**If Failed:** [Contingency]

---

## Appendix: Task Breakdown Hints
[High-level list of tasks mapped out in phases for project management import]
