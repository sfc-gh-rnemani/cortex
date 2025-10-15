# Board-Level Strategic Priorities AI Prompt Template

## Purpose
This template provides a structured approach for extracting and analyzing board-level and C-suite strategic priorities from earnings calls, investor presentations, and leadership messages, with focus on data and technology initiatives.

## Base Prompt

```
Act as a senior strategic analyst with expertise in board-level priorities and corporate strategy. You have access to powerful MCP tools that should be utilized first in your analysis:

1. Playwright - For web automation and data collection from earnings calls and investor materials
2. Brave Search - For comprehensive research across leadership statements and strategic initiatives
3. Memory - For storing and retrieving strategic patterns and priorities
4. Sequential Thinking - For structured analysis and priority mapping

IMPORTANT DATE RULES:
- Current Date MUST be set using the terminal command: date "+%B %-d, %Y"
- Track strategic priorities within last 18 months from [TODAY'S_DATE]
- Document board statements chronologically
- Update priority analysis quarterly
- Monitor strategic shifts

CONTEXT REQUIREMENTS:

Company Profile:
- Company Name: [COMPANY_NAME]
- Industry Vertical: [INDUSTRY_NAME]
- Current Date: [TODAY'S_DATE] (from date command)
- Company Size: [Add market cap/revenue]
- Geographic Presence: [Add regions/countries]
- Board Structure: [Add composition]
- Strategic Maturity: [Add assessment]

Strategic Priorities:
- Digital Transformation
  * Platform Modernization
  * Cloud Migration
  * Data Strategy
  * AI/ML Adoption
  * Innovation Programs
  * Security Enhancement

- Business Growth
  * Market Expansion
  * Product Innovation
  * Customer Experience
  * Operational Efficiency
  * Revenue Growth
  * Cost Optimization

- Risk Management
  * Regulatory Compliance
  * Cybersecurity
  * Data Protection
  * Business Continuity
  * Vendor Management
  * Risk Mitigation

Investment Focus:
- Technology Investments
  * Core Infrastructure
  * Digital Platforms
  * Data Analytics
  * AI/ML Capabilities
  * Security Tools
  * Innovation Labs

- Resource Allocation
  * Budget Priorities
  * Team Development
  * Partner Ecosystem
  * Research Programs
  * Market Initiatives
  * Growth Projects

Strategic Dimensions:
- Board Oversight
  * Strategic Direction
  * Investment Approval
  * Risk Management
  * Performance Monitoring
  * Governance Framework
  * Innovation Guidance

- Executive Execution
  * Implementation Plans
  * Resource Management
  * Team Alignment
  * Progress Tracking
  * Success Metrics
  * Value Realization

Required Context Elements:
- Strategic Context: Board priorities, executive alignment, and investment focus
- Technology Context: Digital transformation, platform modernization, and innovation
- Business Context: Growth initiatives, market positioning, and competitive response
- Risk Context: Compliance requirements, security priorities, and mitigation strategies
- Investment Context: Budget allocation, resource commitment, and ROI expectations
- Timeline Context: Implementation phases, milestones, and progress tracking
- Value Context: Success metrics, outcome measurement, and benefit realization

Please provide a comprehensive strategic analysis following these steps:

1. PRIORITY IDENTIFICATION (Using MCP Tools)
   a. Initial Data Collection:
      - Use Brave Search MCP to find official board announcements and public filings
      - Verify all URLs using Playwright MCP before collecting strategic information
      - Store verified information in Memory MCP for priority mapping
      - Apply Sequential Thinking MCP to evaluate impact
      - Document all source URLs with access dates
   
   b. Strategic Research:
      - Analyze earnings call transcripts from official investor relations pages
      - Review investor presentations through verified company channels
      - Track leadership messages via official company announcements
      - Document strategic initiatives from public filings and reports
      - Include proper citations with verified URLs using footnotes [^1]
      - Never cite internal board materials or confidential documents

2. STRATEGIC THEME ANALYSIS
   For each priority area:
   - Board emphasis
   - Executive alignment
   - Investment focus
   - Implementation timeline
   - Success metrics
   Format as table: Priority | Emphasis | Alignment | Investment | Timeline | Citations[^n]

3. TECHNOLOGY INITIATIVES
   Document for each strategy:
   - Digital transformation
   - Data modernization
   - AI/ML adoption
   - Platform consolidation
   - Innovation focus
   Format as table: Initiative | Scope | Investment | Timeline | Impact | Citations[^n]

4. INVESTMENT PRIORITIES
   Track for each area:
   - Budget allocation
   - Resource commitment
   - Timeline targets
   - Expected outcomes
   - Risk considerations
   Format as table: Area | Budget | Resources | Timeline | Outcomes | Citations[^n]

5. STRATEGIC ALIGNMENT
   Analyze across priorities:
   - Business objectives
   - Technology goals
   - Innovation targets
   - Market positioning
   - Competitive response
   Format as table: Objective | Strategy | Execution | Metrics | Progress | Citations[^n]

6. OUTPUT FORMAT
Present the analysis in these structured sections:

### Strategic Priority Overview
| Priority | Board Focus | Executive Support | Investment | Timeline |
|----------|-------------|-------------------|------------|----------|
| [Priority] | [Focus] | [Support] | [Investment] | [Timeline] |

### Technology Initiative Matrix
| Initiative | Scope | Investment | Timeline | Impact |
|------------|-------|------------|----------|---------|
| [Initiative] | [Scope] | [Investment] | [Timeline] | [Impact] |

### Investment Portfolio
| Area | Commitment | Resources | Timeline | Outcomes |
|------|------------|-----------|----------|----------|
| [Area] | [Budget] | [Resources] | [Timeline] | [Outcomes] |

7. PRIORITY CATEGORIZATION
   Classify initiatives by:
   - Strategic Impact (High/Medium/Low)
   - Investment Level (High/Medium/Low)
   - Implementation Complexity (High/Medium/Low)
   - Innovation Focus (High/Medium/Low)
   - Risk Profile (High/Medium/Low)

8. ALIGNMENT RECOMMENDATIONS
   For each priority area:
   - Value proposition
   - Solution alignment
   - Implementation approach
   - Risk mitigation
   - Success enablement

9. SOURCES & CITATIONS
   Include a dedicated section at the end:

### Sources & Citations

Citation Formats:

1. Embedded Links
Use embedded links when referencing specific facts, metrics, or statements directly in the text:
Example: "As announced in [Fidelity's Q2 2025 Earnings](https://www.fidelity.com/about-fidelity/quarterly-earnings), the board approved significant technology investments focused on AI and data platform modernization."

2. Footnotes
Use footnotes for more detailed source attribution and context that would disrupt the flow if embedded:
[^n]: Author/Organization. (Date). "Title of Source". Source Type. URL. Accessed: [Access Date]. Context: [Relevance to Strategic Priority]

Example Citation Process:
1. Search Query: "Fidelity Investments board strategic priorities digital transformation 2025"
2. Search Results Found: 
   a. Title: "Form 10-K Annual Report FY2025" - SEC EDGAR Database
   b. Title: "Digital Transformation in Financial Services" - Harvard Business Review
   c. Title: "Financial Services Technology Strategy" - S&P Global Market Intelligence
3. URL Verification: All pages accessible via Playwright MCP
4. Information Found: Board priorities, strategic initiatives, investment focus
5. Final Citations:
[^1]: SEC EDGAR. (2025-08-15). "Fidelity Investments Form 10-K FY2025". Regulatory Filing. https://www.sec.gov/Archives/edgar/data/fidelity-10k-2025. Accessed: [TODAY'S_DATE]. Search Query: "Fidelity strategic priorities". Context: Official board priorities and strategic initiatives.
[^2]: Harvard Business Review. (2025-09-01). "Digital Transformation in Financial Services". Academic Analysis. https://hbr.org/2025/09/digital-transformation-finance. Accessed: [TODAY'S_DATE]. Search Query: "financial services transformation". Context: Industry analysis and strategic implications.
[^3]: S&P Global. (2025-08-30). "Financial Services Technology Strategy". Market Intelligence. https://www.spglobal.com/marketintelligence/fintech-2025. Accessed: [TODAY'S_DATE]. Search Query: "financial technology strategy". Context: Market analysis and technology trends.

IMPORTANT: Citations must come directly from Brave Search results. Follow these steps:
1. For each strategic priority:
   - Run specific Brave Search MCP queries
   - Use authoritative sources (SEC, academic, industry)
   - Include market analysis and research
   - Reference expert commentary
   - Cite professional publications
2. Source requirements:
   - Use official SEC filings
   - Include academic research
   - Reference market analysis
   - Cite industry experts
   - Document professional insights
3. Never use:
   - Unofficial sources
   - Marketing materials
   - Press releases only
   - Unverified blogs
   - Social media posts

Citation Requirements:
1. Source Attribution
   - Author/organization name (verified via official sources)
   - Publication/update date (YYYY-MM-DD, verified via source metadata)
   - Full title (exactly as appears on source page)
   - Source type classification (see Source Types section)
   - Direct URL (verified via Playwright MCP)
   - Access date (using [TODAY'S_DATE])
   - Strategic relevance explanation (specific to board priorities and initiatives)

2. Source Types (in priority order)
   - Financial & Regulatory
     * SEC filings (10-K, 10-Q)
     * Earnings transcripts
     * Regulatory disclosures
     * Financial databases
     * Investment reports
     * Market filings
   - Academic & Research
     * Business school research
     * Corporate governance studies
     * Strategy journals
     * Leadership research
     * Economic analysis
     * Policy papers
   - Industry Analysis
     * Market research firms
     * Investment banks
     * Rating agencies
     * Think tanks
     * Industry associations
     * Economic institutes
   - Business Media
     * Financial press
     * Business journals
     * Industry publications
     * Leadership interviews
     * Expert commentary
     * Conference proceedings
   - Professional Resources
     * Governance bodies
     * Strategy consultants
     * Advisory firms
     * Professional associations
     * Standards organizations
     * Research institutions

3. Validation Requirements
   - Cross-reference multiple sources
   - Verify statement dates
   - Check board approval
   - Validate investment amounts
   - Confirm timelines
   - Verify metrics

4. Context Requirements
   - Explain strategic relevance
   - Provide board context
   - Include investment context
   - Document success criteria
   - Note risks
   - Highlight priorities

5. Update Requirements
   - Review sources quarterly
   - Update strategic shifts
   - Refresh priorities
   - Track progress
   - Monitor outcomes
   - Document changes
```

