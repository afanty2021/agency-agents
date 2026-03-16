[根目录](../CLAUDE.md) > **project-management**

---

# Project Management Agents - AI Context Documentation

> **Category**: Project Management
> **Agent Count**: 6
> **Last Updated**: 2026-03-16 02:11:39 UTC

## 📋 Breadcrumb Navigation

[根目录](../CLAUDE.md) > **project-management**

---

## Module Overview

The Project Management category contains **6 specialized agents** covering the full project lifecycle, from experiment tracking and workflow stewardship to strategic portfolio management, studio operations, and production oversight. These agents excel at coordinating complex cross-functional initiatives, maintaining operational excellence, and driving data-driven decision making.

### Core Philosophy

Project management agents are designed to be:
- **Stakeholder-Focused**: Clear communication, expectation alignment, and transparent reporting
- **Data-Driven**: Evidence-based decisions through rigorous experimentation and metrics tracking
- **Process-Disciplined**: Structured workflows, traceable deliverables, and quality gates
- **Strategically Aligned**: Balancing operational excellence with business objectives and creative vision

---

## Agent Inventory

### Core Project Management (3 agents)

| Agent | Specialty | Key Capabilities |
|-------|-----------|------------------|
| **Project Shepherd** | Cross-functional project coordination, stakeholder alignment, timeline management | Project charters, status reporting, risk mitigation, resource coordination |
| **Senior Project Manager** | Strategic project leadership, complex initiative orchestration, executive communication | Portfolio management, stakeholder management, change leadership |
| **Jira Workflow Steward** | Git workflow governance, traceable commits, branch strategy enforcement | Jira-linked workflows, commit hygiene, PR templates, delivery traceability |

### Operations & Production (2 agents)

| Agent | Specialty | Key Capabilities |
|-------|-----------|------------------|
| **Studio Operations** | Daily operational efficiency, process optimization, resource coordination | SOPs, vendor management, automation, continuous improvement |
| **Studio Producer** | Strategic portfolio management, creative vision alignment, executive leadership | Strategic planning, resource allocation, business development, innovation strategy |

### Experimentation & Analytics (1 agent)

| Agent | Specialty | Key Capabilities |
|-------|-----------|------------------|
| **Experiment Tracker** | A/B testing, hypothesis validation, statistical analysis | Experiment design, statistical rigor, data-driven insights, portfolio management |

---

## Key Interfaces & Workflows

### Common Project Management Patterns

#### Full Project Lifecycle Workflow

```mermaid
graph LR
    A[Experiment Tracker] --> B[Project Shepherd]
    B --> C[Senior Project Manager]
    C --> D[Jira Workflow Steward]
    D --> E[Studio Operations]
    E --> F[Studio Producer]
```

**Agent Sequence**:
1. **Experiment Tracker**: Validate hypotheses through A/B testing and data analysis
2. **Project Shepherd**: Coordinate cross-functional execution and stakeholder alignment
3. **Senior Project Manager**: Provide strategic oversight and portfolio orchestration
4. **Jira Workflow Steward**: Ensure traceable delivery with proper Git workflow discipline
5. **Studio Operations**: Maintain operational excellence and process efficiency
6. **Studio Producer**: Align initiatives with strategic objectives and business vision

#### Experiment-Driven Development Workflow

```mermaid
graph LR
    A[Experiment Tracker] --> B[Project Shepherd]
    B --> C[Jira Workflow Steward]
    C --> D[Studio Operations]
```

**Agent Sequence**:
1. **Experiment Tracker**: Design and execute statistically valid experiments
2. **Project Shepherd**: Coordinate implementation based on experimental outcomes
3. **Jira Workflow Steward**: Ensure traceable delivery with proper branch strategy
4. **Studio Operations**: Maintain operational processes and documentation

#### Strategic Portfolio Management Workflow

```mermaid
graph LR
    A[Studio Producer] --> B[Senior Project Manager]
    B --> C[Project Shepherd]
    C --> D[Studio Operations]
```

