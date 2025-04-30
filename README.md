# Rikor AI Prompts

Welcome to the **Rikor AI Prompt Repository**, a curated library of custom-built AI prompts designed to streamline insurance data extraction, risk assessment, policy benchmarking, and FDD (Franchise Disclosure Document) analysis.

This repository is **purpose-built for insurance professionals at Rikor** who are leveraging AI (e.g., ChatGPT) to improve workflows, automate underwriting tasks, and enhance franchise compliance intelligence.

---

## 📌 Purpose

The goal of this repository is to:

- **Standardize AI prompt usage** across teams and projects
- **Accelerate manual workflows** such as document review, clause extraction, and coverage comparisons
- **Ensure accuracy and consistency** in how we analyze and benchmark insurance policies
- **Enable faster iterations** in product development and operations

---

## 🧠 Repository Structure

| File Name                                           | Purpose                                                                 |
|----------------------------------------------------|-------------------------------------------------------------------------|
| `Benchmark Comparison Prompt`                      | Master prompt for comparing policies against benchmark requirements     |
| `Coverage Benchmark - Construction`                | Industry-specific coverage benchmark for construction franchises        |
| `Coverage Benchmark - Retail Clothing Store`       | Benchmark tailored for retail clothing industry                         |
| `Coverage Comparison - Cyber Liability`            | Policy analysis and comparison prompt for cyber coverage                |
| `Coverage Comparison - GL Sport Facility`          | Comparison prompt for general liability specific to sports facilities   |
| `Coverage Comparison - General Liability`          | Foundational prompt for GL policy comparisons                           |
| `Extracting Unique Allegations from Claims Letters`| Extracts core allegations from written claims reports                   |
| `FDD Coverage Extraction`                          | Extracts coverage obligations from Franchise Disclosure Documents        |
| `FDD Insurance Compliance Metadata Extraction`     | Captures compliance metadata from FDDs for tracking and analysis        |
| `FDD Item 8 Clause`                                | Prompt for analyzing and summarizing Item 8 of an FDD                   |
| `FDD Risk Assessment`                              | Evaluates risk based on FDD inputs and insurance provisions             |
| `Franchisee Average Insurance Expenses`            | Calculates benchmarks from existing policy spend data                   |
| `Franchisor Description of Operations`             | Generates a concise operations description for underwriting purposes    |
| `NAICS, SIC, and NCCI Classification`              | Classifies risk using regulatory code systems                          |

---

## 🛠️ How to Use

### Requirements
- Access to Gemini, ChatGPT or another LLM-based system capable of running structured prompts.
- Optional: Internal Rikor tooling that integrates these prompts into workflows (e.g., RMS, compliance scoring engine).

### Usage Steps
1. **Select a prompt** based on the use case (e.g., FDD review, policy comparison).
2. **Copy the prompt** into your AI environment.
3. **Insert structured input data** as indicated (e.g., PDF policy text, JSON metadata, raw claims letter).
4. **Review output** for insights, errors, or gaps.
5. **Iterate as needed** and contribute improvements if applicable.

---

## 🤝 Contribution Guidelines

Rikor team members are encouraged to:
- Submit new prompts for emerging workflows or insurance types.
- Update existing prompts as coverage terms evolve.
- Rename and organize files clearly.
- Use consistent formatting and Markdown structure for readability.

If submitting a new prompt, please:
- Name it descriptively (e.g., `Coverage Comparison - Workers Compensation`).
- Include an inline comment or section header describing inputs and outputs.
- Ensure the prompt aligns with Rikor's data handling and compliance standards.

---

## 🔐 Access Control

This repository is public for transparency, but **meant only for internal Rikor use**. Any usage outside of Rikor must be approved in writing.

---

## 📣 About Rikor

[Rikor](https://www.protectmyfranchise.com) is a technology-first retail insurance agency specializing in the franchising ecosystem. Our AI initiatives help scale compliance monitoring, streamline broker services, and deliver real-time insurance 
intelligence to brands and their franchisees.

---

## 📬 Feedback & Support

For questions, ideas, or improvements:
- Email: wade@rikor.io
- GitHub Issues: Use the [Issues](../../issues) tab to report bugs or request enhancements.

---

Let’s build faster, smarter, and more accurate insurance workflows — together.

**– Rikor Engineering & Compliance Automation Teams**
