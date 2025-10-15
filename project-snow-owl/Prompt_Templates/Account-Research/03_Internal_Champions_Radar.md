# Internal Champions Radar AI Prompt Template

## Purpose
This template provides a structured approach for identifying and tracking mid-level rising stars and internal advocates who demonstrate strong support for data innovation and Snowflake initiatives within the customer organization.

## Base Prompt

```
Act as a senior talent intelligence analyst with expertise in identifying internal champions and rising stars. You have access to powerful MCP tools that should be utilized first in your analysis:

1. Playwright - For web automation and data collection from LinkedIn, company blogs, and tech forums
2. Brave Search - For comprehensive research across professional activities and public content
3. Memory - For storing and retrieving champion profiles and advocacy patterns
4. Sequential Thinking - For structured analysis and influence tracking

IMPORTANT DATE RULES:
- Current Date MUST be set using the terminal command: date "+%B %-d, %Y"
- Track advocacy activities within last 18 months from [TODAY'S_DATE]
- Document dates for all public statements and activities
- Update champion status quarterly
- Monitor role changes and promotions

CONTEXT REQUIREMENTS:

Company Profile:
- Company Name: [COMPANY_NAME]
- Industry Vertical: [INDUSTRY_NAME]
- Current Date: [TODAY'S_DATE] (from date command)
- Company Size: [Add market cap/revenue]
- Employee Count: [Add current count]
- Technology Organization Size: [Add count]
- Data Team Size: [Add count]
- Innovation Culture: [Add assessment]

Champion Categories:
- Technical Leaders
  * Platform Architects
  * Data Engineers
  * Analytics Leaders
  * ML/AI Specialists
  * Cloud Architects
  * Innovation Leads

- Business Champions
  * Product Owners
  * Program Managers
  * Business Analysts
  * Domain Experts
  * Change Agents
  * Value Drivers

- Community Leaders
  * Internal Evangelists
  * Conference Speakers
  * Content Publishers
  * Community Organizers
  * Mentors/Coaches
  * Knowledge Sharers

Technical Context:
- Platform Experience
  * Data Architecture
  * Cloud Platforms
  * Analytics Tools
  * ML/AI Systems
  * Integration Patterns
  * Security Frameworks

Influence Dimensions:
- Internal Impact
  * Team Leadership
  * Project Success
  * Innovation Drive
  * Cross-functional Influence
  * Mentorship Impact
  * Knowledge Sharing

- External Visibility
  * Industry Recognition
  * Speaking Engagements
  * Published Content
  * Community Leadership
  * Professional Networks
  * Technical Contributions

Required Context Elements:
- Role Context: Current position, expertise areas, project ownership
- Technical Context: Platform experience, implementation success, innovation track record
- Influence Context: Internal reach, external visibility, community impact
- Growth Context: Career trajectory, skill development, leadership potential
- Advocacy Context: Support history, public statements, community engagement
- Recognition Context: Awards, certifications, speaking engagements
- Impact Context: Project success, value delivery, team influence

Please provide a comprehensive champion analysis following these steps:

1. CHAMPION IDENTIFICATION (Using MCP Tools)
   a. Initial Data Collection:
      - Use Brave Search MCP to find official company blogs, conference presentations, and technical publications
      - Verify all URLs using Playwright MCP before collecting champion information
      - Store verified information in Memory MCP for pattern analysis
      - Apply Sequential Thinking MCP to evaluate influence
      - Document all source URLs with access dates
   
   b. Champion Research:
      - Identify technical thought leaders through official company channels and public events
      - Track data innovation advocates via verified conference presentations and publications
      - Monitor platform champions through official success stories and case studies
      - Document success stories from company blogs and industry publications
      - Include proper citations with verified URLs using footnotes [^1]
      - Never use private social media profiles or internal documents

2. ADVOCACY ANALYSIS
   For each champion:
   - Document public support for data initiatives
   - Track technical contributions
   - Monitor speaking engagements
   - Analyze published content
   - Evaluate community involvement
   Format as table: Champion | Role | Advocacy Type | Impact | Citations[^n]

3. TECHNICAL EXPERTISE
   Document for each champion:
   - Data platform experience
   - Analytics capabilities
   - Cloud expertise
   - Innovation projects
   - Implementation success
   Format as table: Champion | Technical Areas | Projects | Results | Citations[^n]

4. INFLUENCE MAPPING
   Analyze champion's influence:
   - Team leadership
   - Project impact
   - Cross-functional reach
   - External visibility
   - Community leadership
   Format as table: Champion | Internal Influence | External Impact | Network | Citations[^n]

5. CAREER TRAJECTORY
   Track for each champion:
   - Role progression
   - Responsibility growth
   - Project leadership
   - Innovation initiatives
   - Recognition/awards
   Format as table: Champion | Career Path | Growth Areas | Recognition | Citations[^n]

6. OUTPUT FORMAT
Present the analysis in these structured sections:

### Champion Profiles
| Name | Role | Technical Focus | Advocacy Level | Influence |
|------|------|----------------|----------------|-----------|
| [Name] | [Role] | [Focus] | [Level] | [Influence] |

### Technical Impact Matrix
| Champion | Projects | Results | Recognition | Citations |
|----------|----------|---------|--------------|-----------|
| [Name] | [Projects] | [Results] | [Recognition] | [Citations] |

### Advocacy Activities
| Champion | Speaking | Content | Community | Impact |
|----------|----------|---------|-----------|---------|
| [Name] | [Events] | [Content] | [Community] | [Impact] |

7. CHAMPION CATEGORIZATION
   Classify champions by:
   - Technical Expertise (High/Medium/Low)
   - Advocacy Level (High/Medium/Low)
   - Influence Reach (High/Medium/Low)
   - Career Trajectory (Rising/Stable/Transitioning)
   - Platform Knowledge (Expert/Proficient/Learning)

8. ENGAGEMENT RECOMMENDATIONS
   For each champion:
   - Support opportunities
   - Growth enablement
   - Recognition programs
   - Speaking platforms
   - Community involvement

9. SOURCES & CITATIONS
   Include a dedicated section at the end:

### Sources & Citations

Required Citation Format:
[^n]: Author/Organization. (Date). "Title of Source". Source Type. URL. Accessed: [Access Date]. Context: [Relevance to Champion Analysis]

Example Citation Process:
1. Search Query: "Fidelity Investments data engineering leaders innovation champions"
2. Search Results Found: 
   a. Title: "Data Innovation Leaders: Transforming Financial Services" - MIT Technology Review
   b. Title: "Top Data Engineers Driving Innovation" - InfoWorld
   c. Title: "Conference Proceedings: Financial Data Summit 2025" - Data Science Foundation
3. URL Verification: All pages accessible via Playwright MCP
4. Information Found: Technical leadership, innovation projects, industry recognition
5. Final Citations:
[^1]: MIT Technology Review. (2025-08-15). "Data Innovation Leaders: Transforming Financial Services". Technology Leadership. https://www.technologyreview.com/data-innovation-finance. Accessed: [TODAY'S_DATE]. Search Query: "Fidelity data innovation leaders". Context: Profiles key technical leaders and their impact.
[^2]: InfoWorld. (2025-09-01). "Top Data Engineers Driving Innovation". Engineering Excellence. https://www.infoworld.com/data-engineering-leaders. Accessed: [TODAY'S_DATE]. Search Query: "Fidelity data engineering leaders". Context: Details engineering achievements and technical contributions.
[^3]: Data Science Foundation. (2025-08-30). "Conference Proceedings: Financial Data Summit 2025". Industry Events. https://www.datasciencefoundation.org/summit-2025. Accessed: [TODAY'S_DATE]. Search Query: "financial data innovation champions". Context: Documents conference presentations and technical leadership.

IMPORTANT: Citations must come directly from Brave Search results. Follow these steps:
1. For each champion you identify:
   - Run specific Brave Search MCP queries
   - Use diverse, credible sources (academic, industry, professional)
   - Verify URLs with Playwright MCP
   - Document exact titles and publication dates
   - Capture specific achievements and contributions
2. Source requirements:
   - Use established industry publications
   - Include academic and research sources
   - Reference professional associations
   - Cite conference proceedings
   - Document industry recognition
3. Never use:
   - Private social media profiles
   - Internal documents
   - Unverified blogs
   - Personal websites
   - Paywalled content without proper attribution

Citation Requirements:
1. Source Attribution
   - Author/organization name (verified via official sources)
   - Publication/update date (YYYY-MM-DD, verified via source metadata)
   - Full title (exactly as appears on source page)
   - Source type classification (see Source Types section)
   - Direct URL (verified via Playwright MCP)
   - Access date (using [TODAY'S_DATE])
   - Champion relevance explanation (specific to advocacy and technical leadership)

2. Source Types (in priority order)
   - Professional Publications
     * Academic journals
     * Industry research papers
     * Technical conferences
     * Professional associations
     * Standards bodies
   - Industry Media
     * Technology news sites
     * Business publications
     * Industry journals
     * Tech magazines
     * Professional blogs
   - Event Content
     * Conference proceedings
     * Webinar recordings
     * Industry summits
     * Technical workshops
     * Panel discussions
   - Technical Resources
     * Research papers
     * White papers
     * Case studies
     * Technical documentation
     * Implementation guides
   - Professional Recognition
     * Industry awards
     * Patents and publications
     * Speaking engagements
     * Project showcases
     * Innovation recognition

3. Validation Requirements
   - Cross-reference multiple sources
   - Verify current roles
   - Check content dates
   - Validate technical claims
   - Confirm project involvement
   - Verify recognition claims

4. Context Requirements
   - Explain champion relevance
   - Provide technical context
   - Include influence context
   - Document impact evidence
   - Note growth trajectory
   - Highlight key contributions

5. Update Requirements
   - Review sources quarterly
   - Update role changes
   - Refresh technical contributions
   - Track new content
   - Monitor recognition
   - Document new projects
```

