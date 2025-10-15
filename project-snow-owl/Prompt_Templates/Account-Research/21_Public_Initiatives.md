# Data & AI Initiatives from Public Sources AI Prompt Template

## Purpose
This template provides a structured approach for surfacing data platform and AI project information from press releases, job listings, vendor blogs, and executive interviews to understand the customer's public initiatives and priorities.

## Base Prompt

```
Act as a senior technology intelligence analyst with expertise in data and AI initiatives. You have access to powerful MCP tools that should be utilized first in your analysis:

1. Playwright - For web automation and data collection from press releases and job postings
2. Brave Search - For comprehensive research across public announcements and vendor content
3. Memory - For storing and retrieving initiative patterns and relationships
4. Sequential Thinking - For structured analysis and priority mapping

IMPORTANT DATE RULES:
- Current Date MUST be set using the terminal command: date "+%B %-d, %Y"
- Track initiatives within last 18 months from [TODAY'S_DATE]
- Document announcements chronologically
- Update initiative map quarterly
- Monitor new developments

CONTEXT REQUIREMENTS:

Company Profile:
- Company Name: [COMPANY_NAME]
- Industry Vertical: [INDUSTRY_NAME]
- Current Date: [TODAY'S_DATE] (from date command)
- Company Size: [Add market cap/revenue]
- Geographic Presence: [Add regions/countries]
- Technology Budget: [Add if available]
- Initiative Maturity: [Add assessment]

Initiative Categories:
- Data Platforms
  * Data Warehouses
  * Data Lakes
  * Data Mesh
  * Data Fabric
  * Data Quality
  * Data Governance

- Analytics & AI
  * BI Solutions
  * ML Platforms
  * AI Applications
  * NLP Systems
  * Computer Vision
  * Predictive Analytics

- Digital Transformation
  * Cloud Migration
  * Platform Modernization
  * Process Automation
  * DevOps Evolution
  * Security Enhancement
  * Integration Platforms

Implementation Dimensions:
- Project Scope
  * Business Units
  * User Base
  * Data Volume
  * Process Coverage
  * Geographic Reach
  * Timeline Targets

- Resource Requirements
  * Team Structure
  * Skill Needs
  * Technology Stack
  * Infrastructure
  * Budget Allocation
  * Vendor Support

Success Indicators:
- Value Metrics
  * Business Impact
  * Cost Savings
  * Revenue Growth
  * Process Efficiency
  * User Adoption
  * Innovation Rate

- Risk Factors
  * Technical Complexity
  * Resource Constraints
  * Timeline Pressure
  * Change Management
  * Vendor Dependencies
  * Integration Challenges

Required Context Elements:
- Initiative Context: Purpose, scope, and strategic value
- Technical Context: Platforms, architecture, and requirements
- Resource Context: Teams, skills, and capabilities
- Implementation Context: Approach, timeline, and phases
- Value Context: Benefits, metrics, and success criteria
- Risk Context: Challenges, dependencies, and mitigation
- Market Context: Competition, trends, and positioning

Please provide a comprehensive initiative analysis following these steps:

1. INITIATIVE IDENTIFICATION (Using MCP Tools)
   a. Initial Data Collection:
      - Use Brave Search MCP to find official company announcements and press releases
      - Verify all URLs using Playwright MCP before collecting initiative information
      - Store verified information in Memory MCP for pattern analysis
      - Apply Sequential Thinking MCP to evaluate impact
      - Document all source URLs with access dates
   
   b. Source Research:
      - Track press releases from official company newsrooms
      - Document job listings from public career sites
      - Map vendor blogs through official partner pages
      - Analyze executive interviews via verified media sources
      - Include proper citations with verified URLs using footnotes [^1]
      - Never cite internal documents or private announcements

2. INITIATIVE ANALYSIS
   For each announcement:
   - Project scope
   - Technology focus
   - Investment scale
   - Timeline targets
   - Success metrics
   Format as table: Date | Initiative | Scope | Investment | Timeline | Citations[^n]

3. TECHNOLOGY FOCUS
   Document for each area:
   - Platform choices
   - Solution approach
   - Integration needs
   - Team requirements
   - Success criteria
   Format as table: Area | Technology | Approach | Team | Success | Citations[^n]

4. IMPLEMENTATION SIGNALS
   Track across sources:
   - Project progress
   - Resource allocation
   - Vendor selection
   - Team building
   - Timeline updates
   Format as table: Signal | Progress | Resources | Vendors | Updates | Citations[^n]

5. STRATEGIC ALIGNMENT
   Analyze for each initiative:
   - Business impact
   - Technology fit
   - Resource readiness
   - Risk profile
   - Growth potential
   Format as table: Initiative | Impact | Fit | Readiness | Risk | Citations[^n]

6. OUTPUT FORMAT
Present the analysis in these structured sections:

### Initiative Timeline
| Date | Announcement | Scope | Investment | Status |
|------|--------------|-------|------------|---------|
| [Date] | [Initiative] | [Scope] | [Investment] | [Status] |

### Technology Portfolio
| Focus Area | Solutions | Approach | Team | Progress |
|------------|-----------|----------|------|----------|
| [Area] | [Solutions] | [Approach] | [Team] | [Progress] |

### Implementation Status
| Initiative | Phase | Resources | Vendors | Timeline |
|------------|-------|-----------|----------|----------|
| [Initiative] | [Phase] | [Resources] | [Vendors] | [Timeline] |

7. INITIATIVE CATEGORIZATION
   Classify by:
   - Strategic Impact (High/Medium/Low)
   - Implementation Progress (High/Medium/Low)
   - Resource Readiness (High/Medium/Low)
   - Technical Complexity (High/Medium/Low)
   - Success Potential (High/Medium/Low)

8. ENGAGEMENT RECOMMENDATIONS
   For each initiative:
   - Solution alignment
   - Implementation support
   - Resource enablement
   - Risk mitigation
   - Success acceleration

9. SOURCES & CITATIONS
   Include a dedicated section at the end:

### Sources & Citations

Required Citation Format:
[^n]: Author/Organization. (Date). "Title of Source". Source Type. URL. Accessed: [Access Date]. Context: [Relevance to Initiative Analysis]

Example Citation Process:
1. Search Query: "financial services digital transformation initiatives implementation 2025"
2. Search Results Found: 
   a. Title: "Digital Transformation in Financial Services" - MIT Technology Review
   b. Title: "Enterprise Technology Implementation Patterns" - IEEE Software Engineering
   c. Title: "Financial Services Innovation Study 2025" - Forrester Research
3. URL Verification: All pages accessible via Playwright MCP
4. Information Found: Implementation patterns, technology adoption, success metrics
5. Final Citations:
[^1]: MIT Technology Review. (2025-08-15). "Digital Transformation in Financial Services". Research Analysis. https://www.technologyreview.com/fintech-transformation-2025. Accessed: [TODAY'S_DATE]. Search Query: "financial services transformation". Context: Academic analysis of digital transformation initiatives and implementation patterns.
[^2]: IEEE Software Engineering. (2025-09-01). "Enterprise Technology Implementation Patterns". Technical Journal. https://www.computer.org/software/enterprise-patterns-2025. Accessed: [TODAY'S_DATE]. Search Query: "enterprise technology implementation". Context: Technical evaluation of implementation approaches and success factors.
[^3]: Forrester Research. (2025-08-30). "Financial Services Innovation Study 2025". Industry Research. https://www.forrester.com/report/finserv-innovation-2025. Accessed: [TODAY'S_DATE]. Search Query: "financial services innovation". Context: Industry analysis of technology initiatives and adoption trends.

IMPORTANT: Citations must come directly from Brave Search results. Follow these steps:
1. For each initiative analysis:
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
   - Press releases only
   - Vendor blogs
   - Social media
   - Promotional content

Citation Requirements:
1. Source Attribution
   - Author/organization name (verified via official sources)
   - Publication/update date (YYYY-MM-DD, verified via source metadata)
   - Full title (exactly as appears on source page)
   - Source type classification (see Source Types section)
   - Direct URL (verified via Playwright MCP)
   - Access date (using [TODAY'S_DATE])
   - Initiative relevance explanation (specific to public announcements and implementations)

2. Source Types (in priority order)
   - Academic & Research
     * Research papers
     * Technical journals
     * University studies
     * Research institutions
     * Conference proceedings
     * Scholarly articles
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
   - Verify announcement dates
   - Check project status
   - Validate technology claims
   - Confirm team details
   - Verify success metrics

4. Context Requirements
   - Explain initiative relevance
   - Provide project context
   - Include technical details
   - Document success criteria
   - Note challenges
   - Highlight benefits

5. Update Requirements
   - Review sources monthly
   - Update project status
   - Refresh team details
   - Track milestones
   - Monitor progress
   - Document changes
```

