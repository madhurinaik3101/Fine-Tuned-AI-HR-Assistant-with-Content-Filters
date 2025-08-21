# Fine-Tuned-AI-HR-Assistant-with-Content-Filters

## Table of Contents

- [Overview](#overview)
- [Situation](#situation)
- [Task](#task)
- [Action](#action)
- [Result](#results)    
- [Technologies Used](#technologies-used)
- [Demo](#demo)  

## Overview

HRWise is a fine-tuned, enterprise-ready AI assistant designed to help employees of a fictitious international bank navigate HR policies, benefits, and internal processes with clarity, compliance, and consistency. Unlike generic assistants that provide vague or misaligned answers, HRWise is trained on synthetic internal HR documentation to reflect the organization’s voice and standards—ensuring employees always receive accurate and trustworthy guidance.

Built with Azure AI Foundry, HRWise combines GPT model fine-tuning, prompt engineering, and layered content filters to promote responsible use of AI while safeguarding against harmful outputs. The assistant demonstrates how enterprises can build domain-specific AI solutions that are accurate, compliant, and conversationally intelligent—tailored for real-world HR scenarios.

To ensure safety, HRWise integrates custom content filters on top of the defaults, blocking harmful responses across four critical categories:
Violence – Language that describes, advocates, or glorifies violence.
Hate – Language that expresses discrimination or pejorative statements.
Sexual – Sexually explicit or abusive language.
Self-harm – Language that describes or encourages self-harm.

## Situation

I was inspired by how companies like Workday and Oracle use AI to streamline HR operations, but I wanted something more precise and aligned with an organization’s internal voice. I envisioned a solution where an AI assistant could understand HR policies, procedures, and employee queries in the company’s exact language—consistent, compliant, and context-aware.

By fine-tuning GPT models with examples of conversations compliant with HR policies from a fictitious international bank and adding robust content filters, the goal was to create a responsible HR AI system that delivers accurate guidance while preventing harmful or inappropriate outputs. Instead of acting like a generic HR chatbot, HRWise behaves like a trusted, well-informed HR representative—available 24/7.

## Task 

Fine-tune the language model with the Azure AI Foundry to provide consistency in the desired behavior and add content filters to promote responsible use of AI and prevent any potential harm. 

## Action

1. Create a Synthetic Training Dataset – Generate examples of realistic employee HR queries (e.g., leave requests, payroll, background checks) paired with policy-compliant responses.
2. Test the Base Model – Evaluate tone, accuracy, and level of detail in baseline responses. Adjust system prompts to verify limits of grounded information.
3. Refine Training Data – Each dataset entry includes a system message, user prompt, and a compliant HR response to shape the assistant’s conversational style.
4. Fine-tune and Deploy – Upload the training dataset, run the fine-tuning job in Azure AI Foundry, monitor progress, and deploy the custom model.
5. Evaluate the Fine-Tuned Model – Re-test with the same HR queries to measure improvements in consistency, accuracy, and tone.
6. Implement Content Filters – Extend Azure’s default filters with a custom policy to block all responses in the categories of violence, hate, sexual, and self-harm. Test and validate against edge cases.

## Result

1. Delivered a policy-aligned HR assistant that provides consistent, context-aware, and compliant responses instead of generic or potentially misleading answers.
2. Achieved improved consistency and accuracy across multi-turn employee queries, reducing HR-related confusion and enhancing trust.
3. Strengthened responsible AI safeguards with layered content filters, ensuring safe and professional interactions across all employee use cases.

## Technologies Used

1. Azure AI Foundry – Model deployment & orchestration
2. Azure OpenAI Service – gpt-4o model for response generation
3. Custom Content Filters – Safety enforcement for HR use cases

## Demo

LINK: 

--
