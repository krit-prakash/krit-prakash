
# Krit Prakash
### Applied AI Engineer | AI Engineer | Generative AI | Agentic AI | RAG | MLOps

**M.Tech, IIT (ISM) Dhanbad | 8+ Years of Experience**

I enjoy building things that bring Machine Learning and AI beyond experimentation and into practical applications.

Over the years, I have worked with Python and Machine Learning, and my recent focus has been on Generative AI, Agentic workflows, and Retrieval-Augmented Generation (RAG). I am particularly interested in building AI applications that combine intelligent workflows with reliable backend systems, vector databases, and cloud deployment.

I believe good AI engineering is not just about choosing the right model. It is also about how the application retrieves information, handles failures, evaluates responses, and performs under real-world constraints.

**Currently focused on:** Applied AI Engineering | Agentic AI | Enterprise RAG | Production-Oriented AI Systems

---

## Featured Projects

### 1. Enterprise Multi-Tenant Compliance AI Agent

**Cloud-Deployed Agentic RAG Application**

[Live API & Swagger Documentation](https://compliance-policy-ai-agent.onrender.com/docs) | [GitHub Repository](https://github.com/krit-prakash/compliance-policy-ai-agent)

**Tech Stack:** Python, FastAPI, LangGraph, Qdrant Cloud, Groq, Cohere, Docker, Render

This is one of my recent hands-on projects, where I explored some of the challenges involved in building AI applications for enterprise-oriented use cases.

The application combines document retrieval, tenant-level filtering, answer evaluation, and cloud deployment.

**What I worked on:**

- **Tenant-Level Data Isolation:** Implemented `tenant_id` metadata filtering in Qdrant Cloud to scope document retrieval to the respective tenant.
- **Answer Validation:** Built a self-reflective evaluation workflow using LangGraph StateGraph. An evaluation node checks generated answers against retrieved document context.
- **Safe Failure Handling:** When an answer is not supported by the retrieved context, the workflow returns a safe fallback response.
- **Cloud Optimization:** Integrated Cohere's embedding API (`embed-english-light-v3.0`) instead of running a heavyweight local embedding model.
- **Backend & Deployment:** Developed REST APIs using FastAPI and deployed the containerized application on Render.

**Key Learning:** Building a useful RAG application involves much more than connecting an LLM to a vector database. Retrieval boundaries, answer reliability, failure handling, and deployment decisions matter just as much.

---

### 2. NASA Turbofan Predictive Maintenance

**End-to-End Machine Learning & MLOps Pipeline**

[GitHub Repository](https://github.com/krit-prakash/turbofan-predictive-maintenance-mlops)

**Tech Stack:** Python, PySpark, XGBoost, FastAPI, Docker, Azure, GitHub Actions

A predictive maintenance project focused on analyzing turbofan engine degradation data and estimating remaining useful life.

**What I worked on:**

- Used PySpark for data processing and feature preparation.
- Developed an XGBoost-based predictive model.
- Achieved the following evaluation results:
  - RMSE: 12.71
  - MAE: 8.56
  - R²: 0.906
- Integrated FastAPI for model serving.
- Used Docker, Azure, and GitHub Actions as part of the deployment and MLOps workflow.

**Key Learning:** Connecting data processing, model development, API serving, and deployment into an end-to-end ML workflow.

---

### 3. Multi-Agent Grant Proposal Generator

**LangGraph-Based Multi-Agent AI Application**

[GitHub Repository](https://github.com/krit-prakash/Multi-Agent-AI-Grant-Proposal-Generator-LangGraph)

**Tech Stack:** Python, LangGraph, Ollama, Mistral, FAISS, Streamlit, SQLite

Built a multi-agent application to assist with grant proposal generation using locally hosted language models.

**What I worked on:**

- Designed an agent-based workflow using LangGraph.
- Integrated Ollama and Mistral for local LLM inference.
- Used FAISS for vector-based retrieval and contextual information access.
- Developed an interactive Streamlit interface.
- Integrated SQLite for data persistence.
- Evaluated generated outputs, achieving scores of 81 and 87.

**Key Learning:** Understanding how multiple AI agents can work together to organize tasks and generate context-aware outputs.

---
## Technical Skills

### Programming & Backend Engineering
- Python
- SQL
- FastAPI
- REST API Development
- Object-Oriented Programming

### Generative AI & Agentic AI
- Large Language Models (LLMs)
- Retrieval-Augmented Generation (RAG)
- Agentic AI Workflows
- LangGraph
- LangChain
- Multi-Agent Systems
- Prompt Engineering
- LLM Evaluation
- RAGAS
- Ollama

### Vector Databases & AI Infrastructure
- Qdrant Cloud
- FAISS
- ChromaDB
- Cohere Embeddings
- Groq API
- Semantic Search
- Metadata Filtering

### Data Science & Machine Learning
- Machine Learning
- Scikit-learn
- XGBoost
- PySpark
- Pandas
- NumPy
- Exploratory Data Analysis
- Feature Engineering
- Model Evaluation

### MLOps, Cloud & Deployment
- Docker
- Microsoft Azure
- Render
- GitHub Actions
- Model Serving
- CI/CD Fundamentals
- Cloud Deployment

---

## What I Enjoy Working On

- Building practical Agentic AI applications.
- Designing RAG pipelines for enterprise document workflows.
- Improving retrieval quality and LLM response evaluation.
- Developing Python backends for AI-powered applications.
- Working with vector databases and LLM integrations.
- Deploying containerized applications to cloud environments.
- Connecting Machine Learning models with real-world applications.

---

## Education

**Master of Technology (M.Tech)**  
Indian Institute of Technology (ISM), Dhanbad

---

## Professional Interests

I am interested in opportunities where I can contribute to building and deploying practical AI systems.

**Roles:** Applied AI Engineer | AI Engineer | Generative AI Engineer | Agentic AI Engineer

**Preferred Locations:** Hyderabad | Bengaluru | Remote (India)

---

## Let's Connect

- **GitHub:** [github.com/krit-prakash](https://github.com/krit-prakash)
- **LinkedIn:** [Krit Prakash](https://www.linkedin.com/in/krit-prakash-9a32a1246)

---

*Learning continuously, building thoughtfully, and turning AI ideas into practical engineering solutions.*
