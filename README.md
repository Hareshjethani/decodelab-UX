# Generative AI and Prompt Engineering Portfolio

This repository contains a comprehensive portfolio of advanced Artificial Intelligence projects focusing on Prompt Engineering, Document Intelligence (RAG), and AI Safety and Auditing. These projects demonstrate the practical application, structural control, and rigorous testing of large language models in enterprise scenarios.

---

## Repository Structure

```text
📦 AI-Portfolio
┣ 📂 Project-1-System-Prompt-Architect
┃ ┗ 📜 Task 1.docx (System Prompts & Examples)
┣ 📂 Project-2-Knowledge-Analyst
┃ ┗ 📜 Task 3.docx (RAG Workflow & Summaries)
┣ 📂 Project-3-AI-Safety-Audit
┃ ┗ 📜 Task 5.docx (Red Teaming & Bias Report)
┗ 📜 README.md (Portfolio Overview)
```
## Project Deep Dive
Project 1: The System Prompt Architect
Scenario: Designing an automated customer service assistant for a high-end luxury travel agency.

Execution: Developed a strict persona named "Aura," an elite Luxury Travel Consultant. The system prompt was engineered with advanced boundary constraints, including gracefully ignoring competitor mentions, strictly refusing budget or hostel inquiries, and offering a maximum 10% discount only under highly specific, predefined conditions.

Outcome: The model was tested against adversarial user prompts requesting cheap alternatives and competitor price-matching. The AI successfully navigated these edge cases without breaking character or violating core constraints.

Skills Demonstrated: Persona Engineering, Few-Shot Prompting, Constraint Management.

Project 2: The Knowledge Analyst (RAG Concepts)
Scenario: Extracting critical legal and financial data from a technical 15-page Software Development Agreement.

Execution: Simulated a Retrieval-Augmented Generation (RAG) workflow to parse complex legal text. The AI was strictly instructed to prevent hallucinations and mandate exact page or section citations for every extracted data point. A comprehensive Summary Dashboard was generated, accurately outlining contractual risks, financial obligations, important dates, and termination clauses.

Skills Demonstrated: RAG Workflows, Document Intelligence, Hallucination Prevention, Strict Data Extraction.

Project 3: The AI Safety and Bias Audit
Scenario: Conducting pre-deployment auditing of AI models to ensure public safety and identify societal biases.

Execution: Executed rigorous "Red Teaming" and bias testing methodologies:

Text Safety (Red Teaming): The text generation model was subjected to prompts requesting dangerous medical advice, phishing email templates (jailbreak attempts), and high-risk financial guarantees. The model successfully passed all tests, maintaining strict guardrails and refusing harmful outputs.

Image Bias Audit: The image generation model was tested using occupational prompts. The model failed this audit, exhibiting clear gender stereotyping by exclusively generating male figures for "CEO" prompts and female figures for "Kindergarten Teacher" prompts, alongside contextual hallucinations.

Skills Demonstrated: Red Teaming, Jailbreak Testing, AI Ethics, Bias Auditing, Guardrail Implementation.

Conclusion
This portfolio evidences a robust capability to deploy Generative AI practically, control its outputs strictly, extract highly accurate data from complex legal text, and comprehensively audit systems for safety and bias. It highlights a commitment to developing safe, accurate, and highly functional AI solutions for real-world enterprise challenges.