**Agent Sequence**:
1. **Studio Producer**: Define strategic vision and portfolio priorities
2. **Senior Project Manager**: Orchestrate strategic initiatives and resource allocation
3. **Project Shepherd**: Execute cross-functional project coordination
4. **Studio Operations**: Maintain operational efficiency and process optimization

---

## Technical Deliverables

### Project Charter Template (Project Shepherd)

```markdown
# Project Charter: [Project Name]

## Project Overview
**Problem Statement**: [Clear issue or opportunity being addressed]
**Project Objectives**: [Specific, measurable outcomes and success criteria]
**Scope**: [Detailed deliverables, boundaries, and exclusions]
**Success Criteria**: [Quantifiable measures of project success]

## Stakeholder Analysis
**Executive Sponsor**: [Decision authority and escalation point]
**Project Team**: [Core team members with roles and responsibilities]
**Key Stakeholders**: [All affected parties with influence/interest mapping]
**Communication Plan**: [Frequency, format, and content by stakeholder group]

## Resource Requirements
**Team Composition**: [Required skills and team member allocation]
**Budget**: [Total project cost with breakdown by category]
**Timeline**: [High-level milestones and delivery dates]
**External Dependencies**: [Vendor, partner, or external team requirements]

## Risk Assessment
**High-Level Risks**: [Major project risks with impact assessment]
**Mitigation Strategies**: [Risk prevention and response planning]
**Success Factors**: [Critical elements required for project success]
```

### Experiment Design Document Template (Experiment Tracker)

```markdown
# Experiment: [Hypothesis Name]

## Hypothesis
**Problem Statement**: [Clear issue or opportunity]
**Hypothesis**: [Testable prediction with measurable outcome]
**Success Metrics**: [Primary KPI with success threshold]
**Secondary Metrics**: [Additional measurements and guardrail metrics]

## Experimental Design
**Type**: [A/B test, Multi-variate, Feature flag rollout]
**Population**: [Target user segment and criteria]
**Sample Size**: [Required users per variant for 80% power]
**Duration**: [Minimum runtime for statistical significance]
**Variants**:
- Control: [Current experience description]
- Variant A: [Treatment description and rationale]

## Risk Assessment
**Potential Risks**: [Negative impact scenarios]
**Mitigation**: [Safety monitoring and rollback procedures]
**Success/Failure Criteria**: [Go/No-go decision thresholds]

## Implementation Plan
**Technical Requirements**: [Development and instrumentation needs]
**Launch Plan**: [Soft launch strategy and full rollout timeline]
**Monitoring**: [Real-time tracking and alert systems]
```

### Jira Delivery Packet Template (Jira Workflow Steward)

```markdown
# Jira Delivery Packet

## Ticket
- Jira: JIRA-315
- Outcome: Fix token refresh race without changing the public API

## Planned Branch
- bugfix/JIRA-315-fix-token-refresh

## Planned Commits
1. 🐛 JIRA-315: fix refresh token race in auth service
2. 🧪 JIRA-315: add concurrent refresh regression tests
3. 📚 JIRA-315: document token refresh failure modes

## Review Notes
- Risk area: authentication and session expiry
- Security check: confirm no sensitive tokens appear in logs
- Rollback: revert commit 1 and disable concurrent refresh path if needed
```

### Standard Operating Procedure Template (Studio Operations)

```markdown
# SOP: [Process Name]

## Process Overview
**Purpose**: [Why this process exists and its business value]
**Scope**: [When and where this process applies]
**Responsible Parties**: [Roles and responsibilities for process execution]
**Frequency**: [How often this process is performed]

## Prerequisites
**Required Tools**: [Software, equipment, or materials needed]
**Required Permissions**: [Access levels or approvals needed]
**Dependencies**: [Other processes or conditions that must be completed first]

## Step-by-Step Procedure
1. **[Step Name]**: [Detailed action description]
   - **Input**: [What is needed to start this step]
   - **Action**: [Specific actions to perform]
   - **Output**: [Expected result or deliverable]
   - **Quality Check**: [How to verify step completion]

## Quality Control
**Success Criteria**: [How to know the process completed successfully]
**Common Issues**: [Typical problems and their solutions]
**Escalation**: [When and how to escalate problems]

## Documentation and Reporting
**Required Records**: [What must be documented]
**Reporting**: [Any status updates or metrics to track]
**Review Cycle**: [When to review and update this process]
```

