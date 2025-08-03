# 🧠 Research AI Agent

An AI-powered research assistant built using **IBM Granite via watsonx.ai**, designed exclusively for academic and educational use. This agent is focused, fact-based, and ethically aligned to assist students, educators, and researchers in extracting structured, reliable, and citation-driven knowledge.

---

## 📌 Problem Statement

Information overload and unreliable sources have made academic research increasingly inefficient. Most AI tools are generalized, often hallucinate facts, and lack strict boundaries for educational use. I built this agent to act as a **focused, domain-locked AI research assistant** that delivers **factual**, **unbiased**, and **well-structured academic information**, and rejects any non-research queries.

---

## 🛠️ Technology Stack

### ✅ Core Components
- **IBM watsonx.ai** – Accessed and deployed the Granite model via IBM’s enterprise AI platform.
- **Granite Foundation Model** – Used for its strong factual grounding and controlled response generation.
- **IBM Cloud Object Storage** – For storing prompts, documents (e.g. PDFs), and output logs securely.

### 🧰 Other Tools & Techniques
- **Prompt Engineering** – Strict system prompt to lock behavior to academic-only responses.
- **Content Filtering** – Input validation to reject speculative, creative, or irrelevant prompts.
- **Structured Output Design** – Bullet points, citation references, and academic formatting.
- *(Optional)*: Plans to add APIs for PDF summarization and citation sourcing.

---

## 🚀 Features

- 🔒 **Domain-Restricted**: Only responds to educational or academic research queries.
- 📚 **Fact-Based Output**: Factual, structured, and grounded in real academic sources.
- 🚫 **Hallucination Mitigation**: No guessing; if it doesn't know, it says so.
- 🔍 **Strict Prompt Governance**: Controlled tone, format, and behavioral rules.
- ☁️ **Cloud-Native & Scalable**: Built on IBM Cloud services for secure, production-ready deployment.
- 📁 **Data Storage**: Stores documents and outputs in Cloud Object Storage for traceability.

---

## 🌟 Wow Factors

- **Precision over Personality**: No fluff, no fiction — just facts.
- **Backed by IBM Granite**: High-quality, low-bias foundation model with enterprise reliability.
- **Ethical by Design**: No misinformation, biased outputs, or non-academic responses.
- **Plug-and-Play Ready**: Scalable for integration into LMS platforms, academic tools, or research systems.

---

## 📈 Future Scope

- 🔗 **Real-time Academic API Integration** (e.g., Semantic Scholar, PubMed)
- 📄 **PDF & Document Summarization**
- ✍️ **Plagiarism Detection Integration**
- 🌍 **Multilingual Academic Query Support**
- 🧠 **User Feedback Loop for Continual Learning**
- 📚 **LMS Integration** (Moodle, Canvas, etc.)
- 🎙️ **Voice Interface for Accessibility**

---


## 🧪 Usage (Basic Flow)

1. User submits an academic or research-based question.
2. Input is validated and pre-processed.
3. Agent queries the IBM Granite model via watsonx.ai with the enforced system prompt.
4. Output is filtered, structured, and returned to the user.
5. *(Optional)*: Store logs or documents in IBM Cloud Object Storage.

---

## 🙋‍♂️ Author

Built by **Anish Sambhwani**, a Computer Science Engineering student passionate about solving real-world problems using responsible AI.
