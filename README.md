# Langchain Project

This project focuses on understanding various sections of Langchain, including Chats, Prompts, Chains, RAG, and Agents.

# Sections

## [Chat Models](Langchain_chat_models.ipynb)
- Basic Chat Model - How to set it up?
- Simple Realtime Chat Model: Implemented within the notebook.
- Realtime Chat Model with Cloud Firestore: Save chat history in Cloud Firestore Database.

## [Prompt Template](langchain_prompt_template.ipynb) 
- Prompt Template Basics

![image](https://github.com/user-attachments/assets/3e7e1d47-60b9-434e-93f5-e62e21a933ae)

- Prompt Template with Chat Models

## [Chains](langchain_chains.ipynb)

Chain Overview

![image](https://github.com/user-attachments/assets/bc7ba726-6586-4733-a6e3-4a7246f86223)

Different Chain Possibilities 

![image](https://github.com/user-attachments/assets/1bbae555-3d4d-4c33-855a-f8a07ea8180d)
![image](https://github.com/user-attachments/assets/6867b814-57db-4ad2-ab57-f93e3a2a5c66)

Chain Examples
- Chains Basic Example

- Chains - Under the Hood
  - Executed under the Runnable class with two main parts: RunnableLambda and RunnableSequence.

- Chains - Extended
  - Use RunnableLambda to add additional executable functions.

- Chains - Parallel
  - implement using RunnableParallel.

- Chain - Branching
  - Implement using RunnableBranching.

## [Retrieval Augmented Generation (RAG)](langchain_rag.ipynb)

RAG Overview 

![image](https://github.com/user-attachments/assets/b280adb0-72d2-4aa7-bc3d-7770aaf387b4)

![image](https://github.com/user-attachments/assets/d6236cb9-057e-49c3-9c01-8a9d3c3eac4c)
![image](https://github.com/user-attachments/assets/6eab8ece-79f2-485f-aaf6-e846a87d5474)

Vector DB Workings
![image](https://github.com/user-attachments/assets/25598ae5-4b45-4b2c-ae6c-050132b472c6)

- Simple RAG Working overview
- RAG Working with Metadata
- Text Splitters
  - Different Text Splitters available
  - When to use what
  - How does each output look like
- Different Retriver options
  - Similarity
  - MMR
  - Similarity with Threshold  
- RAG : Answering the query based on the retrived relevant docs
- RAG: Conversation QA
- RAG: Web Scrapping with Firecrawl

## Agents & Tools
![image](https://github.com/user-attachments/assets/fe667e9a-f0fb-4a2d-ad6e-c508dc28e04c)
