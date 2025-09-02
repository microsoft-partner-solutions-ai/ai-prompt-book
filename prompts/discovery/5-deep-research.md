## Research 
Prompt to perform deep holistic technical and business research to prep for a partner engagement.

Special thanks to Bob Jacobs for contributing this prompt.

### Recommended Tool:
Copilot Researcher

### User Prompt Template:
Create a research briefing for a upcoming project that can be consumed by the system architect.

Identify the likely project scope based off the data provided.  It will most likely be related to{{technology, e.g. Agentic AI}}.

Use the following as guidance:
1.  Check the product description from the provided information to understand what the product does and predict what they may want to do with it using AI.  Ideas as welcome.
2.  Look at the company's job postings to get an undertsanding of their tech stack.  If you cannot determine or if there are multiple indications, please provide proposed guidance for the 3 most popular tech stacks.
3.  After you predict how {{technology, e.g. agents}} might be added to their system, please provide a proposed architecture based on the tech stack(s)
4.  Ensure that you proposed architecure takes into account the delivery date.  We do not want to propose a technical solution that is too immature or in alpha.
5.  Detail how security can be implemented in this proposed solutions
6.  Based on the proposed architecture, project any objections that the customer might have to the approach.  Please offer answers to their objections.
7.  To best answer customer objections, propose potential alternative solutions with pros and cons.
8.  Predict how the customer would like to extend the solution.  Please consider:
      - Extending the code in the proposed solution
      - Extending the solution to include low-code or visual extensions for non-developers
      - Extend the observability of the solution
9.  Please provide all resources that you use for your predictions including the dates.  We need to make sure we are basing the proposed solution on the latest information

The solution should be for Microsoft Azure.  When creating the proposed solution, we are only interested in an Azure Solution.  No other cloud provider should be considered.

The information about the project is below:

Project Name: {{Company: Project}}

Company Website: {{website}}

Executive Summary

{{Contextual summary}}