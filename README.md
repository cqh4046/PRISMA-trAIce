# PRISMA-trAIce: A Reporting Guideline for AI-Assisted Evidence Synthesis

**PRISMA-trAIce** (Transparent Reporting of Artificial Intelligence in Comprehensive Evidence-synthesis) is a proposed extension to the PRISMA 2020 Statement. It aims to establish uniform and transparent standards for reporting the use of Artificial Intelligence (AI) as a methodological tool in Systematic Literature Reviews (SLRs).

## 🚀 The Problem

Systematic Reviews are the gold standard for evidence synthesis, but they are extremely demanding in terms of time and personnel. AI tools, especially Large Language Models (LLMs), can significantly accelerate this process. However, a standard for transparently reporting the use of these tools to ensure scientific traceability and trustworthiness is currently missing. Existing guidelines like PRISMA-AI focus on AI as a subject of research, not as a tool. **PRISMA-trAIce** closes this critical gap.

## 🌱 A Living Guideline

This project is designed as a "Living Guideline". In a field as dynamic as AI, a static standard quickly becomes obsolete. We therefore actively invite the scientific community to help shape and evolve this guideline.

* **Stable Anchor:** This GitHub repository serves as the "Single Source of Truth". Here you will find the most current version of the checklist and all associated materials.
* **Community Hub:** For discussions, questions, and rapid collaboration, we have set up a Discord server. Join our community on Discord!

## ✍️ How to Cite

If you use or refer to PRISMA-trAIce in your research, please cite both the original publication and this GitHub repository to specify the version used.

**Original Paper:**
Holst, D., Koch, J., Moenck, K., Gomse, M., & Schüppstuhl, T. (YEAR). PRISMA-trAIce: A Proposed Checklist for Transparent Reporting of Artificial Intelligence in Comprehensive Evidence-synthesis. [Journal Name], [Volume], [Pages]. [DOI-Link] *(Please update upon publication)*

**GitHub Repository (for a specific version):**
Holst, D., Koch, J., et al. (YEAR). PRISMA-trAIce: A Living Reporting Guideline (Version X.X.X). GitHub. Retrieved from [https://github.com/cqh4046/PRISMA-trAIce](https://github.com/cqh4046/PRISMA-trAIce/blob/main/PRISMA-trAIce_flow_diagram.png)

## ✅ The PRISMA-trAIce Checklist

The following checklist provides the recommended items for reporting the use of AI tools in systematic reviews. Items are categorized by their importance for reproducibility and transparency (Mandatory, Highly Recommended, Recommended, Optional).

| Section | Item ID | Level | Recommended Reporting Item |
| :--- | :--- | :--- | :--- |
| **TITLE** | **P-trAIce T1** | Optional | **Title:** Indicate the use of AI in the title or subtitle if it played a substantial role (e.g., in screening or data extraction). |
| **ABSTRACT** | **P-trAIce A1** | Optional | **Abstract:** Briefly summarize the AI tool(s) used, the review stage(s) where they were applied, and their primary role. |
| **INTRO** | **P-trAIce I1** | Recommended | **Introduction:** Briefly state the rationale for using AI tools for specific tasks (e.g., to manage large volumes of literature, enhance efficiency). |
| **METHODS** | **P-trAIce M1** | **Mandatory** | **Protocol:** State if the use of AI was pre-specified in a protocol (provide access) and report any deviations. |
| | **P-trAIce M2** | **Mandatory** | **Tool Identification:** Specify name, version, and provider/developer for each tool. Provide access details (URL, repo) or description for custom tools. |
| | **P-trAIce M3** | **Mandatory** | **Purpose & Stage:** Describe the specific SLR stage (e.g., screening) and the precise task the AI performed. |
| | **P-trAIce M4** | **Mandatory** | **Input Data:** Describe data provided to the AI (e.g., training data for fine-tuning, or specific abstracts/full-texts for processing). |
| | **P-trAIce M5** | **Mandatory** | **Output Data:** Describe the output format (e.g., JSON, scores) and any automated post-processing. |
| | **P-trAIce M6** | **Mandatory** | **Prompts (LLMs):** Report prompt engineering process, full prompts (or detailed description), key parameters (e.g., temperature), and refinement. |
| | **P-trAIce M7** | Highly Rec. | **Settings (Non-LLMs):** Describe key operational settings, algorithms, or configurations influencing performance. |
| | **P-trAIce M8** | **Mandatory** | **Human Oversight:** Describe human interaction (number of reviewers, verification process, discrepancy resolution, training). |
| | **P-trAIce M9** | **Mandatory** | **Performance:** Describe methods used to evaluate AI performance (metrics, reference standards, bias checks), if applicable. |
| | **P-trAIce M10** | Recommended | **Ethics & Data:** Describe data management, storage, privacy measures, and compliance (e.g., copyright, ToS). |
| **RESULTS** | **P-trAIce R1** | **Mandatory** | **Flow Diagram:** In the PRISMA flow diagram/text, distinguish between records handled by AI versus human reviewers. |
| | **P-trAIce R2** | **Mandatory** | **Performance Metrics:** Report results of any AI performance evaluations (e.g., agreement rates, recall, precision). |
| **DISCUSSION**| **P-trAIce D1** | Recommended | **Limitations:** Discuss limitations (technical issues, biases, hallucinations) and their potential impact on findings. |
| | **P-trAIce D2** | Optional | **Implications:** Briefly discuss the experience of using AI tools (benefits, challenges, workload reduction) for future reviews. |

## 📊 The PRISMA-trAIce Flow Diagram

To transparently report the study selection process, we propose an adaptation of the PRISMA 2020 Flow Diagram. The template explicitly distinguishes between administrative, rule-based tools (e.g., for deduplication) and AI systems that perform evaluative tasks.
![PRISMA-trAIce Flow Diagram](https://github.com/cqh4046/PRISMA-trAIce/blob/main/PRISMA-trAIce_flow_diagram.webp)
## 🤝 How to Contribute

We welcome community contributions! There are several ways to get involved:

1.  **Start a Discussion:** Have an idea, suggestion, or question? Open a new Issue to start a discussion.
2.  **Propose Changes:** If you want to propose a specific change to the checklist, please open a Pull Request. Clearly describe the reason for your change.
3.  **Give Feedback:** Participate in the discussions in existing Issues and Pull Requests.
4.  **Join the Community:** Join our Discord Server to chat with other community members.

## 📄 License

This project is licensed under the MIT License. This means you are free to use, modify, and distribute the content as long as you retain the original copyright notice. See the LICENSE file for more details.
