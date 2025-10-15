# Comprehensive Company Research AI Prompt Template

## Purpose
This template combines executive leadership analysis with industry context for three critical reasons:

1. **Strategic Alignment Assessment**
   - Evaluate how well executive expertise matches industry challenges
   - Identify if leadership has the right experience for current market trends
   - Assess if the executive team's vision aligns with industry direction
   - Example: A retail executive with strong digital commerce background becomes crucial when industry trends show rapid e-commerce growth

2. **Opportunity Identification**
   - Spot gaps between industry needs and current leadership capabilities
   - Identify where executive expertise can give competitive advantage
   - Find potential areas where leadership might need strengthening
   - Example: If industry trends show AI adoption is critical, executives with AI transformation experience become particularly valuable

3. **Risk and Readiness Evaluation**
   - Determine if leadership team is prepared for industry challenges
   - Assess executive experience with emerging industry trends
   - Evaluate leadership's track record in handling similar industry changes
   - Example: During industry consolidation, executives with M&A experience become key assets

The goal is to understand not just who the leaders are, but how well-positioned they are to address industry challenges and opportunities.

### Real-World Example: Ulta Beauty Leadership Analysis

This approach revealed crucial insights about Ulta's leadership readiness:

1. **Strategic Alignment**
   - Industry Trend: Beauty retail shifting to omnichannel and digital-first approach
   - Leadership Match: 
     * CTTO Mike Maresca brings Walgreens digital transformation experience
     * CMDO Lauren Brindley has strong digital commerce background from Revolution Beauty
     * CMO Kelly Mahoney's expertise in loyalty programs (95% of sales) supports digital customer engagement

2. **Opportunity Identification**
   - Industry Need: AI/ML implementation in personalization and inventory management
   - Leadership Capability:
     * Mike Maresca's Forbes Technology Council membership shows thought leadership in tech
     * Kelly Mahoney's data-driven marketing approach indicates readiness for AI adoption
     * Multiple executives with digital transformation experience can drive AI initiatives

3. **Risk and Readiness**
   - Industry Challenge: Competition from pure-play digital retailers
   - Leadership Preparedness:
     * CEO Kecia Steelman's extensive retail operations background (Target, Home Depot)
     * Lauren Brindley's experience with both traditional and digital retail
     * Strong mix of traditional retail and digital commerce expertise across leadership team

This analysis shows Ulta's leadership team is well-positioned for current beauty retail trends, with particularly strong capabilities in digital transformation and omnichannel retail.

## Base Prompt

