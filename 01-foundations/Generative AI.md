# Generative AI – Exam & Notes

## 1. History of Generative AI

Generative AI refers to a class of artificial intelligence systems that can **create new content** such as text, images, code, audio, or video.

### Key Milestones
- **1950s–1980s:** Rule-based and symbolic AI (no learning)
- **1990s–2000s:** Statistical machine learning models
- **2014:** Generative Adversarial Networks (GANs) introduced
- **2017:** Transformer architecture (“Attention Is All You Need”)
- **2020–Present:** Large Language Models (LLMs) enable text, code, and reasoning at scale

📌 **Exam Tip:**  
Modern Generative AI became practical due to **Transformers + Big Data + GPUs**.

---

## 2. What is Generative AI?

**Generative AI** is a type of AI that:
- Learns patterns from existing data
- Generates **new and original content**
- Works probabilistically rather than deterministically

### What Generative AI Can Do
- Generate text (chatbots, summaries, emails)
- Generate code (Python, SQL, Java)
- Create images and designs
- Produce audio and video

### What Generative AI is NOT
- ❌ A rule engine  
- ❌ A search engine  
- ❌ A traditional classifier  

---

## 3. Examples of Generative AI

### Example 1: Text Generation

**Prompt**


Write a professional email requesting one day of leave.


**Output**


Dear Manager,
I would like to request leave for one day due to personal reasons.
Please let me know if this works for you.
Thank you.


---

### Example 2: Code Generation

**Prompt**


Write a Python function to check if a number is even.


**Output**
```python
def is_even(number):
    return number % 2 == 0

Example 3: Summarization

Prompt

Summarize the following document in 3 bullet points.


Output

• Key objective of the document
• Major findings and risks
• Final recommendations


📌 Key Concept:
The model generates output by predicting the next most likely token repeatedly.

4. Prompts, LLM Inputs, and Outputs
What is a Prompt?

A prompt is the instruction or input given to a Generative AI model to guide its response.

A prompt may include:

Instructions

Context

Constraints

Examples

Example Prompt

Explain Generative AI in simple terms for a beginner.

LLM Inputs

Large Language Models process the following inputs internally:

System Instructions – Define behavior and rules

User Prompt – The main instruction

Context / History – Previous conversation or documents

Parameters – Temperature, max tokens, etc.

📌 Exam Tip:
Higher temperature → more creative output
Lower temperature → more consistent output

LLM Outputs

The output is:

Generated token-by-token

Context-aware

Probabilistic

Output Types

Plain text

Code

Structured data (JSON)

Reasoned responses

5. Prompt → LLM → Output Flow (Diagram)
┌─────────────┐
│   User      │
│   Prompt    │
└─────┬───────┘
      │
      ▼
┌──────────────────────────┐
│  Prompt Processing       │
│  • Tokenization          │
│  • Context embedding     │
└─────┬────────────────────┘
      │
      ▼
┌──────────────────────────┐
│  Large Language Model    │
│  (Transformer Network)  │
│  • Attention mechanism  │
│  • Probability scoring  │
└─────┬────────────────────┘
      │
      ▼
┌──────────────────────────┐
│  Token Generation        │
│  • Next token predicted  │
│  • Repeated until stop   │
└─────┬────────────────────┘
      │
      ▼
┌─────────────┐
│   Output    │
│ (Text /     │
│  Code /     │
│  JSON)      │
└─────────────┘

6. Key Exam Takeaways

Generative AI creates new content

LLMs work on tokens, not full words

Prompts strongly influence output quality

Outputs are probabilistic, not fixed

Transformers are the core architecture behind LLMs

7. Common Exam Traps
Question	Correct Answer
Is Generative AI deterministic?	❌ No
Does it browse the internet?	❌ No
Is output always correct?	❌ No
Are prompts important?	✅ Yes
Is training done every time?	❌ No (only inference runs)

📌 Use this file for:

GitHub notes

Exam revision

Interview preparation

Quick reference