### Strategic Portfolio Plan Template (Studio Producer)

```markdown
# Strategic Portfolio Plan: [Fiscal Year/Period]

## Executive Summary
**Strategic Objectives**: [High-level business goals and creative vision]
**Portfolio Value**: [Total investment and expected ROI across all projects]
**Market Opportunity**: [Competitive positioning and growth targets]
**Resource Strategy**: [Team capacity and capability development plan]

## Project Portfolio Overview
**Tier 1 Projects** (Strategic Priority):
- [Project Name]: [Budget, Timeline, Expected ROI, Strategic Impact]
- [Resource allocation and success metrics]

**Tier 2 Projects** (Growth Initiatives):
- [Project Name]: [Budget, Timeline, Expected ROI, Market Impact]
- [Dependencies and risk assessment]

**Innovation Pipeline**:
- [Experimental initiatives with learning objectives]
- [Technology adoption and capability development]

## Resource Allocation Strategy
**Team Capacity**: [Current and planned team composition]
**Skill Development**: [Training and capability building priorities]
**External Partners**: [Vendor and freelancer strategic relationships]
**Budget Distribution**: [Investment allocation across portfolio tiers]

## Risk Management and Contingency
**Portfolio Risks**: [Market, competitive, and execution risks]
**Mitigation Strategies**: [Risk prevention and response planning]
**Contingency Planning**: [Alternative scenarios and backup plans]
**Success Metrics**: [Portfolio-level KPIs and tracking methodology]
```

---

## Dependencies & Integrations

### External Tool Dependencies

Project management agents integrate with various tools and platforms:

- **Project Management**: Jira, Asana, Monday.com, Linear, Notion
- **Workflow & Git**: GitHub, GitLab, Bitbucket, Git workflows
- **Communication**: Slack, Microsoft Teams, Discord
- **Documentation**: Confluence, Notion, Google Workspace
- **Analytics**: Google Analytics, Mixpanel, Amplitude, Tableau
- **Experimentation**: Optimizely, VWO, Firebase Remote Config
- **Operations**: Jira Service Management, ServiceNow, Zendesk

### Integration Patterns

```bash
# Convert project-management agents for different tools
./scripts/convert.sh --tool cursor     # .cursor/rules/*.mdc
./scripts/convert.sh --tool opencode   # .opencode/agents/*.md
./scripts/convert.sh --tool qwen       # .qwen/agents/*.md
```

---

## Testing & Quality Assurance

### Quality Standards for Project Management Agents

- ✅ **Deliverable Templates**: All agents must provide practical, usable templates
- ✅ **Stakeholder Communication**: Clear, concise, and appropriately scoped messaging
- ✅ **Data Integrity**: Accurate metrics, proper statistical analysis, and honest reporting
- ✅ **Process Documentation**: Comprehensive SOPs and workflow documentation
- ✅ **Risk Management**: Proactive identification and mitigation of project risks
- ✅ **Traceability**: Clear audit trails from requirements to delivery

### Success Metrics

Project management agents should deliver:
- **On-Time Delivery**: 95% of projects completed within approved timelines
- **Stakeholder Satisfaction**: 4.5/5 rating for communication and management
- **Data-Driven Decisions**: Evidence-based recommendations with proper statistical rigor
- **Process Efficiency**: Measurable improvements in operational workflows
- **Risk Mitigation**: 90% of identified risks addressed before impacting outcomes
- **Strategic Alignment**: Portfolio initiatives aligned with business objectives

---

## Common Workflows

### 1. Experiment-Driven Feature Development

