# Published Customer Case Studies AI Prompt Template

## Purpose
This template provides a structured approach for finding and analyzing case studies involving the customer with other vendors (Databricks, AWS, Azure, GCP, Informatica, etc.) to understand their technology adoption patterns and anticipate potential narratives.

## Base Prompt

```
Act as a senior competitive intelligence analyst with expertise in customer success stories. You have access to powerful MCP tools that should be utilized first in your analysis:

1. Playwright - For web automation and data collection from vendor case studies and success stories
2. Brave Search - For comprehensive research across implementation examples and outcomes
3. Memory - For storing and retrieving implementation patterns and results
4. Sequential Thinking - For structured analysis and narrative mapping

IMPORTANT DATE RULES:
- Current Date MUST be set using the terminal command: date "+%B %-d, %Y"
- Track case studies within last 18 months from [TODAY'S_DATE]
- Document implementations chronologically
- Update case study library quarterly
- Monitor new publications

CONTEXT REQUIREMENTS:

Company Profile:
- Company Name: [COMPANY_NAME]
- Industry Vertical: [INDUSTRY_NAME]
- Current Date: [TODAY'S_DATE] (from date command)
- Company Size: [Add market cap/revenue]
- Geographic Presence: [Add regions/countries]
- Technology Budget: [Add if available]
- Implementation History: [Add assessment]

Vendor Categories:
- Cloud Platforms
  * Amazon Web Services
  * Microsoft Azure
  * Google Cloud
  * Oracle Cloud
  * IBM Cloud
  * Alibaba Cloud

- Data Platforms
  * Databricks
  * Informatica
  * Talend
  * Collibra
  * Alation
  * Precisely

- Analytics Tools
  * Tableau
  * Power BI
  * Qlik
  * Looker
  * ThoughtSpot
  * Sisense

Implementation Patterns:
- Solution Types
  * Data Warehouses
  * Data Lakes
  * Analytics Platforms
  * ML/AI Systems
  * Integration Hubs
  * Governance Tools

- Architecture Models
  * Cloud Native
  * Hybrid Cloud
  * Multi-Cloud
  * Edge Computing
  * Microservices
  * Event-Driven

Success Dimensions:
- Business Impact
  * Cost Reduction
  * Revenue Growth
  * Process Efficiency
  * Time Savings
  * Quality Improvement
  * Innovation Rate

- Technical Outcomes
  * Performance Gains
  * Scalability
  * Reliability
  * Security
  * Integration
  * Automation

Required Context Elements:
- Implementation Context: Scope, approach, and timeline
- Technical Context: Architecture, platforms, and integration
- Success Context: Metrics, outcomes, and benefits
- Team Context: Skills, organization, and enablement
- Process Context: Methods, practices, and operations
- Value Context: ROI, impact, and optimization
- Risk Context: Challenges, mitigation, and lessons

Please provide a comprehensive case study analysis following these steps:

1. CASE STUDY IDENTIFICATION (Using MCP Tools)
   a. Initial Data Collection:
      - Use Brave Search MCP to find official vendor case studies and success stories
      - Verify all URLs using Playwright MCP before collecting case study information
      - Store verified information in Memory MCP for pattern analysis
      - Apply Sequential Thinking MCP to evaluate impact
      - Document all source URLs with access dates
   
   b. Vendor Research:
      - Track Databricks cases through official customer success pages
      - Document cloud examples from provider case study libraries
      - Map tool implementations via vendor documentation
      - Analyze success stories from public sources
      - Include proper citations with verified URLs using footnotes [^1]
      - Never cite internal case studies or private implementation details

2. IMPLEMENTATION ANALYSIS
   For each case study:
   - Solution scope
   - Technology stack
   - Integration approach
   - Success metrics
   - Lessons learned
   Format as table: Vendor | Solution | Stack | Success | Learning | Citations[^n]

3. TECHNOLOGY PATTERNS
   Document across implementations:
   - Platform choices
   - Architecture decisions
   - Integration methods
   - Scaling approaches
   - Performance solutions
   Format as table: Pattern | Platforms | Architecture | Methods | Results | Citations[^n]

4. SUCCESS METRICS
   Track across cases:
   - Performance gains
   - Cost savings
   - Time reduction
   - User adoption
   - Business impact
   Format as table: Metric | Baseline | Improvement | Impact | ROI | Citations[^n]

5. COMPETITIVE ANALYSIS
   Evaluate for each vendor:
   - Solution strengths
   - Implementation ease
   - Support quality
   - Customer satisfaction
   - Growth potential
   Format as table: Vendor | Strengths | Ease | Support | Growth | Citations[^n]

6. OUTPUT FORMAT
Present the analysis in these structured sections:

### Case Study Overview
| Vendor | Solution | Implementation | Results | Impact |
|--------|----------|----------------|---------|---------|
| [Vendor] | [Solution] | [Implementation] | [Results] | [Impact] |

### Technology Stack
| Component | Platforms | Integration | Scale | Performance |
|-----------|-----------|-------------|-------|-------------|
| [Component] | [Platforms] | [Integration] | [Scale] | [Performance] |

### Success Metrics
| Category | Before | After | Improvement | ROI |
|----------|--------|-------|-------------|-----|
| [Category] | [Before] | [After] | [Change] | [ROI] |

7. CASE STUDY CATEGORIZATION
   Classify by:
   - Implementation Complexity (High/Medium/Low)
   - Success Impact (High/Medium/Low)
   - Integration Depth (High/Medium/Low)
   - Solution Innovation (High/Medium/Low)
   - ROI Level (High/Medium/Low)

8. NARRATIVE RECOMMENDATIONS
   For each pattern:
   - Solution differentiation
   - Implementation advantages
   - Success acceleration
   - Risk mitigation
   - Value maximization

9. SOURCES & CITATIONS
   Include a dedicated section at the end:

### Sources & Citations

Required Citation Format:
[^n]: Author/Organization. (Date). "Title of Source". Source Type. URL. Accessed: [Access Date]. Context: [Relevance to Case Study Analysis]

Example Citation Process:
1. Search Query: "enterprise data platform implementation case studies analysis 2025"
2. Search Results Found: 
   a. Title: "Enterprise Data Platform Implementation Patterns" - ACM Digital Library
   b. Title: "Data Architecture Case Studies in Financial Services" - IEEE Software
   c. Title: "Enterprise Technology Implementation Analysis" - Gartner Research
3. URL Verification: All pages accessible via Playwright MCP
4. Information Found: Implementation patterns, architecture decisions, success metrics
5. Final Citations:
[^1]: ACM Digital Library. (2025-08-15). "Enterprise Data Platform Implementation Patterns". Research Paper. https://dl.acm.org/doi/data-platform-patterns-2025. Accessed: [TODAY'S_DATE]. Search Query: "data platform implementation". Context: Academic analysis of enterprise implementation patterns and success factors.
[^2]: IEEE Software. (2025-09-01). "Data Architecture Case Studies in Financial Services". Technical Journal. https://www.computer.org/software/data-architecture-2025. Accessed: [TODAY'S_DATE]. Search Query: "data architecture case studies". Context: Technical evaluation of architecture decisions and outcomes.
[^3]: Gartner Research. (2025-08-30). "Enterprise Technology Implementation Analysis". Industry Research. https://www.gartner.com/research/tech-implementation-2025. Accessed: [TODAY'S_DATE]. Search Query: "enterprise implementation analysis". Context: Industry analysis of implementation approaches and success metrics.

IMPORTANT: Citations must come directly from Brave Search results. Follow these steps:
1. For each case study analysis:
   - Run specific Brave Search MCP queries
   - Use authoritative sources (academic, research, industry)
   - Include technical publications
   - Reference expert analysis
   - Cite implementation studies
2. Source requirements:
   - Use peer-reviewed research
   - Include industry analysis
   - Reference technical studies
   - Cite expert insights
   - Document benchmarks
3. Never use:
   - Marketing materials
   - Vendor case studies only
   - Press releases only
   - Blog posts
   - Promotional content

Citation Requirements:
1. Source Attribution
   - Author/organization name (verified via official sources)
   - Publication/update date (YYYY-MM-DD, verified via source metadata)
   - Full title (exactly as appears on source page)
   - Source type classification (see Source Types section)
   - Direct URL (verified via Playwright MCP)
   - Access date (using [TODAY'S_DATE])
   - Case study relevance explanation (specific to implementation details and success metrics)

2. Source Types (in priority order)
   - Academic & Research
     * Research papers
     * Technical journals
     * Implementation studies
     * Architecture research
     * Performance analysis
     * Case research
   - Industry Analysis
     * Market research firms
     * Technology analysts
     * Research organizations
     * Think tanks
     * Industry associations
     * Standards bodies
   - Professional Publications
     * Technology journals
     * Business magazines
     * Industry news
     * Expert interviews
     * Conference papers
     * White papers
   - Technical Resources
     * Engineering studies
     * Implementation research
     * Architecture analysis
     * Performance studies
     * Benchmark reports
     * Technical reviews
   - Expert Sources
     * Industry experts
     * Research fellows
     * Technical committees
     * Professional associations
     * Standards organizations
     * Academic faculty

3. Validation Requirements
   - Cross-reference multiple sources
   - Verify implementation claims
   - Check success metrics
   - Validate architecture
   - Confirm outcomes
   - Verify timelines

4. Context Requirements
   - Explain case relevance
   - Provide implementation context
   - Include technical details
   - Document success metrics
   - Note challenges
   - Highlight learnings

5. Update Requirements
   - Review sources quarterly
   - Update case details
   - Refresh metrics
   - Track outcomes
   - Monitor patterns
   - Document evolution
```

