<!-- ================= PROFESSIONAL SUMMARY ================= -->
### 🧑‍🦰 Sumit

> *"I don't just train models. I engineer the entire path from raw data to deployed intelligence."*

I'm a **BS Data Science and Applications** student at **IIT Madras** and a **Google Gemini Student Ambassador**, with a deep focus on building intelligent systems end to end. My foundation is mathematics and statistics, my craft is Machine Learning and Deep Learning, and my frontier is **GenAI, Advanced RAG and Agentic AI**.

I implement algorithms from first principles, then scale them into real systems: from EDA, feature engineering and model training, to MLOps, LLM orchestration with LangChain and LangGraph, and full-stack deployment on the cloud. Alongside, I sharpen **DSA** and problem solving, and I'm working toward publishing research and building production-grade AI at product-based companies.

**🎯 Focus Areas:** Machine Learning · Deep Learning · GenAI · Agentic AI · MLOps · Full-Stack Development



<br>

## 💼 Working Experience:

<!-- ================= AI SUPPORT TICKET AUTOMATION ================= -->
### 🎫 AI Support Ticket Automation

> *"Intelligent triage, from ticket to resolution."*

A full-stack application that turns a raw customer support message into a structured case and a ready-to-send reply. Each ticket passes through a four-stage LangChain pipeline: triage (category, priority, language), category-specific case analysis, a resolution decision, and a reply written in the customer's own language. Every stage returns validated Pydantic output, so the system never depends on free-form text. The FastAPI backend runs the pipeline asynchronously and stores every result, the React frontend provides a submission form and a analytics dashboard, and the whole stack is containerized with Docker Compose and served through nginx.

**Highlights**
- Multi-stage LangChain pipeline with a router that sends each ticket to one of six category-specific analysis chains
- Structured output with Pydantic schemas at every stage
- Human-in-the-loop rule: critical tickets always require a human agent, regardless of the model's decision
- Multilingual: detects the ticket language and replies in the same language
- Honest failure handling: empty or invalid model output is stored as a failed ticket with a clear error instead of crashing
- Async FastAPI REST API with request validation, search, filters and pagination
- Dashboard with live stats, category, priority and resolution breakdowns, and a detailed ticket view
- Batch upload from JSON with sequential processing and live per-ticket progress
- Dark and light theme, responsive React interface
- Dockerized with a multi-stage frontend build, nginx reverse proxy and a persistent database volume

<p>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/OpenRouter-6467F2?style=flat-square" />
<img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" />
<img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />
<img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" />
</p>

