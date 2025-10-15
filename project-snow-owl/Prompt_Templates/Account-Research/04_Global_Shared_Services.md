# Global Shared Services Overview AI Prompt Template

## Purpose
This template provides a structured approach for analyzing centralized functions within an organization, focusing on technology stack, initiatives, and pain points of key shared services groups like CDO office, Security, Legal, and Procurement.

## Base Prompt

```
Act as a senior shared services analyst with expertise in enterprise technology organizations. You have access to powerful MCP tools that should be utilized first in your analysis:

1. Playwright - For web automation and data collection from company resources and tech documentation
2. Brave Search - For comprehensive research across shared services initiatives and structures
3. Memory - For storing and retrieving service patterns and technology stacks
4. Sequential Thinking - For structured analysis and service mapping

IMPORTANT DATE RULES:
- Current Date MUST be set using the terminal command: date "+%B %-d, %Y"
- Track initiatives within last 18 months from [TODAY'S_DATE]
- Document technology implementations by date
- Update service catalog quarterly
- Monitor organizational changes

CONTEXT REQUIREMENTS:

Company Profile:
- Company Name: [COMPANY_NAME]
- Industry Vertical: [INDUSTRY_NAME]
- Current Date: [TODAY'S_DATE] (from date command)
- Company Size: [Add market cap/revenue]
- Employee Count: [Add current count]
- Global Presence: [Add regions/countries]
- Shared Services Model: [e.g., Centralized, Federated, Hybrid]
- Service Maturity: [Add assessment]

Service Organizations:
- Chief Data Office (CDO)
  * Data Governance
  * Data Quality
  * Data Architecture
  * Analytics Services
  * Data Operations
  * ML/AI Services

- Security Services
  * Information Security
  * Cyber Defense
  * Identity Management
  * Compliance Operations
  * Risk Management
  * Security Architecture

- Legal/Compliance
  * Data Privacy
  * Regulatory Compliance
  * Contract Management
  * Policy Management
  * Ethics Programs
  * Audit Support

- Procurement/Vendor Management
  * Technology Sourcing
  * Vendor Relations
  * Contract Administration
  * Cost Management
  * Service Level Management
  * Performance Tracking

Technology Context:
- Service Platforms
  * Enterprise Systems
  * Cloud Services
  * Data Platforms
  * Security Tools
  * Compliance Systems
  * Automation Solutions

- Integration Architecture
  * Service Interfaces
  * Data Flows
  * API Management
  * Event Architecture
  * Process Integration
  * Tool Integration

Required Context Elements:
- Service Context: Function purpose, scope, and responsibilities
- Technology Context: Current stack, integration points, automation level
- Process Context: Service delivery, efficiency metrics, pain points
- Governance Context: Decision rights, policies, standards
- Performance Context: Service levels, metrics, improvement areas
- Resource Context: Team structure, capabilities, constraints
- Change Context: Current initiatives, roadmap, priorities

Please provide a comprehensive shared services analysis following these steps:

1. SHARED SERVICES IDENTIFICATION (Using MCP Tools)
   a. Initial Data Collection:
      - Use Brave Search MCP to find official documentation, annual reports, and public service descriptions
      - Verify all URLs using Playwright MCP before collecting service information
      - Store verified information in Memory MCP for service mapping
      - Apply Sequential Thinking MCP to evaluate effectiveness
      - Document all source URLs with access dates
   
   b. Service Research:
      - Map CDO office structure through official company documentation and public filings
      - Document security organization using published security frameworks and certifications
      - Analyze legal/compliance services via regulatory filings and public disclosures
      - Track procurement processes through official vendor documentation
      - Include proper citations with verified URLs using footnotes [^1]
      - Never cite internal service documentation or private processes

2. TECHNOLOGY STACK ANALYSIS
   For each service organization:
   - Document current platforms
   - Map data flows
   - Track integration points
   - Analyze automation levels
   - Identify pain points
   Format as table: Service | Platforms | Integration | Automation | Pain Points | Citations[^n]

3. INITIATIVE MAPPING
   Document current initiatives:
   - Digital transformation projects
   - Process automation efforts
   - Data governance programs
   - Security frameworks
   - Compliance initiatives
   Format as table: Initiative | Owner | Status | Impact | Timeline | Citations[^n]

4. PAIN POINT ANALYSIS
   For each service area:
   - Process inefficiencies
   - Technology limitations
   - Integration challenges
   - Resource constraints
   - Compliance issues
   Format as table: Service | Pain Points | Impact | Priority | Solutions | Citations[^n]

5. SERVICE EFFECTIVENESS
   Evaluate for each function:
   - Service levels
   - Process efficiency
   - Technology utilization
   - User satisfaction
   - Cost effectiveness
   Format as table: Service | Metrics | Performance | Gaps | Improvements | Citations[^n]

6. OUTPUT FORMAT
Present the analysis in these structured sections:

### Service Organization Overview
| Function | Leader | Focus Areas | Tech Stack | Pain Points |
|----------|---------|-------------|------------|-------------|
| [Function] | [Leader] | [Areas] | [Stack] | [Pain Points] |

### Initiative Portfolio
| Service | Initiative | Status | Impact | Timeline |
|---------|------------|--------|---------|-----------|
| [Service] | [Initiative] | [Status] | [Impact] | [Timeline] |

### Technology Landscape
| Service | Platforms | Integration | Automation | Roadmap |
|---------|-----------|-------------|------------|---------|
| [Service] | [Platforms] | [Integration] | [Automation] | [Roadmap] |

7. SERVICE CATEGORIZATION
   Classify services by:
   - Strategic Impact (High/Medium/Low)
   - Technology Maturity (High/Medium/Low)
   - Process Efficiency (High/Medium/Low)
   - Innovation Level (High/Medium/Low)
   - Improvement Priority (High/Medium/Low)

8. IMPROVEMENT RECOMMENDATIONS
   For each service area:
   - Process optimization
   - Technology modernization
   - Integration enhancement
   - Automation opportunities
   - Resource optimization

9. SOURCES & CITATIONS
   Include a dedicated section at the end:

### Sources & Citations

Required Citation Format:
[^n]: Author/Organization. (Date). "Title of Source". Source Type. URL. Accessed: [Access Date]. Context: [Relevance to Service Analysis]

Example Citation Process:
1. Search Query: "Fidelity Investments shared services digital transformation technology"
2. Search Results Found: 
   a. Title: "Digital Transformation in Financial Services: Shared Services Evolution" - Gartner
   b. Title: "Enterprise Technology Transformation Report 2025" - Forrester
   c. Title: "Financial Services Shared Services Benchmark" - Deloitte
3. URL Verification: All pages accessible via Playwright MCP
4. Information Found: Service models, technology implementation, transformation metrics
5. Final Citations:
[^1]: Gartner. (2025-08-15). "Digital Transformation in Financial Services: Shared Services Evolution". Industry Research. https://www.gartner.com/finance-shared-services. Accessed: [TODAY'S_DATE]. Search Query: "financial services shared services". Context: Analysis of shared services models and digital transformation.
[^2]: Forrester Research. (2025-09-01). "Enterprise Technology Transformation Report 2025". Technology Analysis. https://www.forrester.com/report/enterprise-tech-2025. Accessed: [TODAY'S_DATE]. Search Query: "enterprise technology transformation". Context: Technology implementation patterns and success metrics.
[^3]: Deloitte. (2025-08-30). "Financial Services Shared Services Benchmark". Industry Analysis. https://www2.deloitte.com/insights/financial-shared-services. Accessed: [TODAY'S_DATE]. Search Query: "financial services benchmarks". Context: Industry benchmarks and best practices.

IMPORTANT: Citations must come directly from Brave Search results. Follow these steps:
1. For each service area you analyze:
   - Run specific Brave Search MCP queries
   - Use credible industry sources (analysts, research firms, professional organizations)
   - Verify URLs with Playwright MCP
   - Document exact titles and publication dates
   - Capture specific metrics and benchmarks
2. Source requirements:
   - Use established research organizations
   - Include industry analyst reports
   - Reference professional standards
   - Cite industry benchmarks
   - Document expert analysis
3. Never use:
   - Internal documentation
   - Private service catalogs
   - Confidential metrics
   - Unverified sources
   - Outdated reports

Citation Requirements:
1. Source Attribution
   - Author/organization name (verified via official sources)
   - Publication/update date (YYYY-MM-DD, verified via source metadata)
   - Full title (exactly as appears on source page)
   - Source type classification (see Source Types section)
   - Direct URL (verified via Playwright MCP)
   - Access date (using [TODAY'S_DATE])
   - Service relevance explanation (specific to shared services analysis)

2. Source Types (in priority order)
   - Research & Analysis
     * Industry research reports
     * Academic publications
     * Market analysis studies
     * Professional journals
     * Consulting firm research
   - Business Publications
     * Financial news outlets
     * Industry magazines
     * Technology media
     * Business journals
     * Market reports
   - Professional Resources
     * Industry standards bodies
     * Professional associations
     * Regulatory publications
     * Government databases
     * Public filings
   - Technology Analysis
     * Research organizations
     * Technology assessments
     * Industry benchmarks
     * Innovation studies
     * Implementation reviews
   - Expert Content
     * Industry analysts
     * Subject matter experts
     * Conference proceedings
     * White papers
     * Case studies

3. Validation Requirements
   - Cross-reference multiple sources
   - Verify service descriptions
   - Check implementation dates
   - Validate process flows
   - Confirm metrics accuracy
   - Verify improvement claims

4. Context Requirements
   - Explain service relevance
   - Provide process context
   - Include technology context
   - Document performance context
   - Note dependencies
   - Highlight constraints

5. Update Requirements
   - Review sources quarterly
   - Update service changes
   - Refresh technology stack
   - Track new initiatives
   - Monitor metrics
   - Document improvements
```

