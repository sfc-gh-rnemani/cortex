# Customer Vendor Stack AI Prompt Template

## Purpose
This template provides a structured approach for compiling and analyzing the customer's known vendors across key technology areas (CDP, ML, governance, etc.), leveraging press releases, LinkedIn posts, job requirements, and case studies.

## Base Prompt

```
Act as a senior technology stack analyst with expertise in enterprise vendor landscapes. You have access to powerful MCP tools that should be utilized first in your analysis:

1. Playwright - For web automation and data collection from vendor announcements and implementations
2. Brave Search - For comprehensive research across technology partnerships and solutions
3. Memory - For storing and retrieving vendor patterns and relationships
4. Sequential Thinking - For structured analysis and stack mapping

IMPORTANT DATE RULES:
- Current Date MUST be set using the terminal command: date "+%B %-d, %Y"
- Track vendor relationships within last 18 months from [TODAY'S_DATE]
- Document implementation timelines
- Update vendor map quarterly
- Monitor technology changes

CONTEXT REQUIREMENTS:

Company Profile:
- Company Name: [COMPANY_NAME]
- Industry Vertical: [INDUSTRY_NAME]
- Current Date: [TODAY'S_DATE] (from date command)
- Company Size: [Add market cap/revenue]
- Geographic Presence: [Add regions/countries]
- Technology Budget: [Add if available]
- Vendor Strategy: [Add assessment]

Technology Categories:
- Data Management
  * Data Platforms
  * Data Integration
  * Data Quality
  * Data Governance
  * Master Data
  * Data Security

- Analytics & AI
  * BI Platforms
  * Analytics Tools
  * ML Platforms
  * AI Solutions
  * Data Science
  * Visualization

- Customer Data
  * CDP Platforms
  * Marketing Tech
  * CRM Systems
  * Identity Solutions
  * Journey Analytics
  * Personalization

Implementation Status:
- Deployment Phases
  * Planning
  * Implementation
  * Production
  * Optimization
  * Expansion
  * Retirement

- Adoption Metrics
  * User Base
  * Usage Patterns
  * Feature Adoption
  * Value Realization
  * Success Metrics
  * ROI Measures

Vendor Relationships:
- Partnership Levels
  * Strategic Partners
  * Key Vendors
  * Solution Providers
  * Service Partners
  * Technology Partners
  * Support Vendors

- Engagement Models
  * Enterprise Agreements
  * Subscription Services
  * Managed Services
  * Professional Services
  * Support Contracts
  * Training Programs

Required Context Elements:
- Vendor Context: Partnership status, relationship history, and strategic value
- Solution Context: Capabilities, implementation status, and adoption
- Technical Context: Integration points, architecture, and dependencies
- Value Context: ROI, benefits realized, and growth potential
- Support Context: Service levels, responsiveness, and quality
- Cost Context: Investment levels, pricing models, and optimization
- Risk Context: Vendor stability, market position, and alternatives

Please provide a comprehensive vendor analysis following these steps:

1. VENDOR IDENTIFICATION (Using MCP Tools)
   a. Initial Data Collection:
      - Use Brave Search MCP to find official vendor documentation and public announcements
      - Verify all URLs using Playwright MCP before collecting vendor information
      - Store verified information in Memory MCP for stack mapping
      - Apply Sequential Thinking MCP to evaluate patterns
      - Document all source URLs with access dates
   
   b. Vendor Research:
      - Map CDP providers through official product documentation
      - Document ML platforms via vendor success stories and case studies
      - Track governance tools using public implementation examples
      - Analyze integration vendors from partner ecosystem documentation
      - Include proper citations with verified URLs using footnotes [^1]
      - Never cite internal vendor materials or private implementation details

2. SOLUTION ANALYSIS
   For each vendor category:
   - Core capabilities
   - Implementation scope
   - Integration points
   - Usage patterns
   - Success metrics
   Format as table: Category | Vendor | Capabilities | Scope | Success | Citations[^n]

3. IMPLEMENTATION STATUS
   Document for each solution:
   - Deployment phase
   - User adoption
   - Integration status
   - Value realization
   - Growth plans
   Format as table: Solution | Phase | Adoption | Integration | Value | Citations[^n]

4. TECHNOLOGY ALIGNMENT
   Track across domains:
   - Platform synergies
   - Data flows
   - User journeys
   - Process enablement
   - Innovation support
   Format as table: Domain | Solutions | Synergy | Flows | Impact | Citations[^n]

5. VENDOR RELATIONSHIPS
   Analyze for each vendor:
   - Partnership level
   - Investment scale
   - Support quality
   - Innovation alignment
   - Growth potential
   Format as table: Vendor | Level | Investment | Support | Potential | Citations[^n]

6. OUTPUT FORMAT
Present the analysis in these structured sections:

### Vendor Landscape Overview
| Domain | Vendors | Solutions | Status | Investment |
|--------|---------|-----------|---------|------------|
| [Domain] | [Vendors] | [Solutions] | [Status] | [Investment] |

### Implementation Matrix
| Solution | Phase | Adoption | Value | Roadmap |
|----------|-------|----------|--------|---------|
| [Solution] | [Phase] | [Adoption] | [Value] | [Roadmap] |

### Integration Architecture
| Platform | Connected Systems | Data Flows | Users | Impact |
|----------|------------------|------------|-------|---------|
| [Platform] | [Systems] | [Flows] | [Users] | [Impact] |

7. VENDOR CATEGORIZATION
   Classify by:
   - Strategic Importance (High/Medium/Low)
   - Implementation Maturity (High/Medium/Low)
   - Integration Complexity (High/Medium/Low)
   - User Adoption (High/Medium/Low)
   - Growth Potential (High/Medium/Low)

8. OPTIMIZATION OPPORTUNITIES
   For each domain:
   - Platform consolidation
   - Integration enhancement
   - Cost optimization
   - Feature utilization
   - Value acceleration

9. SOURCES & CITATIONS
   Include a dedicated section at the end:

### Sources & Citations

Required Citation Format:
[^n]: Author/Organization. (Date). "Title of Source". Source Type. URL. Accessed: [Access Date]. Context: [Relevance to Vendor Analysis]

Example Citation Process:
1. Search Query: "enterprise data platform vendor comparison analysis 2025"
2. Search Results Found: 
   a. Title: "Data Platform Market Analysis Q3 2025" - Forrester Research
   b. Title: "Enterprise Data Management Platforms" - IDC Technology Assessment
   c. Title: "Data Platform Architecture Patterns" - IEEE Software Journal
3. URL Verification: All pages accessible via Playwright MCP
4. Information Found: Vendor capabilities, market position, implementation patterns
5. Final Citations:
[^1]: Forrester Research. (2025-08-15). "Data Platform Market Analysis Q3 2025". Market Research. https://www.forrester.com/report/data-platform-q3-2025. Accessed: [TODAY'S_DATE]. Search Query: "data platform market analysis". Context: Independent analysis of vendor capabilities and market position.
[^2]: IDC. (2025-09-01). "Enterprise Data Management Platforms". Technology Assessment. https://www.idc.com/research/data-platforms-2025. Accessed: [TODAY'S_DATE]. Search Query: "enterprise data platforms". Context: Technical evaluation of platform capabilities and implementation patterns.
[^3]: IEEE Software. (2025-08-30). "Data Platform Architecture Patterns". Academic Journal. https://www.computer.org/software/data-architecture-2025. Accessed: [TODAY'S_DATE]. Search Query: "data platform architecture". Context: Technical analysis of platform architectures and integration patterns.

IMPORTANT: Citations must come directly from Brave Search results. Follow these steps:
1. For each vendor analysis:
   - Run specific Brave Search MCP queries
   - Use authoritative sources (analysts, research, academic)
   - Include independent evaluations
   - Reference technical studies
   - Cite industry standards
2. Source requirements:
   - Use analyst research
   - Include technical assessments
   - Reference academic studies
   - Cite industry standards
   - Document benchmarks
3. Never use:
   - Vendor marketing
   - Sales materials
   - Press releases only
   - Product brochures
   - Promotional content

Citation Requirements:
1. Source Attribution
   - Author/organization name (verified via official sources)
   - Publication/update date (YYYY-MM-DD, verified via source metadata)
   - Full title (exactly as appears on source page)
   - Source type classification (see Source Types section)
   - Direct URL (verified via Playwright MCP)
   - Access date (using [TODAY'S_DATE])
   - Vendor relevance explanation (specific to technology stack and implementation)

2. Source Types (in priority order)
   - Market Research & Analysis
     * Industry analysts
     * Research firms
     * Market studies
     * Technology surveys
     * Adoption reports
     * Trend analysis
   - Professional Evaluations
     * Independent reviews
     * Technical assessments
     * Comparative studies
     * Benchmark reports
     * Implementation guides
     * Best practices
   - Industry Publications
     * Technology journals
     * Trade magazines
     * Business reviews
     * Expert analysis
     * Conference papers
     * White papers
   - Academic Research
     * Research papers
     * Technical journals
     * University studies
     * Implementation research
     * Performance studies
     * Architecture analysis
   - Standards & Frameworks
     * Industry standards
     * Technical specifications
     * Reference architectures
     * Integration patterns
     * Security frameworks
     * Governance models

3. Validation Requirements
   - Cross-reference multiple sources
   - Verify implementation status
   - Check vendor relationships
   - Validate capabilities
   - Confirm success metrics
   - Verify costs

4. Context Requirements
   - Explain vendor relevance
   - Provide solution context
   - Include implementation context
   - Document success criteria
   - Note challenges
   - Highlight benefits

5. Update Requirements
   - Review sources quarterly
   - Update vendor changes
   - Refresh implementation status
   - Track new features
   - Monitor costs
   - Document optimizations
```