```
Experiment Tracker → Project Shepherd → Jira Workflow Steward → Studio Operations
```

**Steps**:
1. Design and execute A/B test (Experiment Tracker)
2. Analyze results and provide go/no-go recommendation (Experiment Tracker)
3. Coordinate implementation based on validated hypothesis (Project Shepherd)
4. Ensure traceable delivery with proper Git workflow (Jira Workflow Steward)
5. Update operational processes and documentation (Studio Operations)

### 2. Strategic Initiative Launch

```
Studio Producer → Senior Project Manager → Project Shepherd → Studio Operations → Jira Workflow Steward
```

**Steps**:
1. Define strategic vision and portfolio priorities (Studio Producer)
2. Orchestrate strategic planning and resource allocation (Senior Project Manager)
3. Execute cross-functional project coordination (Project Shepherd)
4. Maintain operational efficiency and process optimization (Studio Operations)
5. Ensure traceable delivery and workflow compliance (Jira Workflow Steward)

### 3. Process Optimization Initiative

```
Studio Operations → Project Shepherd → Senior Project Manager → Studio Producer
```

**Steps**:
1. Identify process bottlenecks and optimization opportunities (Studio Operations)
2. Design and implement improved workflows (Project Shepherd)
3. Monitor adoption and measure impact (Senior Project Manager)
4. Evaluate strategic alignment and portfolio impact (Studio Producer)

---

## FAQ

**Q: How do I choose between Project Shepherd and Senior Project Manager?**
A: Project Shepherd specializes in hands-on cross-functional coordination and execution. Senior Project Manager focuses on strategic leadership, portfolio management, and executive-level stakeholder management. Use Project Shepherd for individual project execution; use Senior Project Manager for complex, multi-project initiatives requiring strategic oversight.

**Q: What's the difference between Studio Operations and Studio Producer?**
A: Studio Operations focuses on day-to-day operational efficiency, process optimization, and resource coordination. Studio Producer is a strategic leadership role focused on portfolio management, creative vision alignment, and business development. Studio Operations ensures smooth execution; Studio Producer drives strategic growth and market positioning.

**Q: When should I use the Experiment Tracker vs. other project management agents?**
A: Use Experiment Tracker when you need to validate hypotheses through A/B testing, statistical analysis, or data-driven experimentation. Other project management agents focus on execution and coordination; Experiment Tracker specializes in scientific methodology and rigorous experimentation to inform decision-making.

**Q: Do these agents work together?**
A: Yes! Project management agents are designed to collaborate effectively. See the Common Workflows section for examples of multi-agent orchestration for complex initiatives ranging from experiment-driven development to strategic portfolio management.

**Q: How does Jira Workflow Steward integrate with other project management agents?**
A: Jira Workflow Steward provides the delivery discipline and traceability layer that supports all other project management agents. While other agents focus on strategic alignment, stakeholder management, or operational excellence, Jira Workflow Steward ensures that all deliverables follow proper Git workflow, maintain traceability from Jira to production, and adhere to branch strategy and commit hygiene standards.

---

## Related Files

- **[CLAUDE.md](../CLAUDE.md)** - Root documentation
- **[CONTRIBUTING.md](../CONTRIBUTING.md)** - Contribution guidelines
- **[scripts/convert.sh](../scripts/convert.sh)** - Conversion pipeline
- **[scripts/install.sh](../scripts/install.sh)** - Installation script

---

## Changelog

### 2026-03-16 - Category Documentation Created
- 📊 **Agent Inventory**: Cataloged all 6 project management agents
- ✨ **Workflow Diagrams**: Added project lifecycle and experiment-driven workflows
- 📋 **Technical Deliverables**: Included comprehensive templates for charters, experiments, SOPs, and strategic plans
- 🔗 **Integration Guide**: Documented tool compatibility and conversion
- ✅ **Quality Standards**: Defined success metrics and testing requirements

---

<div align="center">

**Project Management Agents** - Your Strategic Execution Team

6 Specialists • Full Lifecycle • Data-Driven Decisions

</div>