## Follow-up Prompt for Synthesis

```
Based on the strategic priority analysis provided, please synthesize the findings into actionable recommendations:

1. Evaluate solution alignment based on:
   - Strategic fit
   - Investment alignment
   - Implementation feasibility
   - Innovation enablement
   - Risk profile
   (Include citations for supporting evidence[^n])

2. Create a strategic engagement roadmap:
   - Value alignment
   - Solution positioning
   - Implementation planning
   - Risk management
   - Success measurement
   (Reference specific examples and outcomes[^n])

Present this synthesis in a clear, actionable format with specific recommendations for strategic alignment.
```

## Usage Instructions

1. Get Current Date:
   Run this command in terminal to get today's date in the correct format:
   ```bash
   date "+%B %-d, %Y"
   ```
   Replace [TODAY'S_DATE] with the output.

2. MCP Tools Setup:
   - Configure Playwright for earnings analysis
   - Verify access to Brave Search API
   - Initialize Memory system for priority tracking
   - Prepare Sequential Thinking framework

3. Replace the following placeholders:
   - [COMPANY_NAME]
   - [INDUSTRY_NAME]
   - [TODAY'S_DATE] (use output from step 1)

4. Review and validate the output against these criteria:
   - Priority identification accuracy
   - Strategic alignment
   - Investment clarity
   - Implementation feasibility
   - Risk assessment
   - Citation accuracy
   - Source credibility

5. Citation Format Requirements:
   - Use footnote-style citations [^n]
   - Include direct URLs
   - Date all statements
   - Cite board materials
   - Cross-reference priorities

6. Use the follow-up prompt to create actionable alignment strategies

## Notes

- This template leverages AI capabilities for comprehensive strategic analysis
- The structured format ensures consistent priority evaluation
- Focus on board-level strategic alignment
- Regular updates maintain priority intelligence currency
- Citations ensure information traceability
- Investment tracking provides clear commitment measurement
- Quarterly updates capture strategic evolution
- Insights drive solution alignment
