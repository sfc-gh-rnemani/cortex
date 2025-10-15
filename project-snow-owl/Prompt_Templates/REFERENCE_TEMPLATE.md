# [TEMPLATE_NAME] AI Prompt Template

## Purpose
[BRIEF_DESCRIPTION_OF_WHAT_THIS_TEMPLATE_DOES]

---

## Template Information

**Template Category:** [Choose one: Account-Research / Competitive-Analysis / Technical-Assessment / Strategic-Planning / Other]
**Estimated Completion Time:** [X minutes/hours]
**Required Tools:** [List MCP tools needed: Brave Search, Playwright, Memory, etc.]
**Output Format:** [Report/Analysis/Summary/Action Items]

---

## Base Prompt

```
Act as a [ROLE_DESCRIPTION] with expertise in [DOMAIN_EXPERTISE]. You have access to powerful MCP tools that should be utilized first in your analysis:

1. [TOOL_1] - [Brief description of how to use this tool for this template]
2. [TOOL_2] - [Brief description of how to use this tool for this template] 
3. [TOOL_3] - [Brief description of how to use this tool for this template]
4. Sequential Thinking - For structured analysis and problem-solving

[ADDITIONAL_TOOL_CONTEXT_IF_NEEDED]

IMPORTANT DATE RULES:
- Current Date MUST be set using the terminal command: date "+%B %-d, %Y"
- Analysis timeframe is [TIME_PERIOD] prior to [TODAY'S_DATE]
- All statistics and data points must be within this timeframe
- Citations must include publication dates
- Sort findings chronologically when relevant

CONTEXT REQUIREMENTS:

[PRIMARY_SUBJECT] Profile:
- [FIELD_1]: [PLACEHOLDER_OR_INSTRUCTION]
- [FIELD_2]: [PLACEHOLDER_OR_INSTRUCTION]
- [FIELD_3]: [PLACEHOLDER_OR_INSTRUCTION]
- Current Date: [TODAY'S_DATE] (from date command)
- Analysis Timeframe: [TIME_PERIOD] prior to [TODAY'S_DATE]
- [ADDITIONAL_CONTEXT_FIELDS]

[ANALYSIS_DIMENSIONS]:
- [DIMENSION_1]
  * [SUB_DIMENSION_1A]
  * [SUB_DIMENSION_1B]
  * [SUB_DIMENSION_1C]

- [DIMENSION_2]
  * [SUB_DIMENSION_2A]
  * [SUB_DIMENSION_2B]
  * [SUB_DIMENSION_2C]

[ADD_MORE_DIMENSIONS_AS_NEEDED]

YOUR TASK:
Conduct a comprehensive analysis of [PRIMARY_RESEARCH_TARGET] by following these steps:

## Phase 1: [PHASE_1_NAME] (Use [SPECIFIC_TOOLS])
[DETAILED_INSTRUCTIONS_FOR_PHASE_1]

Key questions to answer:
- [QUESTION_1]
- [QUESTION_2]  
- [QUESTION_3]

## Phase 2: [PHASE_2_NAME] (Use [SPECIFIC_TOOLS])
[DETAILED_INSTRUCTIONS_FOR_PHASE_2]

Key questions to answer:
- [QUESTION_1]
- [QUESTION_2]
- [QUESTION_3]

## Phase 3: [PHASE_3_NAME] (Use [SPECIFIC_TOOLS])
[DETAILED_INSTRUCTIONS_FOR_PHASE_3]

Key questions to answer:
- [QUESTION_1]
- [QUESTION_2]
- [QUESTION_3]

[ADD_MORE_PHASES_AS_NEEDED]

RESEARCH REQUIREMENTS:
- [REQUIREMENT_1]
- [REQUIREMENT_2]
- [REQUIREMENT_3]
- [REQUIREMENT_4]

ANALYSIS QUALITY STANDARDS:
- [QUALITY_STANDARD_1]
- [QUALITY_STANDARD_2]
- [QUALITY_STANDARD_3]
- [QUALITY_STANDARD_4]

OUTPUT FORMAT:
Structure your analysis as follows:

# [OUTPUT_TITLE]

## Executive Summary
[BRIEF_OVERVIEW_REQUIREMENTS]

## [SECTION_1_NAME]
[SECTION_1_CONTENT_REQUIREMENTS]

## [SECTION_2_NAME]
[SECTION_2_CONTENT_REQUIREMENTS]

## [SECTION_3_NAME]
[SECTION_3_CONTENT_REQUIREMENTS]

## Key Insights & Recommendations
[INSIGHTS_REQUIREMENTS]

## Supporting Evidence
[EVIDENCE_REQUIREMENTS]

## Next Steps
[ACTION_ITEMS_REQUIREMENTS]

```

