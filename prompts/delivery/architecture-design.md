## Architecture Diagram Creation
Prompts to help solution architects generate Azure architecture diagrams based on use cases and requirements.

Special thanks to Tommy Falgout for contributing this prompt and instructions.

### Recommended Model:
GitHub Copilot Claude Sonnet 4 or GPT-5

### Instructions:
In Visual Studio Code, use the prompt below in GitHub Copilot agent mode

(Optional for Azure shapes):
- Add the "Draw.io Integration" extension by Henning Dieterichs
- Create a sample.drawio file
- Click on "More shapes" at the bottom left
- Select "Azure" under "Networking" and hit "Apply"

### User Prompt Template:
```text

Create a draw.io diagram to show a Cloud Architecture diagram of what the solution would look like in Azure with extension ".drawio". Use the icons from the Azure library shapes. If a shape isn't available, fallback to a rounded rectangle with the service name. Always use "and" instead of "&" within value descriptions so that the XML content can be rendered.

## Use Case
{{Briefly describe the use case or scenario for which you need an architecture diagram.}}

## Additional Context
{{Any specific constraints, requirements, or technologies that should be considered in the architecture design.}}
```

### Example Usage:
```text
Create a draw.io diagram to show a Cloud Architecture diagram of what the solution would look like in Azure with extension ".drawio". Use the icons from the Azure library shapes. If a shape isn't available, fallback to a rounded rectangle with the service name. Always use "and" instead of "&" within value descriptions so that the XML content can be rendered.

## Use Case
Create an architecture diagram for a customer service application that uses AI to triage email support requests based on severity.

## Additional Context
The solution should integrate with the customer's existing ticketing systems and leverage natural language processing to analyze request content. It should use Azure OpenAI, Semantic Kernel, and also be scalable to handle high volumes of requests during peak times. It should be highly secure.
```


