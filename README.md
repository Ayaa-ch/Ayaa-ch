<h1 align="center">Hi, I'm Aya Chakour 👋</h1>

<p align="center">
  <b>Data Science · Big Data · Artificial Intelligence</b><br>
  📍 Tétouan, Morocco &nbsp;|&nbsp; 🎓 Engineering student at ENSA Tétouan
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" />
  <img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</p>

---

## 👩‍💻 About me

I'm a 5th-year engineering student specialising in **Data Science, Big Data and Artificial Intelligence** at ENSA Tétouan (National School of Applied Sciences).

I like turning data into practical solutions. That means building the full chain: collecting and cleaning data, processing it at scale, training or applying models, and wrapping the result in an application people can actually use. 

### 🔭 What I'm focused on

- Building local, privacy-friendly **RAG** and LLM applications
- **AI agents** and orchestration with LangChain and LangGraph
- **NLP** on specialised domains (biomedical, educational)
- Real-time **Big Data** pipelines and streaming architectures
- **Business Intelligence & Data Visualization** to make results readable
- **Cloud computing** (AWS) and data engineering workflows

---
## 🎓 Background

🔹 **2024 – Present** · ENSA Tétouan
> **Engineering Cycle: Big Data & Artificial Intelligence**
> Learning to design data-driven systems from start to finish, with hands-on projects in RAG, streaming and AI-based quality control.

🔹 **2022 – 2024** · ENSA Tétouan
> **Integrated Preparatory Classes**
> Intensive foundation in mathematics, physics and computer science, focused on analytical thinking and problem-solving.

---

## 🚀 Featured Projects

### 📚 LinguaDocs: multilingual RAG document assistant (FR / EN / AR)

> A fully local assistant that answers questions about your own documents, in French, English and Arabic.

**What it does**
- Ingests **PDF, TXT, MD and DOCX** files, with automatic **scan detection** and **language detection**
- **Hybrid retrieval** combining dense embeddings and BM25, merged with **RRF (Reciprocal Rank Fusion)** and refined by a **reranker**
- **Streaming generation** with **cited answers** (file name and page number)
- Refuses to answer when the question falls **outside the document context**, to limit hallucinations

**Backend**
- **FastAPI** REST API with authentication
- Document library management and **per-document chat**
- **Per-stage latency tracking** (retrieval, reranking, generation)
- Conversation history stored **per user**

**Stack:** Python · FastAPI · embeddings · BM25 · reranking · local LLM (Llama / Ollama) · RAG

---

### 🧪 [Educational QA: AI quality-control pipeline for school documents](https://github.com/Ayaa-ch/qa_pedagogique)

> A local pipeline that checks and repairs educational content automatically.

**What it does**
- **Validates** educational JSON documents against a strict schema
- Detects **inconsistencies, duplicates and errors**
- **Generates corrections automatically** instead of just flagging problems
- Produces a **PDF analysis report** with full traceability: every detected error and every applied correction

**Stack:** Python · Pydantic · fastText · Sentence Transformers · Ollama

---

### 💊 [Bio-Sentry: drug side-effect detection (Web Mining)](https://github.com/Ayaa-ch/Biosentry-project)


> Mining the web to spot adverse drug effects.

**What it does**
- Collects medical data by **scraping** various websites and calling **APIs**
- Applies **BioBERT** (biomedical NLP) for **medical entity extraction**
- **Classifies adverse effects** from the extracted text

**Stack:** Python · Web Scraping (BeautifulSoup, Selenium) · BioBERT · NLP

---

### 🏦 [Real-time banking fraud detection (Big Data)](https://github.com/Ayaa-ch/streaming-fraud-detection)

> A streaming pipeline that flags suspicious transactions as they happen.

**What it does**
- Simulates a **real-time transaction stream** with **Kafka**
- Processes the stream with **Spark Streaming**
- Applies **Machine Learning models** trained on historical data to detect fraud

**Stack:** Kafka · Spark Streaming · Python · Scikit-learn

---

## 🛠️ Tech Stack

| Area | Tools |
|---|---|
| **Programming languages** | Python, C++, SQL |
| **Machine Learning & Deep Learning** | Scikit-learn, TensorFlow, PyTorch |
| **NLP & Generative AI** | spaCy, embeddings, Llama, LangChain, LangGraph, RAG |
| **Data analysis & visualization** | Pandas, NumPy, Excel, Power BI |
| **Databases** | MySQL, PostgreSQL (relational) · MongoDB, Cassandra (NoSQL) |
| **Big Data & Data Engineering** | Hadoop, Spark, Kafka, ETL |
| **Tools & DevOps** | Docker, Git/GitHub, Web Scraping (BeautifulSoup, Selenium) |

---


## 📜 Certifications

- ETL and Data Pipelines with Shell, Airflow and Kafka
- Build Chat Applications with OpenAI and LangChain
- AWS Cloud Technology and Services: Concepts
- Introduction to AWS Boto in Python
- Introduction to Data Modeling in Snowflake

---

## 🌍 Languages
 - Arabic 
 - French 
 - English 

---

## 📫 Let's connect

<p>
  <a href="mailto:aya.c.chakour@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="[https://www.linkedin.com/in/YOUR_LINKEDIN](https://www.linkedin.com/in/aya-chakour-3789ab330/?isSelfProfile=true)"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://TON_PORTFOLIO.com"><img src="https://img.shields.io/badge/Portfolio-7C3AED?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  </p>

<p align="center"><i>Thanks for stopping by! ⭐</i></p>