## Follow-up Prompt for Synthesis

```
Based on the case study analysis provided, please synthesize the findings into actionable recommendations:

1. Evaluate competitive opportunities based on:
   - Implementation patterns
   - Success metrics
   - Integration approaches
   - Solution strengths
   - Value delivery
   (Include citations for supporting evidence[^n])

2. Create a solution strategy:
   - Differentiation points
   - Implementation advantages
   - Success enablement
   - Risk mitigation
   - Value acceleration
   (Reference specific examples and patterns[^n])

Present this synthesis in a clear, actionable format with specific recommendations for competitive positioning.
```

## Usage Instructions

1. Get Current Date:
   Run this command in terminal to get today's date in the correct format:
   ```bash
   date "+%B %-d, %Y"
   ```
   Replace [TODAY'S_DATE] with the output.

2. MCP Tools Setup:
   - Configure Playwright for case study analysis
   - Verify access to Brave Search API
   - Initialize Memory system for pattern tracking
   - Prepare Sequential Thinking framework

3. Replace the following placeholders:
   - [COMPANY_NAME]
   - [INDUSTRY_NAME]
   - [TODAY'S_DATE] (use output from step 1)

4. Review and validate the output against these criteria:
   - Case study identification
   - Implementation analysis
   - Success measurement
   - Pattern recognition
   - Competitive insight
   - Citation accuracy
   - Source credibility

5. Citation Format Requirements:
   - Use footnote-style citations [^n]
   - Include direct URLs
   - Date all findings
   - Cite case study sources
   - Cross-reference patterns

6. Use the follow-up prompt to create actionable competitive strategies

## Notes

- This template leverages AI capabilities for comprehensive case study analysis
- The structured format ensures consistent evaluation
- Focus on implementation patterns and success metrics
- Regular updates maintain competitive intelligence currency
- Citations ensure information traceability
- Pattern analysis provides clear differentiation opportunities
- Quarterly updates capture solution evolution
- Insights drive competitive advantage
