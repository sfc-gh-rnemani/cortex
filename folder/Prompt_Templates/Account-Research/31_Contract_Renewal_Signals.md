# Contract Renewal Signals & Vendor Replacement Opportunities Template

## Purpose
This template identifies public signals that may indicate contract renewals, upcoming technology refresh cycles, or opportunities to replace incumbent vendors with Snowflake. It focuses on time-sensitive intelligence that can drive strategic account planning and competitive positioning.

## Base Prompt

```
Act as a strategic business intelligence analyst with expertise in enterprise technology procurement cycles and vendor relationship analysis. You have access to powerful MCP tools that should be utilized first in your analysis:

1. Brave Search - For comprehensive web research across industry sources, procurement sites, and vendor announcements
2. Playwright - For automated data collection from company websites, investor relations pages, and procurement portals
3. Memory - For storing and retrieving contract intelligence across research sessions
4. Sequential Thinking - For structured analysis and timeline development

IMPORTANT DATE RULES:
- Current Date MUST be set using the terminal command: date "+%B %-d, %Y"
- Analysis timeframe is 12 months prior to [TODAY'S_DATE] for recent context
- Focus on signals indicating renewals/decisions in next 6-12 months
- All contract dates and timelines must be verified from multiple sources
- Sort findings chronologically by estimated decision/renewal dates

CONTEXT REQUIREMENTS:

Target Company Profile:
- Company Name: [COMPANY_NAME]
- Industry: [INDUSTRY_SECTOR]
- Current Date: [TODAY'S_DATE] (from date command)
- Analysis Timeframe: 12 months prior to [TODAY'S_DATE]
- Company Size: [EMPLOYEE_COUNT/REVENUE]
- Geographic Presence: [PRIMARY_REGIONS]
- Known Data/Analytics Initiatives: [CURRENT_INITIATIVES]

Contract Intelligence Dimensions:
- Infrastructure Contracts
  * Data center leases and colocation agreements
  * Cloud provider contracts (AWS, Azure, GCP)
  * Network and connectivity agreements
  * Hardware refresh cycles
  * Outsourcing and managed services contracts

- Software & Platform Contracts
  * Data platform licenses (Databricks, Teradata, Oracle, SAP HANA)
  * Analytics and BI tools (Tableau, Power BI, Qlik, Looker)
  * Data governance platforms (Collibra, Informatica, Alation)
  * ETL/ELT tools (Informatica, Talend, Matillion)
  * Database licenses (Oracle, SQL Server, IBM Db2)

- Procurement Indicators
  * Public RFPs and tender documents
  * Vendor selection announcements
  * Contract award notifications
  * Partnership agreement renewals
  * Technology roadmap announcements

YOUR TASK:
Conduct comprehensive contract renewal signal analysis for [COMPANY_NAME] by following these phases:

## Phase 1: Historical Contract Pattern Analysis (Use Brave Search + Memory)
Research the company's historical contract patterns and vendor relationships:

Key research areas:
- Search for "[COMPANY_NAME] + contract + renewal + [VENDOR_NAME]" for major vendors
- Look for investor relations documents mentioning technology investments
- Find press releases about vendor partnerships with start/end dates
- Identify patterns in their procurement cycles (annual, multi-year, etc.)
- Document any publicly disclosed contract values and terms

Key questions to answer:
- What is their typical contract length for major technology vendors?
- When were their last major platform implementations announced?
- What procurement patterns can be identified from public records?
- Which vendors have they publicly partnered with and when?

## Phase 2: Current Contract Status Investigation (Use Brave Search + Playwright)
Investigate current vendor relationships and contract status:

Key research areas:
- Search SEC filings for technology spending and vendor commitments
- Review earnings call transcripts for technology investment mentions
- Find job postings mentioning specific technologies (indicates current usage)
- Look for case studies published by vendors featuring this company
- Search procurement databases and government contract records (if applicable)

Key questions to answer:
- Which data platforms are they currently using based on public evidence?
- What technology investments have been mentioned in recent financial reports?
- Are there job postings indicating upcoming technology changes?
- Which vendors have published recent case studies about this company?

## Phase 3: Renewal Timeline Estimation (Use Sequential Thinking + Memory)
Analyze signals to estimate renewal timelines and opportunities:

Key research areas:
- Calculate likely renewal dates based on implementation announcements
- Identify technology refresh cycles from historical patterns
- Look for executive quotes about upcoming IT modernization
- Find budget cycle information and capital expenditure planning
- Search for RFPs or procurement notices in relevant timeframes

Key questions to answer:
- When are major contracts likely to come up for renewal?
- What signals indicate dissatisfaction with current vendors?
- Are there upcoming business drivers that might trigger technology changes?
- What competitive threats or opportunities can be identified?

## Phase 4: Competitive Intelligence Gathering (Use Brave Search + Playwright)
Research competitive landscape and positioning opportunities:

Key research areas:
- Find vendor case studies older than 3 years (renewal cycle indicators)
- Look for competitive wins/losses in similar companies
- Research industry trends affecting their technology choices
- Identify regulatory or compliance changes driving platform changes
- Search for executive moves that might influence vendor relationships

Key questions to answer:
- Which competitors have recently won or lost deals in this space?
- What industry trends might influence their technology decisions?
- Are there new executives who might change vendor preferences?
- What compliance or regulatory changes might drive platform migration?

RESEARCH REQUIREMENTS:
- Verify all contract dates and vendor relationships from multiple sources
- Focus on publicly available information only
- Document confidence levels for each signal (High/Medium/Low)
- Include direct links to all sources
- Prioritize signals indicating decisions in next 6-12 months
- Cross-reference findings across multiple research phases

ANALYSIS QUALITY STANDARDS:
- All contract timelines must be supported by verifiable public sources
- Distinguish between confirmed dates and estimated timelines
- Include confidence assessment for each opportunity
- Provide specific evidence for renewal risk/opportunity claims
- Focus on actionable intelligence that can drive sales strategy
- Maintain objectivity and avoid speculation without evidence

OUTPUT FORMAT:
Structure your analysis as follows:

# Contract Renewal Signals & Vendor Replacement Opportunities
## Company: [COMPANY_NAME]

## Executive Summary
- Total opportunities identified: [NUMBER]
- High-priority renewal windows: [TIMEFRAME]
- Key competitive threats: [VENDOR_LIST]
- Estimated decision timeline: [TIMELINE]
- Primary opportunity areas: [FOCUS_AREAS]

## Contract Renewal Intelligence Table

| Date (Est/Signal) | Event Type | Vendor/Tool | Description | Renewal Risk/Opportunity for Snowflake | Confidence | Source |
|-------------------|------------|-------------|-------------|----------------------------------------|------------|---------|
| [DATE] | [CONTRACT_TYPE] | [VENDOR] | [DESCRIPTION] | [OPPORTUNITY_ASSESSMENT] | [HIGH/MED/LOW] | [SOURCE_LINK] |

## Detailed Opportunity Analysis

### High-Priority Opportunities (Next 12 months)
[Detailed analysis of immediate opportunities]

### Medium-Term Opportunities (12-18 months)
[Analysis of medium-term renewal cycles]

### Long-Term Strategic Opportunities (18+ months)
[Strategic positioning for future cycles]

## Competitive Landscape Analysis

### Current Vendor Relationships
[Analysis of existing vendor relationships and satisfaction indicators]

### Competitive Threats
[Assessment of competitive risks and vendor strengths]

### Snowflake Positioning Opportunities
[Specific areas where Snowflake can compete effectively]

## Procurement Pattern Analysis

### Historical Contract Patterns
[Analysis of company's procurement behavior and cycles]

### Decision-Making Indicators
[Signals that indicate upcoming procurement decisions]

### Budget Cycle Alignment
[Understanding of company's budget and planning cycles]

## Risk Assessment & Mitigation

### High-Risk Scenarios
[Situations that could negatively impact Snowflake opportunities]

### Mitigation Strategies
[Approaches to address identified risks]

### Success Factors
[Key factors that will determine success in competitive situations]

## Recommended Actions

### Immediate Actions (Next 30 days)
- [Specific action items with owners and timelines]

### Short-term Strategy (Next 90 days)
- [Strategic initiatives to position for opportunities]

### Long-term Positioning (Next 12 months)
- [Long-term relationship building and positioning activities]

## Supporting Evidence
[Comprehensive list of all sources with direct links and access dates]

## Confidence Assessment
- High Confidence Signals: [NUMBER] - Based on verified public contracts/announcements
- Medium Confidence Signals: [NUMBER] - Based on strong indicators and patterns
- Low Confidence Signals: [NUMBER] - Based on circumstantial evidence

```

