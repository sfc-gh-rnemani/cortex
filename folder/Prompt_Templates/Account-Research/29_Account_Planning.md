# Account Planning AI Prompt Template

## MCP Tools Integration
This template leverages the following MCP tools for efficient account planning:

1. **Playwright**
   - Automate research collection
   - Extract industry insights
   - Monitor company updates
   - Track market trends

2. **Brave Search**
   - Research industry developments
   - Find relevant use cases
   - Track competitive moves
   - Discover market opportunities

3. **Memory**
   - Store account insights
   - Track engagement history
   - Maintain relationship data
   - Save relevant citations

4. **Sequential Thinking**
   - Analyze opportunities
   - Connect insights to actions
   - Structure engagement approach
   - Prioritize initiatives

## Base Prompt

```
Act as a senior Snowflake Account Strategy consultant with extensive experience in data platform adoption. You have access to the MCP tools listed above for research and planning.

IMPORTANT DATE RULES:
- Current Date MUST be set using the terminal command: date "+%B %-d, %Y"
- Plan should start from [TODAY'S_DATE]
- Activities should be planned for next 12 months
- Include specific timing for all activities
- Track seasonal business impacts

Context:
- Target Company: [COMPANY_NAME]
- Industry: [INDUSTRY_NAME]
- Current Date: [TODAY'S_DATE] (from date command)
- Planning Timeframe: 12 months from [TODAY'S_DATE]

First, review and analyze all documents in the [COMPANY_NAME] folder:
1. Industry Analysis
2. News Updates
3. Regulatory Research
4. Engagement Calendar
5. Any additional documents

Then, create a comprehensive account plan following these steps:

1. OPPORTUNITY ANALYSIS
   Based on document review, identify:
   - Key business initiatives
   - Data challenges
   - Regulatory requirements
   - Technology needs
   - Market pressures
   [Cite specific documents and sections for each finding]

2. SOLUTION MAPPING
   For each identified opportunity:
   - Relevant Snowflake capabilities (from verified documentation)
   - Industry-specific use cases (from public case studies)
   - Technical requirements (from official guides)
   - Expected business impact (with verified metrics)
   - Implementation considerations (from proven deployments)
   [Link solutions to specific business needs with verified sources]
   
   For each Snowflake capability identified:
   - Official documentation URL (verified via Playwright MCP)
   - Relevant quickstarts (from docs.snowflake.com)
   - Technical guides (with validated links)
   - Solution architectures (from public documentation)
   - Customer case studies (from official success stories)
   [Include verified URLs with access dates in [TODAY'S_DATE] format]

   Example Solution Documentation:
   - Capability: Snowflake Data Sharing
     * Documentation: [Snowflake Docs](https://docs.snowflake.com/en/user-guide/data-sharing). Accessed: [TODAY'S_DATE].
     * Quickstart: [Getting Started](https://quickstarts.snowflake.com/). Accessed: [TODAY'S_DATE].
     * Architecture: [Reference Guide](https://docs.snowflake.com/en/user-guide/intro-solutions). Accessed: [TODAY'S_DATE].
     * Case Study: [Customer Stories](https://www.snowflake.com/customers/). Accessed: [TODAY'S_DATE].
     * Verification: All URLs validated via Playwright MCP

3. STAKEHOLDER ANALYSIS
   Based on research:
   - Key decision makers
   - Technical evaluators
   - Business users
   - Potential champions
   - Possible blockers
   [Reference specific mentions in documents]

4. ENGAGEMENT PLAN
   Create a month-by-month plan with specific activities:

   Month 1 (Current: [MONTH_NAME])
   Week 1:
   - Activity 1 [Reference to supporting research]
   - Activity 2 [Reference to supporting research]
   Week 2:
   - Activities...
   [Continue for all weeks]

   Month 2 ([NEXT_MONTH_NAME])
   Week 1:
   - Activities...
   [Continue for all 12 months]

5. SUCCESS METRICS
   For each initiative:
   - Business KPIs
   - Technical metrics
   - Adoption indicators
   - Timeline milestones
   [Link to specific opportunities identified in research]

6. RISK MITIGATION
   Based on research:
   - Potential obstacles
   - Competitive threats
   - Technical challenges
   - Organizational barriers
   [Cite specific concerns from documents]

7. RESOURCE REQUIREMENTS
   Detail needed support:
   - Technical resources
   - Business resources
   - Training needs
   - Partner involvement
   [Link to specific initiatives]

8. OUTPUT FORMAT
   Present the plan in this structure:

   ## Executive Summary
   - Key opportunities
   - Expected outcomes
   - Critical success factors
   [With document references]

   ## Monthly Activity Calendar
   | Month | Week | Activity | Business Goal | Supporting Research |
   |-------|------|----------|---------------|-------------------|
   | [Month] | [Week] | [Activity] | [Goal] | [Citation] |

   ## Opportunity Details
   | Opportunity | Business Impact | Snowflake Solution | Supporting Research | Snowflake Documentation |
   |------------|-----------------|-------------------|-------------------|----------------------|
   | [Opportunity] | [Impact] | [Solution] | [Citation] | [Doc Links] |

   For each solution, include:
   - Product documentation URL
   - Quickstart guide URL
   - Solution architecture URL
   - Reference deployment URL
   - Case study URL

   ## Risk Management
   | Risk | Mitigation | Monitoring | Research Reference |
   |------|------------|------------|-------------------|
   | [Risk] | [Mitigation] | [Monitoring] | [Citation] |

9. SNOWFLAKE DOCUMENTATION
   For each technical solution:
   - Product Documentation
     * Feature documentation
     * API references
     * Best practices
     * Implementation guides
   
   - Quickstarts & Tutorials
     * Getting started guides
     * Step-by-step tutorials
     * Code samples
     * Video walkthroughs

   - Solution Architectures
     * Reference architectures
     * Design patterns
     * Implementation examples
     * Performance guidelines

   - Customer Success
     * Case studies
     * Success stories
     * Implementation guides
     * ROI examples

10. CITATIONS & REFERENCES

IMPORTANT: All citations must use verified URLs. Follow these steps:
1. Use Brave Search MCP to find official Snowflake documentation and resources
2. Use Playwright MCP to validate each URL before citing
3. Never create or guess URLs - only use verified, accessible links
4. Include access date in [TODAY'S_DATE] format
5. For product information, use official Snowflake documentation
6. For customer stories, cite public case studies
7. Never cite internal documents or private resources

Citation Requirements:
1. Source Attribution
   - Author/organization name (verified via official sources)
   - Publication/update date (YYYY-MM-DD, verified via source metadata)
   - Full title (exactly as appears on source page)
   - Source type classification (see Source Types below)
   - Direct URL (verified via Playwright MCP)
   - Access date (using [TODAY'S_DATE])
   - Planning relevance explanation (specific to account strategy)

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

Example Citation Process:
1. Search Query: "enterprise data platform strategy implementation analysis 2025"
2. Search Results Found: 
   a. Title: "Enterprise Data Strategy: Implementation Patterns" - MIT Sloan Management Review
   b. Title: "Data Platform Transformation Study" - Harvard Business Review
   c. Title: "Enterprise Technology Strategy Analysis" - Gartner Research
3. URL Verification: All pages accessible via Playwright MCP
4. Information Found: Strategy patterns, implementation approaches, success metrics
5. Final Citations:
[^1]: MIT Sloan. (2025-08-15). "Enterprise Data Strategy: Implementation Patterns". Research Paper. https://sloanreview.mit.edu/data-strategy-2025. Accessed: [TODAY'S_DATE]. Search Query: "enterprise data strategy". Context: Academic analysis of data platform strategy and implementation patterns.
[^2]: Harvard Business Review. (2025-09-01). "Data Platform Transformation Study". Management Research. https://hbr.org/2025/09/data-transformation. Accessed: [TODAY'S_DATE]. Search Query: "data platform transformation". Context: Research study on successful transformation approaches.
[^3]: Gartner Research. (2025-08-30). "Enterprise Technology Strategy Analysis". Industry Research. https://www.gartner.com/tech-strategy-2025. Accessed: [TODAY'S_DATE]. Search Query: "technology strategy analysis". Context: Industry analysis of technology strategy and implementation success factors.

For each insight and recommendation:
- Document name (from verified source)
- Section reference (with direct URL)
- Page/line numbers (if applicable)
- Relevant quotes (from verified source)
- Snowflake documentation URLs (validated via Playwright MCP)
- Access date (in [TODAY'S_DATE] format)
- Source verification method
```

