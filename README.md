# AI Prompt Book for Architects

This prompt library provides Microsoft architects with curated, high-impact prompts to accelerate the customer solution journey. The prompts are designed to support **Discovery**, **Rapid Prototyping**, and other **Delivery** phases along the solution journey, enabling faster ideation, clearer requirements, and more efficient build cycles.

## 🧭 How to Use
1. **Browse Categories**: Navigate through the [Prompts](prompts/) directory based on your engagement stage.

> Note: This project was originally designed to support Rapid Prototyping hands-on POCs, but has since expanded to include all phases of the "Roadmap to Revenue" solution journey.  For delivering POCs quickly, focus on [Rapid Prototyping](prompts/rapid-prototyping/) prompts. For the full journey, please explore all categories and refer to the [Engagement Guide](engagement-guide.md) for guidance on how to tools and prompts effectively.

2. **Copy & Customize Prompts**: Tailor prompts to your customer context. Use these as a jumpstart, combining with your own engineering and architecture expertise.

### For **AI Practitioners**:
3. **Leverage AI Foundry**: 
    - Navigate to the **Chat Playground** in Azure AI Foundry to get started: [Quickstart: Use the Chat Playground in Azure AI Foundry](https://learn.microsoft.com/en-us/azure/ai-foundry/quickstarts/get-started-playground). 
    - Use the **System Messages** found in this repository for your model system message, and select **Apply changes**. 
    - Customize the **User Prompt Templates** provided to enter into the chat session. Reference the **Example Usage** prompts as samples on what details to provide.

### For **Anyone**:
3. **Leverage Microsoft 365 Copilot** and other Copilot Agents:
    - Combine the **System Message** with the filled out **User Prompt Template** to create a robust prompt for Microsoft 365 Copilot.

### 💡 Bonus tip!
Many of these prompts have been built into [Architect](https://aka.ms/architectagent), a Copilot agent that you can use today! Use the agent for less manual typing and effort, or use the prompts directly for more configurability.

## 📁 Prompt Categories

### 🔍 Discovery
Use these prompts during early-stage engagements to explore opportunities, assess feasibility, and gather context.

- [**Use Case Ideation**](prompts/discovery/1-use-case-ideation.md): Identify customer business drivers or pain points and map them to use case opportunities.
- [**Use Case Evaluation**](prompts/discovery/2-use-case-evaluation.md): Evaluate proposed use cases for business value, feasibility, and alignment with customer goals.
- [**Research**](prompts/discovery/3-research.md): Perform background research to inform technical approaches and considerations.
- [**Resources**](prompts/discovery/4-resources.md): Retrieve relevant documentation, Microsoft guidance, and supporting materials to share with customers.
- [**Deep Research](prompts/discovery/5-deep-research.md): Conduct holistic business and technical deep research on a partner or customer to prepare for engagement.


### ⚡ Rapid Prototyping 
Use these prompts to quickly move from ideation to working prototypes and proof-of-concepts.

- [**Requirements**](prompts/rapid-prototyping/1-requirements.md): Translate high-level goals into actionable functional and technical requirements.
- [**Data Generation**](prompts/rapid-prototyping/2-data-generation.md): Create synthetic data or test datasets to support initial build phases while customers locate or curate their data.
- [**Code Scaffolding**](prompts/rapid-prototyping/3a-code-scaffolding.md) (Option A): Accelerate development with code scaffolding for use with GitHub Copilot for implementation.
- [**Code Generation**](prompts/rapid-prototyping/3b-code-generation.md) (Option B): Generate code prototypes based on requirements and data, ready for testing, debugging, and iteration.
- [**Insights**](prompts/rapid-prototyping/4-insights-presentation.md): Extract learnings, summarize results, and define next steps from sprints into a customer presentation deck.

### 🚚 Delivery
Use these prompts to support delivering other phases of the solution journey, not captured within Discovery or Rapid Prototyping.
- [**Architecture Design**](prompts/delivery/architecture-design.md): Generate Azure architecture diagrams based on use cases and constraints.
- [**Webinar Planning**](prompts/delivery/webinar-planning.md): Create structured, engaging webinar content to support Co-Sell motions.

### 💻 GitHub Copilot
Use these prompts within GitHub Copilot in the context of a repository to enable faster delivery.
- [**App Modernization**](prompts/github-copilot/app-modernization.md): Generate scoring and validation prompts for App Modernization and Migration workloads.
- [**Awesome Copilot Repository**](https://github.com/github/awesome-copilot/blob/main/README.md): Additional GitHub Copilot prompts for various workloads.

### Disclaimer
This library is intended for internal Microsoft use and experimentation. Prompts require context and responsible use in line with Microsoft's [Responsible AI Standard](https://www.microsoft.com/ai/responsible-ai). Outputs require human validation, testing, and code debugging.
`