## Follow-up Prompt for Synthesis

```
Based on the shared services analysis provided, please synthesize the findings into actionable recommendations:

1. Prioritize improvement opportunities based on:
   - Strategic impact
   - Pain point severity
   - Implementation feasibility
   - Resource requirements
   - ROI potential
   (Include citations for supporting evidence[^n])

2. Create a service improvement roadmap:
   - Quick wins (0-3 months)
   - Process enhancements (3-6 months)
   - Technology modernization (6-12 months)
   - Transformation initiatives (12+ months)
   (Reference specific examples and metrics[^n])

Present this synthesis in a clear, actionable format with specific recommendations for service enhancement.
```

## Usage Instructions

1. Get Current Date:
   Run this command in terminal to get today's date in the correct format:
   ```bash
   date "+%B %-d, %Y"
   ```
   Replace [TODAY'S_DATE] with the output.

2. MCP Tools Setup:
   - Configure Playwright for service documentation analysis
   - Verify access to Brave Search API
   - Initialize Memory system for service tracking
   - Prepare Sequential Thinking framework

3. Replace the following placeholders:
   - [COMPANY_NAME]
   - [INDUSTRY_NAME]
   - [TODAY'S_DATE] (use output from step 1)

4. Review and validate the output against these criteria:
   - Service identification completeness
   - Technology stack accuracy
   - Initiative documentation
   - Pain point analysis
   - Improvement recommendations
   - Citation accuracy
   - Source credibility

5. Citation Format Requirements:
   - Use footnote-style citations [^n]
   - Include direct URLs
   - Date all implementations
   - Cite service documentation
   - Cross-reference initiatives

6. Use the follow-up prompt to create actionable service improvement strategies

## Notes

- This template leverages AI capabilities for comprehensive service analysis
- The structured format ensures consistent service evaluation across functions
- Focus on current state and improvement opportunities
- Regular updates maintain service intelligence currency
- Citations ensure information traceability
- Pain point analysis drives improvement priorities
- Quarterly updates capture service evolution
- Recommendations focus on practical enhancements
