# Customer AI Strategy AI Prompt Template

## Purpose
This template provides a structured approach for analyzing and documenting the customer's stated AI vision, understanding what they are building, what matters to them, and identifying areas where Snowflake's capabilities align with their AI strategy.

## Base Prompt

```
Act as a senior AI strategy analyst with expertise in enterprise AI transformation. You have access to powerful MCP tools that should be utilized first in your analysis:

1. Playwright - For web automation and data collection from AI announcements and initiatives
2. Brave Search - For comprehensive research across AI strategy and implementations
3. Memory - For storing and retrieving AI patterns and priorities
4. Sequential Thinking - For structured analysis and strategy mapping

IMPORTANT DATE RULES:
- Current Date MUST be set using the terminal command: date "+%B %-d, %Y"
- Track AI initiatives within last 18 months from [TODAY'S_DATE]
- Document strategy evolution chronologically
- Update AI analysis quarterly
- Monitor implementation progress

CONTEXT REQUIREMENTS:

Company Profile:
- Company Name: [COMPANY_NAME]
- Industry Vertical: [INDUSTRY_NAME]
- Current Date: [TODAY'S_DATE] (from date command)
- Company Size: [Add market cap/revenue]
- Geographic Presence: [Add regions/countries]
- AI Investment: [Add budget if available]
- AI Maturity: [Add assessment]

AI Strategy Components:
- Vision & Objectives
  * Strategic Goals
  * Business Outcomes
  * Innovation Targets
  * Competitive Position
  * Market Leadership
  * Risk Tolerance

- Implementation Approach
  * Development Model
  * Platform Strategy
  * Team Structure
  * Partner Ecosystem
  * Governance Framework
  * Success Metrics

- Use Case Portfolio
  * Priority Areas
  * Pilot Projects
  * Production Systems
  * Innovation Labs
  * Research Programs
  * Value Targets

Technology Stack:
- AI/ML Platforms
  * Development Tools
  * Model Frameworks
  * Training Infrastructure
  * Deployment Platforms
  * Monitoring Systems
  * MLOps Tools

- Data Architecture
  * Data Platforms
  * Storage Solutions
  * Processing Systems
  * Integration Tools
  * Quality Controls
  * Governance Systems

Capability Dimensions:
- Technical Readiness
  * Infrastructure
  * Platforms
  * Tools
  * Frameworks
  * Standards
  * Best Practices

- Team Capabilities
  * Data Scientists
  * ML Engineers
  * Data Engineers
  * Platform Teams
  * Domain Experts
  * Support Staff

Required Context Elements:
- Strategy Context: AI vision, objectives, and implementation approach
- Technical Context: Platform choices, architecture, and capabilities
- Data Context: Infrastructure, quality, and governance
- Team Context: Skills, organization, and development
- Process Context: Development, deployment, and operations
- Value Context: Business impact, ROI, and success metrics
- Risk Context: Technical, operational, and strategic risks

Please provide a comprehensive AI strategy analysis following these steps:

1. AI VISION IDENTIFICATION (Using MCP Tools)
   a. Initial Data Collection:
      - Use Brave Search MCP to find official AI strategy announcements and public documentation
      - Verify all URLs using Playwright MCP before collecting strategy information
      - Store verified information in Memory MCP for strategy mapping
      - Apply Sequential Thinking MCP to evaluate impact
      - Document all source URLs with access dates
   
   b. Strategy Research:
      - Document stated AI vision from official company sources and public filings
      - Map implementation roadmap using verified company announcements
      - Track pilot projects through official case studies and success stories
      - Analyze success metrics from public financial reports and presentations
      - Include proper citations with verified URLs using footnotes [^1]
      - Never cite internal strategy documents or confidential materials

2. AI INITIATIVE ANALYSIS
   For each major initiative:
   - Strategic objectives
   - Technical approach
   - Implementation timeline
   - Resource allocation
   - Success criteria
   Format as table: Initiative | Objectives | Approach | Timeline | Resources | Citations[^n]

3. TECHNOLOGY STACK
   Document for AI implementation:
   - Platform choices
   - Model development
   - Data infrastructure
   - MLOps practices
   - Integration approach
   Format as table: Component | Technology | Status | Integration | Impact | Citations[^n]

4. USE CASE PORTFOLIO
   Track for each domain:
   - Business problems
   - AI solutions
   - Implementation status
   - Value realized
   - Lessons learned
   Format as table: Domain | Problem | Solution | Status | Value | Citations[^n]

5. CAPABILITY ASSESSMENT
   Analyze across dimensions:
   - Data readiness
   - Technical maturity
   - Team expertise
   - Process maturity
   - Infrastructure scale
   Format as table: Capability | Status | Gaps | Roadmap | Priority | Citations[^n]

6. OUTPUT FORMAT
Present the analysis in these structured sections:

### AI Strategy Overview
| Component | Current State | Vision | Timeline | Investment |
|-----------|--------------|--------|----------|------------|
| [Component] | [State] | [Vision] | [Timeline] | [Investment] |

### Initiative Portfolio
| Initiative | Objective | Approach | Status | Impact |
|------------|-----------|----------|---------|---------|
| [Initiative] | [Objective] | [Approach] | [Status] | [Impact] |

### Technology Architecture
| Component | Platform | Integration | Status | Roadmap |
|-----------|----------|-------------|---------|---------|
| [Component] | [Platform] | [Integration] | [Status] | [Roadmap] |

7. MATURITY ASSESSMENT
   Evaluate across dimensions:
   - Vision Clarity (High/Medium/Low)
   - Implementation Progress (High/Medium/Low)
   - Technical Readiness (High/Medium/Low)
   - Team Capability (High/Medium/Low)
   - Value Realization (High/Medium/Low)

8. ALIGNMENT OPPORTUNITIES
   For each strategic area:
   - Snowflake capabilities
   - Solution alignment
   - Implementation support
   - Value acceleration
   - Risk mitigation

9. SOURCES & CITATIONS
   Include a dedicated section at the end:

### Sources & Citations

Citation Formats:

1. Embedded Links
Use embedded links when referencing specific facts, metrics, or statements directly in the text:
Example: "According to [Fidelity's 2025 AI Investment Report](https://www.fidelity.com/about-fidelity/ai-investment-2025), the company increased AI spending by 45% in 2025."

2. Footnotes
Use footnotes for more detailed source attribution and context that would disrupt the flow if embedded:
[^n]: Author/Organization. (Date). "Title of Source". Source Type. URL. Accessed: [Access Date]. Context: [Relevance to AI Strategy]

Example Citation Process:
1. Search Query: "financial services artificial intelligence strategy implementation 2025"
2. Search Results Found: 
   a. Title: "AI in Financial Services: Implementation Strategies" - MIT Technology Review
   b. Title: "Enterprise AI Adoption Study 2025" - Gartner Research
   c. Title: "Financial Industry AI Transformation" - IEEE Computer Society
3. URL Verification: All pages accessible via Playwright MCP
4. Information Found: AI strategy patterns, implementation approaches, success metrics
5. Final Citations:
[^1]: MIT Technology Review. (2025-08-15). "AI in Financial Services: Implementation Strategies". Research Analysis. https://www.technologyreview.com/ai-finance-2025. Accessed: [TODAY'S_DATE]. Search Query: "financial services AI strategy". Context: Academic analysis of AI implementation patterns.
[^2]: Gartner Research. (2025-09-01). "Enterprise AI Adoption Study 2025". Industry Analysis. https://www.gartner.com/research/ai-adoption-2025. Accessed: [TODAY'S_DATE]. Search Query: "enterprise AI implementation". Context: Industry research on AI adoption trends.
[^3]: IEEE Computer Society. (2025-08-30). "Financial Industry AI Transformation". Technical Journal. https://www.computer.org/journal/ai-finance-2025. Accessed: [TODAY'S_DATE]. Search Query: "AI transformation finance". Context: Technical analysis of AI implementation approaches.

IMPORTANT: Citations must come directly from Brave Search results. Follow these steps:
1. For each AI strategy component:
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
   - Vendor publications
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
   - Strategy relevance explanation (specific to AI initiatives and implementation)

2. Source Types (in priority order)
   - Academic & Research
     * AI research papers
     * Technical journals
     * University studies
     * Research institutions
     * Conference proceedings
     * Scholarly articles
   - Industry Analysis
     * Market research firms
     * Technology analysts
     * Think tanks
     * Research organizations
     * Industry associations
     * Standards bodies
   - Business Publications
     * Technology journals
     * Business magazines
     * Industry news
     * Expert interviews
     * Case studies
     * White papers
   - Technical Resources
     * Research papers
     * Technical reviews
     * Implementation studies
     * Architecture analysis
     * Performance studies
     * Benchmark reports
   - Professional Sources
     * Industry experts
     * Technology leaders
     * Research fellows
     * Academic faculty
     * Technical committees
     * Standards organizations

3. Validation Requirements
   - Cross-reference multiple sources
   - Verify strategy statements
   - Check implementation status
   - Validate technical claims
   - Confirm team capabilities
   - Verify success metrics

4. Context Requirements
   - Explain strategic relevance
   - Provide technical context
   - Include team context
   - Document success criteria
   - Note challenges
   - Highlight innovations

5. Update Requirements
   - Review sources quarterly
   - Update strategy changes
   - Refresh implementation status
   - Track new projects
   - Monitor outcomes
   - Document learnings
```

