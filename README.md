# Building Chatbots with Conversation History using LangChain

## Overview

This project demonstrates how to build an intelligent conversational chatbot using LangChain with conversation history and memory management.

The chatbot can remember previous interactions, maintain conversational context, and provide more natural and context-aware responses using Large Language Models (LLMs).

The project focuses on implementing:

* Conversational AI
* Chat History Management
* Context Retention
* LangChain Memory
* Prompt Templates
* Session-based Conversations

---

## Features

* AI-powered conversational chatbot
* Conversation history tracking
* Context-aware responses
* Memory integration using LangChain
* Session management
* Chat prompt templates
* Human-AI interaction flow
* Dynamic conversation handling

---

## Technologies Used

| Technology                 | Purpose                   |
| -------------------------- | ------------------------- |
| Python                     | Programming Language      |
| LangChain                  | LLM Application Framework |
| OpenAI / Groq API          | Large Language Model      |
| ChatPromptTemplate         | Prompt Engineering        |
| RunnableWithMessageHistory | Conversation Management   |
| ChatMessageHistory         | Session Chat Storage      |
| Jupyter Notebook           | Development Environment   |

---

## Project Structure

```bash
Building-Chatbots-with-Conversation-History/
│
├── 1-chatbots.ipynb
├── vectorretriever.ipynb
├── README.md
├── requirements.txt
└── .env
```

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Building-Chatbots-with-Conversation-History.git
```

---

### 2. Navigate to Project Folder

```bash
cd Building-Chatbots-with-Conversation-History
```

---

### 3. Create Virtual Environment

```bash
python -m venv venv
```

---

### 4. Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Mac/Linux

```bash
source venv/bin/activate
```

---

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Environment Variables

Create a `.env` file in the project root directory.

```env
OPENAI_API_KEY=your_openai_api_key
GROQ_API_KEY=your_groq_api_key
```

---

## Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebooks:

```text
1-chatbots.ipynb
```

and

```text
vectorretriever.ipynb
```

Run all cells sequentially.

---

## How the Chatbot Works

1. User sends a message
2. LangChain stores chat history
3. Previous conversation context is retrieved
4. Prompt template combines history + new question
5. LLM generates context-aware response
6. Updated history is stored for future conversations

---

## Conversation Flow

```text
User Input
     ↓
Chat History Memory
     ↓
Prompt Template
     ↓
LLM Processing
     ↓
AI Response
     ↓
Conversation Stored
```

---

## Key LangChain Concepts Covered

* Chat Models
* Prompt Templates
* Message History
* RunnableWithMessageHistory
* Session-based Memory
* Conversational Chains
* HumanMessage & AIMessage
* Stateful Conversations

---

## Learning Outcomes

By completing this project, you will understand:

* How conversational chatbots work
* How memory improves chatbot interactions
* How LangChain manages chat history
* How to create session-based AI applications
* How to build context-aware GenAI systems

---

## Future Enhancements

* Streamlit chatbot UI
* Voice-based conversations
* Multi-user session handling
* Persistent database memory
* RAG integration
* Agentic AI workflows
* Deployment using FastAPI or Docker

---

## Author

Reshma Manu

QA Automation Engineer | Generative AI Learner

---

## License

This project is developed for educational and learning purposes.