---

## Usage Instructions

### Before Using This Template:

1. **Company Research Preparation**
   - Gather basic company information (size, industry, geography)
   - Identify known technology initiatives from recent announcements
   - Understand their business model and key operational drivers

2. **Vendor Landscape Mapping**
   - Research their current technology stack from job postings and case studies
   - Identify key competitors in their industry and technology space
   - Understand typical contract lengths in their industry

3. **Timeline Calibration**
   - Set realistic expectations for research depth (this is a comprehensive analysis)
   - Plan for 2-3 hours of focused research time
   - Prepare to iterate and refine findings over multiple sessions

### Required Customizations:

| Placeholder | Description | Example |
|-------------|-------------|---------|
| `[COMPANY_NAME]` | Target company name | "Walmart Inc." |
| `[INDUSTRY_SECTOR]` | Primary industry | "Retail/Consumer Goods" |
| `[EMPLOYEE_COUNT/REVENUE]` | Company size indicators | "2.3M employees, $611B revenue" |
| `[PRIMARY_REGIONS]` | Geographic focus | "Global, HQ USA" |
| `[CURRENT_INITIATIVES]` | Known data/AI projects | "Digital transformation, supply chain analytics" |

### Research Quality Checklist:

- [ ] All contract dates verified from multiple sources
- [ ] Confidence levels assigned to each signal
- [ ] Sources documented with direct links
- [ ] Timeline estimates based on verifiable patterns
- [ ] Competitive landscape thoroughly researched
- [ ] Actionable recommendations provided
- [ ] Risk assessment completed
- [ ] Opportunity prioritization clear

