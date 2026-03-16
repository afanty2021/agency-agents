[根目录](../CLAUDE.md) > **sales**

---

# Sales Agents - AI Context Documentation

> **Category**: Sales
> **Agent Count**: 8
> **Last Updated**: 2026-03-16

## 📋 Breadcrumb Navigation

[根目录](../CLAUDE.md) > **sales**

---

## Module Overview

The Sales category contains **8 specialized agents** covering the complete sales lifecycle, from outbound prospecting and pipeline management to deal strategy, proposal development, and post-sale account expansion. These agents are designed to drive revenue growth through systematic, data-driven approaches that prioritize quality over quantity and strategic thinking over tactical execution.

### Core Philosophy

Sales agents are designed to be:
- **Data-Driven**: Decisions based on signals, metrics, and analytical rigor—not gut feel
- **Strategic**: Every tactic connects to a broader revenue strategy and customer lifecycle view
- **Customer-Centric**: Value propositions framed in the buyer's language and business outcomes
- **Process-Disciplined**: Structured methodologies (MEDDPICC, SPIN, Challenger) applied consistently
- **Coaching-Oriented**: Continuous improvement through behavioral feedback and skill development

---

## Agent Inventory

### Pipeline & Revenue Operations (2 agents)

| Agent | Specialty | Key Metrics & Frameworks |
|-------|-----------|-------------------------|
| **Pipeline Analyst** | Pipeline health diagnostics, forecast accuracy, deal velocity analysis | Pipeline Velocity, Coverage Ratios, MEDDPICC scoring, Win Rate analysis |
| **Sales Coach** | Rep development, pipeline review facilitation, call coaching, forecast discipline | Quota Attainment, Win Rate, Forecast Accuracy, Coaching Effectiveness |

### Deal Strategy & Execution (3 agents)

| Agent | Specialty | Key Frameworks |
|-------|-----------|----------------|
| **Deal Strategist** | Complex deal orchestration, competitive displacement, executive engagement | MEDDPICC, Stakeholder Mapping, Mutual Action Plans |
| **Discovery Coach** | Discovery methodology, qualification rigor, needs analysis | SPIN, Challenger, Value Proposition Design |
| **Sales Engineer** | Technical sales, demo strategy, proof-of-concept management | Technical Discovery, Demo Architecture, POC Success Criteria |

### Outbound & Pipeline Generation (1 agent)

| Agent | Specialty | Key Frameworks |
|-------|-----------|----------------|
| **Outbound Strategist** | Signal-based prospecting, multi-channel sequences, ICP definition | Signal-Based Selling, ICP Tiering, Reply Rate Optimization |

### Proposal & Capture (1 agent)

| Agent | Specialty | Key Frameworks |
|-------|-----------|----------------|
| **Proposal Strategist** | Win theme development, RFP response architecture, executive summary craft | Win Theme Matrix, Three-Act Narrative, Competitive Positioning |

### Post-Sale & Expansion (1 agent)

| Agent | Specialty | Key Frameworks |
|-------|-----------|----------------|
| **Account Strategist** | Land-and-expand execution, QBR facilitation, net revenue retention | NRR Optimization, Stakeholder Mapping, Expansion Playbooks |

---

## Key Interfaces & Workflows

### Sales Process Workflows

#### Full Sales Cycle Workflow

```mermaid
graph LR
    A[Outbound Strategist] --> B[Discovery Coach]
    B --> C[Sales Engineer]
    C --> D[Deal Strategist]
    D --> E[Proposal Strategist]
    E --> F[Sales Coach]
    F --> G[Account Strategist]
```

**Agent Sequence**:
1. **Outbound Strategist**: Generate pipeline through signal-based prospecting and ICP targeting
2. **Discovery Coach**: Conduct thorough discovery and qualification using MEDDPICC/SPIN frameworks
3. **Sales Engineer**: Technical validation through demos and proof-of-concept
4. **Deal Strategist**: Orchestrate complex deals, map stakeholders, and navigate competitive dynamics
5. **Proposal Strategist**: Develop winning proposals with compelling win themes and narratives
6. **Sales Coach**: Coach reps through the process, improving skills and forecast accuracy
7. **Account Strategist**: Drive post-sale expansion and net revenue retention

#### Pipeline Management Workflow

```mermaid
graph LR
    A[Pipeline Analyst] --> B[Sales Coach]
    B --> C[Deal Strategist]
    C --> D[Pipeline Analyst]
```

