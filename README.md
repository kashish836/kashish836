<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=750&lines=Hi+%F0%9F%91%8B%2C+I'm+Kashish+Bhiwapurkar;Machine+Learning+Engineer;AI+%2B+Computer+Vision+Builder;RAG+%2B+LLM+Systems+Builder;On-Device+ML+Enthusiast" alt="Typing SVG" />

<br/>

**I build AI systems end-to-end — from models and pipelines to deployable applications.**

<a href="https://kashish-portfolio-eight.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=A78BFA" /></a> <a href="https://www.linkedin.com/in/kashish-bhiwapurkar/"><img src="https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=A78BFA" /></a> <a href="mailto:bhiwapurkarkashish0836@gmail.com"><img src="https://img.shields.io/badge/Email-000000?style=for-the-badge&logo=gmail&logoColor=A78BFA" /></a> <a href="https://leetcode.com/u/kashish_vb08/"><img src="https://img.shields.io/badge/LeetCode-000000?style=for-the-badge&logo=leetcode&logoColor=A78BFA" /></a> <a href="https://x.com/KBhiwapurkar836"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=A78BFA" /></a>

</div>

<br/>

## 🧑‍💻 About Me

I'm a **B.Tech Data Science student at G H Raisoni College of Engineering, Nagpur**, focused on building practical AI/ML systems that go beyond notebooks and work in real applications.

* 🤖 Focused on **Machine Learning, Deep Learning, Computer Vision & AI**
* 🧠 Building with **LLMs, RAG pipelines, AI agents and multimodal AI**
* 👁️ Experienced in **real-time computer vision and landmark-based recognition**
* 📱 Interested in **on-device ML and mobile AI deployment**
* ⚙️ Building **AI backends, APIs and automation pipelines**
* 🛡️ Exploring **AI safety, deterministic guardrails and reliable AI systems**
* 🔬 Interested in **AI research, healthcare AI and ML systems**
* 🚀 Enjoy turning **ideas into working, deployable prototypes**

> **My goal is simple: build AI that is useful, deployable, and reliable — not just impressive in a notebook.**

<br/>

## 🚀 Featured Projects

### 🛡️ Relay — WhatsApp Message Notification Router

An intelligent notification-routing system built during the **HackerRank Orchestrate — August 2026 hackathon**.

Relay processes incoming WhatsApp messages across **text, images/posters and voice notes**, then classifies them into:

`Notify` · `Digest` · `Mute`

The system combines LLM-based personalization with a separate **deterministic safety layer**.

Instead of allowing the LLM to make every decision, Relay uses rules, regex patterns and risk scoring to detect signals such as:

* OTP / credential requests
* Payment-related requests
* Urgency + financial requests
* Suspicious sender/domain inconsistencies
* Other high-risk message patterns

> **Personalization comes from the model. Safety comes from code.**

**Stack**

`Python` · `Groq` · `Llama` · `Vision Models` · `Whisper` · `OCR` · `Rule-based Risk Engine`

🔗 **Repository:** https://github.com/kashish836/whatsapp-notification-router

---

### 🧠 HR-Assist RAG — Grounded HR Policy Assistant

A RAG-based HR policy assistant designed to answer employee questions using **company policy documents without hallucinating unsupported information**.

The pipeline:

`Question → Embedding → Similarity Search → Confidence Check → Grounded Answer / HR Escalation`

The system uses:

* Hugging Face Sentence Transformers for embeddings
* Cosine similarity for policy retrieval
* Groq LLM for grounded responses
* Confidence-based routing
* SMTP escalation when the answer is not covered
* Google Sheets logging
* n8n for workflow orchestration

A key design principle is:

> **If the policy doesn't contain the answer, the system escalates instead of guessing.**

**Stack**

`Python` · `n8n` · `RAG` · `Sentence Transformers` · `Groq` · `Llama` · `SMTP` · `Google Sheets`

🔗 **Repository:** https://github.com/kashish836/hr-assist-rag

---

### 🖐️ Vaani — Indian Sign Language Translator

An offline Android application that translates **Indian Sign Language gestures into text and speech in real time**.

* 35 gesture classes
* 41K+ normalized 63-dimensional landmark samples
* MediaPipe hand landmark extraction
* Random Forest and MLP model experimentation
* TensorFlow / Keras → TFLite deployment
* Flutter Android application
* Native MediaPipe integration through Kotlin
* Real-time text + speech output
* CPU-friendly on-device inference

The final model is designed to run directly on a mobile device rather than relying on cloud inference.

**Stack**

`Python` · `OpenCV` · `MediaPipe` · `TensorFlow` · `Keras` · `TFLite` · `Flutter` · `Dart` · `Kotlin`

