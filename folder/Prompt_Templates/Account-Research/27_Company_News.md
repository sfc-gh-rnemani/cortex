# News Summary Template

## MCP Tools Integration
This template leverages the following MCP tools for efficient news gathering and analysis:

1. **Playwright**
   - Automate news collection from company websites
   - Scrape relevant industry news portals
   - Extract data from financial platforms
   - Navigate through investor relations pages

2. **Brave Search**
   - Perform real-time news searches
   - Filter for recent industry developments
   - Discover competitor activities
   - Track market trends

3. **Memory**
   - Store and categorize news items
   - Track historical trends
   - Maintain competitor activity logs
   - Save relevant URLs and sources

4. **Sequential Thinking**
   - Analyze news impact systematically
   - Prioritize stories by relevance
   - Connect related industry developments
   - Structure market trend analysis

## Required Format

### Date Requirements
Run this command in terminal to get today's date in the correct format:
```bash
date "+%B %-d, %Y"
```
Replace [TODAY'S_DATE] with the output.

### Story Requirements
- **Current Date**: [TODAY'S_DATE] (from date command)
- **Timeliness**: All news stories MUST be from within 30 days prior to [TODAY'S_DATE]
- **Date Format**: Use consistent date format (Month DD, YYYY) from date command
- **Sorting**: Present stories in reverse chronological order (newest first)
- **Relevance**: Focus on company-specific news, industry developments, and market impacts
- **Verification**: All stories must be from credible business news sources
- **Currency**: Update news files at least monthly to maintain relevance

### Story Structure
For each story, utilize MCP tools in the following workflow:

1. **Discovery** (Using MCP Tools):
   - Use Brave Search MCP to find official company announcements and verified news sources
   - Verify all URLs using Playwright MCP before collecting news information
   - Store verified information in Memory MCP for trend analysis
   - Apply Sequential Thinking MCP to evaluate impact
   - Document all source URLs with access dates

2. **Documentation**:
- **Date**: [MM/DD/YYYY] (Must be within last 30 days)
- **Source**: [Official Publication Name] (verified via source metadata)
- **Link**: [Verified URL] (validated via Playwright MCP). Accessed: [TODAY'S_DATE].
- **Summary**: [2-3 sentences describing key points from verified source]
- **Business Impact**: [1-2 sentences on business implications with supporting evidence]
- **Source Type**: [Classification from Source Types list]
- **Verification**: [Brief note on source verification method]

3. **Analysis** (Using Sequential Thinking):
- Evaluate story significance
- Assess market implications
- Connect to broader industry trends

4. **Storage** (Using Memory):
- Save structured story data
- Tag with relevant categories
- Link to related historical items

### Required Sections
1. Company Name and Current Date
2. Three Recent Major News Stories (all within last 30 days)
3. Industry Focus Areas
4. Key Competitor Activities (include stock symbols where applicable)
5. Market Trends
6. Supply Chain Updates
7. Additional Resources
   - Corporate Website
   - Investor Relations
   - Latest Earnings Release
   - Other relevant links

### Link Requirements

IMPORTANT: All citations must use verified URLs. Follow these steps:
1. Use Brave Search MCP to find official news sources and company announcements
2. Use Playwright MCP to validate each URL before citing
3. Never create or guess URLs - only use verified, accessible links
4. Include access date in [TODAY'S_DATE] format
5. For company news, use official press releases and newsroom pages
6. For financial data, cite official investor relations sites
7. Never cite paywalled content or subscription-only articles

Link Verification Requirements:
1. Source Attribution
   - Author/organization name (verified via official sources)
   - Publication/update date (YYYY-MM-DD, verified via source metadata)
   - Full title (exactly as appears on source page)
   - Source type classification (see Source Types below)
   - Direct URL (verified via Playwright MCP)
   - Access date (using [TODAY'S_DATE])
   - News relevance explanation (specific to story impact and context)

2. Source Types (in priority order)
   - Academic & Research
     * Research institutions
     * Business schools
     * Economic research
     * Policy institutes
     * Think tanks
     * Academic journals
   - Financial Analysis
     * Investment banks
     * Research firms
     * Market analysts
     * Rating agencies
     * Economic institutes
     * Industry associations
   - Business Media
     * Financial press
     * Business journals
     * Industry news
     * Expert interviews
     * Conference papers
     * Market reports
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

### Formatting
- Use markdown formatting
- Include hyperlinks using [text](URL) format with verified URLs
- Maintain consistent date format (Month DD, YYYY)
- Use bullet points for lists
- Include company name in title
- Include current date in title

### Example Format:
```markdown
# FIDELITY INVESTMENTS
## News Summary - September 15, 2025

### Story 1: Financial Services Digital Transformation Analysis
- **Date**: September 12, 2025
- **Source**: Harvard Business Review
- **Link**: [Digital Transformation in Financial Services](https://hbr.org/2025/09/digital-transformation-finance). Accessed: [TODAY'S_DATE].
- **Search Query**: "financial services digital transformation trends 2025"
- **Summary**: Comprehensive analysis of digital transformation trends in financial services, with detailed examination of industry leaders' strategies and implementation approaches.
- **Business Impact**: Research highlights key success factors and strategic considerations for digital transformation initiatives in the financial sector.

### Story 2: Market Analysis of Financial Technology Innovation
- **Date**: September 10, 2025
- **Source**: MIT Technology Review
- **Link**: [Financial Technology Innovation Report](https://www.technologyreview.com/fintech-innovation-2025). Accessed: [TODAY'S_DATE].
- **Search Query**: "financial technology innovation analysis 2025"
- **Summary**: In-depth study of financial technology innovation patterns, including analysis of market leaders and emerging technology trends.
- **Business Impact**: Research provides framework for evaluating technology investment strategies and innovation approaches.

### Story 3: Industry Leadership and Strategy Research
- **Date**: September 8, 2025
- **Source**: McKinsey Global Institute
- **Link**: [Financial Services Leadership Study](https://www.mckinsey.com/mgi/finance-leadership-2025). Accessed: [TODAY'S_DATE].
- **Search Query**: "financial services industry leadership strategy 2025"
- **Summary**: Comprehensive research on industry leadership strategies and organizational approaches in financial services.
- **Business Impact**: Study offers insights into successful leadership models and strategic planning frameworks.

### Additional Resources
- **Academic Research**: [MIT Sloan Financial Services Research](https://sloanreview.mit.edu/finance-2025). Accessed: [TODAY'S_DATE].
- **Industry Analysis**: [Financial Services Quarterly Review](https://www.mckinsey.com/industries/financial-services/our-insights). Accessed: [TODAY'S_DATE].
- **Market Research**: [Gartner Financial Technology Analysis](https://www.gartner.com/finance-tech-2025). Accessed: [TODAY'S_DATE].
```

### Maintenance Guidelines

#### Automated Maintenance (Using MCP Tools)
1. **Regular Updates** (Playwright & Brave Search):
   - Schedule automated news searches
   - Run periodic link verification
   - Monitor competitor websites
   - Track industry news portals

2. **Data Management** (Memory):
   - Archive outdated stories (older than 30 days)
   - Maintain historical trend data
   - Update relationship mappings
   - Tag and categorize new information

3. **Analysis Updates** (Sequential Thinking):
   - Reassess market trend patterns
   - Update competitor activity analysis
   - Revise industry focus areas
   - Refresh impact assessments

#### Manual Review
1. Verify current date using terminal command:
   ```bash
   date "+%B %-d, %Y"
   ```
2. Remove stories older than 30 days from [TODAY'S_DATE]
3. Review and validate automated updates monthly
4. Verify source credibility for new outlets
5. Update custom search parameters as needed
6. Refine automated collection rules
7. Adjust analysis frameworks based on industry changes