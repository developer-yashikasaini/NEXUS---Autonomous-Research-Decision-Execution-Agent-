**NEXUS – Autonomous Research, Decision and Executive Agent**

NEXUS is an AI-powered autonomous research, planning, and decision-making assistant designed to transform user-defined goals into structured, actionable, and cost-aware implementation plans. It uses a multi-agent architecture powered by LangGraph, where six specialized agents—Research, Planning, Risk, Decision, Execution, and Review—work together to analyze objectives, generate implementation strategies, identify potential risks, evaluate alternatives, and assess project feasibility.

The system integrates Retrieval-Augmented Generation (RAG) to provide evidence-based research using user-uploaded PDF, TXT, and Markdown documents. It extracts and processes document content, generates semantic embeddings using Sentence-Transformers (all-MiniLM-L6-v2), and stores them in PostgreSQL with pgvector for efficient similarity-based retrieval.

Built with **Python, FastAPI, React, Vite, LangGraph, LangChain, PostgreSQL, pgvector, and Docker**, NEXUS provides an interactive dashboard for goal submission, knowledge-base management, research insights, implementation planning, risk analysis, and final decision-making.

Key features include:
- Six-agent autonomous workflow for research and project planning.
- Document-based knowledge retrieval using RAG.
- Semantic vector search with PostgreSQL and pgvector.
- Evidence-grounded research with source citations.
- Automated risk assessment and weighted decision analysis.
- Budget estimation and deadline feasibility evaluation.
- Groq LLM integration with automatic model fallback.
- Offline functionality through a deterministic MockProvider.
- Docker Compose-based deployment.

NEXUS aims to make technical research and project planning more structured, transparent, reliable, and resource-efficient.
