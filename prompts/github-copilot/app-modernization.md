## App Modernization
Thanks to Jay Schmelzer's team in DevDiv, we have leveraged their prompt for working on App Modernization workloads with GitHub Copilot.  This documentation and prompts have been authored by Manfred Riem.

### Recommended Model:
Latest Claude Sonnet model (at this time, Claude Sonnet 4)

### Overview:
This document provides a generic version of a prompt request that would generate the necessary validation prompt files for scoring any migration. When used with an AI assistant, it will create a set of three prompt files that work together to validate and score a migration from one technology to another. 

### How to Use:
Copy the prompt below 

Replace [REFERENCE_RESOURCES] with links to relevant documentation, knowledge files, or examples that contain migration-specific knowledge 

At the bottom of the prompt, replace X and Y with your specific source and target technologies 

Send the prompt to GitHub Copilot in ask mode.

The AI will generate three prompt files for you to use in your migration validation 

IMPORTANT: Including specific knowledge references is critical for generating accurate validation prompts. These references will be actively used during the generation of all three prompt files, ensuring they incorporate the right technical requirements, migration patterns, and validation criteria specific to your technology stack. 

### Prompt - Generic Migration Validation Request Prompt
```text
I need to validate and score a migration from X to Y. Please create a set of prompt files that can be used to evaluate if this migration has been completed successfully. 
 
For reference, please use these knowledge resources: 
[REFERENCE_RESOURCES] 
 
I need three files: 
 
1. A template file (VALIDATION_PROMPT_TEMPLATE.md) that provides the structure for validation 
2. A scoring file (VALIDATION_PROMPT_SCORE.md) that defines how to calculate the migration success percentage 
3. A combined validation prompt (VALIDATION_PROMPT.md) that applies the template and scoring to the specific X to Y migration 
 
For the template file, focus on these key validation areas: 
- Component migration completeness 
- Removal of legacy technology elements 
- Proper implementation of new technology patterns 
- Configuration updates 
- Dependency management 
- Build system changes 
- Documentation updates 
- Testing modifications 
 
For the scoring file, include: 
- Clear point allocations for each validation category 
- Criteria for partial vs. complete implementation 
- Penalty system for remaining legacy components 
- Bonus points for exemplary implementation of new patterns 
- Formula for calculating the final percentage score 
 
For the combined validation prompt, ensure it: 
- Is specific to the X to Y migration 
- Contains clear evaluation instructions 
- References specific files, patterns, and components to check 
- Defines what evidence constitutes successful migration 
- Requests both a detailed breakdown and a final percentage score 
 
When creating these files, incorporate industry best practices for X to Y migrations, including common pitfalls, required refactoring patterns, and configuration requirements. 
 
X is [FILL IN SOURCE TECHNOLOGY] 
Y is [FILL IN TARGET TECHNOLOGY] 
```

### Understanding the Generated Files:
This file provides a structured template that can be applied to any migration validation. It includes: 

Framework for assessment: The overall structure for evaluating migrations 

Key validation categories: Common areas to check regardless of specific technologies 

Evidence collection guidance: How to gather proof of successful migration 

Report structure: How to present the validation findings 

#### 1. VALIDATION_PROMPT_SCORE.md 
This file defines the specific scoring methodology, including: 

Point allocation: How many points each validation category is worth 

Evaluation criteria: What constitutes full, partial, or failed implementation 

Scoring formula: How to calculate the final percentage 

Weighting system: How to balance different aspects of the migration 

#### 2. VALIDATION_PROMPT.md 
This file combines the template and scoring approach into a specific validation prompt for the particular migration being assessed. It includes: 

Technology-specific checks: Exactly what to look for in this migration 

File patterns: What files should be examined 

Success criteria: What constitutes a successful migration in this context 

Required changes: Specific modifications that must be present 

Reporting requirements: What information to include in the validation report 

### Example Usage:
Here’s an example of how you might customize the prompt for a Spring Boot 2.x to 3.x migration: 

```text
I need to validate and score a migration from X to Y. Please create a set of prompt files that can be used to evaluate if this migration has been completed successfully. 
 
For reference, please use these knowledge resources: 
- https://github.com/spring-projects/spring-boot/wiki/Spring-Boot-3.0-Migration-Guide 
 
I need three files: 
 
1. A template file (VALIDATION_PROMPT_TEMPLATE.md) that provides the structure for validation 
2. A scoring file (VALIDATION_PROMPT_SCORE.md) that defines how to calculate the migration success percentage 
3. A combined validation prompt (VALIDATION_PROMPT.md) that applies the template and scoring to the specific X to Y migration 
 
For the template file, focus on these key validation areas: 
- Component migration completeness 
- Removal of legacy technology elements 
- Proper implementation of new technology patterns 
- Configuration updates 
- Dependency management 
- Build system changes 
- Documentation updates 
- Testing modifications 
 
For the scoring file, include: 
- Clear point allocations for each validation category 
- Criteria for partial vs. complete implementation 
- Penalty system for remaining legacy components 
- Bonus points for exemplary implementation of new patterns 
- Formula for calculating the final percentage score 
 
For the combined validation prompt, ensure it: 
- Is specific to the X to Y migration 
- Contains clear evaluation instructions 
- References specific files, patterns, and components to check 
- Defines what evidence constitutes successful migration 
- Requests both a detailed breakdown and a final percentage score 
 
When creating these files, incorporate industry best practices for X to Y migrations, including common pitfalls, required refactoring patterns, and configuration requirements. 
 
X is Spring Boot 2.7 
Y is Spring Boot 3.2 
```

### Best Practices for Using Generated Prompts:
Provide comprehensive knowledge references: Include links to official documentation, internal guidelines, and example migrations 

Be specific about technologies: Include versions and specific variants of source and target technologies 

Include domain context: Mention if the migration is for a specific type of application (e.g., e-commerce, banking) 

Reference existing documentation: Point to official migration guides when available 

Customize validation areas: Add specific areas important to your particular migration 

Update scoring criteria: Adjust point allocations based on your organization’s priorities 

Iterate on validation: Use the results to improve subsequent migrations 

Note on Knowledge References: The references you provide will directly influence the quality and specificity of the generated prompts. Prioritize including: - Official migration guides from technology vendors - Internal documents that capture your organization’s specific requirements - Examples of previously completed migrations that demonstrate success patterns - Documentation of known pitfalls and their solutions 

### Conclusion:
By using this generic request prompt, you can quickly generate a set of specialized prompt files tailored to your specific migration scenario. These files will provide a structured approach to validating and scoring your migration, helping you ensure completeness and identify any remaining work needed. 