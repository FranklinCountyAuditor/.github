---
name: Business Analysis
about: Document business requirements, process flows, or data needs
title: ''
labels: 'type-documentation'
assignees: ''

---

## Requirement ID
A unique identifier for this requirement (e.g., FCA-REQUIREMENT-001)

## Summary
Brief description of the business need or process being documented.

## Business Context

### Stakeholders Involved

- **Primary User**: [Role, e.g., Tax Clerk, Auditor III]
- **Other Affected Parties**:

### Process Description

Current state vs desired future state (use diagrams if helpful or link to visual graph):

## Functional Requirements

**FR-1:** [Requirement description - what must happen]  
**FR-2:** [Requirement description]

## Non-Functional Requirements

| Category     | Requirement                                          | Priority |
| ------------ | ---------------------------------------------------- | -------- |
| Performance  | Response time < 5 seconds for \_\_\_ operations      | High     |
| Availability | System available during business hours (7am-6pm M-F) | Critical |
| Security     | All PII access logged and auditable                  | Critical |

## Data Requirements

### Source Systems

- Mainframe (FICO): [Tables/Fields needed]
- Property Database: [Tables/Fields needed]
- Tax Records DB: [Table relationships]

### New Fields/Tables Required

If applicable, list new data elements that need to be created.

## Audit & Compliance Considerations

- **Record Retention:** How long must records be kept?
- **Audit Trail:** What changes need to be logged?
- **Regulatory References:** Cite any statutes or regulations (e.g., ORC 57.11)

## Validation Rules

Business rules that data must satisfy:

- [ ] Rule 1 (e.g., Assessment value cannot exceed market value by more than 20%)
- [ ] Rule 2
- [Error handling when validation fails]

## Reporting Needs

List any reports or dashboards required to support this feature:

- Report Name: Purpose, Frequency, Audience
- Dashboard Elements: Key metrics to display

---

_Complete the following checklist before closing:_

- [ ] Requirements reviewed with business stakeholders
- [ ] Data mapping completed
- [ ] Acceptance criteria defined