**Agent Sequence**:
1. **Pipeline Analyst**: Monitor pipeline health, forecast revenue, identify at-risk deals
2. **Sales Coach**: Conduct pipeline reviews, coach reps on deal strategy and qualification
3. **Deal Strategist**: Intervene on high-risk or high-value deals with strategic guidance
4. **Pipeline Analyst**: Track intervention effectiveness and update forecast models

#### Forecast-to-Close Workflow

```mermaid
graph LR
    A[Pipeline Analyst] --> B[Sales Coach]
    B --> C[Deal Strategist]
    C --> D[Proposal Strategist]
    D --> E[Account Strategist]
```

**Agent Sequence**:
1. **Pipeline Analyst**: Build forecast using pipeline velocity and deal health scoring
2. **Sales Coach**: Review forecast with reps, validate commit deals, coach on forecast discipline
3. **Deal Strategist**: Develop strategy for commit deals, identify and mitigate risks
4. **Proposal Strategist**: Create compelling proposals for late-stage opportunities
5. **Account Strategist**: Plan post-sale expansion and retention strategies

---

## Technical Deliverables

### Pipeline Health Dashboard Example

```markdown
# Pipeline Health Report: Q2 2026

## Velocity Metrics
| Metric                  | Current    | Prior Period | Trend | Benchmark |
|-------------------------|------------|-------------|-------|-----------|
| Pipeline Velocity       | $12,500/day| $11,200/day | +11%  | $10,000/day|
| Qualified Opportunities | 156        | 142         | +10%  | 140       |
| Average Deal Size       | $87,000    | $92,000     | -5%   | $85,000   |
| Win Rate (overall)      | 24%        | 22%         | +2%   | 23%       |
| Sales Cycle Length      | 68 days    | 72 days     | -5%   | 70 days   |

## Coverage Analysis
| Segment     | Quota Remaining | Weighted Pipeline | Coverage Ratio | Quality-Adjusted |
|-------------|-----------------|-------------------|----------------|------------------|
| Enterprise  | $2.4M           | $8.8M             | 3.7x           | 2.9x             |
| Mid-Market  | $1.8M           | $5.2M             | 2.9x           | 2.1x             |
| SMB         | $800K           | $2.1M             | 2.6x           | 1.8x             |

## Deals Requiring Intervention
| Deal Name | Stage | Days Stalled | MEDDPICC Score | Risk Signal | Recommended Action |
|-----------|-------|-------------|----------------|-------------|-------------------|
| Acme Corp | Proposal | 22 | 5/8 | Single-threaded, no economic buyer | Assign executive sponsor this week |
| TechGlobal | Negotiation | 18 | 6/8 | Legal security review stalled | Engage Sales Engineer for security briefing |
| InnovateInc | Discovery | 35 | 3/8 | Low engagement, weak champion | Requalify or move to nurture |
```

### Account Expansion Plan Example

```markdown
# Account Expansion Plan: Acme Corporation

## Account Overview
- **Current ARR**: $250,000
- **Contract Renewal**: December 2026
- **Health Score**: Green (Strong product adoption, executive sponsor engaged)
- **Products Deployed**: Core Platform, Analytics Module
- **Whitespace**: Enterprise Features, Professional Services, API Access

## Stakeholder Map
| Name | Title | Role | Influence | Sentiment | Last Contact |
|------|-------|------|-----------|-----------|--------------|
| Sarah Chen | VP of Operations | Champion | High | Positive | 2026-03-10 |
| Michael Torres | CFO | Economic Buyer | High | Neutral | 2026-02-28 |
| Lisa Park | Director of IT | Technical Buyer | Medium | Positive | 2026-03-05 |
| James Wilson | Operations Manager | End User | Medium | Positive | 2026-03-12 |

## Expansion Opportunities
| Opportunity | Trigger Signal | Business Case | Timing | Owner | Stage |
|------------|----------------|---------------|--------|-------|-------|
| Enterprise Features | Analytics team hitting 85% capacity | $120K efficiency gain | Q3 2026 | AE | Discovery |
| Professional Services | Customer requested implementation support | Faster time-to-value | Q2 2026 | CS | Proposal |
| API Access | Development team building integrations | Enable ecosystem expansion | Q4 2026 | AE | Identification |

## Mutual Action Plan
| Action Item | Owner (Us) | Owner (Customer) | Due Date | Status |
|-------------|-----------|-------------------|----------|--------|
| QBR scheduling | Account Strategist | Sarah Chen | 2026-03-20 | In Progress |
| Enterprise Features demo | Sales Engineer | Lisa Park | 2026-03-25 | Scheduled |
| ROI analysis for expansion | AE | Michael Torres | 2026-03-30 | Pending |
```

### Coaching Plan Example

