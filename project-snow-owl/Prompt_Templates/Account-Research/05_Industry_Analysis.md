# Industry Analysis AI Prompt Template

## Purpose
This template provides a structured approach for analyzing industry trends and their implications for data, analytics, and AI investments using top-tier consulting firm research.

## Base Prompt

```
Act as a senior business strategy consultant with extensive experience analyzing [INDUSTRY_NAME]. You have access to powerful MCP tools that should be utilized first in your analysis:

1. Playwright - For web automation and data collection from industry websites
2. Brave Search - For comprehensive web research across industry sources
3. Memory - For storing and retrieving key industry insights
4. Sequential Thinking - For structured analysis and problem-solving

Additionally, you have comprehensive access to recent McKinsey, BCG, and Deloitte research.

IMPORTANT DATE RULES:
- Current Date MUST be set using the terminal command: date "+%B %-d, %Y"
- Analysis timeframe is 18 months prior to [TODAY'S_DATE]
- All statistics and data points must be within this timeframe
- Citations must include publication dates
- Sort findings chronologically when relevant

CONTEXT REQUIREMENTS:

Industry Profile:
- Industry Name: [INDUSTRY_NAME]
- Target Company: [COMPANY_NAME]
- Current Date: [TODAY'S_DATE] (from date command)
- Analysis Timeframe: 18 months prior to [TODAY'S_DATE]
- Market Size: [Add global market value]
- Growth Rate: [Add CAGR]
- Major Players: [Add top 3-5 companies]
- Technology Maturity: [Add assessment]

Industry Dimensions:
- Market Structure
  * Competitive Landscape
  * Value Chain
  * Distribution Channels
  * Customer Segments
  * Supplier Ecosystem
  * Regulatory Framework

- Technology Landscape
  * Digital Transformation Stage
  * Data/AI Adoption Level
  * Cloud Migration Status
  * Innovation Patterns
  * Tech Stack Trends
  * Platform Standards

- Data & Analytics
  * Data Sources
  * Analytics Capabilities
  * AI/ML Applications
  * Data Sharing
  * Industry Data Sets
  * Analytics Tools

Competitive Forces:
- Market Leaders
  * Core Capabilities
  * Tech Investments
  * Data Strategy
  * Innovation Focus
  * Market Share
  * Growth Trajectory

- Emerging Players
  * Value Proposition
  * Tech Advantage
  * Data Assets
  * Innovation Areas
  * Market Entry
  * Growth Rate

Industry Dynamics:
- Growth Drivers
  * Market Forces
  * Technology Trends
  * Customer Demands
  * Regulatory Changes
  * Innovation Waves
  * Economic Factors

- Challenges & Risks
  * Market Barriers
  * Tech Limitations
  * Data Challenges
  * Regulatory Issues
  * Resource Constraints
  * Competition Threats

Required Context Elements:
- Market Context: Industry structure, dynamics, and trends
- Technology Context: Digital transformation and innovation landscape
- Data Context: Industry-specific data and analytics patterns
- Competitive Context: Market leaders and emerging players
- Regulatory Context: Compliance requirements and changes
- Innovation Context: New technologies and applications
- Value Chain Context: End-to-end industry processes

Please provide a detailed analysis following these steps:

1. INDUSTRY RESEARCH (Using MCP Tools)
   a. Initial Data Collection:
      - Use Brave Search MCP to find official consulting firm reports and industry association publications
      - Verify all URLs using Playwright MCP before collecting industry data
      - Store verified information in Memory MCP for structured retrieval
      - Apply Sequential Thinking MCP to organize research approach
      - Document all source URLs with access dates
   
   b. Traditional Research:
      - Analyze consulting firm insights from verified McKinsey, BCG, and Deloitte industry pages
      - Review official industry association publications and verified market research
      - Focus on publicly accessible reports and articles from last 18 months
      - Identify emerging trends using multiple verified sources
      - Include proper citations with verified URLs using footnotes [^1]
      - Never cite paywalled content or subscription-only research

2. TREND ANALYSIS
   - Identify and prioritize the top 3-5 key industry trends
   - For each trend:
     * Provide supporting data and statistics with citations
     * Include specific examples of industry leaders implementing these trends
     * Reference specific consulting reports with dates
     * Format as a table with columns: Industry Trend | Source & Date[^n] | Implications for Data/AI

3. DATA & AI IMPLICATIONS
   - For each identified trend:
     * Analyze specific implications for data strategy
     * Identify AI/ML opportunities
     * Highlight potential implementation challenges
     * Suggest priority areas for investment
     * Cite specific examples and case studies[^n]

4. OUTPUT FORMAT
Present the analysis in the following structured table format:

| Industry Trend | Source & Date[^n] | Implications for Data/AI |
|----------------|---------------|-------------------------|
| [Trend 1]      | [Source][^n]  | [Implications]         |
| [Trend 2]      | [Source][^n]  | [Implications]         |
| [Trend 3]      | [Source][^n]  | [Implications]         |

5. KEY STATISTICS
   - Present key industry statistics with citations[^n]
   - Format as bullet points
   - Include source and date for each statistic

6. INVESTMENT PRIORITIES
   Structure in three timeframes:
   - Quick Wins (0-6 months)
   - Medium-Term Initiatives (6-12 months)
   - Long-Term Strategic Projects (12+ months)

7. SOURCES & CITATIONS
   Include a dedicated section at the end:

### Sources & Citations

Required Citation Format:
[^n]: Author/Organization. (Date). "Title of Source". Source Type. URL. Accessed: [Access Date]. Context: [Relevance to Industry Analysis]

Example Citation Process:
1. Search Query: "financial services industry trends digital transformation 2025"
2. Search Results Found: 
   a. Title: "Digital Banking Evolution: Industry Analysis 2025" - Journal of Financial Technology
   b. Title: "Financial Services Technology Trends" - Federal Reserve Economic Research
   c. Title: "Banking Industry Digital Transformation Report" - World Economic Forum
3. URL Verification: All pages accessible via Playwright MCP
4. Information Found: Industry trends, technology adoption, market statistics
5. Final Citations:
[^1]: Journal of Financial Technology. (2025-08-15). "Digital Banking Evolution: Industry Analysis 2025". Academic Research. https://www.jft.edu/banking-evolution-2025. Accessed: [TODAY'S_DATE]. Search Query: "financial services trends". Context: Peer-reviewed analysis of digital transformation trends.
[^2]: Federal Reserve. (2025-09-01). "Financial Services Technology Trends". Economic Research. https://www.federalreserve.gov/research/fintech-2025. Accessed: [TODAY'S_DATE]. Search Query: "banking technology trends". Context: Official statistics and industry analysis.
[^3]: World Economic Forum. (2025-08-30). "Banking Industry Digital Transformation Report". Industry Research. https://www.weforum.org/reports/banking-digital-2025. Accessed: [TODAY'S_DATE]. Search Query: "banking transformation". Context: Global industry trends and statistics.

IMPORTANT: Citations must come directly from Brave Search results. Follow these steps:
1. For each industry trend you analyze:
   - Run specific Brave Search MCP queries
   - Use diverse, authoritative sources
   - Include academic research when available
   - Reference government data where relevant
   - Cite professional organizations
2. Source requirements:
   - Use peer-reviewed publications
   - Include official statistics
   - Reference expert analysis
   - Cite industry standards
   - Document market research
3. Never use:
   - Unverified statistics
   - Outdated reports
   - Marketing materials
   - Promotional content
   - Non-authoritative blogs

Citation Requirements:
1. Source Attribution
   - Author/organization name (verified via official sources)
   - Publication/update date (YYYY-MM-DD, verified via source metadata)
   - Full title (exactly as appears on source page)
   - Source type classification (see Source Types section)
   - Direct URL (verified via Playwright MCP)
   - Access date (using [TODAY'S_DATE])
   - Industry relevance explanation (specific to trend analysis)

2. Source Types (in priority order)
   - Academic & Research
     * Peer-reviewed journals
     * Research institutions
     * Academic databases
     * Economic research
     * Scientific publications
   - Industry Analysis
     * Market research firms
     * Industry analysts
     * Economic institutes
     * Think tanks
     * Trade associations
   - Business Intelligence
     * Financial news services
     * Business journals
     * Market reports
     * Industry publications
     * Economic reviews
   - Government & Regulatory
     * Official statistics
     * Government reports
     * Regulatory filings
     * Policy papers
     * Public databases
   - Professional Sources
     * Industry conferences
     * Expert publications
     * Technical journals
     * Professional associations
     * Standards organizations

3. Validation Requirements
   - Cross-reference multiple sources
   - Verify market statistics
   - Check publication dates
   - Validate trend claims
   - Confirm company data
   - Verify technology claims

4. Context Requirements
   - Explain industry relevance
   - Provide market context
   - Include technology context
   - Document trend evidence
   - Note limitations
   - Highlight implications

5. Update Requirements
   - Review sources quarterly
   - Update market data
   - Refresh trend analysis
   - Track new studies
   - Monitor changes
   - Document developments
```

