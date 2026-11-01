# aws-cloud-ai-learning
# AWS Cendekiawan Malaysia — Generative AI & Cloud Architecture Repository

This repository documents the technical competencies, architectural understandings, and hands-on practices acquired during the **AWS Cendekiawan Malaysia AI Learning Path** program (administered by Elitery and AWS). 

---

## 📑 Program Overview & Key Technical Takeaways

### 1. Cloud Computing & AWS Infrastructure
* **Deployment & Service Models:** Comparative understanding of On-Premises vs. IaaS vs. PaaS vs. SaaS, as well as Cloud Native and Hybrid architectures.
* **AWS Global Infrastructure:** Architectural leveraging of AWS Regions, Availability Zones (AZs), and Edge Locations for low-latency, highly available system designs.
* **Shared Responsibility Model:** Clear operational distinction between customer responsibilities (*security IN the cloud*) and AWS responsibilities (*security OF the cloud*).
* **Cost Optimization & Value:** Financial transitioning from CapEx to OpEx, leveraging elasticity, pay-as-you-go models, and automated resource scaling.

### 2. Generative AI & Amazon Bedrock
* **Foundational Architecture:** Deep dive into Foundation Models (FMs) and Large Language Models (LLMs) via unified APIs using Amazon Bedrock.
* **Model Families & Modalities:** Evaluation of the Amazon Nova family (Nova Micro, Lite, Pro, Premier, Canvas, Reel, Sonic) and Amazon Titan alongside 3rd-party models (Anthropic Claude, Meta Llama, Cohere, Stability AI).
* **Enterprise Customization Frameworks:**
  * **Retrieval-Augmented Generation (RAG):** Enhancing model responses by connecting private knowledge bases (via Amazon S3 and vector stores) without base-model retraining.
  * **Fine-tuning & Parameter Tuning:** Adjusting model styles and domain knowledge; configuring inference parameters including `Temperature`, `Top-p`, and maximum token bounds.
* **Governance & Responsible AI:** Implementing Guardrails, prompt validation, content moderation, IAM least-privilege policies, and CloudWatch monitoring to mitigate hallucinations and security risks.

### 3. Rapid AI Application Prototyping (PartyRock)
* **No-Code AI Engineering:** Rapid scaffolding of generative applications using Amazon Bedrock foundation models.
* **Widget Composition & Orchestration:** Wiring user inputs (Text, Selectors, Sliders) with AI output widgets (Generated Text, Generated Images, Conversational Bots).
* **Prompt Patterns:** Engineering structured prompts with defined inputs, constraints, output schemas, and dynamic context parameters.

### 4. Agentic AI Development (Kiro IDE / CLI)
* **Spec-Driven Development:** Transitioning from ad-hoc prompt-coding to structured, spec-first engineering (Requirements in EARS notation -> Design Docs -> Actionable Task Sequences).
* **Agentic Workflows:** Utilizing autonomous subagents, property-based testing (PBT), automated triggers (Hooks), and external tool integrations via Model Context Protocol (MCP).

---

## 🛠 Tech Stack & Tools Mastered
* **Cloud Platform:** Amazon Web Services (AWS)
* **AI & LLM Services:** Amazon Bedrock, PartyRock, RAG Frameworks, Amazon S3, AWS Lambda, Amazon Lex
* **Developer Tools:** Kiro IDE (Spec-Driven AI Tooling), Git/GitHub, Linux CLI

---

## 📜 Professional Certification Details
* **Credential:** AWS Cendekiawan Malaysia AI Learning Path
* **Issuing Entity:** Elitery & Amazon Web Services
* **Credential ID:** `2F1F0E6C0E`
* **Recipient:** Muhammad Arif Hakimi Bin Muhammad Hafizan
