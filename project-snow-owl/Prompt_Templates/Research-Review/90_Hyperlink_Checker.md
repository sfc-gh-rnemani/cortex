# Hyperlink Verification Template

## Purpose
This template ensures all documents contain appropriate hyperlinks for references, citations, and key resources. Using automated browser validation, it verifies not only link accessibility but also content relevance and accuracy across all account documentation.

## Base Prompt

```
Act as a senior documentation analyst with expertise in technical writing and automated content validation. Review all completed documents for [COMPANY_NAME] using the following hyperlink verification process:

IMPORTANT RULES:
- Every citation MUST have a corresponding hyperlink
- Every external reference MUST have a hyperlink
- Company names should link to their primary website
- Executive names should link to their professional profiles
- Events should link to their official pages
- All hyperlinks must be properly formatted in markdown: [Text](URL)
- Every link MUST be validated to verify content accuracy

Context:
- Target Company: [COMPANY_NAME]
- Industry: [INDUSTRY_NAME]
- Current Date: [TODAY'S_DATE] (from date command)
- Review Scope: All account documentation

1. AUTOMATED LINK VALIDATION REQUIREMENTS

   For each hyperlink:
   □ Navigate to the URL
   □ Verify page loads successfully
   □ Extract and analyze page content
   □ Confirm content matches citation claims
   □ Check for relevant keywords and data
   □ Document any content mismatches

2. CONTENT VALIDATION CRITERIA

   Company Websites:
   □ Official domain verification
   □ Company name presence
   □ Key business information
   □ Recent content updates
   □ Proper navigation structure

   Executive Profiles:
   □ Name verification
   □ Current role confirmation
   □ Company affiliation
   □ Professional history
   □ Recent activity

   Industry Resources:
   □ Publication date verification
   □ Author/source credibility
   □ Data accuracy
   □ Industry relevance
   □ Citation context match

   News & Press Releases:
   □ Date accuracy
   □ Source verification
   □ Content completeness
   □ Quote accuracy
   □ Data validation

   Case Studies & Success Stories:
   □ Company name verification
   □ Implementation details
   □ Results validation
   □ Timeline accuracy
   □ ROI metrics confirmation

3. DOCUMENT HYPERLINK REQUIREMENTS

   Industry Analysis:
   □ Industry reports citations
   □ Consulting firm references
   □ Statistical sources
   □ Company websites
   □ Technology references

   Regulatory Research:
   □ Regulatory body websites
   □ Policy documents
   □ Compliance frameworks
   □ Enforcement examples
   □ Industry standards

   Executive Research:
   □ Executive LinkedIn profiles
   □ Company leadership pages
   □ Professional organizations
   □ Industry associations
   □ Board memberships

   News Summary:
   □ News article sources
   □ Press releases
   □ Media coverage
   □ Industry updates
   □ Company announcements

   Engagement Calendar:
   □ Event websites
   □ Conference pages
   □ Industry meetups
   □ Trade shows
   □ Registration links

   Account Plan:
   □ Company website
   □ Product pages
   □ Service offerings
   □ Team resources
   □ Support links

   Snowflake POV:
   □ Case study references
   □ Implementation examples
   □ ROI metrics sources
   □ Technical documentation
   □ Customer testimonials
   □ Product capabilities
   □ Industry solutions
   □ Partner ecosystem

4. HYPERLINK VERIFICATION FORMAT

   | Document | Section | Link Text | URL | Content Match | Status |
   |----------|----------|-----------|-----|---------------|---------|
   | [Doc Name] | [Section] | [Text] | [URL] | [Yes/No/Partial] | [Valid/Invalid] |

5. CONTENT VALIDATION REPORT

   For each link:
   - Expected Content: [Key claims or data points]
   - Found Content: [Actual content from page]
   - Match Status: [Full/Partial/None]
   - Discrepancies: [List any mismatches]
   - Recommendations: [Suggested fixes]

6. QUALITY STANDARDS

   Each hyperlink must:
   □ Be relevant to the content
   □ Point to authoritative sources
   □ Use proper markdown format
   □ Have descriptive link text
   □ Be recently verified (within 30 days)
   □ Contain claimed content (verified through validation)

7. AUTOMATED VALIDATION PROCESS

   For each link:
   1. Navigate to URL
   2. Wait for page load
   3. Extract visible text
   4. Compare with expected content
   5. Document validation results
   6. Record any errors

8. ERROR CATEGORIES

   | Error Type | Description | Action Required |
   |------------|-------------|-----------------|
   | Dead Link | URL not accessible | Find current URL |
   | Wrong Format | Incorrect markdown | Fix syntax |
   | Content Mismatch | Expected content not found | Update link or claims |
   | Outdated | Content obsolete | Update to current source |
   | Missing | Required link absent | Add appropriate link |
   | Invalid Content | Content doesn't match claims | Verify and update claims |

9. REPORTING FORMAT

   ### Document Link Status
   **Document Name**: [Name]
   **Review Date**: [Date]
   **Reviewer**: [Name]

   Link Statistics:
   - Total Links: [Number]
   - Valid Links: [Number]
   - Invalid Links: [Number]
   - Missing Links: [Number]
   - Content Mismatches: [Number]

   Content Validation Results:
   - Full Matches: [Number]
   - Partial Matches: [Number]
   - No Matches: [Number]

   Critical Issues:
   - [List of problems requiring immediate attention]

   Recommendations:
   - [Specific actions to resolve issues]

10. QUALITY METRICS

    Score each document (1-5):
    - Link Coverage
    - Link Validity
    - Content Accuracy
    - Format Accuracy
    - Source Authority

## Usage Instructions

1. Get Current Date:
   ```bash
   date "+%B %-d, %Y"
   ```
   Replace [TODAY'S_DATE] with the output.

2. Replace placeholders:
   - [COMPANY_NAME]
   - [INDUSTRY_NAME]
   - [TODAY'S_DATE]

3. Execute automated verification:
   - Process all documents
   - Validate each hyperlink
   - Extract and verify content
   - Document results
   - Generate recommendations

4. Review criteria:
   - Link functionality
   - Content accuracy
   - Source authority
   - Format accuracy
   - Coverage completeness

## Maintenance Notes
- Update verification results monthly
- Document all link and content issues
- Track resolution progress
- Maintain link database
- Monitor source reliability
- Update content validation criteria as needed

## Content Validation Examples

1. Executive Profile Link:
   - Expected: Current role, company affiliation
   - Check: Page contains executive name and current position
   - Validate: Role and company match claims

2. News Article Link:
   - Expected: Specific news, date, quotes
   - Check: Article content matches citation
   - Validate: Data points and quotes are accurate

3. Industry Report Link:
   - Expected: Statistics, findings, date
   - Check: Report contains cited data
   - Validate: Numbers and conclusions match

4. Company Website Link:
   - Expected: Product info, services
   - Check: Content matches references
   - Validate: Information is current and accurate

5. Case Study Link:
   - Expected: Company name, implementation details, results
   - Check: Success metrics and timeline accuracy
   - Validate: ROI claims and technical details

## Validation Code Example

```python
async def validate_link(url, expected_content):
    # Use appropriate web automation tools to validate links
    try:
        # Navigate to URL and extract content
        content = extract_page_content(url)
        
        validation = {
            'accessible': True,
            'content_found': all(text in content for text in expected_content)
        }
    except Exception as e:
        validation = {
            'accessible': False,
            'error': str(e)
        }
    
    return validation
```