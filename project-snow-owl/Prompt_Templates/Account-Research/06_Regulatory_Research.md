# Regulatory Research Template

## MCP Tools Integration
This template leverages the following MCP tools for efficient regulatory research:

1. **Playwright**
   - Automate regulatory website navigation
   - Extract compliance documentation
   - Monitor regulatory updates
   - Access industry frameworks

2. **Brave Search**
   - Research regulatory requirements
   - Find enforcement examples
   - Track compliance trends
   - Discover industry standards

3. **Memory**
   - Store regulatory findings
   - Track compliance history
   - Maintain framework relationships
   - Save relevant citations

4. **Sequential Thinking**
   - Analyze regulatory impact
   - Connect requirements to architecture
   - Structure compliance approach
   - Prioritize implementation

## Base Prompt

```
Act as a senior data governance expert with extensive experience in regulatory compliance. You have access to the MCP tools listed above for research and analysis.

IMPORTANT DATE RULES:
- Current Date MUST be set using the terminal command: date "+%B %-d, %Y"
- Only include regulations and frameworks current as of [TODAY'S_DATE]
- Focus on enforcement actions within 18 months of [TODAY'S_DATE]
- Track upcoming regulatory changes announced but not yet in effect
- Sort findings by implementation urgency

CONTEXT REQUIREMENTS:

Company Profile:
- Company Name: [COMPANY_NAME]
- Industry Vertical: [INDUSTRY_NAME]
- Current Date: [TODAY'S_DATE] (from date command)
- Analysis Timeframe: Current regulations and 18 months of enforcement history
- Company Size: [Add market cap/revenue]
- Geographic Presence: [Add regions/countries]
- Regulatory Jurisdiction: [Add primary regulators]
- Compliance Maturity: [Add assessment]

Regulatory Framework:
- Primary Regulators
  * Federal Agencies
  * State Regulators
  * Industry Bodies
  * International Authorities
  * Standards Organizations
  * Self-Regulatory Bodies

- Compliance Areas
  * Data Privacy
  * Information Security
  * Financial Controls
  * Industry Standards
  * Operational Requirements
  * Reporting Obligations

- Enforcement Mechanisms
  * Audits
  * Examinations
  * Investigations
  * Penalties
  * Remediation
  * Reporting

Technology Impact:
- Data Requirements
  * Storage Location
  * Retention Periods
  * Access Controls
  * Encryption Standards
  * Audit Trails
  * Data Quality

- Platform Controls
  * Security Measures
  * Access Management
  * Monitoring Systems
  * Backup Requirements
  * Recovery Standards
  * Documentation Needs

Implementation Context:
- Current State
  * Compliance Status
  * Control Framework
  * Technology Stack
  * Data Architecture
  * Process Maturity
  * Resource Capability

- Change Management
  * Implementation Timeline
  * Resource Requirements
  * Training Needs
  * Documentation Updates
  * Process Changes
  * Control Adjustments

Required Context Elements:
- Regulatory Context: Current requirements, upcoming changes, enforcement trends
- Technology Context: System implications, control requirements, architecture impact
- Process Context: Operational changes, workflow adjustments, documentation needs
- Resource Context: Implementation capacity, expertise requirements, training needs
- Risk Context: Compliance gaps, control weaknesses, remediation priorities
- Timeline Context: Implementation deadlines, phase requirements, milestone dates
- Cost Context: Implementation budget, resource allocation, ongoing maintenance

Please provide a comprehensive regulatory analysis following these steps:

1. REGULATORY IDENTIFICATION (Using MCP Tools)
   a. Initial Data Collection:
      - Use Brave Search MCP to find official regulatory agency websites and documentation
      - Verify all URLs using Playwright MCP before collecting regulatory information
      - Store verified information in Memory MCP for requirement tracking
      - Apply Sequential Thinking MCP to evaluate compliance impact
      - Document all source URLs with access dates
   
   b. Regulatory Research:
      - Search official government agency websites for industry-specific regulations
      - Document data governance frameworks from authoritative sources
      - Track compliance mandates through official regulatory bulletins
      - Monitor enforcement actions via official agency announcements
      - Follow upcoming regulatory changes through official channels
      - Never cite unofficial sources or draft regulations

2. REQUIREMENT ANALYSIS (Using Sequential Thinking)
   For each regulation/framework:
   - Core requirements
   - Data/analytics platform implications
   - Architecture impact
   - Security requirements
   - Audit/reporting needs

3. DOCUMENTATION FORMAT
   Structure findings in this table format:

   | Regulation/Framework | Requirement Summary | Architecture Impact | Implementation Priority | Enforcement Examples |
   |---------------------|---------------------|---------------------|------------------------|---------------------|
   | [Name] | [Summary] | [Impact] | [Priority] | [Examples] |

4. RELATIONSHIP MAPPING (Using Memory)
   Create connections between:
   - Related regulations
   - Common requirements
   - Shared compliance needs
   - Implementation dependencies

5. OUTPUT SECTIONS
   A. Current Regulatory Environment
      - Active regulations
      - Implementation deadlines
      - Compliance requirements
      - Recent updates

   B. Enforcement Trends
      - Recent actions
      - Common violations
      - Penalty patterns
      - Industry focus areas

   C. Architecture Implications
      - Data governance requirements
      - Security controls
      - Audit capabilities
      - Reporting needs

   D. Implementation Roadmap
      - Immediate priorities
      - Medium-term requirements
      - Long-term planning
      - Resource needs

   E. Sources & Citations

Required Citation Format:
[^n]: Author/Organization. (Date). "Title of Source". Source Type. URL. Accessed: [Access Date]. Context: [Relevance to Regulatory Analysis]

Example Citation Process:
1. Search Query: "financial services data privacy regulations compliance requirements 2025"
2. Search Results Found: 
   a. Title: "Financial Privacy Rule Implementation Guide" - Federal Register
   b. Title: "Data Protection in Financial Services" - Harvard Law Review
   c. Title: "ISO 27701 Privacy Information Management" - International Standards Organization
3. URL Verification: All pages accessible via Playwright MCP
4. Information Found: Privacy requirements, implementation guidelines, compliance standards
5. Final Citations:
[^1]: Federal Register. (2025-08-15). "Financial Privacy Rule Implementation Guide". Government Publication. https://www.federalregister.gov/documents/2025/privacy-implementation. Accessed: [TODAY'S_DATE]. Search Query: "financial privacy regulations". Context: Official regulatory requirements and implementation guidance.
[^2]: Harvard Law Review. (2025-09-01). "Data Protection in Financial Services". Legal Analysis. https://harvardlawreview.org/2025/data-protection-finance. Accessed: [TODAY'S_DATE]. Search Query: "financial data protection". Context: Legal interpretation and compliance implications.
[^3]: ISO. (2025-08-30). "ISO 27701 Privacy Information Management". International Standard. https://www.iso.org/standard/27701. Accessed: [TODAY'S_DATE]. Search Query: "privacy management standards". Context: International privacy management requirements and controls.

IMPORTANT: Citations must come directly from Brave Search results. Follow these steps:
1. For each regulatory requirement:
   - Run specific Brave Search MCP queries
   - Use authoritative sources (government, legal, academic)
   - Include official standards and frameworks
   - Reference expert legal analysis
   - Cite professional publications
2. Source requirements:
   - Use official government sources
   - Include academic legal research
   - Reference industry standards
   - Cite professional analysis
   - Document expert commentary
3. Never use:
   - Unofficial interpretations
   - Marketing materials
   - Draft regulations
   - Internal policies
   - Uncredited sources

Citation Requirements:
1. Source Attribution
   - Author/organization name (verified via official regulatory sources)
   - Publication/update date (YYYY-MM-DD, verified via source metadata)
   - Full title (exactly as appears on source page)
   - Source type classification (see Source Types section)
   - Direct URL (verified via Playwright MCP)
   - Access date (using [TODAY'S_DATE])
   - Regulatory relevance explanation (specific to compliance requirements)

2. Source Types (in priority order)
   - Official Government Sources
     * Federal regulations
     * State regulations
     * Regulatory agencies
     * Government databases
     * Official bulletins
     * Public records
   - Legal & Academic Sources
     * Law journals
     * Legal databases
     * Academic research
     * Policy papers
     * Research institutions
     * Scholarly articles
   - Industry Standards Bodies
     * International standards
     * National standards
     * Industry frameworks
     * Certification bodies
     * Professional associations
     * Technical committees
   - Professional Resources
     * Bar associations
     * Law reviews
     * Regulatory journals
     * Compliance publications
     * Industry guides
     * Expert commentary
   - Verified News Sources
     * Legal news services
     * Regulatory updates
     * Industry publications
     * Professional journals
     * Conference proceedings
     * Expert analysis

3. Validation Requirements
   - Cross-reference multiple sources
   - Verify current status
   - Check effective dates
   - Validate requirements
   - Confirm applicability
   - Verify control specifications

4. Context Requirements
   - Explain regulatory relevance
   - Provide compliance context
   - Include technical impact
   - Document control requirements
   - Note dependencies
   - Highlight deadlines

5. Update Requirements
   - Review sources monthly
   - Update requirement changes
   - Refresh control specifications
   - Track new guidance
   - Monitor enforcement
   - Document interpretations
```

