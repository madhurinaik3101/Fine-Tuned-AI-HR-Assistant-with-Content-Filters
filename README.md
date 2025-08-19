# RAG-based-AI-Assistant-for-HR

## Table of Contents

- [Overview](#overview)
- [Situation](#situation)
- [Task](#task)
- [Action](#action)
- [Result](#results)    
- [Technologies Used](#technologies-used)
- [Demo](#demo)  

## Overview

A RAG-based AI Assistant built with Azure AI Foundry that combines vector search and LLMs to deliver accurate, context-aware answers to HR-related employee queries. Trained on synthetic internal HR data for a fictitious multinational bank, the assistant acts as a trusted knowledge companion, reducing HR workload and improving employee support efficiency.

## Situation

Employees often face challenges when seeking quick answers to common HR questions, such as onboarding processes, leave planning, tax filing, and workplace reporting.
Traditionally, this requires HR intervention, which can be time-consuming, repetitive, and inefficient.
A context-aware AI Assistant provides instant, accurate responses grounded in official HR documentation—helping employees self-serve while reducing the load on HR staff.

## Task 

Design and implement a Retrieval-Augmented Generation (RAG) based AI Assistant that can:
1. Ingest and index HR documentation.
2. Retrieve relevant information and ground responses in trusted company knowledge.
3. Provide multi-turn, context-aware support for employees.

## Action

1. Used the Azure AI Foundry portal to create Azure AI Foundry Resources and for Model Deployments.
2. Applied Ada-002 Embedding Model to vectorize HR documents and created a vector + keyword index for semantic retrieval.
3. Integrated the GPT-4o model to generate natural, conversational answers grounded in retrieved context.
4. Implemented the RAG pipeline via Azure OpenAI SDK to handle ingestion, retrieval, and response generation.
5. Applied prompt engineering techniques to improve accuracy and reduce hallucinations.

## Result

1. Reduced HR team workload by automating common employee questions.
2. Delivered faster, accurate, and reliable answers compared to generic assistants.
3. Demonstrated enterprise-ready deployment with Azure AI Foundry.
4. Showcased how RAG enhances LLMs with domain-specific knowledge

## Technologies Used

1. Azure AI Foundry – Model deployment & orchestration
2. Azure Cognitive Search – Vector + keyword index for retrieval
3. Azure OpenAI Service – gpt-4o model for response generation
4. Ada-002 Embedding Model – Document embeddings
5. Python SDKs – Integration and client application

## Demo

LINK: 

--
