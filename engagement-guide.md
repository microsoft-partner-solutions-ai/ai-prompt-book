# AI Engagement Guide for the Solution Journey Framework
> **Purpose:** Provide a practical, plug-and-play guide for Partner Solution Architects (PSAs) to accelerate every phase of the Partner Solution Journey using GenAI. This guide highlights where to use your this repository's curated prompts and where to creatively apply GenAI to reduce time and effort across the journey.
> **Audience:** Partner Solution Architects (PSAs) and other architects engaging with partners and customers.


## How to Use This Guide

- **Accelerate with GenAI:** Use this guide to identify where AI tools can reduce manual effort and speed up delivery.
- **Plug and play:** Use the repository's curated prompts when available, and supplement with additional recommended GenAI tooling elsewhere.
- **Flexible by design:** Not all steps apply in every engagement — tailor as needed while staying grounded in the Solution Journey Framework.


## Accelerating Stages of the Solution Journey
### Plan

**Objective:** Understand the partner or customer's current state, strategic goals, and potential areas for Cloud innovation.

✅ Actions:
- Research the partner or customer’s business, architecture, and industry context.
- Identify pain points, strategic priorities, and key stakeholders.
- Begin forming hypotheses around potential solution areas.

🧠 How to Use GenAI:
- Summarize lengthy documents (e.g., architecture overviews, emails, transcripts of previous calls that have been shared with you).
- Draft discovery questions tailored to the partner or customer's domain.
- Analyze public web content (e.g., partner/customer websites) to surface potential opportunity areas.

🔹 Tools to Use:
- Microsoft 365 Copilot **Researcher** agent

---

### Envision

**Objective:** Identify, shape, and prioritize AI use cases aligned to partner & customer goals.

✅ Actions:
- Facilitate use case ideation via workshops (Innovation Workshop, Discovery Cards Workshop, or quick envisioning sessions).
- Collaboratively evaluate value, feasibility, and alignment with business outcomes.

🧠 How to Use GenAI:
- Expand rough ideas into clearly defined use cases.
- Score use cases by complexity, data requirements, or time-to-impact.

🔹 Prompts to Use:
- [Use Case Ideation Prompts](discovery/1-use-case-ideation.md)
- [Use Case Evaluation Prompts](discovery/2-use-case-evaluation.md)
- If running a Discovery Cards Workshop for AI: [Discovery Cards Workshop Prompts](discovery/0-discovery-cards-workshop.md)

---

### Architecture Design Session (ADS)

**Objective:** Collaboratively design a solution architecture with the partner or customer that aligns with the selected use case(s).

✅ Actions:
- Identify key components, services, and data flows.
- Recommend the appropriate Microsoft technologies and outline integration points.
- Document trade-offs, constraints, and assumptions.

🧠 How to Use GenAI:
- Generate draft architecture diagrams or summaries based on the chosen use case.
- Recommend appropriate Azure services and technologies based on requirements.
- Compare architecture options and trade-offs.

🔹 Prompts to Use:
- [Requirements Prompts](rapid-prototyping/1-requirements.md)
- [Architecture Design Prompts](delivery/architecture-design.md)
- [Research Prompts](discovery/3-research.md)

---

### Proof of Concept (POC)

**Objective:** Build and test a lightweight prototype to validate technical feasibility and demonstrate early value.

✅ Actions:
- Define success criteria and key functionality.
- Build and test a focused subset of the full solution.
- Collect feedback and iterate quickly.

🧠 How to Use GenAI:
- Generate code or code scaffolding for early POC components.
- Create synthetic data or test datasets to support initial build phases.
- Document findings, insights, and open questions automatically.

🔹 Prompts to Use:
- [Data Generation Prompts](rapid-prototyping/2-data-generation.md)
- [Code Scaffolding Prompts](rapid-prototyping/3a-code-scaffolding.md)
- [Code Generation Prompts](rapid-prototyping/3b-code-generation.md)
- [Insights Prompts](rapid-prototyping/4-insights-presentation.md)

---

### Build

**Objective:** Evolve the POC into a fuller solution with more complete features, integrations, and production-readiness.

✅ Actions:
- Support partner or customer teams in building out the solution.
- Provide guidance on best practices, patterns, and anti-patterns.
- Help teams navigate integration challenges, edge cases, and scale considerations.

🧠 How to Use GenAI:
- Leverage the same components under POC to accelerate development, but shift focus to production-readiness.
- Generate guidance on implementing best practices for security, observability, and other non-functional requirements.
- Leverage AI tools to respond to specific coding challenges or questions during development.

🔹 Tools to Use:
- [Resources Prompts](discovery/4-resources.md)
- Microsoft 365 Copilot **Researcher** agent
- GitHub Copilot to support debugging sessions with partners or customers

---

### Validate

**Objective:** Assess the solution's architecture, implementation quality, and adherence to the Well-Architected Framework. Assess SI practices for capability and readiness to deliver customer solutions.

✅ Actions:
- Evaluate whether the solution is well-architected, secure, and production-ready.
- Review partner (SI or SDC) delivery practices, implementation quality, and adherence to best practices.
- Identify risks, gaps, or areas that may require redesign before go-to-market or deployment.
- Provide recommendations to improve scalability, reliability, or maintainability.

🧠 How to Use GenAI:
- Use AI to help summarize complex architecture docs, identify missing patterns, or flag potential issues.
- Draft validation reports that capture strengths, risks, and suggested remediations.
- Assist with generating example test plans or security considerations for further validation.

🔹 Tools to Use:
- Microsoft 365 Copilot to support dynamically.

---

### Publish

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

🔹 Tools to Use:
- Microsoft 365 Copilot to support dynamically.

---

### Co-Sell

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

🔹 Prompts to Use:
- [Webinar Planning Prompts](delivery/webinar-planning.md)