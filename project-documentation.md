# Project Documentation

## 1. Project Overview

### Objective & Goals

The project aims to develop an **AI-powered system for efficiently summarizing legal documents and conducting comprehensive risk assessments** using **LLMs, advanced NLP models, and vector databases**. This intelligent system automates **clause extraction, regulatory compliance verification, anomaly detection, and legal risk identification**, significantly enhancing accuracy, speed, and reliability in document processing while reducing manual effort.

### Problem Statement & Significance

Manual legal document review is **time-consuming, error-prone, and expensive**. Identifying **non-compliance risks, critical clauses, and legal conflicts** requires expertise and extensive reading. This project automates these tasks using **AI-powered summarization, clause matching, and risk assessment**, improving accuracy and efficiency.

### Challenges in Manual Document Review

- **Volume of documents:** Large legal contracts take days to analyze.
- **Human error:** Risk of missing critical clauses.
- **Compliance tracking:** Ensuring adherence to **GDPR & HIPAA regulations**.
- **Clause comparison:** Identifying discrepancies across multiple contracts.

### Need for an AI-Based Automated System

- **Reduces manual workload** by summarizing documents within seconds.
- **Enhances risk identification** using AI-powered clause matching.
- **Ensures legal compliance** by fetching real-time legal clauses.
- **Automates reporting** via **SendGrid email integration**.

## 2. System Architecture & Workflow

### System Components & Data Flow

- **Frontend:** Built using **Streamlit** for an intuitive, user-friendly experience.
- **Backend:** Implements **LangChain for text processing, Hugging Face models for NLP, and FAISS for vector search, Groq models API for summary and other processes**.
- **Database:** Uses **FAISS for semantic search and vector-based clause matching**.

### Workflow & Processing Steps

1. **Document Upload**: Users upload PDFs containing legal documents.
2. **Preprocessing & Chunking**: Text is extracted, cleaned, and split into smaller segments.
3. **AI Summarization**: LLM models generate concise summaries.
4. **Risk Assessment**: AI detects potential risks and non-compliance issues.
5. **Clause Matching**: The system fetches legal clauses from real-time web sources and compares them against uploaded documents to ensure compliance and identify key legal provisions.
6. **Document Comparisons**: The system performs document-to-document comparisons, detecting inconsistencies, missing clauses, and discrepancies across multiple contracts to maintain uniformity and accuracy.
7. **MapReduce for Chunking & Faster Processing**: Implements a distributed processing approach to efficiently handle large legal documents by splitting them into smaller, manageable chunks and enabling parallel AI processing for faster insights.
8. **Email Automation**: Processed documents and reports are sent via **SendGrid** for seamless delivery to users.

## 3. Week by Week/ Milestone wise progress

## **Milestone 1**:- Foundation/Basics
### Task :- Python file operations for document handling and LLM prompt engineering excercises.
1) Basic python programming and some Machine Learning basics like Supervised and Unsupervised models.
2) Explored the LLM models like [Groq](https://console.groq.com/playground).
3) In the Groq playground, experimented with various models, system and user prompts and parameters like temperature and max completion tokens. 
4) Implementing [Streamlit API](https://streamlit.io/) (Create tabs, headings).


## **Milestone 2**:- Advanced Concept Development
### Task :- Implement Basic vector database operations and create a interface for summary tab.
1) Understanding what RAG systems are, and its architecture.
2) Implementing vector databases in our project like [FAISS](https://ai.meta.com/tools/faiss/) (Facebook AI similary search).
3) Use [Groq](https://console.groq.com/playground) for summarizing a legal doc which user inputs into the [Streamlit UI](https://streamlit.io/).


## **Milestone 3**:- Advanced Concept Development
### Task :- Document Processing and Risk Detection.
1) Implement Chatbot with the help of prompts in [Groq](https://console.groq.com/playground).
2) Deploy LLMs for clause extractions.
3) Develop Risk Scoring Algorithms (severity + likelihood)
4) Integrate compliance checklists (GDPR/HIPAA).

## **Milestone 4**:- Full Integration and Deployment.
### Task :- Achieve full system integration and prepare for deployment.
1) Connect analysis modules to streamlit.
2) Attach visualisations for risk assessment.
3) Use [Hugging Face](https://huggingface.co/) for deployment.
4) In hugging face, set up environment variables in the secrets tab, this is where all the api keys are kept
5) Integrate email automation using [Sendgrid](https://sendgrid.com/en-us), where the user inputs his/her email address and then the downloadable pdfs are sent to the inputted email address.
6) After all the functionalities are setup, deploy the model on hugging face.


## 4. UI Design & User Experience

- **Simple Upload Interface:** Drag-and-drop feature for **easy document uploads**.
- **Real-Time Processing:** Users receive **instant AI-generated summaries**.
- **Smooth Navigation:** Well-structured **dashboard for risk analysis reports**.

## 5. Conclusion & Results

### Accuracy & Efficiency Improvements

The AI-powered system significantly improves **accuracy and efficiency** in legal document processing by automating **summarization, risk assessment, and clause matching**. Using **MapReduce for chunking**, the system enables **faster processing** and **parallel execution**, reducing the time taken for document analysis. The integration of **vector-based searches** enhances clause matching accuracy, ensuring better **legal compliance and risk mitigation**.

### Future Enhancements & References

- **Expand AI model capabilities** for more complex legal reasoning.
- **Improve UI/UX** to make interaction more seamless.
- **Enhance real-time legal compliance tracking** with regulatory updates.
- **Extend MapReduce implementation** for handling larger document sets more efficiently.


### ------------------------------------------------COMPLETION OF PROJECT-----------------------------------------------