## Usage Instructions

1. Get Current Date:
   Run this command in terminal to get today's date in the correct format:
   ```bash
   date "+%B %-d, %Y"
   ```
   Replace [TODAY'S_DATE] with the output.

2. MCP Tools Setup:
   - Configure Playwright for regulatory site automation
   - Set up Brave Search for compliance research
   - Initialize Memory for requirement tracking
   - Prepare Sequential Thinking framework

3. Replace the following placeholders:
   - [COMPANY_NAME]
   - [INDUSTRY_NAME]
   - [TODAY'S_DATE] (use output from step 1)

4. Execution Process:
   - Run initial regulatory discovery
   - Analyze requirements and impact
   - Document findings systematically
   - Create requirement relationships
   - Generate implementation roadmap

5. Review Criteria:
   - Regulation currency and relevance
   - Requirement completeness
   - Implementation feasibility
   - Citation accuracy
   - Source credibility

## Maintenance Guidelines

### Automated Maintenance (Using MCP Tools)
1. **Regular Updates** (Playwright & Brave Search):
   - Monitor regulatory changes
   - Track enforcement actions
   - Update requirement details
   - Verify citation links

2. **Data Management** (Memory):
   - Archive outdated regulations
   - Update requirement relationships
   - Track compliance history
   - Maintain citation database

3. **Analysis Updates** (Sequential Thinking):
   - Reassess implementation priorities
   - Update impact assessments
   - Revise roadmap timelines
   - Refresh requirement connections

### Manual Review
1. Verify current date using terminal command:
   ```bash
   date "+%B %-d, %Y"
   ```
2. Review regulatory currency
3. Validate enforcement examples
4. Update implementation priorities
5. Refresh roadmap timelines
6. Verify citation accuracy

## Notes
- Update analysis when new regulations announced
- Consider regional variations in requirements
- Track industry-specific interpretations
- Monitor enforcement patterns
- Document compliance decisions