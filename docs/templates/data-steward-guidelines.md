# Data Steward Guidelines

**Purpose**: This document provides guidance for Data Steward responsibilities, including data quality checks, data dictionary ownership, and reporting cadence.

**Instructions**: Use these guidelines as a reference for the Data Steward role. Customize based on your organization's data governance policies and compliance requirements.

---

## Data Steward Role Overview

Data Stewards are responsible for ensuring data quality, consistency, governance, and compliance across systems and projects. They act as the authoritative source for data definitions and coordinate data-related requirements across teams.

---

## Core Responsibilities

### 1. Data Dictionary and Standards Ownership

**What**: Maintain a comprehensive, up-to-date data dictionary that defines all data elements, their business meaning, format, and ownership.

**Key Activities**:
- [ ] Create and maintain data dictionary/glossary: `[Link to data dictionary]`
- [ ] Define standard data formats, naming conventions, and classifications
- [ ] Document business rules and validation logic for data fields
- [ ] Establish data lineage (source systems, transformations, destinations)
- [ ] Define data ownership and stewardship assignments per domain
- [ ] Review and approve new data element definitions
- [ ] Ensure consistency of definitions across systems and teams

**Deliverables**:
- Data dictionary with field names, definitions, types, constraints, and owners
- Data standards documentation (naming conventions, formatting rules)
- Data lineage diagrams or documentation
- Data classification and sensitivity labels (e.g., PII, confidential)

**Cadence**: 
- Review and update data dictionary monthly or when new data elements are introduced
- Quarterly review of data standards with stakeholders

---

### 2. Data Quality Monitoring and Improvement

**What**: Monitor data quality metrics, identify data issues, and coordinate remediation efforts to maintain high-quality data.

**Key Activities**:
- [ ] Define data quality dimensions and metrics:
  - Completeness (% of required fields populated)
  - Accuracy (% of data matching expected values/ranges)
  - Consistency (% of data matching across systems)
  - Timeliness (data freshness and latency)
  - Validity (% conforming to business rules)
- [ ] Set data quality thresholds: `[e.g., completeness ≥95%, accuracy ≥98%]`
- [ ] Implement automated data quality checks and monitoring
- [ ] Generate data quality reports and dashboards: `[Link]`
- [ ] Identify and log data quality issues: `[Issue tracking system]`
- [ ] Coordinate with Engineering and BA to resolve data issues
- [ ] Track data quality trends over time

**Deliverables**:
- Data quality metrics dashboard
- Data quality reports (weekly/monthly)
- Data quality issue log with resolution status
- Data quality improvement plans

**Cadence**:
- Monitor data quality metrics continuously (automated)
- Weekly review of critical data quality issues
- Monthly data quality report to stakeholders
- Quarterly data quality retrospective and improvement planning

---

### 3. Data Governance and Compliance

**What**: Ensure data practices comply with organizational policies, regulatory requirements, and industry standards.

**Key Activities**:
- [ ] Understand and document applicable data regulations: `[e.g., GDPR, CCPA, HIPAA, SOC2]`
- [ ] Define and enforce data access controls and permissions
- [ ] Coordinate data privacy impact assessments (DPIAs)
- [ ] Ensure data retention and deletion policies are followed
- [ ] Monitor compliance with data security requirements
- [ ] Facilitate data governance committee or review board meetings
- [ ] Audit data usage and access logs for compliance
- [ ] Coordinate data breach response procedures (if applicable)

**Deliverables**:
- Data governance policies and procedures documentation
- Data access control matrix (who has access to what)
- Data retention schedules
- Compliance audit reports
- Data privacy impact assessments

**Cadence**:
- Ongoing monitoring of data access and usage
- Monthly compliance review
- Quarterly data governance committee meetings
- Annual compliance audits

---

### 4. Data Validation and Acceptance

**What**: Validate data deliverables (new data sources, migrations, integrations) to ensure accuracy, completeness, and compliance with requirements.

**Key Activities**:
- [ ] Review data requirements from Business Analyst: `[Link]`
- [ ] Define data validation rules and acceptance criteria
- [ ] Validate data models and schema designs with Engineering Lead
- [ ] Perform data profiling on new data sources
- [ ] Conduct data reconciliation for migrations and integrations:
  - Record counts match source and target
  - Key field values match
  - Data types and formats are correct
  - No unexpected null or default values
- [ ] Sign off on data deliverables when acceptance criteria are met
- [ ] Document known data issues and limitations

**Deliverables**:
- Data validation plans and test cases
- Data reconciliation reports
- Data migration sign-off documentation
- Known data issues and limitations log

**Cadence**:
- Ad hoc, triggered by new data sources, migrations, or integrations
- Sign-off within agreed timeline (e.g., within 5 business days of data delivery)

---

### 5. Data Access and Support

**What**: Facilitate data access requests, clarify data definitions, and provide guidance on data usage.

