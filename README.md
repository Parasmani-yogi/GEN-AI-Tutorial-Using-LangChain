# 📘 Generative AI Tutorial using LangChain

> A structured **step-by-step tutorial** to learn **Generative AI with LangChain**, from basics to advanced concepts.

---

## 🎯 About This Tutorial

This repository is designed to help you **learn and understand LangChain practically** using notebooks.

It covers:

* Core concepts
* Hands-on examples
* Real-world use cases


---

## 📚 What You Will Learn

### 🔹 Basics

* Introduction to LangChain
* Chat models & prompting

### 🔹 Tools

* Creating custom tools
* Tool integration with LLMs

### 🔹 Agents

* What are agents
* How agents use tools
* Multi-tool agents

### 🔹 Messages

* HumanMessage, AIMessage
* Chat flow handling

### 🔹 Structured Output

* Pydantic models
* JSON output from LLMs

### 🔹 Memory

* Thread-based memory
* Conversation persistence

### 🔹 Middleware

* Summarization middleware
* Human-in-the-loop (Approve / Edit / Reject)

---

## 📂 Tutorial Structure

```bash id="a9yqg4"
Gen_AI_Crash_Course_3HR/
│
├── 1_langchainintro.ipynb
├── 2_tools.ipynb
├── 3_agentintro.ipynb
├── 4_agent_with_multiple_tools.ipynb
├── 5_messages.ipynb
├── 6_structuredoutput.ipynb
├── 7_memory.ipynb
├── 8_middleware.ipynb
```

📌 Follow notebooks in sequence for best understanding.

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash id="uvd2ox"
git clone https://github.com/Parasmani-yogi/GEN-AI-Tutorial-Using-LangChain.git
cd GEN-AI-Tutorial-Using-LangChain
```

---

### 2️⃣ Create Virtual Environment

```bash id="vwhcl1"
python -m venv .venv
```

Activate:

```bash id="v6h7co"
# Windows
.venv\Scripts\activate

# Mac/Linux
source .venv/bin/activate
```

---

### 3️⃣ Install Requirements

```bash id="b4k3n0"
pip install -r requirements.txt
```

---

### 4️⃣ Add API Key

Create a `.env` file:

```bash id="c9t8fn"
OPENAI_API_KEY=your_openai_api_key_here
GROQ_API_KEY=your_groq_api_key_here

```
## 💡 Key Takeaways

* Understand how **LLMs work with LangChain**
* Learn how to build **tools & agents**
* Handle **structured outputs**
* Implement **memory & middleware**
* Reduce **hallucinations using tools**

---


