# Business Unit Workload Mapping AI Prompt Template

## Purpose
Maps business units to their specific data workloads, analytics requirements, and technology needs by analyzing organizational structure, job postings, press releases, and public statements to identify targeted engagement opportunities and workload-specific value propositions.

---

## Template Information

**Template Category:** Account-Research
**Estimated Completion Time:** 90-120 minutes
**Required Tools:** Brave Search, Memory, Sequential Thinking
**Output Format:** Business Unit Workload Analysis and Engagement Strategy Report

---

## Base Prompt

```
Act as a senior business analyst with expertise in organizational structure analysis, workload identification, and technology requirement mapping. You have access to powerful MCP tools that should be utilized systematically in your analysis:

1. Brave Search - For comprehensive research on business unit structure, job postings, press releases, and workload indicators
2. Memory - For organizing and storing business unit intelligence across multiple divisions and workload categories
3. Sequential Thinking - For structured workload analysis and engagement strategy development

IMPORTANT DATE RULES:
- Current Date MUST be set using the terminal command: date "+%B %-d, %Y"
- Analysis timeframe is 12 months prior to [TODAY'S_DATE] for current organizational structure and workload patterns
- All business unit information must be verified and documented with confidence levels
- Focus on current organizational structure while noting recent changes

CONTEXT REQUIREMENTS:

Target Company Profile:
- Company Name: [COMPANY_NAME]
- Industry: [INDUSTRY_SECTOR]
- Current Date: [TODAY'S_DATE] (from date command)
- Analysis Timeframe: 12 months prior to [TODAY'S_DATE]

YOUR TASK:
Conduct comprehensive analysis of [COMPANY_NAME]'s business unit structure and map specific data workloads, analytics requirements, and technology needs for each division. Follow these research phases to build actionable workload intelligence for targeted engagement.

## Phase 1: Organizational Structure & Business Unit Identification (Use Brave Search, Memory, Sequential Thinking)
Research and map the current organizational structure and key business units.

Research Focus:
- What are the primary business units, divisions, or operating segments at [COMPANY_NAME]?
- How is the organization structured (geographic, product, functional, or matrix organization)?
- Who are the key leaders for each business unit and what are their backgrounds?
- Have there been recent organizational changes, mergers, or restructuring activities?

## Phase 2: Business Unit Function & Workload Analysis (Use Brave Search, Memory, Sequential Thinking)
Analyze each business unit's core functions and likely data/analytics workloads.

Investigation Areas:
- What are the primary business functions and operational focus areas for each unit?
- What types of data and analytics workloads would each business unit typically require?
- Are there industry-specific or function-specific analytics requirements for different units?
- How might each business unit's workloads align with Snowflake's capabilities and use cases?

## Phase 3: Job Posting & Hiring Pattern Analysis (Use Brave Search, Memory, Sequential Thinking)
Research job postings and hiring patterns to identify technology requirements and workload indicators.

Key Research Areas:
- What data, analytics, and technology roles is each business unit actively hiring for?
- What specific skills, tools, and platforms are mentioned in job requirements?
- Are there patterns in hiring that suggest specific workload types or technology initiatives?
- How do job postings reveal business unit priorities and technology transformation efforts?

## Phase 4: Press Release & Public Statement Analysis (Use Brave Search, Memory, Sequential Thinking)
Analyze press releases and public statements for business unit workload and technology insights.

Analysis Focus:
- What business unit initiatives, projects, or strategic priorities have been publicly announced?
- Are there technology implementations, digital transformation efforts, or analytics initiatives mentioned by business unit?
- How do business unit leaders discuss data, analytics, and technology requirements in public forums?
- What partnerships, vendor relationships, or technology investments have been announced by business unit?

## Phase 5: Industry & Functional Workload Mapping (Use Brave Search, Memory, Sequential Thinking)
Map industry-standard and function-specific workloads to identified business units.

Strategic Intelligence:
- What are the typical data and analytics workloads for similar business units in [INDUSTRY_SECTOR]?
- How do functional areas (finance, marketing, operations, etc.) typically utilize data platforms?
- What are the common use cases and workload patterns for each type of business unit?
- How might industry trends and best practices inform workload requirements for each unit?

## Phase 6: Workload-Specific Engagement Strategy Development (Use Memory, Sequential Thinking)
Synthesize business unit intelligence to develop targeted engagement strategies and value propositions.

Strategic Planning:
- What are the highest-priority business units for Snowflake engagement based on workload alignment?
- How should value propositions be tailored for each business unit's specific workload requirements?
- What are the optimal engagement approaches for different business unit types and leaders?
- How can workload-specific use cases and ROI models be developed for targeted business units?

RESEARCH REQUIREMENTS:
- Focus on current organizational structure and recent workload patterns
- Verify business unit information from multiple public sources
- Document confidence levels for each workload assessment (High/Medium/Low)
- Include direct links to all sources with publication dates
- Cross-reference workload intelligence across organizational and functional dimensions
- Store comprehensive business unit intelligence in Memory for strategic analysis

ANALYSIS QUALITY STANDARDS:
- All business unit information must be supported by verifiable public sources
- Distinguish between confirmed workloads and inferred requirements based on industry patterns
- Provide specific insights about workload alignment with Snowflake capabilities

OUTPUT FORMAT:
Structure your analysis as follows:

# Business Unit Workload Mapping for [COMPANY_NAME]

## Executive Summary
[Concise overview of organizational structure, key business units, workload patterns, and strategic engagement priorities.]

## 1. Organizational Structure & Business Unit Overview
[Detailed analysis of organizational structure, business unit hierarchy, and leadership mapping.]

## 2. Business Unit Function & Workload Analysis
[Comprehensive analysis of each business unit's functions, data requirements, and analytics workloads.]

## 3. Job Posting & Technology Requirement Intelligence
[Assessment of hiring patterns, technology requirements, and workload indicators from job postings.]

## 4. Public Initiative & Technology Investment Analysis
[Analysis of announced initiatives, technology investments, and business unit strategic priorities.]

## 5. Industry Workload Benchmarking & Best Practices
[Comparison of identified workloads with industry standards and functional best practices.]

## 6. Workload-Specific Engagement Strategy & Prioritization
[Strategic recommendations for business unit engagement, value proposition tailoring, and priority targeting.]

## Supporting Evidence and References
### Business Unit Intelligence Sources
- **High confidence sources with direct links and publication dates**
- **Confidence levels for each workload assessment (High/Medium/Low)**
- **Cross-references and validation methods with source URLs**
- **Additional research recommendations for ongoing workload monitoring**

### Business Unit Workload Matrix
| Business Unit | Primary Functions | Data Workloads | Technology Requirements | Snowflake Alignment | Engagement Priority |
|---------------|-------------------|----------------|------------------------|-------------------|-------------------|
| [UNIT_NAME] | [FUNCTIONS] | [WORKLOADS] | [TECH_REQUIREMENTS] | [ALIGNMENT_SCORE] | [HIGH/MED/LOW] |

### Workload Category Analysis
- **Analytics & BI Workloads:** [Business units with reporting and analytics requirements]
- **Data Science & ML Workloads:** [Units requiring advanced analytics and machine learning]
- **Operational Data Workloads:** [Units with real-time and operational data processing needs]
- **Compliance & Governance Workloads:** [Units with regulatory and data governance requirements]

### Engagement Strategy by Business Unit
- **Tier 1 Priority Units:** [Highest alignment and engagement potential]
- **Tier 2 Target Units:** [Medium alignment with specific value proposition opportunities]
- **Tier 3 Monitoring Units:** [Lower immediate priority but future potential]

### Value Proposition Tailoring
- **Finance & Accounting:** [CFO office analytics, financial reporting, regulatory compliance]
- **Marketing & Sales:** [Customer analytics, campaign optimization, revenue intelligence]
- **Operations:** [Supply chain analytics, operational efficiency, performance monitoring]
- **Technology & IT:** [Data platform consolidation, infrastructure optimization, developer productivity]

### Action Plan by Business Unit Priority
- **Immediate Engagement (Tier 1):** [Specific engagement actions for highest-priority units]
- **Strategic Positioning (Tier 2):** [Relationship building and value demonstration approaches]
- **Future Development (Tier 3):** [Long-term relationship development and monitoring strategies]
```