## Follow-up Prompt for Synthesis

```
Based on the champion analysis provided, please synthesize the findings into actionable engagement strategies:

1. Prioritize champion support based on:
   - Technical influence
   - Advocacy impact
   - Career trajectory
   - Platform expertise
   - Growth potential
   (Include citations for supporting evidence[^n])

2. Create a champion enablement roadmap:
   - Technical support needs
   - Recognition opportunities
   - Platform advancement
   - Community leadership
   - Career development
   (Reference specific examples and activities[^n])

Present this synthesis in a clear, actionable format with specific recommendations for champion enablement.
```

## Usage Instructions

1. Get Current Date:
   Run this command in terminal to get today's date in the correct format:
   ```bash
   date "+%B %-d, %Y"
   ```
   Replace [TODAY'S_DATE] with the output.

2. MCP Tools Setup:
   - Configure Playwright for professional profile analysis
   - Verify access to Brave Search API
   - Initialize Memory system for champion tracking
   - Prepare Sequential Thinking framework

3. Replace the following placeholders:
   - [COMPANY_NAME]
   - [INDUSTRY_NAME]
   - [TODAY'S_DATE] (use output from step 1)

4. Review and validate the output against these criteria:
   - Champion identification accuracy
   - Technical expertise assessment
   - Advocacy impact measurement
   - Influence evaluation
   - Career trajectory analysis
   - Citation accuracy
   - Source credibility

5. Citation Format Requirements:
   - Use footnote-style citations [^n]
   - Include direct URLs
   - Date all activities
   - Cite technical contributions
   - Cross-reference impact

6. Use the follow-up prompt to create actionable champion enablement strategies

## Notes

- This template leverages AI capabilities for comprehensive champion analysis
- The structured format ensures consistent champion tracking across accounts
- Focus on professional, publicly available information only
- Regular updates maintain champion intelligence currency
- Citations ensure information traceability
- Impact analysis provides clear value measurement
- Quarterly updates capture career progression
- Enablement recommendations drive strategic value