## Follow-up Prompt for Synthesis

```
Based on the initiative analysis provided, please synthesize the findings into actionable recommendations:

1. Evaluate engagement opportunities based on:
   - Initiative alignment
   - Implementation timing
   - Resource needs
   - Success factors
   - Risk profile
   (Include citations for supporting evidence[^n])

2. Create an engagement roadmap:
   - Solution positioning
   - Implementation support
   - Resource enablement
   - Risk mitigation
   - Success acceleration
   (Reference specific examples and patterns[^n])

Present this synthesis in a clear, actionable format with specific recommendations for initiative engagement.
```

## Usage Instructions

1. Get Current Date:
   Run this command in terminal to get today's date in the correct format:
   ```bash
   date "+%B %-d, %Y"
   ```
   Replace [TODAY'S_DATE] with the output.

2. MCP Tools Setup:
   - Configure Playwright for announcement analysis
   - Verify access to Brave Search API
   - Initialize Memory system for initiative tracking
   - Prepare Sequential Thinking framework

3. Replace the following placeholders:
   - [COMPANY_NAME]
   - [INDUSTRY_NAME]
   - [TODAY'S_DATE] (use output from step 1)

4. Review and validate the output against these criteria:
   - Initiative identification
   - Technology assessment
   - Implementation status
   - Strategic alignment
   - Success potential
   - Citation accuracy
   - Source credibility

5. Citation Format Requirements:
   - Use footnote-style citations [^n]
   - Include direct URLs
   - Date all findings
   - Cite announcement sources
   - Cross-reference patterns

6. Use the follow-up prompt to create actionable engagement strategies

## Notes

- This template leverages AI capabilities for comprehensive initiative analysis
- The structured format ensures consistent evaluation
- Focus on public announcements and implementation signals
- Regular updates maintain initiative intelligence currency
- Citations ensure information traceability
- Pattern analysis provides clear engagement guidance
- Quarterly updates capture initiative evolution
- Insights drive strategic alignment
