<!-- =======================================================
     Generative AI Notes — Kick Start page
     Save as: generative-ai-notes.md
======================================================= -->

# Generative AI — Visual Notes (Exam + Examples)

![Notes](https://img.shields.io/badge/Notes-Generative%20AI-blue)
![Level](https://img.shields.io/badge/Level-Beginner%20to%20Exam-green)
![Format](https://img.shields.io/badge/Format-Interactive%20Markdown-orange)

> ✅ **Goal:** Quick revision notes with examples + visuals.  
> 🧠 **Focus:** History → What is GenAI → Prompts → Inputs/Outputs → Diagram → Exam traps.

---

## 🔎 Table of Contents
- [1) History of Generative AI](#1-history-of-generative-ai)
- [2) What is Generative AI](#2-what-is-generative-ai)
- [3) How LLMs Work](#3-how-llms-work)
- [4) Prompts](#4-prompts)
- [5) LLM Inputs & Outputs](#5-llm-inputs--outputs)
- [6) Examples](#6-examples)
- [7) Prompt → LLM → Output (Visual Flow)](#7-prompt--llm--output-visual-flow)
- [8) Exam Takeaways](#8-exam-takeaways)
- [9) Exam Traps](#9-exam-traps)
- [10) Quick Quiz (Click to Reveal)](#10-quick-quiz-click-to-reveal)

---

## 1) History of Generative AI

### 🕒 Timeline (High Yield)
- **1950s–1980s:** Rule-based AI (hard-coded logic)
- **1990s–2000s:** Statistical ML (probability-based)
- **2014:** **GANs** popularize generation (images)
- **2017:** **Transformers** introduced (attention mechanism)
- **2020+ :** **LLMs** scale generation (text, code, reasoning)

> 📌 **Exam Tip:** Modern GenAI = **Transformers + Big Data + GPU compute**

<details>
  <summary><b>🧾 10-second recap</b></summary>

GenAI progressed from rules → statistics → deep nets.  
Transformers (2017) enabled scaling, which led to LLMs (2020+).
</details>

---

## 2) What is Generative AI

### ✅ Definition
**Generative AI** learns patterns from data and then **creates new content**: text, code, images, etc.

### 🧩 What it CAN do
- ✍️ Generate text (emails, summaries, chat)
- 👨‍💻 Generate code (Python, SQL)
- 🖼️ Generate images/designs
- 🎧 Generate audio/video (in some systems)

### 🚫 What it is NOT
- ❌ Search engine  
- ❌ Rule engine  
- ❌ Always correct  

> 🔥 Key idea: It generates by **predicting tokens**.

---

## 3) How LLMs Work

### 🧠 Core concept
LLMs generate output by repeatedly predicting the **next most likely token**.

- Token = piece of word (not always a full word)
- Output quality depends on prompt + context + parameters

---

## 4) Prompts

### 🧾 What is a Prompt?
A **prompt** is the instruction input to the model.

✅ A good prompt includes:
- **Task**
- **Context**
- **Constraints**
- **Output format**

#### Example Prompt
```txt
Explain Generative AI in simple terms for a beginner in 5 bullet points.
```