## Follow-up Prompt for Synthesis

```
Based on the analysis provided, please synthesize the findings into actionable insights:

1. Prioritize the identified trends based on:
   - Immediate impact potential
   - Implementation complexity
   - Required investment level
   - Competitive advantage potential
   (Include citations for supporting evidence[^n])

2. Create a high-level roadmap suggesting:
   - Quick wins (0-6 months)
   - Medium-term initiatives (6-12 months)
   - Long-term strategic projects (12+ months)
   (Reference specific industry examples and success cases[^n])

Present this synthesis in a clear, executive-friendly format with specific recommendations for data and AI investments.
```

## Usage Instructions

1. Get Current Date:
   Run this command in terminal to get today's date in the correct format:
   ```bash
   date "+%B %-d, %Y"
   ```
   Replace [TODAY'S_DATE] with the output.

2. MCP Tools Setup:
   - Ensure Playwright is configured for web automation
   - Verify access to Brave Search API
   - Initialize Memory system for data storage
   - Prepare Sequential Thinking framework

3. Replace the following placeholders:
   - [INDUSTRY_NAME]
   - [COMPANY_NAME]
   - [TODAY'S_DATE] (use output from step 1)

2. Ensure the analysis timeframe is adjusted if needed (default: past 18 months)

3. Review and validate the output against these criteria:
   - Specificity of insights
   - Actionability of recommendations
   - Currency of sources
   - Relevance to company context
   - Proper citation format
   - Working hyperlinks

4. Citation Format Requirements:
   - Use footnote-style citations [^n]
   - Include direct URLs
   - Date all sources
   - Cite statistics and key claims
   - Cross-reference related sources

5. Use the follow-up prompt to create an actionable synthesis of the findings

## Notes

- This prompt is designed to leverage advanced AI capabilities including deep research
- The structured format ensures consistency across different industry analyses
- The focus on data and AI implications helps identify specific investment opportunities
- The template can be customized based on specific industry requirements or company focus areas
- Citations and links ensure traceability and credibility of insights
- Regular updates to sources maintain relevance of analysis