<<<<<<< HEAD
# Natural Language Processing

## From Human Language to Intelligent Machines

🌎 Every day you interact with systems that understand language.

You ask questions to chatbots, search Google, send messages, read AI-generated summaries, and even generate code.

Behind all of these experiences is **Natural Language Processing (NLP)** — one of the most exciting intersections of:

* 🤖 **Machine Learning**
* 📊 **Data Science**
* 🧠 **Artificial Intelligence**
* 💬 **Human Language**

NLP teaches computers how to **understand, analyze, and generate human language**.

But modern NLP goes far beyond simple text processing.

Today it powers systems such as:

* 🧠 **Large Language Models (LLMs)** like ChatGPT
* 🔎 **Retrieval Augmented Generation (RAG)** systems
* 🤖 **AI Agents that can reason and take actions**
* 📄 **Document understanding systems**
* 💬 **Conversational AI and chatbots**
* 📊 **Text analytics and sentiment analysis**

---

# Why NLP Matters in Modern AI

Organizations generate enormous amounts of text data every day:

* Emails
* Customer support conversations
* Research papers
* Legal documents
* Social media
* Product reviews
* Internal reports

Most of this data is **unstructured**, meaning traditional data analysis tools cannot easily process it.

NLP allows us to convert this **human language** into **machine-readable data** that AI systems can analyze.

---

# The Big Picture: NLP in Modern AI Systems

Modern AI systems often combine multiple technologies.

Here is a simplified view:

```
Human Language
      ↓
 Natural Language Processing
      ↓
 Text Representations (Vectors / Embeddings)
      ↓
 Machine Learning Models
      ↓
 Large Language Models (LLMs)
      ↓
 Retrieval Augmented Generation (RAG)
      ↓
 Intelligent AI Agents
```

This means the **fundamentals of NLP are still the foundation** of many cutting-edge AI systems.

---

# The NLP Pipeline

Before machines can learn from text, the text must go through a sequence of transformations called the **NLP Pipeline**.

Think of it like a **text processing assembly line**.

```
Raw Text
   ↓
Cleaning & Normalization
   ↓
Tokenization
   ↓
Stopword Removal
   ↓
Stemming / Lemmatization
   ↓
Feature Extraction
   ↓
Numerical Representation
   ↓
Machine Learning Model
```

Each step gradually converts **messy human language** into **structured numerical features** that machine learning models can understand.

---

# Where This Pipeline Appears in Real AI Systems

Even modern AI systems still rely on these concepts.

Example architecture:

```
User Question
      ↓
Text Processing (NLP Pipeline)
      ↓
Embedding Model
      ↓
Vector Database
      ↓
Relevant Documents Retrieved
      ↓
Large Language Model
      ↓
Generated Answer
```

This architecture is known as **Retrieval Augmented Generation (RAG)**.

It is widely used in:

* Enterprise AI systems
* Knowledge assistants
* AI copilots
* Research tools
* Customer support automation

---

# Learning Activity Overview

In this learning activity, you will explore the **foundational components of the NLP pipeline** through hands-on code examples.

The notebook demonstrates how text moves from **raw language to structured machine learning features**.

### The activity includes:

* Loading and exploring text data
* Cleaning and normalizing language
* Tokenizing text into smaller units
* Removing irrelevant words
* Transforming text into numerical features
* Preparing text data for machine learning models

These steps represent the **core building blocks of NLP systems used across industry and research.**

---

# What You Will Learn

By completing this activity, you will learn how to:

✔ Prepare raw text data for analysis
✔ Understand how machines interpret language
✔ Transform text into numerical features
✔ Build the foundation for machine learning models using language data
✔ Connect classical NLP techniques to modern AI systems like **LLMs, RAG pipelines, and AI agents**

---

# Why This Matters for Your Career

Understanding NLP pipelines opens the door to building powerful AI systems such as:

* 💬 Chatbots
* 🔎 Intelligent search engines
* 📄 Document analysis tools
* 🤖 AI assistants
* 📚 Knowledge retrieval systems
* 🧠 LLM-powered applications
* ⚡ AI agents capable of complex reasoning

