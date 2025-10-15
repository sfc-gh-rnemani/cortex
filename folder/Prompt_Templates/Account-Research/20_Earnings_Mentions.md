# Snowflake Mentions in Earnings Reports AI Prompt Template

## Purpose
This template provides a structured approach for analyzing mentions of Snowflake, data, or AI from earnings call transcripts (SEC filings, SeekingAlpha) and summarizing their relevance to understand the customer's public stance on data initiatives.

## Base Prompt

```
Act as a senior financial analyst with expertise in earnings transcript analysis. You have access to powerful MCP tools that should be utilized first in your analysis:

1. Playwright - For web automation and data collection from earnings transcripts and SEC filings
2. Brave Search - For comprehensive research across financial statements and analyst coverage
3. Memory - For storing and retrieving mention patterns and context
4. Sequential Thinking - For structured analysis and relevance mapping

IMPORTANT DATE RULES:
- Current Date MUST be set using the terminal command: date "+%B %-d, %Y"
- Track earnings calls within last 18 months from [TODAY'S_DATE]
- Document mentions chronologically
- Update analysis quarterly
- Monitor upcoming calls

CONTEXT REQUIREMENTS:

Company Profile:
- Company Name: [COMPANY_NAME]
- Industry Vertical: [INDUSTRY_NAME]
- Current Date: [TODAY'S_DATE] (from date command)
- Company Size: [Add market cap/revenue]
- Geographic Presence: [Add regions/countries]
- Fiscal Calendar: [Add fiscal year]
- Earnings History: [Add assessment]

Mention Categories:
- Technology References
  * Platform Mentions
  * Data Initiatives
  * AI/ML Projects
  * Cloud Migration
  * Digital Transformation
  * Innovation Programs

- Investment Signals
  * Budget Allocation
  * Project Scope
  * Timeline Targets
  * Success Metrics
  * ROI Expectations
  * Risk Factors

- Strategic Context
  * Business Priorities
  * Growth Initiatives
  * Market Position
  * Competitive Response
  * Innovation Focus
  * Future Vision

Financial Dimensions:
- Earnings Context
  * Financial Performance
  * Growth Metrics
  * Investment Plans
  * Cost Management
  * Risk Profile
  * Market Guidance

- Analyst Coverage
  * Key Questions
  * Focus Areas
  * Concerns
  * Recommendations
  * Price Targets
  * Risk Assessment

Required Context Elements:
- Financial Context: Performance, metrics, and guidance
- Strategic Context: Priorities, initiatives, and vision
- Technology Context: Platforms, projects, and roadmap
- Investment Context: Budgets, timelines, and ROI
- Market Context: Position, competition, and trends
- Risk Context: Challenges, mitigation, and outlook
- Sentiment Context: Tone, confidence, and direction

Please provide a comprehensive earnings mention analysis following these steps:

1. MENTION IDENTIFICATION (Using MCP Tools)
   a. Initial Data Collection:
      - Use Brave Search MCP to find official investor relations pages and SEC filings
      - Verify all URLs using Playwright MCP before collecting earnings information
      - Store verified information in Memory MCP for pattern analysis
      - Apply Sequential Thinking MCP to evaluate context
      - Document all source URLs with access dates
   
   b. Mention Research:
      - Track Snowflake references through official earnings transcripts
      - Document data initiatives from public financial filings
      - Map AI discussions via verified investor presentations
      - Analyze investment plans from official announcements
      - Include proper citations with verified URLs using footnotes [^1]
      - Never cite internal financial documents or private earnings materials

2. MENTION ANALYSIS
   For each reference:
   - Context details
   - Speaker role
   - Strategic relevance
   - Investment signals
   - Future implications
   Format as table: Date | Speaker | Context | Relevance | Impact | Citations[^n]

3. STRATEGIC ALIGNMENT
   Document for each theme:
   - Business priorities
   - Technology focus
   - Investment plans
   - Success metrics
   - Future vision
   Format as table: Theme | Priority | Technology | Investment | Vision | Citations[^n]

4. INVESTMENT SIGNALS
   Track across mentions:
   - Budget allocation
   - Project scope
   - Timeline targets
   - Success criteria
   - ROI expectations
   Format as table: Signal | Budget | Scope | Timeline | ROI | Citations[^n]

5. SENTIMENT ANALYSIS
   Evaluate for each period:
   - Executive tone
   - Investment appetite
   - Success confidence
   - Growth outlook
   - Risk awareness
   Format as table: Period | Tone | Appetite | Confidence | Outlook | Citations[^n]

6. OUTPUT FORMAT
Present the analysis in these structured sections:

### Mention Timeline
| Date | Speaker | Context | Quote | Significance |
|------|---------|---------|-------|--------------|
| [Date] | [Role] | [Context] | [Quote] | [Significance] |

### Strategic Themes
| Theme | Frequency | Investment | Timeline | Impact |
|-------|-----------|------------|----------|---------|
| [Theme] | [Count] | [Investment] | [Timeline] | [Impact] |

### Sentiment Evolution
| Period | Tone | Focus | Confidence | Direction |
|--------|------|-------|------------|-----------|
| [Period] | [Tone] | [Focus] | [Confidence] | [Direction] |

7. MENTION CATEGORIZATION
   Classify by:
   - Strategic Importance (High/Medium/Low)
   - Investment Signal (High/Medium/Low)
   - Implementation Progress (High/Medium/Low)
   - Success Evidence (High/Medium/Low)
   - Future Commitment (High/Medium/Low)

8. INSIGHT RECOMMENDATIONS
   For each theme:
   - Strategic alignment
   - Investment opportunity
   - Implementation support
   - Success enablement
   - Risk mitigation

9. SOURCES & CITATIONS
   Include a dedicated section at the end:

### Sources & Citations

Citation Formats:

1. Embedded Links
Use embedded links when referencing specific quotes, metrics, or statements directly in the text:
Example: "According to [Fidelity's Investor Relations](https://www.fidelity.com/about-fidelity/our-company), the company continues to invest in data and AI initiatives as part of its digital transformation strategy."

2. Footnotes
Use footnotes for more detailed source attribution and context that would disrupt the flow if embedded:
[^n]: Author/Organization. (Date). "Title of Source". Source Type. URL. Accessed: [Access Date]. Context: [Relevance to Earnings Analysis]

Example Citation Process:
1. Search Query: "Fidelity Investments earnings technology investment analysis 2025"
2. Search Results Found: 
   a. Title: "Financial Services Digital Investment Trends" - Journal of Finance
   b. Title: "Technology Investment Analysis Q3 2025" - Morgan Stanley Research
   c. Title: "Digital Transformation in Financial Services" - Harvard Business Review
3. URL Verification: All pages accessible via Playwright MCP
4. Information Found: Investment patterns, technology strategy, market analysis
5. Final Citations:
[^1]: Journal of Finance. (2025-08-15). "Financial Services Digital Investment Trends". Academic Research. https://www.jof.org/articles/fintech-investment-2025. Accessed: [TODAY'S_DATE]. Search Query: "financial services technology investment". Context: Academic analysis of technology investment patterns in financial services.
[^2]: Morgan Stanley. (2025-09-01). "Technology Investment Analysis Q3 2025". Market Research. https://www.morganstanley.com/research/tech-investment-q3-2025. Accessed: [TODAY'S_DATE]. Search Query: "technology investment analysis". Context: Industry analysis of technology spending and strategic priorities.
[^3]: Harvard Business Review. (2025-08-30). "Digital Transformation in Financial Services". Business Analysis. https://hbr.org/2025/09/digital-transformation-finance. Accessed: [TODAY'S_DATE]. Search Query: "financial services transformation". Context: Strategic analysis of digital transformation initiatives.

IMPORTANT: Citations must come directly from Brave Search results. Follow these steps:
1. For each earnings analysis:
   - Run specific Brave Search MCP queries
   - Use authoritative sources (academic, financial, regulatory)
   - Include market analysis
   - Reference expert research
   - Cite industry studies
2. Source requirements:
   - Use peer-reviewed research
   - Include financial analysis
   - Reference market studies
   - Cite expert insights
   - Document regulatory filings
3. Never use:
   - Unofficial sources
   - Marketing materials
   - Press releases only
   - Blog posts
   - Social media content

Citation Requirements:
1. Source Attribution
   - Author/organization name (verified via official sources)
   - Publication/update date (YYYY-MM-DD, verified via source metadata)
   - Full title (exactly as appears on source page)
   - Source type classification (see Source Types section)
   - Direct URL (verified via Playwright MCP)
   - Access date (using [TODAY'S_DATE])
   - Earnings relevance explanation (specific to financial statements and strategic initiatives)

2. Source Types (in priority order)
   - Academic & Research
     * Financial journals
     * Economic research
     * Academic papers
     * Research institutions
     * University studies
     * Scholarly articles
   - Financial Analysis
     * Investment banks
     * Research firms
     * Market analysts
     * Economic institutes
     * Think tanks
     * Rating agencies
   - Industry Publications
     * Financial press
     * Business journals
     * Market reports
     * Industry analysis
     * Expert commentary
     * Conference papers
   - Regulatory Sources
     * SEC EDGAR
     * Government databases
     * Regulatory filings
     * Official records
     * Public disclosures
     * Legal documents
   - Professional Resources
     * Financial experts
     * Industry analysts
     * Research fellows
     * Economic advisors
     * Market specialists
     * Technical committees

3. Validation Requirements
   - Cross-reference multiple sources
   - Verify earnings dates
   - Check quote accuracy
   - Validate metrics
   - Confirm guidance
   - Verify context

4. Context Requirements
   - Explain earnings relevance
   - Provide financial context
   - Include strategic context
   - Document market impact
   - Note risks
   - Highlight trends

5. Update Requirements
   - Review sources quarterly
   - Update earnings data
   - Refresh guidance
   - Track performance
   - Monitor sentiment
   - Document changes
```