🔗 **Repository:** https://github.com/kashish836/isl-translator

---

### 👕 Fashion Recommender

A computer vision recommendation system that finds visually similar fashion items from an uploaded image.

```text
Image
  ↓
Feature Extraction
  ↓
Visual Similarity
  ↓
Recommendation
```

Built using **ResNet50** for visual feature extraction, with a FastAPI backend and Google Cloud Vision experimentation for web-based visual matching.

**Stack**

`Python` · `PyTorch` · `ResNet50` · `FastAPI` · `Google Cloud Vision`

---

### 🌐 AI Portfolio — Chapter One: The Bookstore

A personal portfolio designed around a **bookstore / reading experience** instead of a conventional developer portfolio.

The goal was to combine technical presentation with an interactive experience while keeping the interface professional and easy to navigate.

**Stack**

`React` · `TypeScript` · `Three.js` · `Framer Motion`

🔗 **Portfolio:** https://kashish-portfolio-eight.vercel.app/

<br/>

## 🧪 What I'm Building Toward

<table>
<tr>
<td width="50%" valign="top">

### 🤖 AI / ML

* Machine Learning
* Deep Learning
* Computer Vision
* NLP & LLM Applications
* RAG Systems
* Multimodal AI
* AI Agents
* Model Deployment
* On-Device ML
* AI Safety & Guardrails

</td>

<td width="50%" valign="top">

### 🔬 Research Interests

* AI for Healthcare
* ML Systems
* Multimodal Learning
* Model Optimization
* Edge / Mobile AI
* Reliable AI Systems
* Responsible AI
* Applied Machine Learning

</td>
</tr>
</table>

<br/>

## 🧰 Tech Stack

### Languages

<img src="https://skillicons.dev/icons?i=python,java,js,cpp,sql,dart,kotlin" />

### AI / ML / Computer Vision

<img src="https://skillicons.dev/icons?i=tensorflow,pytorch,opencv" />

`Scikit-learn` · `MediaPipe` · `TFLite` · `Sentence Transformers`

### LLMs & AI Systems

`Groq` · `Llama` · `RAG` · `Embeddings` · `Vector Similarity` · `Prompt Engineering` · `AI Agents`

### Backend & APIs

<img src="https://skillicons.dev/icons?i=fastapi,nodejs,flask" />

`REST APIs` · `n8n` · `SMTP`

### App Development

<img src="https://skillicons.dev/icons?i=flutter,dart,kotlin,androidstudio,firebase" />

### Cloud, DevOps & Tools

<img src="https://skillicons.dev/icons?i=git,github,linux,vscode,figma,gcp,aws,docker" />

<br/>

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=kashish836&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=A78BFA&text_color=FFFFFF" width="48%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kashish836&layout=compact&theme=dark&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=FFFFFF" width="48%" />

<br/>

<img src="https://streak-stats.demolab.com?user=kashish836&theme=dark&hide_border=true&background=0D1117&ring=A78BFA&fire=A78BFA&currStreakLabel=A78BFA" width="70%" />

</div>

<br/>

## 📈 Activity Graph

<img src="https://github-readme-activity-graph.vercel.app/graph?username=kashish836&theme=react-dark&bg_color=0D1117&color=A78BFA&line=A78BFA&point=FFFFFF&hide_border=true" width="100%" />

<br/>

## 🐍 Contribution Snake

<img src="https://raw.githubusercontent.com/kashish836/kashish836/output/github-contribution-grid-snake-dark.svg" width="100%" />

<br/>

## 💡 Currently Learning

```text
Machine Learning
      ↓
Deep Learning
      ↓
Computer Vision + NLP
      ↓
LLMs + RAG + AI Agents
      ↓
AI Systems + Deployment
      ↓
Reliable / Responsible AI
```

I'm particularly interested in understanding **how ML systems behave outside controlled notebooks** — including deployment constraints, model reliability, safety mechanisms, latency, and real-world user interaction.

<br/>

## 🤝 Connect With Me

<div align="center">

<a href="https://kashish-portfolio-eight.vercel.app/">Portfolio</a>
• <a href="https://www.linkedin.com/in/kashish-bhiwapurkar/">LinkedIn</a>
• <a href="mailto:bhiwapurkarkashish0836@gmail.com">Email</a>
• <a href="https://leetcode.com/u/kashish_vb08/">LeetCode</a>
• <a href="https://x.com/KBhiwapurkar836">X</a>
• <a href="https://huggingface.co/">Hugging Face</a>

</div>

<br/>

<div align="center">

<img src="https://komarev.com/ghpvc/?username=kashish836&label=Profile%20Views&color=A78BFA&style=flat" />

</div>