Many advanced systems may appear complex, but they are built on **simple, powerful ideas** like the ones you will explore in this activity.

---

# Ready?

Let's start exploring **how machines begin to understand human language**.

🚀 Open the notebook and begin the activity.
=======
# NLP Language Processing Workshop

## Author

Group Number: 5 

Alamir Ibrahim - 9104960 
Asangika Hettiarachchi - 7461502  
Preethi Vasudevan - 9125985  
Arya Vinodbhai Patel - 9084843 

**Deconstructing Language for AI Agents**

A hands-on Jupyter Notebook workshop that shows how raw text is turned into clean, structured data that a machine learning model can use. It builds a simple Natural Language Processing (NLP) pipeline step by step on real, messy text.

## What we Learned

- How to explore a text dataset (20 Newsgroups, about 18,800 documents)
- **Tokenization:** splitting text into words
- **Normalization and stop-word removal:** lowercasing and removing common words
- **Stemming:** reducing words to a root form (Porter Stemmer)
- **Lemmatization:** converting words to proper dictionary forms, compared with stemming
- **Bag-of-Words:** turning processed text into word counts
- **LLM token costs:** how tokenization affects the price of commercial LLMs
- **BERT demo:** using a pre-trained question-answering model from Hugging Face

## Repository Contents

| File | Description |
|---|---|
| `NLP-Pipeline-Introduction.ipynb` | The workshop notebook: explanations, code, and challenges |
| `requirements.txt` | Python packages needed to run the notebook |
| `.gitignore` | Files and folders Git should ignore (virtual environment, caches, NLTK data) |
| `README.md` | This file |

## Workshop Outline

1. **Introduction:** how an AI learns language
2. **The raw material:** loading and exploring the 20 Newsgroups dataset
3. **The NLP pipeline:** tokenization, normalization and stop words, stemming, and the full pipeline
4. **Conclusion:** the before and after, and the vocabulary reduction
5. **Fun activity:** asking BERT a question, and its limitations
6. **Challenges:** four exercises that extend the pipeline

## Challenges

| # | Challenge | Main idea |
|---|---|---|
| 1 | Are we throwing away important words? | Keep negation words such as "not", "no", and "never" during stop-word removal |
| 2 | Is stemming too aggressive? | Compare stemming and lemmatization on a list of words |
| 3 | Turning text into features | Build a Bag-of-Words summary and a small word-count vector |
| 4 | Tokenization and LLM billing | Compare token counts after different preprocessing steps |

Each challenge ends with talking points that explain the observations.

## Getting Started

### Requirements

- Python 3.10 or newer
- Jupyter Notebook, JupyterLab, or VS Code with the Jupyter extension
- An internet connection for the first run (to download the dataset, NLTK data, and the BERT model)

### Setup

```bash
# 1. Clone the repository
git clone <https://github.com/PreethiVNair/NLP-Language-Processing-Workshop.git>
cd NLP-Language-Processing-Workshop

# 2. Create and activate a virtual environment
python -m venv .venv

# Windows
.venv\Scripts\activate
# macOS / Linux
source .venv/bin/activate

# 3. Install the dependencies
pip install -r requirements.txt

# 4. Start Jupyter
jupyter notebook
```

Open `NLP-Pipeline-Introduction.ipynb` and run the cells from top to bottom.

### Notes

- The notebook downloads the NLTK resources it needs (`punkt`, `stopwords`, `wordnet`) the first time it runs. They are saved in a local `nltk_data` folder, which is ignored by Git.
- The 20 Newsgroups dataset is downloaded automatically by scikit-learn.
- The BERT demo needs `torch` and `transformers` (included in `requirements.txt`). The first run downloads a model, so it can take a few minutes.
- `requirements.txt` includes `pywin32`, which is only needed on Windows. On macOS or Linux, remove that line if `pip install` fails.

## Tools Used

Python, Jupyter Notebook, NLTK, scikit-learn, Hugging Face Transformers, PyTorch, and Matplotlib.

>>>>>>> ad95401 (Challenge 4)

