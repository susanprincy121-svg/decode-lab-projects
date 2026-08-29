# Decode Labs Project 1: AI Chatbot System

An interactive Rule-Based AI Chatbot built in Python designed to process natural language user inputs and deliver intelligent, contextual responses.

---

## 📌 Project Overview
The objective of this project is to build and deploy a conversational AI agent capable of understanding user intent and providing relevant, automated assistance. By leveraging pattern matching, keyword analysis, and predefined conversational flows, the chatbot simulates human-like interaction for everyday queries.

This project demonstrates foundational concepts in Natural Language Processing (NLP), rule-based intent recognition, input normalization, and interactive command-line application structure.

---

## 🛠️ Key Features & Technical Architecture

* **Input Normalization:** Preprocesses raw user text by converting inputs to lowercase and stripping punctuation/whitespace for consistent pattern evaluation.
* **Intent Recognition Engine:** Maps user queries to broad intent categories (e.g., greetings, help requests, general inquiries, fallbacks) using string matching and regular expressions.
* **Dynamic Response Generation:** Delivers structured responses tailored to recognized intents and context.
* **Fallback & Exception Handling:** Gracefully handles unrecognized queries by providing helpful fallback prompts rather than breaking the conversation loop.
* **Interactive CLI Loop:** Operates inside a continuous runtime loop until an explicit exit command (e.g., `exit`, `quit`, `bye`) is triggered.

---

## 📊 Intent & Knowledge Mapping

The chatbot evaluates incoming messages across key intent categories:

### Supported Intent Categories
1. **Greetings & Openings:** Welcomes users and establishes interactive context (e.g., *"hello"*, *"hi"*, *"hey"*).
2. **Help & Capability Inquiries:** Explains what assistance the bot can provide (e.g., *"what can you do"*, *"help"*).
3. **General Knowledge / Domain Queries:** Answers predefined domain-specific questions.
4. **Farewells & Exit Commands:** Terminates the session cleanly (e.g., *"bye"*, *"quit"*, *"exit"*).
5. **Default Fallback:** Captures out-of-scope inputs and prompts the user for clarification.

---

## ⚙️ Tech Stack & Dependencies

* **Language:** Python 3.x
* **Environment:** Jupyter Notebook / Anaconda / Python CLI
* **Libraries:**
  * `re` – Regular expressions for pattern matching and text normalization
  * `random` – Dynamic selection of varied response templates

---

## 💻 Installation & Usage

### 1. Clone the Repository
```bash


