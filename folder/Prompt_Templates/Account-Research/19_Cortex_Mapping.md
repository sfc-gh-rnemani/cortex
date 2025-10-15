# Cortex Feature → Use Case Mapping AI Prompt Template

## Purpose
This template provides a structured approach for mapping Snowflake Cortex features (Search, Analyst, Agents, Doc AI) to vertical-specific use cases for the customer, helping identify high-value implementation opportunities.

## Base Prompt

```
Act as a senior solution architect with deep expertise in Snowflake Cortex capabilities and industry-specific implementations. You have access to powerful MCP tools that must be utilized comprehensively in your analysis:

1. Playwright 
   - Primary: Automated collection of Cortex documentation and feature specifications
   - Secondary: Capture of implementation patterns and success stories
   - Usage: Must capture full context including feature limitations and dependencies

2. Brave Search
   - Primary: Deep research on industry-specific implementations and patterns
   - Secondary: Competitive analysis and market adoption trends
   - Usage: Must include direct source links and publication dates

3. Memory
   - Primary: Pattern recognition across use cases and implementations
   - Secondary: Success metrics and ROI tracking
   - Usage: Must maintain context relationships between patterns

4. Sequential Thinking
   - Primary: Structured analysis of feature-to-use-case fit
   - Secondary: Implementation complexity assessment
   - Usage: Must document reasoning chain for each mapping

IMPORTANT DATE RULES:
- Current Date MUST be set using the terminal command: date "+%B %-d, %Y"
- Track Cortex features available as of [TODAY'S_DATE]
- Document implementation examples with specific dates and versions
- Update use case map quarterly with version-specific changes
- Monitor feature releases and deprecations
- Include feature availability dates and roadmap timelines
- Track implementation timeline examples from case studies

CONTEXT REQUIREMENTS:

Company Profile:
- Company Name: [COMPANY_NAME]
- Industry Vertical: [INDUSTRY_NAME]
- Current Date: [TODAY'S_DATE] (from date command)
- Company Size: [Add market cap/revenue]
- Geographic Presence: [Add regions/countries]
- Technology Budget: [Add if available]
- Snowflake Maturity: [Add assessment]

Cortex Features:
- Search Capabilities
  * Natural Language
  * Semantic Search
  * Document Analysis
  * Content Extraction
  * Metadata Indexing
  * Security Controls

- Analyst Functions
  * Data Analysis
  * Pattern Detection
  * Trend Analysis
  * Anomaly Detection
  * Predictive Models
  * Reporting Tools

- Agent Capabilities
  * Automated Tasks
  * Workflow Automation
  * Decision Support
  * Process Optimization
  * Alert Management
  * Response Actions

Implementation Context:
- Technical Environment
  * Platform Version
  * Feature Status
  * Dependencies
  * Limitations
  * Integration Points
  * Security Controls

- Resource Requirements
  * Team Skills
  * Training Needs
  * Support Model
  * Budget Allocation
  * Timeline Constraints
  * Success Criteria

Industry Dimensions:
- Market Context
  * Industry Trends
  * Competitive Pressures
  * Regulatory Requirements
  * Technology Standards
  * Best Practices
  * Success Patterns

- Use Case Patterns
  * Common Scenarios
  * Value Drivers
  * Implementation Models
  * Success Metrics
  * ROI Measures
  * Risk Factors

Required Context Elements:
- Feature Context: Capabilities, limitations, and requirements
- Technical Context: Platform, integration, and architecture
- Implementation Context: Resources, timeline, and approach
- Industry Context: Trends, regulations, and patterns
- Value Context: Benefits, ROI, and success metrics
- Risk Context: Dependencies, limitations, and mitigation
- Support Context: Training, maintenance, and operations

Please provide a comprehensive feature mapping analysis following these steps:

1. FEATURE IDENTIFICATION (Using MCP Tools)
   a. Initial Data Collection:
      - Use Brave Search MCP to find official Snowflake documentation and feature announcements
      - Verify all URLs using Playwright MCP before collecting feature information
      - Store verified information in Memory MCP for pattern mapping
      - Apply Sequential Thinking MCP to evaluate fit
      - Document all source URLs with access dates
   
   b. Feature Research:
      - Document Search capabilities from official Snowflake documentation
      - Map Analyst features using verified product documentation
      - Track Agent functions through official feature guides
      - Analyze Doc AI features via public implementation examples
      - Include proper citations with verified URLs using footnotes [^1]
      - Never cite internal documentation or private implementation details

2. USE CASE ANALYSIS
   For each Cortex feature:
   - Core capabilities
   - Industry applications
   - Implementation patterns
   - Success metrics
   - Value drivers
   Format as table: Feature | Capabilities | Applications | Success | Value | Citations[^n]

3. INDUSTRY ALIGNMENT
   Document for each use case:
   - Business problems
   - Solution approach
   - Implementation steps
   - Success criteria
   - ROI potential
   Format as table: Use Case | Problem | Solution | Steps | ROI | Citations[^n]

4. IMPLEMENTATION PATTERNS
   Track across deployments:
   - Setup approach
   - Integration methods
   - Data requirements
   - User adoption
   - Success factors
   Format as table: Pattern | Setup | Integration | Data | Success | Citations[^n]

5. VALUE REALIZATION
   Analyze for each mapping:
   - Business impact
   - Technical fit
   - User benefits
   - Cost efficiency
   - Growth potential
   Format as table: Mapping | Impact | Fit | Benefits | Value | Citations[^n]

6. OUTPUT FORMAT
Present the analysis in these detailed sections:

### Feature → Use Case Matrix
| Cortex Feature | Industry Use Cases | Value Drivers | Implementation | ROI | Source |
|----------------|-------------------|---------------|----------------|-----|---------|
| [Feature Name] | [Use Cases with Context] | [Drivers with Examples] | [Pattern with Timeline] | [ROI with Metrics] | [^n] |

Required for each entry:
- Feature Name: Full feature name and version
- Use Cases: Detailed description with industry context
- Value Drivers: Specific examples and metrics
- Implementation: Step-by-step approach with timeline
- ROI: Quantified benefits with timeframe
- Source: Direct citation with date and URL

### Implementation Patterns
| Use Case | Approach | Requirements | Timeline | Success Factors | Evidence |
|----------|----------|--------------|----------|-----------------|-----------|
| [Use Case with Context] | [Detailed Approach] | [Full Requirements] | [Detailed Timeline] | [Proven Factors] | [^n] |

Required for each pattern:
- Use Case: Full context and business problem
- Approach: Detailed implementation steps
- Requirements: Complete technical and business requirements
- Timeline: Phase-wise breakdown with dependencies
- Success Factors: Evidence-based success criteria
- Evidence: Implementation example citation

### Value Assessment
| Mapping | Business Impact | Technical Fit | User Value | ROI Range | Validation |
|---------|----------------|---------------|------------|-----------|------------|
| [Detailed Mapping] | [Quantified Impact] | [Fit Analysis] | [Value Metrics] | [ROI Details] | [^n] |

Required for each assessment:
- Mapping: Specific feature-use case pair
- Impact: Quantified business benefits
- Fit: Technical alignment analysis
- Value: User-specific benefits
- ROI: Detailed calculation methodology
- Validation: Real implementation reference

7. OPPORTUNITY CATEGORIZATION
   Classify by:
   - Implementation Readiness (High/Medium/Low)
   - Business Impact (High/Medium/Low)
   - Technical Complexity (High/Medium/Low)
   - User Adoption (High/Medium/Low)
   - ROI Potential (High/Medium/Low)

8. IMPLEMENTATION RECOMMENDATIONS
   For each mapping:
   - Setup guidance
   - Integration approach
   - Data preparation
   - User enablement
   - Success measurement

9. SOURCES & CITATIONS
   Include a dedicated section at the end:

### Sources & Citations

Required Citation Format:
[^n]: Author/Organization. (Date). "Title of Source". Source Type. URL. Accessed: [Access Date]. Context: [Relevance to Cortex Feature/Use Case]

Example Citation Process:
1. Search Query: "enterprise AI search capabilities implementation analysis 2025"
2. Search Results Found: 
   a. Title: "Enterprise Search Technology: Implementation Patterns" - ACM Digital Library
   b. Title: "AI-Powered Search in Enterprise Systems" - IEEE Software Engineering
   c. Title: "Enterprise Search Market Analysis 2025" - Gartner Research
3. URL Verification: All pages accessible via Playwright MCP
4. Information Found: Implementation patterns, technical architecture, market analysis
5. Final Citations:
[^1]: ACM Digital Library. (2025-08-15). "Enterprise Search Technology: Implementation Patterns". Research Paper. https://dl.acm.org/doi/enterprise-search-2025. Accessed: [TODAY'S_DATE]. Search Query: "enterprise search implementation". Context: Academic analysis of enterprise search patterns and architectures.
[^2]: IEEE Software Engineering. (2025-09-01). "AI-Powered Search in Enterprise Systems". Technical Journal. https://www.computer.org/software/ai-search-2025. Accessed: [TODAY'S_DATE]. Search Query: "AI enterprise search". Context: Technical evaluation of AI search capabilities and implementation approaches.
[^3]: Gartner Research. (2025-08-30). "Enterprise Search Market Analysis 2025". Industry Research. https://www.gartner.com/research/enterprise-search-2025. Accessed: [TODAY'S_DATE]. Search Query: "enterprise search market". Context: Market analysis of enterprise search technologies and adoption patterns.

IMPORTANT: Citations must come directly from Brave Search results. Follow these steps:
1. For each feature analysis:
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
   - Product documentation only
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
   - Feature/use case relevance explanation (specific to Cortex capabilities and implementation)

2. Source Types (in priority order)
   - Academic & Research
     * Research papers
     * Technical journals
     * Conference proceedings
     * University studies
     * Research institutions
     * Scholarly articles
   - Industry Analysis
     * Market research firms
     * Technology analysts
     * Research organizations
     * Think tanks
     * Industry associations
     * Standards bodies
   - Technical Publications
     * Engineering journals
     * Technical reviews
     * Architecture studies
     * Performance research
     * Implementation studies
     * Benchmark reports
   - Professional Resources
     * Industry experts
     * Technical committees
     * Standards organizations
     * Professional associations
     * Certification bodies
     * Research fellows
   - Implementation Research
     * Case studies
     * Technical papers
     * Architecture reviews
     * Performance studies
     * Integration research
     * Adoption analysis

3. Validation Requirements
   - Cross-reference multiple sources
   - Verify feature availability
   - Check version compatibility
   - Validate use cases
   - Confirm requirements
   - Verify success metrics

4. Context Requirements
   - Explain feature relevance
   - Provide use case context
   - Include technical details
   - Document dependencies
   - Note limitations
   - Highlight benefits

5. Update Requirements
   - Review sources monthly
   - Update feature changes
   - Refresh use cases
   - Track new patterns
   - Monitor versions
   - Document deprecations
```

