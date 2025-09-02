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
Project Name: {{Company: Project, e.g. FIS: Next Generation Compliance}}

Company Website: {{website, e.g. https://www.fisglobal.com/}}

Executive Summary

{{Contextual summary, e.g.The U.S. market for sell side regulatory compliance software spend is expected to continue growing by 17% YoY from $629M in 2023 to $2.03B through 2027. This is in response to the sustained increase in regulatory oversight levied by U.S. regulators. The number of rule proposals issued by the SEC under Gary Gensler in his first 30 months is 61% and 91% more than his two most recent predecessors respectively. This creates an expanding enforcement market where U.S. regulatory fines are already fourteen times higher than in the APAC and four times that in Europe in 2023.i

Compliance monitoring systems have historically used logic-based rules technology developed in the 60’s and 70’s known as “expert systems” and were specialized during the 80’s and 90’s. These systems represent most solutions in use today and have difficulty keeping up with rapid market changes, growing complexities, and increasing data volumes. The result is an acceptance of inefficiency and noise as the norm which overwhelm compliance reviewers and limit firms’ risk mitigation abilities.

The market is primed for a new generation of compliance tools leveraging advanced machine learning and artificial intelligence-based technology. A “collective” approach would yield the best overall results by providing access to the largest possible data sets required for advanced ML and AI models to be effective, while solving the need for lower ownership and compute costs which can be excessive with AI model-based systems. It also creates a deployment model with the quickest possible time to market.

Data Bridge estimates the 2022 trade surveillance market to be valued at $902M with a CAGR of 14% through 2030, resulting in an estimated trade surveillance market worth $2.9B.ii FIS Compliance Suite has roughly 6% of the current market. If FIS can position itself to capture an additional 5% during this time for an 11% market share, trade surveillance revenues could increase from $60M to over $315M. If 15% market share is captured, FIS revenues reach $435M.

This collective approach will create an entirely new ecosystem positioning FIS for sustained leadership and expansion opportunities with barriers for competitive entry. Participants in this collective will be reluctant to leave because it will best reflect the approach regulators use to plan and execute their own enforcement activities. Using advanced modeling techniques focused on a large cross section of the market provides the best representative view of activity and trends and potential issues whether in their own firm or elsewhere. Identifying risks elsewhere in the market allows firms to look forward rather than waiting for similar issues to appear in their own business activity. In short, financial institutions can for the first-time have the insights to be proactive with compliance risk mitigation instead of reactive, while also leveling the playing field by shifting their surveillance automation to something that mirrors how regulators view the market.}}