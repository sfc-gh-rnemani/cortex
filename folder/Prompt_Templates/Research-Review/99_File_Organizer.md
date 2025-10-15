# File Organization and Naming Convention Template

## Purpose
This template ensures consistent file naming and organization across all account documentation, following the standardized numbering system used in the prompts directory.

## Base Prompt

```
Act as a file organization specialist with expertise in documentation management. Review and standardize file naming conventions for [COMPANY_NAME] using the following process:

IMPORTANT RULES:
- All files must follow the standard numbering convention from prompts
- File numbers must be two digits with leading zero (01_, 02_, etc.)
- Company code must be uppercase
- Dates must be in YYYY_MM_DD format
- File extensions must be lowercase (.md)
- No spaces in filenames (use underscores)
- Maintain consistent capitalization

Context:
- Target Company: [COMPANY_NAME]
- Company Code: [COMPANY_CODE]
- Current Date: [TODAY'S_DATE] (from date command)
- Base Directory: [COMPANY_CODE lowercase]

1. STANDARD FILE NAMING PATTERNS

Required Files and Numbering:
01_Industry_Analysis:
   - Format: {##}_{Industry_Name}_Analysis_YYYY.md
   - Example: 01_Industrial_Manufacturing_Analysis_2025.md

02_Regulatory_Research:
   - Format: {##}_{COMPANY_CODE}_YYYY_Regulatory_Research.md
   - Example: 02_DOVER_2025_Regulatory_Research.md

10_Executive_Research:
   - Format: {##}_{COMPANY_CODE}_YYYY_Executive_Research.md
   - Example: 10_DOVER_2025_Executive_Research.md

11_Company_News:
   - Format: {##}_{COMPANY_CODE}_YYYY_MM_DD_news.md
   - Example: 11_DOVER_2025_08_05_news.md

50_Engagement_Calendar:
   - Format: {##}_{COMPANY_CODE}_YYYY_Engagement_Calendar.md
   - Example: 50_DOVER_2025_Engagement_Calendar.md

70_Account_Planning:
   - Format: {##}_{COMPANY_CODE}_YYYY_Account_Plan.md
   - Example: 70_DOVER_2025_Account_Plan.md

80_Snowflake_POV:
   - Format: {##}_{COMPANY_CODE}_YYYY_Snowflake_POV.md
   - Example: 80_DOVER_2025_Snowflake_POV.md

98_Hyperlink_Checker:
   - Format: {##}_{COMPANY_CODE}_YYYY_Hyperlink_Verification.md
   - Example: 98_DOVER_2025_Hyperlink_Verification.md

99_Completion_Verification:
   - Format: {##}_{COMPANY_CODE}_YYYY_Completion_Verification.md
   - Example: 99_DOVER_2025_Completion_Verification.md

2. VERIFICATION PROCESS

For each company directory:
a. List all existing files
b. Compare against required naming pattern
c. Identify any mismatches
d. Generate rename commands if needed
e. Verify no duplicate files
f. Check for missing required files

3. OUTPUT FORMAT

### File Organization Report for [COMPANY_NAME]
Current as of: [TODAY'S_DATE]

#### File Inventory
| Current Filename | Required Pattern | Status | Action Needed |
|-----------------|------------------|--------|---------------|
| [Filename] | [Pattern] | [Match/Mismatch] | [Action] |

#### Missing Required Files
- [List any missing required files]

#### Rename Actions Required
```bash
mv [old_name] [new_name]
```

#### Verification Checklist
□ All required files present
□ Consistent numbering prefix (##_)
□ Consistent company code usage
□ Correct date formats
□ Proper capitalization
□ No duplicate files
□ No extraneous files

4. MAINTENANCE GUIDELINES

- Review file organization monthly
- Update dates in filenames as needed
- Archive outdated files
- Maintain consistent naming for new files
- Document any deviations from standard
```

## Usage Instructions

1. Get Current Date:
   ```bash
   date "+%B %-d, %Y"
   ```
   Replace [TODAY'S_DATE] with the output.

2. Replace placeholders:
   - [COMPANY_NAME]
   - [COMPANY_CODE]
   - [TODAY'S_DATE]

3. Execute verification:
   - Review all files in company directory
   - Compare against required patterns
   - Generate rename commands if needed
   - Document missing files
   - Create verification report

4. Review criteria:
   - Filename accuracy
   - Pattern compliance
   - Numbering prefix consistency
   - Date format consistency
   - Capitalization standards
   - Required file presence

## Notes
- Update verification monthly
- Document any exceptions
- Track rename actions
- Maintain history of changes
- Review for new requirements
- Adjust patterns as needed