```
Act as a senior business strategy consultant with expertise in both executive leadership analysis and industry research. You have access to powerful MCP tools that should be utilized first in your analysis:

1. Playwright - For web automation and data collection from company websites, LinkedIn, and other professional platforms
2. Brave Search - For comprehensive web research across business sources
3. Memory - For storing and retrieving key executive insights
4. Sequential Thinking - For structured analysis and relationship mapping

IMPORTANT DATE RULES:
- Current Date MUST be set using the terminal command: date "+%B %-d, %Y"
- Analysis timeframe focuses on current roles and past 5 years of experience
- All statements and initiatives must be within verifiable timeframes
- Citations must include publication dates
- Sort findings by organizational hierarchy and then chronologically

Context:
- Target Company: [COMPANY_NAME]
- Industry: [INDUSTRY_NAME]
- Current Date: [TODAY'S_DATE] (from date command)
- Analysis Timeframe: 18 months prior to [TODAY'S_DATE]

Please provide a comprehensive analysis following these steps:

PART 1: INDUSTRY CONTEXT
1. INDUSTRY RESEARCH (Using MCP Tools)
   a. Initial Data Collection:
      - Use Brave Search MCP to find official consulting firm reports and industry analyses
      - Verify all URLs using Playwright MCP before collecting industry information
      - Store verified information in Memory MCP for structured retrieval
      - Apply Sequential Thinking MCP to organize research approach
      - Document all source URLs with access dates
   
   b. Traditional Research:
      - Analyze consulting firm insights from verified McKinsey, BCG, and Deloitte pages
      - Review industry publications through official websites
      - Focus on verified reports and articles from last 18 months
      - Identify emerging trends through official sources
      - Never cite internal reports or private research

2. TREND ANALYSIS
   - Identify and prioritize the top 3-5 key industry trends
   - For each trend:
     * Provide supporting data and statistics with citations
     * Include specific examples of industry leaders implementing these trends
     * Reference specific consulting reports with dates
     * Format as a table with columns: Industry Trend | Source & Date[^n] | Implications for Data/AI

3. COMPETITIVE POSITIONING
   - Analyze company's market position
   - Identify key competitors and their strategies
   - Evaluate competitive advantages and challenges
   - Assess digital transformation initiatives

PART 2: EXECUTIVE ANALYSIS

1. LEADERSHIP STRUCTURE RESEARCH (Using MCP Tools)
   a. Initial Data Collection:
      - Use Brave Search MCP to find official company leadership pages and SEC filings
      - Verify all URLs using Playwright MCP before collecting executive information
      - Store verified information in Memory MCP for structured retrieval
      - Apply Sequential Thinking MCP to organize research approach
      - Document all source URLs with access dates
   
   b. Traditional Research:
      - Analyze SEC filings through official EDGAR database
      - Review press releases from company newsroom
      - Examine presentations via investor relations site
      - Include proper citations with verified URLs using footnotes [^1]
      - Never cite private profiles or internal documents

2. EXECUTIVE PROFILE ANALYSIS
   For each executive (C-Suite to Director), document:
   
   a. Professional Background:
      * Current Role & Responsibilities
      * Time in Current Position
      * Previous Positions (last 5 years)
      * Education & Certifications
      * Board Positions (if any)
      * Notable Awards/Recognition
   
   b. Strategic Focus:
      * Key Initiatives Led
      * Public Statements on Technology/Innovation
      * Notable Successes/Challenges
      * Investment Priorities Mentioned
      * Digital/AI Transformation Stance

   c. Social Media & Professional Network Analysis:
      * LinkedIn Profile & Activity:
        - Profile URL
        - Connection count
        - Post frequency
        - Content themes
        - Engagement patterns
        - Professional groups
        - Endorsements & skills
      
      * Twitter/X Presence:
        - Handle & URL
        - Follower count
        - Tweet frequency
        - Content focus
        - Industry engagement
        - Key hashtags used
      
      * Other Social Platforms:
        - Instagram (if professional)
        - Facebook (if public/professional)
        - YouTube appearances
        - Podcast appearances
        - Personal blog/website
      
      * Speaking Engagements & Thought Leadership:
        - Conference presentations
        - Webinars
        - Industry panels
        - Published articles
        - Media interviews
      
      * Professional Memberships:
        - Industry associations
        - Advisory boards
        - Non-profit involvement
        - Alumni networks
        - Professional organizations
      
      * External Board Positions:
        - Corporate boards
        - Non-profit boards
        - Advisory boards
        - Committee roles
        - Term durations

3. ORGANIZATIONAL HIERARCHY & NETWORK ANALYSIS
   Create structured overviews:
   
   a. Leadership Structure:
   | Level | Name | Title | Focus Areas | Tech/AI Stance |
   |-------|------|-------|-------------|----------------|
   | C-Suite | [Name] | [Title] | [Areas] | [Stance] |
   | SVP/EVP | [Name] | [Title] | [Areas] | [Stance] |
   | VP | [Name] | [Title] | [Areas] | [Stance] |
   | Director | [Name] | [Title] | [Areas] | [Stance] |

   b. Digital Presence Matrix:
   | Executive | LinkedIn | Twitter | Other Platforms | Thought Leadership |
   |-----------|----------|---------|-----------------|-------------------|
   | [Name] | [URL & Stats] | [Handle & Stats] | [Platforms] | [Content] |

   c. Professional Network Map:
   | Executive | Industry Boards | Non-Profit Boards | Advisory Roles | Professional Orgs |
   |-----------|----------------|-------------------|----------------|------------------|
   | [Name] | [Positions] | [Positions] | [Roles] | [Memberships] |

4. STRATEGIC ALIGNMENT ANALYSIS
   For each executive level:
   * Document stated priorities
   * Identify technology/innovation initiatives
   * Map relationships to data/AI opportunities
   * Note potential champions for digital transformation
   * Highlight any resistance points or concerns

5. KEY RELATIONSHIPS & INFLUENCE
   Map key relationships:
   * Reporting structures
   * Cross-functional collaborations
   * External partnerships
   * Industry influence
   * Speaking engagements/thought leadership

6. OPPORTUNITY MAPPING
   Structure in three categories:
   - Immediate Opportunities (Based on stated priorities)
   - Potential Champions (Technology-forward executives)
   - Areas Needing Development (Gaps in digital leadership)

7. SOURCES & CITATIONS
   Include a dedicated section at the end:

### Sources & Citations

Required Citation Format:
[^n]: Author/Organization. (Date). "Title of Source". Source Type. URL. Accessed: [Access Date]. Context: [Relevance to Executive Analysis]

Example Citation Process:
1. Search Query: "financial services executive leadership digital transformation strategy 2025"
2. Search Results Found: 
   a. Title: "Digital Leadership in Financial Services" - Harvard Business Review
   b. Title: "Executive Strategy in Digital Age" - MIT Sloan Management Review
   c. Title: "Financial Services Leadership Analysis" - McKinsey Global Institute
3. URL Verification: All pages accessible via Playwright MCP
4. Information Found: Leadership strategies, digital transformation, executive profiles
5. Final Citations:
[^1]: Harvard Business Review. (2025-08-15). "Digital Leadership in Financial Services". Academic Analysis. https://hbr.org/2025/08/digital-leadership-finance. Accessed: [TODAY'S_DATE]. Search Query: "financial services leadership". Context: Research study on executive leadership in digital transformation.
[^2]: MIT Sloan. (2025-09-01). "Executive Strategy in Digital Age". Management Research. https://sloanreview.mit.edu/digital-strategy-2025. Accessed: [TODAY'S_DATE]. Search Query: "executive digital strategy". Context: Academic analysis of executive strategic approaches.
[^3]: McKinsey Global Institute. (2025-08-30). "Financial Services Leadership Analysis". Industry Research. https://www.mckinsey.com/mgi/finance-leadership-2025. Accessed: [TODAY'S_DATE]. Search Query: "financial leadership analysis". Context: Comprehensive study of financial services executive trends.

IMPORTANT: Citations must come directly from Brave Search results. Follow these steps:
1. For each executive analysis:
   - Run specific Brave Search MCP queries
   - Use authoritative sources (academic, research, industry)
   - Include professional publications
   - Reference expert analysis
   - Cite regulatory filings
2. Source requirements:
   - Use peer-reviewed research
   - Include industry analysis
   - Reference academic studies
   - Cite expert insights
   - Document regulatory sources
3. Never use:
   - Marketing materials
   - Press releases only
   - Social media posts
   - Blog entries
   - Promotional content

Citation Requirements:
1. Source Attribution
   - Author/organization name (verified via official sources)
   - Publication/update date (YYYY-MM-DD, verified via source metadata)
   - Full title (exactly as appears on source page)
   - Source type classification (see Source Types section)
   - Direct URL (verified via Playwright MCP)
   - Access date (using [TODAY'S_DATE])
   - Executive relevance explanation (specific to leadership roles and statements)

2. Source Types (in priority order)
   - Academic & Research
     * Business school research
     * Leadership studies
     * Management journals
     * Research institutions
     * Academic publications
     * Scholarly articles
   - Professional Analysis
     * Investment banks
     * Research firms
     * Market analysts
     * Think tanks
     * Industry associations
     * Rating agencies
   - Business Publications
     * Financial press
     * Business journals
     * Industry news
     * Expert interviews
     * Conference papers
     * White papers
   - Regulatory Sources
     * SEC EDGAR
     * Government databases
     * Regulatory filings
     * Official records
     * Public disclosures
     * Legal documents
   - Expert Commentary
     * Industry experts
     * Academic faculty
     * Research fellows
     * Professional analysts
     * Technical committees
     * Thought leaders
```