## Follow-up Prompt for Synthesis

```
Based on the vendor stack analysis provided, please synthesize the findings into actionable recommendations:

1. Evaluate optimization opportunities based on:
   - Platform consolidation
   - Integration enhancement
   - Cost optimization
   - Feature utilization
   - Value acceleration
   (Include citations for supporting evidence[^n])

2. Create a stack optimization roadmap:
   - Quick wins (0-3 months)
   - Core improvements (3-6 months)
   - Strategic initiatives (6-12 months)
   - Innovation enablement (12+ months)
   (Reference specific examples and patterns[^n])

Present this synthesis in a clear, actionable format with specific recommendations for vendor stack optimization.
```

## Usage Instructions

1. Get Current Date:
   Run this command in terminal to get today's date in the correct format:
   ```bash
   date "+%B %-d, %Y"
   ```
   Replace [TODAY'S_DATE] with the output.

2. MCP Tools Setup:
   - Configure Playwright for vendor analysis
   - Verify access to Brave Search API
   - Initialize Memory system for stack tracking
   - Prepare Sequential Thinking framework

3. Replace the following placeholders:
   - [COMPANY_NAME]
   - [INDUSTRY_NAME]
   - [TODAY'S_DATE] (use output from step 1)

4. Review and validate the output against these criteria:
   - Vendor identification accuracy
   - Solution assessment
   - Implementation status
   - Integration analysis
   - Optimization potential
   - Citation accuracy
   - Source credibility

5. Citation Format Requirements:
   - Use footnote-style citations [^n]
   - Include direct URLs
   - Date all findings
   - Cite implementation evidence
   - Cross-reference patterns

6. Use the follow-up prompt to create actionable optimization strategies

## Notes

- This template leverages AI capabilities for comprehensive vendor analysis
- The structured format ensures consistent stack evaluation
- Focus on implementation status and value realization
- Regular updates maintain vendor intelligence currency
- Citations ensure information traceability
- Pattern analysis provides clear optimization opportunities
- Quarterly updates capture stack evolution
- Insights drive platform optimization