---

## Usage Instructions

### Before Using This Template:

1. **Replace All Placeholders**
   - Fill in all `[PLACEHOLDER]` fields with specific information
   - Customize the context requirements for your use case
   - Adjust timeframes and scope as needed

2. **Customize Tools Selection**
   - Review which MCP tools are actually needed
   - Remove tools that aren't relevant
   - Add specific instructions for tool usage

3. **Adapt Analysis Phases**
   - Modify phases to match your research objectives
   - Adjust the number of phases as needed
   - Ensure logical flow between phases

### Required Customizations:

| Placeholder | Description | Example |
|-------------|-------------|---------|
| `[TEMPLATE_NAME]` | Name of your specific template | "Customer Technology Stack Analysis" |
| `[BRIEF_DESCRIPTION]` | What this template accomplishes | "Analyzes customer's current technology landscape and identifies integration opportunities" |
| `[ROLE_DESCRIPTION]` | AI persona for the task | "senior technology consultant" |
| `[DOMAIN_EXPERTISE]` | Specific expertise area | "enterprise data architecture and cloud migrations" |
| `[PRIMARY_SUBJECT]` | Main research target | "Customer Technology Environment" |
| `[TIME_PERIOD]` | Research timeframe | "12 months" |
| `[ANALYSIS_DIMENSIONS]` | Research categories | "Technology Landscape" |

### Quality Checklist:

- [ ] All placeholders replaced with specific information
- [ ] Tool selection matches research needs
- [ ] Analysis phases flow logically
- [ ] Output format matches desired deliverable
- [ ] Quality standards are measurable
- [ ] Context requirements are complete
- [ ] Research questions are specific and actionable

---

## Template Categories & Examples

### Account-Research Templates
Focus on understanding customers, their business context, and engagement opportunities.
*Examples: Stakeholder mapping, industry analysis, competitive landscape*

### Technical-Assessment Templates  
Analyze technical capabilities, architectures, and implementation readiness.
*Examples: Data maturity assessment, integration analysis, performance evaluation*

### Strategic-Planning Templates
Support strategic decision-making and planning processes.
*Examples: ROI analysis, roadmap development, risk assessment*

### Competitive-Analysis Templates
Research competitive positioning and market dynamics.
*Examples: Competitor profiling, feature comparison, market positioning*

---

## Best Practices

### 1. Tool Selection
- **Brave Search**: Use for comprehensive web research and recent information
- **Playwright**: Use for automated data collection from specific websites
- **Memory**: Use for storing and retrieving insights across sessions
- **Sequential Thinking**: Use for complex analysis requiring structured problem-solving

### 2. Context Definition
- Be specific about what information the AI needs
- Include relevant timeframes and scope limitations
- Provide clear business context and objectives
- Define quality standards and success criteria

### 3. Analysis Structure
- Break complex research into logical phases
- Ensure each phase builds on the previous one
- Include specific deliverables for each phase
- Provide clear transition points between phases

### 4. Output Requirements
- Specify exact format and structure needed
- Include examples of desired output when helpful
- Define minimum quality standards
- Specify how insights should be prioritized

---

## Contributing Guidelines

When creating new templates using this reference:

1. **Follow the Standard Structure**
   - Use the same header organization
   - Maintain consistent placeholder format `[PLACEHOLDER]`
   - Include all required sections

2. **Test Before Submitting**
   - Validate that all placeholders are clearly defined
   - Ensure tool selection matches research needs
   - Verify output format produces actionable results

3. **Documentation Requirements**
   - Complete the usage instructions section
   - Provide specific examples for key placeholders
   - Include quality checklist items

4. **Naming Convention**
   - Use descriptive, specific names
   - Include template number if part of a series
   - Follow format: `[NUMBER]_[DESCRIPTIVE_NAME].md`

---

## Support & Questions

For questions about using this reference template or contributing new templates:
1. Review existing templates in the Account-Research folder for examples
2. Ensure your template follows the standard structure
3. Test with real use cases before submitting
4. Include comprehensive documentation and examples

---

*This reference template provides a standardized structure for creating new AI prompt templates. Customize all placeholders and sections to match your specific research objectives and deliverable requirements.*
