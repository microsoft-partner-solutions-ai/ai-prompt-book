# GenAI-Powered "Roadmap to Revenue" Solution Journey Guide 
_A modular playbook to accelerate every stage of the "Roadmap to Revenue" solution journey._

> **Purpose:** Provide a practical, plug-and-play guide for Partner Solution Architects (PSAs) to accelerate every stage of the "Roadmap to Revenue" solution journey using GenAI. This guide highlights where to use your this repository's curated prompts and where to creatively apply GenAI to reduce time and effort across the journey as a Frontier PSA.

> **Audience:** Partner Solution Architects (PSAs) and other architects engaging with partners and customers.

> Note: This guide expands upon the AI Prompt Book to enable Customer-Zero adoption of AI throughout the "Roadmap to Revenue" solution journey. Please refer to the [README](README.md) for AI Prompt Book documentation.

## How to Use This Guide

- **Accelerate with GenAI:** Use this guide to identify where AI tools can support you as a Frontier PSA in reducing manual effort and speeding up delivery.
- **Plug and play:** Use the repository's curated prompts when available, and supplement with additional recommended GenAI tooling elsewhere.
- **Flexible by design:** Not all steps apply in every engagement — tailor as needed while staying grounded in the Solution Journey Framework.


## Accelerating Stages of the "Roadmap to Revenue" Solution Journey
### 1. Plan

**Objective:** Understand the partner or customer's current state, strategic goals, and potential areas for Cloud innovation.

✅ Actions:
- Research the partner or customer’s business, architecture, and industry context.
- Identify pain points, strategic priorities, and key stakeholders.
- Begin forming hypotheses around potential solution areas.

🧠 How to Use GenAI:
- Summarize lengthy documents (e.g., architecture overviews, emails, transcripts of previous calls that have been shared with you).
- Draft discovery questions tailored to the partner or customer's domain.
- Analyze public web content (e.g., partner/customer websites) to surface potential opportunity areas.
- Leverage GenAI to do business research on your partner to help inform technical planning.

🛠️ Tools to Use:
- Copilot **Researcher** agent
- Copilot **Analyst** agent
- Microsoft 365 Copilot

