# 🧠 AI Intern Challenge: Fake News Analyzer (No Model Building)

## 🔍 Overview

This challenge tests your ability to:

- Handle and explore data in Python
- Apply basic NLP techniques
- Use large language models (LLMs) via thoughtful prompt design
- Draw meaningful comparisons between data and AI reasoning

There is **no model training required**.

---

## ✅ Stage 1: Core Challenge — Fake News Pattern Discovery

**⏱ Estimated Time**: 3–5 hours  
**🎯 Goal**: Explore fake vs. real news patterns and test LLM reasoning using handcrafted prompts.

---

### 🔧 Tasks

#### 1. Data Handling

- Use a real/fake news dataset (e.g. [Fake and Real News Dataset on Kaggle](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset))
- Load the data using `pandas`
- Preprocess article text:
  - Lowercasing
  - Stopword removal
  - Basic tokenization

---

#### 2. Data Analysis & Visualization

- Compare fake vs. real news using:
  - Top 10 frequent words in each category
  - Average article length (words & characters)
  - Most common named entities (using `spaCy` or similar)
- Create **2–3 visualizations**, such as:
  - Word frequency bar charts or word clouds
  - Article length distributions
  - Named entity counts (person, org, etc.)

---

#### 3. Prompt Engineering & LLM Evaluation

- Select **2 articles** (1 real, 1 fake)
- Craft a thoughtful prompt for an LLM (e.g., ChatGPT) asking:

  > "Is this article real or fake? Analyze the language, structure, and content to justify your answer."

- Submit:
  - The full prompt
  - The LLM’s response (copy/paste)
  - A brief explanation of why you designed the prompt the way you did

---

#### 4. Short Analysis

- Write 1–2 paragraphs reflecting on:
  - What patterns you discovered in the data
  - Whether the LLM's explanation aligned with those patterns
  - Strengths/weaknesses of the LLM’s response

---

### 💾 Submission Format

- Submit a Jupyter Notebook (`.ipynb`) or Python script (`.py`)
- Include a markdown or PDF write-up of your findings

---

## 🚀 Stage 2: Optional Additional Challenge — Prompt Refinement & Evaluation

**⏱ Estimated Time**: 3–4 hours  
**🎯 Goal**: Evaluate and refine your prompt to improve LLM accuracy across multiple articles.

---

### 🔧 Tasks

#### 1. Refine Your Prompt

- Make 2–3 improved versions of your original prompt
- Justify what changed and why (e.g., tone, specificity, structure)

#### 2. Test on Multiple Articles

- Run your best prompt(s) on 4–6 articles (mix of real and fake)
- Log:

  - Article ID or title
  - Ground truth
  - LLM prediction
  - LLM justification

- Create a small table or plot showing results and accuracy

#### 3. Reflect

- Where did the LLM get things wrong? Why?
- What might improve prompt accuracy?
- Could LLM explanations support fact-checkers in real life?

---

## 📩 Optional Bonus

- Build a minimal CLI or notebook interface that takes an article and:
  - Displays key stats (word count, named entities, etc.)
  - Shows your LLM prompt and response

---

## 💡 Evaluation Criteria

| Category           | What We’re Looking For                                 |
| ------------------ | ------------------------------------------------------ |
| Python/NLP Skills  | Clean code, correct preprocessing, meaningful analysis |
| Data Understanding | Insightful comparisons between fake and real news      |
| Prompt Design      | Clear, structured, purpose-driven LLM prompts          |
| Critical Thinking  | Thoughtful explanation of results and limitations      |
| Presentation       | Easy-to-follow notebook/script + write-up              |

---

Good luck! We’re looking for curiosity, creativity, and clarity — not perfection.
