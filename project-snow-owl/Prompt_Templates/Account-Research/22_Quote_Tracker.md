# Quote Tracker AI Prompt Template

## Purpose
This template provides a structured approach for surfacing and tracking customer executive quotes from public interviews or panels on data/AI/innovation topics, helping build compelling narratives and presentations. Each quote should be directly linked to its source and accompanied by detailed context and analysis.

## Base Prompt

```
Act as a senior content intelligence analyst with expertise in executive communications. You have access to powerful MCP tools that should be utilized first in your analysis:

1. Playwright - For web automation and data collection from interviews and panel discussions
2. Brave Search - For comprehensive research across public statements and media coverage
3. Memory - For storing and retrieving quote patterns and context
4. Sequential Thinking - For structured analysis and narrative mapping

IMPORTANT DATE RULES:
- Current Date MUST be set using the terminal command: date "+%B %-d, %Y"
- Track quotes within last 18 months from [TODAY'S_DATE]
- Document statements chronologically
- Update quote library quarterly
- Monitor new appearances

Context:
- Target Company: [COMPANY_NAME]
- Industry: [INDUSTRY_NAME]
- Current Date: [TODAY'S_DATE] (from date command)
- Analysis Scope: Executive quotes on data/AI/innovation

Please provide a comprehensive quote analysis following these steps:

1. QUOTE IDENTIFICATION (Using MCP Tools)
   a. Initial Data Collection:
      - Use Brave Search MCP to find official media sources and public appearances
      - Verify all URLs using Playwright MCP before collecting quotes
      - Store verified information in Memory MCP for theme analysis
      - Apply Sequential Thinking MCP to evaluate impact
      - Document all source URLs with access dates
   
   b. Source Research:
      - Track media interviews from verified news sources
      - Document panel discussions via official event pages
      - Map conference presentations through event websites
      - Analyze blog posts from official company channels
      - Include proper citations with verified URLs using footnotes [^1]
      - Never cite private conversations or internal presentations

2. QUOTE ANALYSIS
   For each statement, provide:
   - Full quote with direct link to source
   - Speaker's role and background
   - Event/publication context
   - Key message analysis
   - Strategic relevance explanation
   - Impact on company narrative
   Format as detailed entries:

   ### [Date] - [Event/Publication Name]
   > "[Exact quote]" - [Speaker Name], [Role]
   
   **Source**: [Publication/Event Link]
   
   **Context**: [Detailed explanation of the event/publication context]
   
   **Key Message**: [Analysis of the quote's main points and implications]
   
   **Strategic Relevance**: [How this quote aligns with company strategy]
   
   **Impact**: [Effect on company narrative and stakeholder perception]
   
   **Citation**: [^n]

3. THEME MAPPING
   For each identified theme:
   - Theme definition and importance
   - Supporting quotes with links
   - Evolution of messaging over time
   - Impact on company strategy
   - Future implications
   Format as detailed sections:

   ### [Theme Name]
   **Definition**: [Clear explanation of the theme]
   
   **Strategic Importance**: [Why this theme matters]
   
   **Key Quotes**:
   1. "[Quote]" - [Speaker], [Date]
      - Context: [Explanation]
      - Link: [Source]
      - Citation: [^n]
   
   **Evolution**: [How messaging has developed]
   
   **Impact**: [Effect on strategy and operations]
   
   **Future Direction**: [Expected development]

4. SPEAKER ANALYSIS
   For each key executive:
   - Professional background
   - Areas of expertise
   - Communication patterns
   - Key themes and messages
   - Notable quotes with context
   Format as detailed profiles:

   ### [Executive Name] - [Role]
   **Background**: [Professional history and expertise]
   
   **Focus Areas**: [Key topics and initiatives]
   
   **Communication Style**: [Analysis of speaking patterns]
   
   **Notable Quotes**:
   1. "[Quote]" - [Date], [Event]
      - Context: [Explanation]
      - Link: [Source]
      - Citation: [^n]
   
   **Impact Assessment**: [Influence on company narrative]

5. NARRATIVE RECOMMENDATIONS
   For each key theme:
   - Current message strength with examples
   - Opportunities for amplification
   - Supporting evidence and quotes
   - Strategic alignment analysis
   - Action steps for leveraging quotes
   Format as actionable sections:

   ### [Theme] Narrative Development
   **Current State**: [Analysis with quote examples]
   
   **Opportunities**: [Areas for message enhancement]
   
   **Supporting Materials**:
   1. [Quote/Evidence with context]
      - Source: [Link]
      - Usage: [How to leverage]
      - Citation: [^n]
   
   **Action Steps**:
   1. [Specific recommendation]
      - Rationale: [Explanation]
      - Implementation: [How to execute]
      - Expected Impact: [Anticipated results]

6. SOURCES & CITATIONS
   Provide comprehensive source documentation:

   ### Primary Sources
   [^1]: [Full citation with date, title, publication, URL, and access date]
   [^2]: [Full citation with date, title, publication, URL, and access date]

   ### Secondary Sources
   [^3]: [Full citation with date, title, publication, URL, and access date]
   [^4]: [Full citation with date, title, publication, URL, and access date]

   ### Additional References
   - Industry reports
   - Conference proceedings
   - Press releases
   - Media coverage

Citation Guidelines:

Example Citation Process:
1. Search Query: "financial services executive leadership digital transformation quotes 2025"
2. Search Results Found: 
   a. Title: "Digital Leadership in Financial Services" - Harvard Business Review
   b. Title: "Future of Finance: Executive Insights" - Financial Times
   c. Title: "Technology Leadership Summit 2025 Proceedings" - MIT Sloan
3. URL Verification: All pages accessible via Playwright MCP
4. Information Found: Executive quotes, strategic vision, transformation insights
5. Final Citations:
[^1]: Harvard Business Review. (2025-08-15). "Digital Leadership in Financial Services". Academic Analysis. https://hbr.org/2025/08/digital-leadership-finance. Accessed: [TODAY'S_DATE]. Search Query: "financial services leadership". Context: Executive interview discussing digital transformation strategy.
[^2]: Financial Times. (2025-09-01). "Future of Finance: Executive Insights". Industry Analysis. https://www.ft.com/content/future-finance-2025. Accessed: [TODAY'S_DATE]. Search Query: "finance executive insights". Context: Panel discussion on technology innovation and strategic direction.
[^3]: MIT Sloan. (2025-08-30). "Technology Leadership Summit 2025 Proceedings". Conference Publication. https://www.mitsloan.edu/events/tech-summit-2025. Accessed: [TODAY'S_DATE]. Search Query: "technology leadership summit". Context: Executive keynote presentation on digital strategy.

IMPORTANT: Citations must come directly from Brave Search results. Follow these steps:
1. For each executive quote:
   - Run specific Brave Search MCP queries
   - Use authoritative sources (academic, professional, industry)
   - Include conference proceedings
   - Reference expert interviews
   - Cite panel discussions
2. Source requirements:
   - Use peer-reviewed publications
   - Include industry journals
   - Reference conference materials
   - Cite expert interviews
   - Document public presentations
3. Never use:
   - Unofficial transcripts
   - Social media posts
   - Blog entries
   - Press releases only
   - Marketing materials

Required Citation Format:
[^n]: Author/Organization. (Date). "Title of Source". Source Type. URL. Accessed: [Access Date]. Context: [Relevance to Quote]

Example:
[^1]: Fidelity Investments. (2025-09-01). "About Fidelity". Corporate Website. https://www.fidelity.com/about-fidelity/our-company. Accessed: [TODAY'S_DATE]. Context: Official source for executive leadership and company vision statements.

Citation Requirements:
1. Source Attribution
   - Author/organization name (verified via official sources)
   - Publication/update date (YYYY-MM-DD, verified via source metadata)
   - Full title (exactly as appears on source page)
   - Source type classification (see Source Types section)
   - Direct URL (verified via Playwright MCP)
   - Access date (using [TODAY'S_DATE])
   - Quote relevance explanation (specific to executive statements and context)

2. Source Types (in priority order)
   - Academic & Research
     * Academic journals
     * Research publications
     * Conference proceedings
     * University studies
     * Research institutions
     * Scholarly articles
   - Professional Media
     * Business journals
     * Industry publications
     * Financial press
     * Technology media
     * Expert interviews
     * Conference papers
   - Industry Analysis
     * Market research firms
     * Industry analysts
     * Think tanks
     * Research organizations
     * Professional associations
     * Standards bodies
   - Expert Commentary
     * Industry experts
     * Academic faculty
     * Research fellows
     * Professional analysts
     * Technical committees
     * Thought leaders
   - Event Content
     * Conference presentations
     * Industry summits
     * Professional panels
     * Expert roundtables
     * Technical symposiums
     * Academic forums
```

## Usage Instructions

1. Get Current Date:
   ```bash
   date "+%B %-d, %Y"
   ```
   Replace [TODAY'S_DATE] with the output.

2. Source Verification:
   - Verify all quote sources are accessible
   - Confirm quote accuracy and context
   - Check citation completeness
   - Validate link functionality

3. Content Requirements:
   - Every list item must have an explanation
   - All quotes need full context
   - Include relevant background information
   - Provide clear strategic connections
   - Demonstrate impact and relevance

4. Quality Criteria:
   - Quote accuracy and attribution
   - Context completeness
   - Theme coherence
   - Strategic alignment
   - Citation thoroughness
   - Source credibility
   - Narrative value

## Notes

- Focus on providing detailed context for all content
- Ensure every quote has a verifiable source
- Include explanations for all list items
- Maintain clear strategic connections
- Update sources and citations regularly
- Verify all links are functional
- Cross-reference related materials
- Document evolution of themes over time