## Follow-up Prompt for Synthesis

```
Based on the AI strategy analysis provided, please synthesize the findings into actionable recommendations:

1. Evaluate solution alignment based on:
   - Strategic fit
   - Technical readiness
   - Implementation feasibility
   - Team capability
   - Value potential
   (Include citations for supporting evidence[^n])

2. Create an engagement roadmap:
   - Solution positioning
   - Technical enablement
   - Implementation support
   - Team development
   - Value realization
   (Reference specific examples and outcomes[^n])

Present this synthesis in a clear, actionable format with specific recommendations for AI strategy enablement.
```

## Usage Instructions

1. Get Current Date:
   Run this command in terminal to get today's date in the correct format:
   ```bash
   date "+%B %-d, %Y"
   ```
   Replace [TODAY'S_DATE] with the output.

2. MCP Tools Setup:
   - Configure Playwright for AI announcement analysis
   - Verify access to Brave Search API
   - Initialize Memory system for strategy tracking
   - Prepare Sequential Thinking framework

3. Replace the following placeholders:
   - [COMPANY_NAME]
   - [INDUSTRY_NAME]
   - [TODAY'S_DATE] (use output from step 1)

4. Review and validate the output against these criteria:
   - Vision clarity
   - Strategy completeness
   - Implementation feasibility
   - Technical readiness
   - Team capability
   - Citation accuracy
   - Source credibility

5. Citation Format Requirements:
   - Use footnote-style citations [^n]
   - Include direct URLs
   - Date all statements
   - Cite strategy documents
   - Cross-reference initiatives

6. Use the follow-up prompt to create actionable alignment strategies

## Notes

- This template leverages AI capabilities for comprehensive strategy analysis
- The structured format ensures consistent vision evaluation
- Focus on implementation readiness and value realization
- Regular updates maintain strategy intelligence currency
- Citations ensure information traceability
- Capability assessment provides clear maturity measurement
- Quarterly updates capture strategy evolution
- Insights drive solution alignment
