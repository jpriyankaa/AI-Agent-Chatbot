# AI-Agent-Chatbot
AI Agent that combines custom PDF-based knowledge with real-time web search using Retrieval-Augmented Generation (RAG), LangGraph, and Groq's LLaMA 3 model!


🔍 A full-stack, modular AI system that:
Accepts PDF uploads and stores content in Pinecone.
Uses LangGraph for agent orchestration (Router, RAG, Web Search, Answer)
Offers a user toggle to control web search behavior
Displays transparent AI decisions with full traceability
Leverages Groq for fast LLM inference + Tavily for web search

🧠 Technologies Used:
FastAPI (Backend)
Streamlit (Frontend UI)
LangGraph + LangChain
Groq LLaMA 3
Pinecone Vector DB
HuggingFace Sentence Transformers (MiniLM)
Tavily Search API