```markdown
# Coaching Plan: Jordan Martinez

## Current Performance
- **Quota Attainment (YTD)**: 78%
- **Win Rate**: 19%
- **Average Deal Size**: $72,000
- **Sales Cycle Length**: 82 days
- **Pipeline Coverage**: 2.4x

## Skill Assessment
| Competency | Current Level | Target Level | Gap |
|-----------|--------------|-------------|-----|
| Discovery quality | 3/5 | 4/5 | Struggles to uncover business impact |
| Qualification rigor | 2/5 | 4/5 | MEDDPICC often incomplete |
| Objection handling | 4/5 | 4/5 | Strong |
| Executive presence | 3/5 | 4/5 | Needs more C-suite engagement |
| Closing / next-step commitment | 2/5 | 4/5 | Weak commitment language |

## Focus Areas (Max 3)
### Focus 1: MEDDPICC Qualification
- **Current behavior**: Often advances deals without identifying economic buyer
- **Target behavior**: Complete 7/8 MEDDPICC fields before advancing to Evaluation stage
- **Coaching actions**: Weekly pipeline reviews with MEDDPICC audit, role-play economic buyer identification
- **Milestone**: 90% of Stage 2+ deals have 7/8 MEDDPICC fields complete
- **Target date**: 2026-04-15

### Focus 2: Discovery Question Depth
- **Current behavior**: Averages 2.3 follow-up questions before presenting solution
- **Target behavior**: Minimum 5 follow-up questions per pain point uncovered
- **Coaching actions**: Call reviews focusing on discovery, shadow top performer's calls
- **Milestone**: 5+ follow-up questions in 80% of discovery calls
- **Target date**: 2026-04-30

## Coaching Cadence
- **Weekly 1:1**: Mondays 2pm, focus on skill development and pipeline quality
- **Call reviews**: 3 calls per week, mix of discovery, demo, and negotiation
- **Deal prep sessions**: All deals over $100K entering negotiation
- **Debrief sessions**: All lost deals within 48 hours of close date
```

---

## Dependencies & Integrations

### Sales Stack Dependencies

Sales agents integrate with common sales technology platforms:

- **CRM Systems**: Salesforce, HubSpot, Pipedrive, Microsoft Dynamics
- **Sales Engagement**: Outreach, Salesloft, Apollo, Gong, Chorus
- **Intent Data**: 6sense, Bombora, Demandbase, ZoomInfo
- **Analytics**: Tableau, Looker, Power BI for sales dashboards
- **Communication**: ZoomInfo, LinkedIn Sales Navigator, email platforms

### Integration Patterns

```bash
# Convert sales agents for different tools
./scripts/convert.sh --tool cursor     # .cursor/rules/*.mdc
./scripts/convert.sh --tool opencode   # .opencode/agents/*.md
./scripts/convert.sh --tool qwen       # .qwen/agents/*.md
```

---

## Key Frameworks & Methodologies

### Sales Qualification Frameworks

- **MEDDPICC**: Metrics, Economic Buyer, Decision Criteria, Decision Process, Paper Process, Implicated Pain, Champion, Competition
- **SPIN**: Situation, Problem, Implication, Need-Payoff
- **BANT**: Budget, Authority, Need, Timeline
- **Challenger**: Teach, Tailor, Take Control

### Sales Methodologies

- **Solution Selling**: Focus on customer problems and outcomes
- **Challenger Sale**: Teach customers something new about their business
- **Sandler**: Establish upfront contracts, no mutual mystification
- **Consultative Selling**: Ask questions, listen, diagnose before prescribing

### Key Metrics Definitions

- **Pipeline Velocity**: (Qualified Opportunities × Average Deal Size × Win Rate) / Sales Cycle Length
- **Pipeline Coverage**: Weighted Pipeline / Remaining Quota
- **Net Revenue Retention (NRR)**: (Starting ARR + Expansion - Contraction - Churn) / Starting ARR
- **Forecast Accuracy**: |Forecast - Actual| / Actual

---

## Common Workflows

### 1. New Deal Qualification Workflow

```
Outbound Strategist → Discovery Coach → Pipeline Analyst → Sales Coach
```

**Steps**:
1. Generate or receive qualified lead (Outbound Strategist)
2. Conduct discovery using MEDDPICC/SPIN (Discovery Coach)
3. Score deal quality and add to pipeline (Pipeline Analyst)
4. Coach rep on qualification gaps and next steps (Sales Coach)

### 2. Complex Deal Strategy Workflow

```
Deal Strategist → Sales Engineer → Proposal Strategist → Sales Coach
```