**Key Activities**:
- [ ] Process data access requests and coordinate approvals
- [ ] Answer questions about data definitions and usage
- [ ] Provide training or guidance on data standards and quality
- [ ] Coordinate with Data Engineering on data pipeline issues
- [ ] Support analytics and reporting teams with data clarifications
- [ ] Maintain FAQ or knowledge base for common data questions: `[Link]`

**Deliverables**:
- Data access request log and approvals
- Data usage documentation and FAQs
- Training materials on data standards

**Cadence**:
- Respond to data access requests within 2-3 business days
- Monthly office hours or Q&A sessions for data-related questions

---

## Interaction and Handoff Criteria

### Primary Touchpoints

**With Engineering Lead**:
- Validate data models and schema designs
- Coordinate on data quality automation and monitoring
- Resolve technical data issues

**With Business Analyst**:
- Clarify data requirements and business rules
- Define data acceptance criteria
- Validate that data supports business needs

**With Product Manager**:
- Prioritize data quality improvements
- Align on data roadmap and initiatives
- Report data quality risks

**With QA**:
- Validate data integrity in test environments
- Coordinate on data setup for testing
- Review data-related test cases

**With Compliance/Security**:
- Ensure data governance and privacy requirements
- Coordinate on data audits and access controls
- Respond to data security incidents

### Handoff Criteria

**Data Steward approves data deliverables when**:
- [ ] Data definitions are documented in data dictionary
- [ ] Data quality metrics meet agreed thresholds (e.g., completeness ≥95%, accuracy ≥98%)
- [ ] Data validation rules are implemented and passing
- [ ] Data migration (if applicable) is reconciled: record counts match, key values validated
- [ ] Data access controls and privacy requirements are validated
- [ ] Known data issues are documented and acceptable

---

## Reporting and Communication

### Regular Reports

**Weekly**:
- Critical data quality issues and resolution status
- Data access requests processed

**Monthly**:
- Data quality metrics report (completeness, accuracy, trends)
- Data dictionary updates and new definitions
- Compliance status update

**Quarterly**:
- Data governance review (policies, access controls, audits)
- Data quality retrospective and improvement plans
- Data roadmap and strategic initiatives

**Ad Hoc**:
- Data validation and migration reports
- Data incident reports (quality issues, security events)

### Communication Channels
- Data quality dashboard: `[Link]`
- Regular stakeholder meetings: `[Frequency]`
- Data governance committee: `[Frequency]`
- Slack/Teams channel for data questions: `[Channel name]`

---

## Tools and Resources

### Common Tools for Data Stewards
- **Data Dictionary**: `[Tool/Location - e.g., Confluence, data catalog tool]`
- **Data Quality Monitoring**: `[Tool - e.g., Great Expectations, custom dashboards]`
- **Data Lineage**: `[Tool - e.g., data lineage tool, documentation]`
- **Data Governance**: `[Tool - e.g., Collibra, Alation, spreadsheets]`
- **Issue Tracking**: `[Tool - e.g., Jira, GitHub Issues]`

### Reference Documentation
- Data governance policies: `[Link]`
- Data standards and conventions: `[Link]`
- Compliance requirements: `[Link]`
- Data architecture documentation: `[Link]`

---

## Best Practices

1. **Start with critical data**: Focus on high-value, high-risk data first (e.g., customer data, financial data)
2. **Automate quality checks**: Implement automated monitoring to catch issues early
3. **Make data dictionary accessible**: Ensure all team members can easily find and understand data definitions
4. **Collaborate closely**: Data Stewards succeed when they partner with Engineering, BA, and Product
5. **Document everything**: Good documentation prevents repeated questions and reduces risk
6. **Be proactive**: Monitor trends and address data quality degradation before it becomes critical
7. **Educate the team**: Share data best practices and build a data-conscious culture

---

## Example Data Quality Metrics

| Metric | Definition | Target | Current | Status |
|--------|------------|--------|---------|--------|
| Completeness | % of required fields populated | ≥95% | 97% | ✅ Pass |
| Accuracy | % of values matching expected range/format | ≥98% | 96% | ⚠️ Warning |
| Consistency | % of records matching across systems | ≥99% | 99.5% | ✅ Pass |
| Timeliness | % of data updated within SLA | ≥95% | 94% | ⚠️ Warning |
| Validity | % of records conforming to business rules | ≥98% | 99% | ✅ Pass |

---

## Why This Matters

High-quality data is foundational to effective decision-making, analytics, and operations. A Data Steward ensures:
- **Trust**: Teams can rely on data accuracy and consistency
- **Compliance**: Data practices meet regulatory and policy requirements
- **Efficiency**: Clear definitions and standards reduce confusion and rework
- **Risk mitigation**: Proactive monitoring catches data issues before they impact business
- **Scalability**: Well-governed data supports growth and new use cases

Use these guidelines to establish a strong data stewardship practice that supports your organization's data-driven goals.

---

**Related to Issue #5**: These guidelines support the Data Steward persona by providing comprehensive responsibilities, quality metrics, and collaboration touchpoints.