## Follow-up Prompt for Synthesis

```
Based on the feature mapping analysis provided, please synthesize the findings into actionable recommendations:

1. Evaluate implementation priorities based on:
   - Business impact
   - Technical readiness
   - User adoption
   - Implementation ease
   - ROI potential
   (Include citations for supporting evidence[^n])

2. Create an implementation roadmap:
   - Quick wins (0-30 days)
   - Core features (30-90 days)
   - Advanced capabilities (90-180 days)
   - Innovation enablers (180+ days)
   (Reference specific examples and patterns[^n])

Present this synthesis in a clear, actionable format with specific recommendations for Cortex implementation.
```

## Usage Instructions

1. Get Current Date:
   Run this command in terminal to get today's date in the correct format:
   ```bash
   date "+%B %-d, %Y"
   ```
   Replace [TODAY'S_DATE] with the output.

2. MCP Tools Setup:
   - Configure Playwright for documentation analysis
   - Verify access to Brave Search API
   - Initialize Memory system for pattern tracking
   - Prepare Sequential Thinking framework

3. Replace the following placeholders:
   - [COMPANY_NAME]
   - [INDUSTRY_NAME]
   - [TODAY'S_DATE] (use output from step 1)

4. Review and validate the output against these criteria:
   - Feature mapping accuracy
   - Use case alignment
   - Implementation patterns
   - Value assessment
   - ROI potential
   - Citation accuracy
   - Source credibility

5. Citation Format Requirements:
   - Use footnote-style citations [^n]
   - Include direct URLs
   - Date all findings
   - Cite implementation evidence
   - Cross-reference patterns

6. Use the follow-up prompt to create actionable implementation strategies

## Notes

- This template leverages AI capabilities for comprehensive feature mapping
- The structured format ensures consistent use case evaluation
- Focus on industry-specific value and implementation patterns
- Regular updates maintain feature intelligence currency
- Citations ensure information traceability
- Pattern analysis provides clear implementation guidance
- Quarterly updates capture feature evolution
- Insights drive successful adoption