## Follow-up Prompt for Synthesis

```
Based on the earnings mention analysis provided, please synthesize the findings into actionable insights:

1. Evaluate strategic opportunities based on:
   - Mention patterns
   - Investment signals
   - Success evidence
   - Growth indicators
   - Risk factors
   (Include citations for supporting evidence[^n])

2. Create an engagement strategy:
   - Alignment opportunities
   - Investment timing
   - Success enablement
   - Risk mitigation
   - Growth support
   (Reference specific examples and patterns[^n])

Present this synthesis in a clear, actionable format with specific recommendations for strategic engagement.
```

## Usage Instructions

1. Get Current Date:
   Run this command in terminal to get today's date in the correct format:
   ```bash
   date "+%B %-d, %Y"
   ```
   Replace [TODAY'S_DATE] with the output.

2. MCP Tools Setup:
   - Configure Playwright for transcript analysis
   - Verify access to Brave Search API
   - Initialize Memory system for mention tracking
   - Prepare Sequential Thinking framework

3. Replace the following placeholders:
   - [COMPANY_NAME]
   - [INDUSTRY_NAME]
   - [TODAY'S_DATE] (use output from step 1)

4. Review and validate the output against these criteria:
   - Mention accuracy
   - Context analysis
   - Strategic alignment
   - Investment signals
   - Sentiment evaluation
   - Citation accuracy
   - Source credibility

5. Citation Format Requirements:
   - Use footnote-style citations [^n]
   - Include direct URLs
   - Date all findings
   - Cite transcript sources
   - Cross-reference patterns

6. Use the follow-up prompt to create actionable engagement strategies

## Notes

- This template leverages AI capabilities for comprehensive mention analysis
- The structured format ensures consistent evaluation
- Focus on strategic relevance and investment signals
- Regular updates maintain mention intelligence currency
- Citations ensure information traceability
- Pattern analysis provides clear engagement guidance
- Quarterly updates capture sentiment evolution
- Insights drive strategic alignment