🔗 **Repository:** [Itz-Me-Sumit/AI-SUPPORT-TICKET-AUTOMATION](https://github.com/Itz-Me-Sumit/AI-SUPPORT-TICKET-AUTOMATION)

<br>


<!-- ================= CHATBOT ================= -->
### 💡 Chatbot: Agentic RAG Assistant

> *"A production-deployed, tool-using AI assistant, from model to cloud."*

A full-stack conversational AI system built on an agentic architecture. The backend orchestrates LLM workflows with LangChain and LangGraph, retrieves grounded context through an Advanced RAG pipeline, and calls external tools via the Model Context Protocol (MCP). Runs are traced and debugged with LangSmith. The React frontend talks to a FastAPI service backed by PostgreSQL, and the entire stack is containerized with Docker and deployed on an AWS EC2 instance.

**Highlights**
- Agentic workflow design with LangGraph (stateful, multi-step reasoning)
- Advanced RAG for accurate, source-grounded answers
- MCP integration for standardized tool access
- LangSmith tracing for observability and debugging
- REST API with FastAPI, persistence with PostgreSQL
- Responsive React and TypeScript frontend
- Dockerized and deployed on AWS EC2

<p>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" />
<img src="https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square" />
<img src="https://img.shields.io/badge/MCP-000000?style=flat-square" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/AWS%20EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white" />
</p>

🔗 **Repository:** [GitHub Repository](https://github.com/Itz-Me-Sumit/Chatbot)

🌐 **Live Demo:** [Chatbot](https://13-203-14-221.sslip.io/)

<br>


## 📚 Learning Journey:

<!-- ================= DATA SCIENCE ================= -->

### 📊 Data Science

> *"Data is the raw material. Mathematics is the language. Models are the story it tells."*

A structured, end-to-end Data Science curriculum, built from first principles and implemented in code. It starts with Python and the mathematical foundations (Linear Algebra, Calculus, Probability, Inferential Statistics, Hypothesis Testing, A/B Testing), moves through the scientific Python stack (NumPy, Pandas, Matplotlib, Seaborn), and extends into Machine Learning, Deep Learning and applied AI.

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Mathematics-6a11cb?style=flat-square" />
<img src="https://img.shields.io/badge/Statistics-2575fc?style=flat-square" />
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" />
</p>

🔗 **Repository:** [Itz-Me-Sumit/Data-Science](https://github.com/Itz-Me-Sumit/Data-Science)

<br>

<!-- ================= MACHINE LEARNING ================= -->
#### 🧠 Machine Learning

> *"From raw data to production-ready models."*

Complete, hands-on coverage of the Machine Learning lifecycle, with algorithms implemented both from scratch and with scikit-learn.

- **Data Understanding:** Exploratory Data Analysis (EDA), statistical profiling, outlier and missing-value analysis, data visualization
- **Feature Engineering:** encoding, scaling, transformation, feature selection, feature extraction, handling imbalanced data
- **Supervised Learning:** Linear / Ridge / Lasso / Elastic Net Regression, Logistic Regression, KNN, Naive Bayes, Decision Trees, SVM
- **Ensemble Methods:** Random Forest, Bagging, AdaBoost, Gradient Boosting, XGBoost, LightGBM, CatBoost
- **Unsupervised Learning:** K-Means, Hierarchical Clustering, DBSCAN, PCA
- **Model Training and Tuning:** cross-validation, hyperparameter tuning (Grid / Random Search), bias-variance trade-off, regularization
- **Model Evaluation:** Accuracy, Precision, Recall, F1, ROC-AUC, Confusion Matrix, RMSE, MAE, R²
- **MLOps:** experiment tracking and model registry with MLflow, reproducible pipelines, the complete ML lifecycle from problem definition to deployment

<p>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square" />
<img src="https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square" />
<img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
<img src="https://img.shields.io/badge/XGBoost-189AB4?style=flat-square" />
<img src="https://img.shields.io/badge/LightGBM-02A676?style=flat-square" />
<img src="https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square&logoColor=black" />
<img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" />
</p>

🔗 **Repository:** [Itz-Me-Sumit/Machine-Learning](https://github.com/Itz-Me-Sumit/Machine-Learning)

<br>

<!-- ================= DEEP LEARNING ================= -->
#### 🔬 Deep Learning

> *"Teaching machines to see, read and reason."*

Deep Learning fundamentals to modern architectures, implemented from scratch and with PyTorch and TensorFlow.

- **Foundations:** Perceptron, Multi-Layer Perceptron, Backpropagation, Activation and Loss Functions, Optimizers (SGD, Adam, RMSprop), Regularization, Batch Normalization
- **Computer Vision:** Convolutional Neural Networks (CNN), classic architectures, Image Classification, Object Detection and Segmentation
- **Sequence Modeling:** RNN, LSTM, GRU, Bidirectional RNNs
- **Encoder-Decoder Architectures:** Seq2Seq, Attention Mechanism
- **Transformers:** Self-Attention, Multi-Head Attention, Positional Encoding, BERT and GPT-style models
- **Transfer Learning:** pretrained models, fine-tuning and feature extraction
- **Natural Language Processing:** tokenization, embeddings, text classification, language modeling

<p>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" />
<img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white" />
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
</p>

🔗 **Repository:** [Itz-Me-Sumit/Deep-Learning](https://github.com/Itz-Me-Sumit/Deep-Learning)

<br>

<!-- ================= AI ENGINEERING ================= -->
### 🤖 AI Engineering

> *"Models are the engine. Engineering is what makes them useful."*

Building LLM-powered systems end to end: from prompting and orchestration to retrieval pipelines, autonomous agents and production deployment. The umbrella repository links three focused repositories, each covering one layer of the modern AI stack.

🔗 **Umbrella Repository:** [Itz-Me-Sumit/AI-Engineering](https://github.com/Itz-Me-Sumit/AI-Engineering)

<br>

#### 💬 Generative AI

> *"From a single prompt to composable LLM pipelines."*

- **LLM Fundamentals:** model integration, prompt engineering, structured output parsing
- **LangChain Core:** chains, runnables (LCEL), memory, tool calling
- **Data Ingestion:** document loaders, text splitters
- **Retrieval Basics:** embeddings, vector stores, retrievers

<p>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/Vector%20Stores-6a11cb?style=flat-square" />
<img src="https://img.shields.io/badge/Prompt%20Engineering-2575fc?style=flat-square" />
</p>

🔗 **Repository:** [Itz-Me-Sumit/GenAI](https://github.com/Itz-Me-Sumit/GenAI)

<br>

#### 🔎 Advanced RAG

> *"Retrieval that is accurate, grounded and measurable."*

Retrieval-Augmented Generation beyond the naive pipeline: improving retrieval quality, grounding responses in source documents and evaluating the system end to end.

- **Retrieval Optimization:** chunking strategies, hybrid search, re-ranking, query transformation
- **Pipeline Design:** multi-step and context-aware retrieval
- **Evaluation:** faithfulness, relevance and retrieval metrics

<p>
<img src="https://img.shields.io/badge/RAG-6a11cb?style=flat-square" />
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/Embeddings-2575fc?style=flat-square" />
</p>

🔗 **Repository:** [Itz-Me-Sumit/Advance-RAG](https://github.com/Itz-Me-Sumit/Advance-RAG)

<br>

#### 🕹️ Agentic AI

> *"Systems that plan, use tools and act."*

Designing autonomous, tool-using agents with stateful, graph-based orchestration.

- **Agent Orchestration:** LangGraph state machines, nodes, edges and conditional routing
- **Tool Use:** function calling and Model Context Protocol (MCP) integration
- **Observability:** tracing and debugging agent runs with LangSmith

<p>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" />
<img src="https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square" />
<img src="https://img.shields.io/badge/MCP-000000?style=flat-square" />
</p>

🔗 **Repository:** [Itz-Me-Sumit/Agentic-AI](https://github.com/Itz-Me-Sumit/Agentic-AI)

<br>
