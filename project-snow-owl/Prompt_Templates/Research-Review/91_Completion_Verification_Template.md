# Account Research Completion Verification Template

## Purpose
This template ensures thorough completion of all research activities across the Industry Overview templates. Use this checklist to verify that each component has been properly executed and documented.

## Base Prompt

```
Act as a senior quality assurance analyst with expertise in comprehensive account research. Review all completed documents for [COMPANY_NAME] using the following verification process:

IMPORTANT DATE RULES:
- Verify all dates are current using terminal command: date "+%B %-d, %Y"
- Confirm all analysis is within specified timeframes
- Check that no outdated information is included
- Verify all citations include dates

Context:
- Target Company: [COMPANY_NAME]
- Industry: [INDUSTRY_NAME]
- Current Date: [TODAY'S_DATE] (from date command)
- Review Timeframe: All documents created/updated within last 30 days

1. DOCUMENT INVENTORY VERIFICATION
   Review presence and completeness of all required files:
   - 01 Industry Analysis (_{COMPANY_CODE}_Industry_Analysis.md)
   - 02 Regulatory Research (_{COMPANY_CODE}_YYYY_Regulatory_Research.md)
   - 10 Executive Research (_{COMPANY_CODE}_YYYY_Executive_Research.md)
   - 11 News Summary (_{COMPANY_CODE}_YYYY_MM_DD_news.md)
   - 50 Engagement Calendar (_{COMPANY_CODE}_YYYY_Engagement_Calendar.md)
   - 70 Account Plan (_{COMPANY_CODE}_YYYY_Account_Plan.md)
   - 80 Snowflake POV (_{COMPANY_CODE}_YYYY_Snowflake_POV.md)
   - 98 Hyperlink Verification (_{COMPANY_CODE}_YYYY_Hyperlink_Verification.md)
   - 99 Completion Verification (_{COMPANY_CODE}_YYYY_Completion_Verification.md)

2. INDUSTRY ANALYSIS VERIFICATION
   □ Industry trends identified with citations
   □ Data/AI implications documented
   □ Investment priorities specified
   □ Key statistics included
   □ Sources properly cited
   □ Maintenance notes included

3. NEWS SUMMARY VERIFICATION
   □ Recent major news stories (within 30 days)
   □ Industry focus areas identified
   □ Competitor activities documented
   □ Market trends analyzed
   □ Supply chain updates included
   □ Additional resources listed
   □ All links functional

4. REGULATORY RESEARCH VERIFICATION
   □ Current regulatory environment documented
   □ Enforcement trends analyzed
   □ Architecture implications detailed
   □ Implementation roadmap provided
   □ Citations included
   □ Risk mitigation strategies outlined

5. EXECUTIVE RESEARCH VERIFICATION
   □ Leadership structure documented
   □ Professional backgrounds detailed
   □ Strategic focus identified
   □ Social media presence analyzed:
     - LinkedIn profiles
     - Twitter/X presence
     - Other platforms
     - Speaking engagements
   □ Professional network mapped:
     - Industry boards
     - Non-profit boards
     - Advisory roles
     - Professional organizations
   □ Citations included
   □ Maintenance notes provided

6. ENGAGEMENT CALENDAR VERIFICATION
   □ Future events only (from current date)
   □ Event details complete:
     - Dates
     - Types
     - Locations
     - Target audiences
     - Strategic value
   □ Early bird deadlines noted
   □ Prioritization provided
   □ Links functional

7. ACCOUNT PLAN VERIFICATION
   □ Executive summary complete
   □ Opportunity analysis detailed
   □ Solution mapping comprehensive
   □ Stakeholder analysis included
   □ Monthly activity calendar populated
   □ Success metrics defined
   □ Risk mitigation strategies outlined
   □ Resource requirements specified
   □ Citations included
   □ Maintenance guidelines provided

8. SNOWFLAKE POV VERIFICATION
   □ Current state assessment complete:
     - Business challenges
     - Technical limitations
     - Market pressures
     - Regulatory requirements
   □ Strategic business outcomes defined:
     - Business outcomes mapped to capabilities
     - Case study references included
     - Success metrics specified
     - Implementation prerequisites noted
   □ Technical value drivers identified:
     - Data integration & quality
     - Analytics & ML/AI capabilities
     - Security & governance
     - Scalability & performance
     - Cost optimization
     - Time-to-market benefits
   □ Implementation approach detailed:
     - Quick wins identified
     - Strategic initiatives outlined
     - Risk mitigation strategies
     - Change management approach
   □ Proof points included:
     - Customer success stories
     - Industry-specific examples
     - Implementation details
     - Verified outcomes
     - Source links
     - Implementation timeframes
   □ Next steps defined:
     - Immediate actions
     - Proof of concept plan
     - Success criteria
     - Timeline
   □ All claims supported by case studies
   □ ROI claims verified with sources
   □ Implementation prerequisites noted
   □ Citations included and verified

9. CROSS-DOCUMENT CONSISTENCY CHECK
   □ Company name consistent across all documents
   □ Dates aligned and current
   □ Industry trends consistently referenced
   □ Executive information matches across documents
   □ Strategic priorities aligned
   □ Citations consistent and current
   □ Technical capabilities aligned across documents
   □ Business outcomes consistently referenced

10. CITATION VERIFICATION
    For each document:
    □ All sources cited properly
    □ Links functional
    □ Publication dates included
    □ Sources credible and current
    □ Cross-references accurate
    □ Case studies verified
    □ ROI claims validated

11. MAINTENANCE VERIFICATION
    □ Update schedules specified
    □ Responsibility assignments clear
    □ Review cycles defined
    □ Version control noted
    □ Change tracking process outlined
    □ Case study currency verified

12. OUTPUT FORMAT
    Provide verification results in this structure:

    ### [Document Name] Verification Results
    **Status**: [Complete/Incomplete/Needs Review]
    **Completion Rate**: [Percentage]
    **Critical Gaps**:
    - [Gap 1]
    - [Gap 2]
    **Recommendations**:
    - [Recommendation 1]
    - [Recommendation 2]

13. FOLLOW-UP ACTIONS
    For each incomplete item:
    - Specific action needed
    - Priority level
    - Recommended timeline
    - Required resources
    - Impact of omission

14. QUALITY METRICS
    Score each document (1-5) on:
    - Completeness
    - Currency
    - Accuracy
    - Citation quality
    - Internal consistency
    - Strategic value
    - ROI validation
    - Case study relevance

15. VERIFICATION SUMMARY
    Provide overall assessment:
    - Total completion percentage
    - Critical gaps summary
    - Priority recommendations
    - Required follow-up actions
    - Quality score average
```

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
   - [COMPANY_CODE]

3. Execute verification process:
   - Review all documents systematically
   - Complete all checklist items
   - Document gaps and recommendations
   - Provide specific follow-up actions

4. Review criteria:
   - Thoroughness of completion
   - Currency of information
   - Quality of analysis
   - Citation accuracy
   - Internal consistency
   - Strategic alignment
   - ROI validation
   - Case study verification

## Notes
- Update verification results monthly
- Document all identified gaps
- Track completion of recommendations
- Maintain verification history
- Review quality metrics trends
- Adjust checklist as needed
- Verify case study currency
- Validate ROI claims