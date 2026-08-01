# 🧠 Chain-of-Thought + Persona Prompting Experiment

## 📌 Project Overview

This project demonstrates how **prompt design can influence the quality, structure, and usefulness of AI-generated responses**.

The experiment compares two approaches for solving the same business decision problem:

1. **Plain Prompt** — a direct instruction without a persona or explicit reasoning instruction.
2. **Chain-of-Thought + Persona Prompt** — the same problem with a relevant professional persona and a reasoning-oriented instruction.

The goal is to observe whether adding structured reasoning guidance and a domain-specific persona produces a clearer, deeper, and more useful response.

---

## 🎯 Objective

The main objectives of this experiment are to:

- Understand Chain-of-Thought (CoT) prompting.
- Understand Persona/Role prompting.
- Compare a basic prompt with a more structured prompt.
- Evaluate differences in correctness, clarity, reasoning quality, and structure.
- Understand how prompt design can influence the behavior of an AI model.

---

## 💼 Problem Selected

A small software company has **$50,000 available for one major investment**.

The company has three possible options:

1. Spend the money on marketing to attract more customers.
2. Hire two additional developers to speed up product development.
3. Improve the existing product by investing in performance, reliability, and user experience.

The company currently has:

- A small development team.
- Customer complaints about product performance.
- Slower customer growth during the last six months.

The company wants to increase revenue while maintaining customer satisfaction and financial stability.

The AI was asked to determine which option would be the best investment.

---

# 🧪 Experiment Design

The same business scenario was given to the AI using two different prompts.

This ensures that the comparison focuses on the **prompting technique** rather than changes to the problem itself.

---

## 1️⃣ Plain Prompt

The first prompt directly asked the AI to analyze the scenario and recommend the best option.

It did not specify:

- A professional persona.
- An explicit reasoning instruction.
- A particular reasoning framework.

### Prompt

```text
Analyze the following business scenario and recommend which option the company should choose.

Compare the three options and explain the advantages and disadvantages of each.

Then provide a final recommendation and explain why it is the best choice for the company.