📝 Prompts to Use:
- _Researcher_: "Create a technical discovery prep brief for an upcoming meeting with [Partner Name], including architecture insights and industry signals.
- _Analyst_: "From this partner skills assessment spreadsheet, identify technical gaps and suggest a learning roadmap for [Partner Name]. [Upload Assessment spreadsheet]"
- _Copilot_: "Based on these notes about the partner, please draft a skilling guide for the partner's team with recommended learning paths and resources. [Upload PTS notes or other]"
- 💡 Example prompts to uncover business context to give ideas for business drivers, plans, timelines, and potential innovation opportunities
  - _Researcher_: Summarize [Partner Name's] strategic differentiation and industry expertise based on recent blog articles, LinkedIn posts, Azure Marketplace listings, and additional public web content you find.
  - _Researcher_: What are the current industry trends for [Partner Name's] industry?
  - _Researcher_: Summarize [Partner Name's] recent SEC filings and financial statements
  - _Copilot_: Come up with sample prompts for me to help uncover more business context about [Partner Name] so that I can get a good idea of their business drivers, plans, timelines, or potential innovation opportunities.
  
---

### 2. Envision

**Objective:** Identify, shape, and prioritize AI use cases aligned to partner & customer goals.

✅ Actions:
- Facilitate use case ideation via workshops (Innovation Workshop, Discovery Cards Workshop, or quick envisioning sessions).
- Collaboratively evaluate value, feasibility, and alignment with business outcomes.

🧠 How to Use GenAI:
- Expand rough ideas into clearly defined use cases.
- Score use cases by complexity, data requirements, or time-to-impact.

🛠️ Tools to Use:
- Microsoft 365 Copilot
- AI Foundry Chat Playground
- Copilot **Researcher** agent
- Copilot **Analyst** agent

📝 Prompts to Use:
- [Use Case Ideation Prompts](discovery/1-use-case-ideation.md) - Identify customer business drivers or pain points and map them to use case opportunities.
- [Use Case Evaluation Prompts](discovery/2-use-case-evaluation.md) - Evaluate proposed use cases for business value, feasibility, and alignment with customer goals.
- [Discovery Cards Workshop Prompts](discovery/0-discovery-cards-workshop.md) (for use in the AI Discovery Cards Workshop to ideate AI use cases)

🧰 Workshop Options:
- **Innovation Workshop:** A structured workshop to identify and prioritize Cloud innovation opportunities.
- **Discovery Cards Workshop:** A workshop using AI Discovery Cards to explore and prioritize use cases.
- **Responsible AI Maturity Model Workshop:** An interactive deep dive into the Responsible AI Maturity Model to assess and determine a roadmap for responsible AI practices.

---

### 3. Architecture Design Session (ADS)

**Objective:** Collaboratively design a solution architecture with the partner or customer that aligns with the selected use case(s).

✅ Actions:
- Identify key components, services, and data flows.
- Recommend the appropriate Microsoft technologies and outline integration points.
- Document trade-offs, constraints, and assumptions.

🧠 How to Use GenAI:
- Generate draft architecture diagrams or summaries based on the chosen use case.
- Recommend appropriate Azure services and technologies based on requirements.
- Compare architecture options and trade-offs.

🛠️ Tools to Use:
- Microsoft 365 Copilot
- AI Foundry Chat Playground

📝 Prompts to Use:
- [Requirements Prompts](rapid-prototyping/1-requirements.md) - Translate high-level goals into actionable functional and technical requirements.
- [Architecture Design Prompts](delivery/architecture-design.md) - Generate Azure architecture diagrams based on use cases and constraints.
- [Research Prompts](discovery/3-research.md) - Perform background research to inform technical approaches and considerations.

---

### 4. Proof of Concept (POC)

**Objective:** Build and test a rapid prototype to validate technical feasibility and demonstrate early value. This phase can be prepared in advance from the Microsoft side to show early value to the partner. 

✅ Actions:
- Define success criteria and key functionality.
- Build and test a focused subset of the full solution.
- Collect feedback and iterate quickly.

🧠 How to Use GenAI:
- Generate code or code scaffolding for early POC components.
- Create synthetic data or test datasets to support initial build phases.
- Document findings, insights, and open questions automatically.
- "Show your work": Describe to partner upon POC delivery how AI was leveraged throughout so that they can replicate themselves and with customers.

🛠️ Tools to Use:
- Microsoft 365 Copilot
- AI Foundry Chat Playground
- GitHub Copilot

📝 Prompts to Use:
- [Requirements Prompts](rapid-prototyping/1-requirements.md) - Define technical requirements for the POC based on the use case.
- [Data Generation Prompts](rapid-prototyping/2-data-generation.md) - Generate synthetic data or test datasets to support initial build phases while customers locate or curate their data.
- Coding Prompt Options:
  - [Code Scaffolding Prompts](rapid-prototyping/3a-code-scaffolding.md) - Generate code scaffolding for use with GitHub Copilot for implementation. This is recommended for complex POCs where you want to leverage GitHub Copilot to accelerate development.
  - [Code Generation Prompts](rapid-prototyping/3b-code-generation.md) - Generate code prototypes based on requirements and data to bring into VS Code for testing, debugging, and iteration. This is recommended for simpler POCs or when you want to quickly generate code without scaffolding.
  - Options for using these prompts:
    - _AI Foundry Chat Playground_: Use the system message and user prompt template to generate code scaffolds and prototypes based on requirements and data. Bring generated code into VS Code for testing, debugging, and additional iteration with GitHub Copilot.
    - _GitHub Copilot_: Use only the user prompt template within Agent mode. For best results, connect the MS Learn Docs MCP Server to VS Code folowing this information: [Connect to the Microsoft Learn Docs MCP Server](https://github.com/microsoftdocs/mcp) to provide GitHub Copilot with MS Learn content.
- [Insights Prompts](rapid-prototyping/4-insights-presentation.md) - Extract learnings, summarize results, and define next steps from sprints into a customer presentation deck.

---

### 5. Build

**Objective:** Evolve the POC into a fuller solution with more complete features, integrations, and production-readiness.

✅ Actions:
- Support partner or customer teams in building out the solution.
- Provide guidance on best practices, patterns, and anti-patterns.
- Help teams navigate integration challenges, edge cases, and scale considerations.

🧠 How to Use GenAI:
- Leverage the same components under POC to accelerate development, but shift focus to production-readiness.
- Generate guidance on implementing best practices for security, observability, and other non-functional requirements.
- Leverage AI tools to respond to specific coding challenges or questions during development.

🛠️ Tools to Use:
- Microsoft 365 Copilot
- AI Foundry Chat Playground
- GitHub Copilot to support debugging sessions with partners or customers

📝 Prompts to Use:
- [Research Prompts](discovery/3-research.md) - Perform background technical research to inform approaches and considerations.
- [Resources Prompts](discovery/4-resources.md) - Retrieve relevant documentation, Microsoft guidance, and supporting materials to share with partners and customers.
- _Copilot_: 💡Leverage **Copilot** to help inform your responses to partner questions over email or summarize Teams chats to give you more clarity.
- _Copilot_: “Draft a solution implementation guide based on our POC notes. Include architecture summary, key components, and delivery considerations. [Upload notes or documents]”

---

### 6. Offering Validation

**Objective:** Assess the solution's architecture, implementation quality, and adherence to the Well-Architected Framework. Assess SI practices for capability and readiness to deliver customer solutions. Log TTA.

✅ Actions:
- Evaluate whether the solution is well-architected and production-ready.
- Identify risks, gaps, or areas that may require redesign before go-to-market or deployment.

🧠 How to Use GenAI:
- Use AI to help summarize complex architecture docs, identify missing patterns, or flag potential issues.
- Draft validation reports that capture strengths, risks, and suggested remediations.

🛠️ Tools to Use:
- Copilot **Analyst** agent
- Copilot **Researcher** agent

📝 Prompts to Use:
- _Analyst_: "Analyze this architecture document for gaps against the Well-Architected Framework and summarize key risks or opportunities. [Upload]"
- _Researcher_: "Create a validation summary for this solution architecture, including strengths, risks, and recommendations. Summarize Well-Architected Framework alignment gaps. [Upload]"


---

### 7. Offering Commercialization

**Objective:** Support partners (SDCs or SIs) in preparing and publishing their solutions or offers to Marketplace.

✅ Actions:
- Guide partners through Marketplace technical requirements and offer types (e.g., transactable SaaS, consulting services).
- Review solution packaging, documentation, and listing metadata for accuracy and completeness.
- Ensure alignment with co-sell and Marketplace readiness criteria.
- Help partners position their offer clearly for target customers.

🧠 How to Use GenAI:
- Draft Marketplace listing content (e.g., solution overview, offer description, customer value statements).
- Summarize architecture documentation into Marketplace-ready technical details.
- Generate starter FAQs, pricing guidance, or onboarding materials based on the solution's capabilities.
- Review existing listings to suggest clarity or messaging improvements.

🛠️ Tools to Use:
- Microsoft 365 Copilot

📝 Prompts to Use:
- _Copilot_: "Create an Azure Marketplace-ready offer description and technical summary for this partner solution. [Provide solution details]"
- _Copilot_: "Rewrite this README into a quick-start guide tailored for Azure Marketplace publication. [Provide README content]”

---

### 8. Offering Activation

**Objective:** Support partners in positioning and selling their solutions to customers through Microsoft co-sell motions.

✅ Actions:
- Assist in developing talk tracks, demos, or webinars tailored to customer scenarios.
- Partner with PTSs, PDMs, and field sellers to activate co-sell opportunities.
- Join partner-led customer meetings to provide technical expertise and credibility.

🧠 How to Use GenAI:
- Generate tailored demo scripts, talk tracks, and webinar outlines based on the solution and target industry.
- Draft technical FAQs, speaker notes, or onboarding briefs to support co-selling.
- Create customer-ready assets (e.g., one-pagers, technical deep dives) to support meetings led by partners or Microsoft sellers.
- Translate complex solution features into compelling customer narratives to reinforce your presence as a technical expert in joint calls.

🛠️ Tools to Use:
- Microsoft 365 Copilot
- AI Foundry Chat Playground

📝 Prompts to Use:
- [Webinar Planning Prompts](delivery/webinar-planning.md) - Create structured, engaging webinar content to support Co-Sell motions.
- _Copilot_: "Draft a technical deep dive presentation for a customer meeting on [Partner Solution]. Focus on key features, benefits, and integration points. [Upload solution details]"