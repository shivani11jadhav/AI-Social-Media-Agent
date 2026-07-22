# AI-Powered Social Media Agent 🚀

## 📌 Problem Statement
Brands, influencers, and organizations struggle to keep up with the fast-paced and fragmented world of social media. Content trends evolve rapidly, audience sentiment changes continuously, and competitor activities are difficult to track across multiple platforms. Managing social media manually often results in scattered insights, delayed decisions, and missed engagement opportunities.

## 💡 Proposed Solution
The proposed solution is an AI-powered Social Media Agent that leverages IBM Bob, IBM watsonx.ai, IBM Granite Models, Retrieval-Augmented Generation (RAG), and Vector Databases to automate content creation, trend analysis, sentiment monitoring, and campaign optimization.

## ✨ Features
* Multi-platform social media monitoring
* AI-powered content generation (Captions & Hashtags)
* Trend prediction & Audience sentiment analysis
* Competitor analysis & Best posting time recommendation
* Campaign analytics dashboard
* AI-powered recommendations
* Multi-Agent Architecture
* RAG-powered contextual responses

## 🏗 System Architecture

```text
       User 
        │ Text / Voice / Image 
        ▼ 
  IBM Bob Platform (Agent Orchestration Layer) 
 ───────────────────────────────────────────────
    │          │            │            │ 
    ▼          ▼            ▼            ▼ 
 Social     Content       Trend       Campaign 
 Media     Generator     Forecast    Analytics 
 Agent       Agent        Agent        Agent 
    │          │            │            │ 
    └──────────┼────────────┼────────────┘
               │
               ▼
       IBM Granite Model
    (Reasoning + Generation)
               │
               ▼
           watsonx.ai
 (Model Deployment + Embeddings)
               │
               ▼
        Vector Database
       (FAISS / Chroma)
               ▲
               │
      RAG Retrieval Layer
               ▲
               │
 X | LinkedIn | Instagram | Facebook 
 Trending APIs | News | Brand Docs

*Project UI*
<img width="959" height="500" alt="image" src="https://github.com/user-attachments/assets/e23d5f3a-cd4c-4c69-b631-8762d52e854d" />