---

## Usage Instructions

### When to Use This Template
- Developing targeted engagement strategies for specific business units
- Understanding organizational structure and workload distribution
- Tailoring value propositions for different functional areas and use cases
- Supporting account planning with business unit-specific intelligence

### Key Success Factors
- Focus on current organizational structure and verified business unit information
- Map workloads based on both public information and industry best practices
- Prioritize business units based on Snowflake capability alignment and engagement potential
- Provide specific, actionable engagement strategies for different business unit types

### Quality Checklist
- [ ] Organizational structure and business unit hierarchy researched and documented
- [ ] Business unit functions and workload requirements analyzed
- [ ] Job posting patterns analyzed for technology and workload indicators
- [ ] Public initiatives and technology investments mapped to business units
- [ ] All sources verified with confidence levels and direct links
- [ ] Actionable engagement strategy provided with business unit prioritization

---

## Built-in Best Practices

- **Organizational Mapping:** Comprehensive coverage of business unit structure and leadership
- **Workload Analysis:** Systematic mapping of data and analytics requirements by business unit
- **Industry Benchmarking:** Comparison with industry standards and functional best practices
- **Engagement Prioritization:** Clear prioritization based on workload alignment and engagement potential
- **Tailored Strategy:** Specific value propositions and engagement approaches for different business unit types