## Usage Instructions

1. Get Current Date:
   Run this command in terminal to get today's date in the correct format:
   ```bash
   date "+%B %-d, %Y"
   ```
   Replace [TODAY'S_DATE] with the output.

2. MCP Tools Setup:
   - Configure Playwright for research automation
   - Set up Brave Search for market insights
   - Initialize Memory for relationship tracking
   - Prepare Sequential Thinking framework

3. Replace the following placeholders:
   - [COMPANY_NAME]
   - [INDUSTRY_NAME]
   - [TODAY'S_DATE] (use output from step 1)
   - [MONTH_NAME] (current month)
   - [NEXT_MONTH_NAME] (following month)

4. Execution Process:
   - Review all company documents
   - Analyze opportunities and challenges
   - Create detailed engagement plan
   - Link activities to research
   - Generate implementation roadmap

5. Review Criteria:
   - Activity relevance to research
   - Citation accuracy
   - Timeline feasibility
   - Resource availability
   - Risk assessment

## Maintenance Guidelines

### Automated Maintenance (Using MCP Tools)
1. **Regular Updates** (Playwright & Brave Search):
   - Monitor company news
   - Track industry changes
   - Update opportunity data
   - Refresh market insights

2. **Data Management** (Memory):
   - Update engagement history
   - Track relationship progress
   - Maintain citation database
   - Record activity outcomes

3. **Plan Optimization** (Sequential Thinking):
   - Reassess priorities
   - Update timelines
   - Revise activities
   - Refresh opportunities

### Manual Review
1. Verify current date using terminal command:
   ```bash
   date "+%B %-d, %Y"
   ```
2. Review plan progress
3. Update activity status
4. Adjust timelines
5. Refresh citations
6. Update stakeholder information

## Notes
- Update plan monthly
- Track activity outcomes
- Monitor stakeholder changes
- Document success stories
- Maintain citation accuracy
- Align with company events