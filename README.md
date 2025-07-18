# AI Prompt Book for Architects & Engineers

This prompt library provides Microsoft architects and engineers with curated, high-impact prompts to accelerate the customer solution journey. The prompts are designed to support **Discovery** and **Rapid Prototyping** phases, enabling faster ideation, clearer requirements, and more efficient build cycles.

## 📁 Prompt Categories

### 🔍 Discovery
Use these prompts during early-stage engagements to explore opportunities, assess feasibility, and gather context.

- [**Use Case Ideation**](1-discovery/1-use-case-ideation.md): Identify customer business drivers or pain points and map them to use case opportunities.
- [**Use Case Evaluation**](1-discovery/2-use-case-evaluation.md): Evaluate proposed use cases for business value, feasibility, and alignment with customer goals.
- [**Research**](1-discovery/3-research.md): Perform background research to inform technical approaches and considerations.
- [**Resources**](1-discovery/4-resources.md): Retrieve relevant documentation, Microsoft guidance, and supporting materials to share with customers.

### ⚡ Rapid Prototyping 
Use these prompts to quickly move from ideation to working prototypes and proof-of-concepts.

- [**Requirements**](2-rapid-prototyping/1-requirements.md): Translate high-level goals into actionable functional and technical requirements.
- [**Data Generation**](2-rapid-prototyping/2-data-generation.md): Create synthetic data or test datasets to support initial build phases while customers locate or curate their data.
- [**Code Scaffolding**](2-rapid-prototyping/3a-code-scaffolding.md) (Option A): Accelerate development with code scaffolding for use with GitHub Copilot for implementation.
- [**Code Generation**](2-rapid-prototyping/3b-code-generation.md) (Option B): Generate code prototypes based on requirements and data, ready for testing, debugging, and iteration.
- [**Insights**](2-rapid-prototyping/4-insights-presentation.md): Extract learnings, summarize results, and define next steps from sprints into a customer presentation deck.

## 🧭 How to Use
1. **Browse Categories**: Navigate through [Discovery](1-discovery/) or [Rapid Prototyping](2-rapid-prototyping/) based on your engagement stage.
2. **Copy & Customize Prompts**: Tailor prompts to your customer context. Use these as a jumpstart, combining with your own engineering and architecture expertise.
3. **Leverage AI Foundry**: 
    - Navigate to the **Chat Playground** in Azure AI Foundry to get started: [Quickstart: Use the Chat Playground in Azure AI Foundry](https://learn.microsoft.com/en-us/azure/ai-foundry/quickstarts/get-started-playground). 
    - Use the **System Messages** found in this repository for your model system message, and select **Apply changes**. 
    - Customize the **User Prompt Templates** provided to enter into the chat session. Reference the **Example Usage** prompts as samples on what details to provide.

### Disclaimer
This library is intended for internal Microsoft use and experimentation. Prompts require context and responsible use in line with Microsoft's [Responsible AI Standard](https://www.microsoft.com/ai/responsible-ai). Outputs require human validation, testing, and code debugging.
`