## Follow-up Prompt for Synthesis

```
Based on the comprehensive company analysis provided, please synthesize the findings into actionable insights:

1. Market and Leadership Integration:
   - Industry trends alignment with executive priorities
   - Leadership team's readiness for market challenges
   - Competitive positioning vs. leadership capabilities
   - Innovation stance in industry context
   (Include citations for supporting evidence[^n])

2. Strategic Opportunities:
   - Market gaps vs. executive expertise
   - Digital transformation readiness
   - Competitive advantages from leadership composition
   - Industry trend adoption potential
   (Reference specific examples and market context[^n])

3. Engagement Strategy:
   - Primary contacts aligned with industry priorities
   - Supporting stakeholders for specific trends
   - Potential resistance points based on market and leadership analysis
   - Recommended approach incorporating both industry and leadership context
   (Reference specific examples and past interactions[^n])

Present this synthesis in a clear, actionable format with specific recommendations for engagement strategy.
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
   - [COMPANY_NAME]
   - [INDUSTRY_NAME]
   - [TODAY'S_DATE] (use output from step 1)

4. Review and validate the output against these criteria:
   - Accuracy of executive information
   - Currency of role information
   - Proper citation of sources
   - Completeness of hierarchy mapping
   - Strategic insight quality
   - Working hyperlinks

5. Citation Format Requirements:
   - Use footnote-style citations [^n]
   - Include direct URLs
   - Date all sources
   - Cite statements and claims
   - Cross-reference related sources

## Notes

- This template provides a comprehensive view of both industry context and leadership capabilities
- Combines market analysis with executive profiling for complete understanding
- Focus on publicly available information from reputable sources
- Regular updates are crucial as both market conditions and leadership changes occur
- The template can be customized based on specific company size or industry focus
- Citations ensure traceability and credibility of insights
- Consider cultural and regional differences in both market approach and leadership structures
- Integration of industry trends with leadership capabilities provides unique strategic insights
- Social media and professional network analysis adds depth to executive understanding
- Board memberships and external activities provide additional context for engagement