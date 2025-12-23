# Generative AI – Complete Notes with Examples

---

## 1. History of Generative AI

Generative AI is a branch of Artificial Intelligence that focuses on **creating new content** rather than only analyzing or classifying existing data.

### Evolution Timeline

- **1950s–1980s: Rule-Based AI**
  - Hard-coded rules
  - No learning or generation

- **1990s–2000s: Statistical Machine Learning**
  - Probabilistic models
  - Limited creativity

- **2014: Generative Adversarial Networks (GANs)**
  - First major success in image generation

- **2017: Transformer Architecture**
  - Introduced attention mechanism
  - Enabled parallel processing

- **2020–Present: Large Language Models (LLMs)**
  - Text, code, reasoning, and multimodal generation

📌 **Exam Tip:**  
Modern Generative AI exists because of **Transformers + Big Data + High Compute (GPUs)**.

---

## 2. What is Generative AI?

**Generative AI** is an AI system that:
- Learns patterns from training data
- Generates **new, original content**
- Produces probabilistic (non-deterministic) outputs

### What Generative AI Can Generate
- Text (chat, summaries, emails)
- Code (Python, SQL, Java)
- Images and designs
- Audio and video

### What Generative AI is NOT
- ❌ Rule-based system
- ❌ Search engine
- ❌ Traditional classifier

---

## 3. How Generative AI Works (Core Idea)

Generative AI models:
- Break text into **tokens**
- Predict the **next most likely token**
- Repeat prediction until output is complete

📌 The model does **not understand** like humans — it predicts probabilities.

---

## 4. Prompts

### What is a Prompt?

A **prompt** is the instruction or input provided to a Generative AI model to guide its response.

A prompt may include:
- Task instruction
- Context
- Constraints
- Examples

### Prompt Example


📌 **Exam Tip:**  
Clear prompts = better outputs.

---

## 5. LLM Inputs

Large Language Models internally process:

1. **System Instructions**
   - Define behavior and rules

2. **User Prompt**
   - Main task or question

3. **Context / History**
   - Previous conversation or documents

4. **Parameters**
   - Temperature (creativity)
   - Max tokens (output length)

📌 Higher temperature → more creative  
📌 Lower temperature → more consistent

---

## 6. LLM Outputs

LLM outputs are:
- Generated token-by-token
- Context-aware
- Probabilistic

### Output Types
- Text
- Code
- Structured data (JSON)
- Reasoned responses

📌 Output may vary for the same prompt.

---

## 7. Examples of Generative AI

### Example 1: Text Generation

**Prompt:**
Write a professional email requesting one day of leave.

**Output:**
```
Dear Manager,
I would like to request leave for one day due to personal reasons.
Please let me know if this works for you.

Thank you.
```
---

### Example 2: Code Generation

**Prompt**
Write a Python function to check if a number is even.

**Output**
```python
def is_even(number):
    return number % 2 == 0
```
### Example 3: Summarization

**Prompt**

Summarize the following document in 3 bullet points.


**Output**
```
• Key objective of the document 
• Major findings and risks
• Final recommendations

```
### Example 4: Question Answering

**Prompt**

What is the difference between Generative AI and Traditional AI?


**Output**
```text
Traditional AI focuses on prediction or classification,
while Generative AI creates new content such as text, images, or code.
```

## 8. Prompt → LLM → Output Flow (Diagram)

```
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
```
## 9. Common Exam Traps

```
| Question                               | Correct Answer             |
| -------------------------------------- | -------------------------- |
| Is Generative AI deterministic?        | ❌ No                       |
| Does it browse the internet?           | ❌ No                       |
| Is output always correct?              | ❌ No                       |
| Are prompts important?                 | ✅ Yes                      |
| Is model trained during every request? | ❌ No (only inference runs) |