**Steps**:
1. Map stakeholders and develop deal strategy (Deal Strategist)
2. Design technical validation approach (Sales Engineer)
3. Create winning proposal with win themes (Proposal Strategist)
4. Coach rep on negotiation and closing (Sales Coach)

### 3. At-Risk Deal Intervention Workflow

```
Pipeline Analyst → Sales Coach → Deal Strategist → Account Strategist
```

**Steps**:
1. Identify at-risk deal through health scoring (Pipeline Analyst)
2. Conduct pipeline review and coaching session (Sales Coach)
3. Develop intervention strategy for stalled deals (Deal Strategist)
4. If post-sale, execute retention playbook (Account Strategist)

### 4. Quarterly Business Review Workflow

```
Account Strategist → Sales Coach → Pipeline Analyst
```

**Steps**:
1. Prepare QBR with ROI data and expansion opportunities (Account Strategist)
2. Coach rep on QBR delivery and strategy (Sales Coach)
3. Analyze QBR impact on pipeline and forecast (Pipeline Analyst)

---

## FAQ

**Q: How do I choose between Deal Strategist and Sales Coach for deal support?**
A: Deal Strategist focuses on the specific deal—stakeholder mapping, competitive positioning, and deal strategy. Sales Coach focuses on the rep's skill development—what they need to learn to handle similar deals independently in the future. Use Deal Strategist for deal-critical moments and Sales Coach for ongoing rep development.

**Q: What's the difference between Discovery Coach and Sales Engineer?**
A: Discovery Coach specializes in the early-stage conversation—uncovering pain, qualifying the opportunity, and building the business case. Sales Engineer focuses on technical validation—demonstrating technical fit, managing proof-of-concept, and addressing technical objections. They often collaborate on complex technical sales.

**Q: When should I involve Proposal Strategist?**
A: Involve Proposal Strategist for formal RFP responses, complex proposals over $100K, or any situation where a well-crafted narrative could be decisive. For simple proposals or standard presentations, the Deal Strategist or Sales Coach can provide sufficient guidance.

**Q: How do Pipeline Analyst and Sales Coach work together on pipeline reviews?**
A: Pipeline Analyst provides the analytical foundation—metrics, diagnostics, and deal scoring. Sales Coach uses that analysis to coach reps, turning data into behavioral feedback. Pipeline Analyst identifies what needs attention; Sales Coach helps reps execute the improvement.

**Q: Can these agents work together on complex sales cycles?**
A: Absolutely! Sales agents are designed for collaborative orchestration. A major enterprise deal might involve Outbound Strategist (prospect), Discovery Coach (qualify), Sales Engineer (technical validation), Deal Strategist (orchestrate), Proposal Strategist (proposal), Sales Coach (coaching throughout), and Account Strategist (post-sale expansion).

---

## Related Files

- **[CLAUDE.md](../CLAUDE.md)** - Root documentation
- **[sales-account-strategist.md](./sales-account-strategist.md)** - Post-sale expansion specialist
- **[sales-coach.md](./sales-coach.md)** - Sales rep development and coaching
- **[sales-deal-strategist.md](./sales-deal-strategist.md)** - Complex deal orchestration
- **[sales-discovery-coach.md](./sales-discovery-coach.md)** - Discovery and qualification methodology
- **[sales-engineer.md](./sales-engineer.md)** - Technical sales and demos
- **[sales-outbound-strategist.md](./sales-outbound-strategist.md)** - Signal-based outbound prospecting
- **[sales-pipeline-analyst.md](./sales-pipeline-analyst.md)** - Pipeline analytics and forecasting
- **[sales-proposal-strategist.md](./sales-proposal-strategist.md)** - Proposal and RFP strategy
- **[CONTRIBUTING.md](../CONTRIBUTING.md)** - Contribution guidelines
- **[scripts/convert.sh](../scripts/convert.sh)** - Conversion pipeline

---

## Changelog

### 2026-03-16 - Sales Category Documentation Created
- 📊 **Agent Inventory**: Cataloged all 8 sales agents with specialties and frameworks
- ✨ **Workflow Diagrams**: Added sales cycle, pipeline management, and forecast-to-close workflows
- 📋 **Technical Deliverables**: Included pipeline dashboards, account expansion plans, and coaching templates
- 🔗 **Integration Guide**: Documented sales stack compatibility and conversion
- ✅ **Quality Standards**: Defined key metrics and methodologies used across sales agents
- 🎯 **FAQ Section**: Addressed common questions about agent selection and collaboration

---

<div align="center">

**Sales Agents** - Your Revenue Growth Team

8 Specialists • Full Cycle • Data-Driven Selling

</div>
