# 🤖 Autonomous Multi-Agent Product Discovery Loop

This project is an advanced, production-ready multi-agent orchestration pipeline built in n8n. It transforms raw, non-deterministic product definitions into structured market assessments, persona-validated critiques, comprehensive Product Requirement Documents (PRDs), and Jira backlog manifests.

## 🎯 The Problem This Solves

Turning a raw business concept into a fully scoped technical brief usually takes product management and engineering teams days of back-and-forth alignment:
* **Market gaps** are frequently evaluated using outdated data frameworks.
* **Persona analysis** relies on static user profiles rather than dynamic, high-fidelity consumer simulations.
* **PRD drafting** becomes bottlenecked by manual copy-pasting, formatting, and structural misalignment.

This automation loops together standalone LLM reasoning steps, custom JSON schemas, and structured output parsers to automate the entire discovery phase.

## ⚙️ How the Orchestration Loop Works

The pipeline executes through a sequence of specialized node dependencies:

1. **Input Command Center:** Receives raw product concepts from a frontend user interface via an incoming Webhook Trigger.
2. **Orchestrator (Input Optimizer):** Refines and standardizes the product vision using an integrated Structured Output Parser.
3. **Agent 1 (Market Researcher):** Conducts competitive landscape analyses, uncovers structural integration gaps, and designs defensive moats.
4. **Orchestrator (Market Evaluator):** Reviews the findings of Agent 1 and extracts actionable market vulnerabilities into an explicit JSON array.
5. **Agent 2 (Persona Group):** Spawns virtual customer profiles representing target demographics to run simulated feedback focus groups.
6. **Orchestrator (Persona Evaluator):** Translates focus group critiques into strict qualitative parameters.
7. **Agent 3 (PRD Synthesizer):** Generates an unmitigated, markdown-formatted Product Requirements Document mapped to exact structural enterprise guidelines.
8. **Edit Fields (Flattening Layer):** Extracts the nested metadata properties from the underlying JSON parser architecture to flatten the object output.
9. **Webpage Delivery Layer:** Hands the polished, tabbed data payload back to the client interface cleanly.

## 📊 What the Pipeline Looks Like


<img width="737" height="191" alt="image" src="https://github.com/user-attachments/assets/7a56da2c-fff6-41d4-b240-1ad979dd7b7f" />

## 🛠️ How to Import and Setup This Workspace

1. **Copy the Code:** Download the `autonomous_product_discovery_loop.json` workflow file located in this repository.
2. **Import to n8n:** Go to your n8n cloud dashboard, create a brand-new blank workflow canvas, click the top-right menu, and select **Import from File**.
3. **Set Up LLM Credentials:** Ensure your OpenAI Chat Model nodes are connected to your active API credentials.
4. **Deploy Output Parsers:** Verify that the attached Structured Output Parsers match your target JSON schemas.
5. **Execute:** Activate the loop and trigger your command center to begin generation.