---

## Key Signal Types to Investigate

### Infrastructure Signals
- **Data Center Contracts**: Lease expirations, colocation renewals
- **Cloud Agreements**: AWS/Azure/GCP contract terms and renewals
- **Network Contracts**: Connectivity and bandwidth agreement renewals

### Platform Signals  
- **Database Licenses**: Oracle, SQL Server, IBM renewal cycles
- **Analytics Platforms**: Tableau, Power BI, Qlik licensing renewals
- **Data Platforms**: Databricks, Teradata, SAP HANA contract cycles

### Procurement Signals
- **RFPs/Tenders**: Public procurement documents for data platforms
- **Vendor Announcements**: Partnership renewals or terminations
- **Case Study Age**: Vendor case studies older than 3 years indicate renewal cycles

### Executive Signals
- **Leadership Changes**: New CTOs/CDOs who might change vendor preferences
- **Strategic Announcements**: Board-level technology modernization initiatives
- **Financial Guidance**: CapEx guidance indicating technology refresh cycles

---

## Best Practices

### 1. Source Verification
- Always verify contract information from multiple independent sources
- Distinguish between confirmed dates and estimated timelines
- Document confidence levels for all findings

### 2. Timeline Accuracy
- Focus on realistic renewal windows (typically 3-5 year cycles)
- Account for procurement lead times (6-18 months for major platforms)
- Consider budget cycle alignment and approval processes

### 3. Competitive Intelligence
- Research both direct competitors (Databricks, Teradata) and adjacent threats
- Understand vendor strengths and weaknesses in target accounts
- Identify unique Snowflake differentiators for each opportunity

### 4. Actionability
- Prioritize opportunities with clear decision timelines
- Provide specific next steps and recommended actions
- Align findings with sales team capabilities and resources

---

*This template provides comprehensive contract renewal intelligence to identify and prioritize vendor replacement opportunities for strategic account planning.*
