# Langchain 

Welcome to the Langchain ! Use Langchain to create your own AI agents, building from basic concepts to advanced techniques.

## Course Outline

1. **Setup Environment**
2. **Chat Models**
3. **Prompt Templates**
4. **Chains**
5. **RAG (Retrieval-Augmented Generation)**
6. **Agents & Tools**

## Getting Started

### Prerequisites

- **Python**: Version 3.10 or 3.11
- **Poetry**: Follow the [Poetry installation tutorial](https://python-poetry.org/docs/#installation) to install Poetry on your system.

## Repository Structure

Here’s a breakdown of the folders and their contents:

### 1. Chat Models
- `1_chat_model_basic.py`: Basic interaction with a chat model.
- `2_chat_model_basic_conversation.py`: Simple conversation flow.
- `3_chat_model_alternatives.py`: Exploring different chat models (e.g., ChatGPT, Claude, Gemini).
- `4_chat_model_conversation_with_user.py`: Interactive user conversation.
- `5_chat_model_save_message_history_firestore.py`: Saving chat history to Firestore.

Learn how to interact with models like ChatGPT, Claude, and Gemini.

### 2. Prompt Templates
- `1_prompt_template_basic.py`: Introduction to prompt templates.
- `2_prompt_template_with_chat_model.py`: Combining prompt templates with chat models.

Understand the basics of prompt templates and how to use them effectively.

### 3. Chains
- `1_chains_basics.py`: Fundamentals of chaining tasks.
- `2_chains_under_the_hood.py`: How chains work internally.
- `3_chains_extended.py`: Advanced chain examples.
- `4_chains_parallel.py`: Running chains in parallel.
- `5_chains_branching.py`: Conditional branching in chains.

Learn how to create chains using chat models and prompts to automate tasks.

### 4. RAG (Retrieval-Augmented Generation)
- `1a_rag_basics.py`: Basic RAG setup (Part 1).
- `1b_rag_basics.py`: Basic RAG setup (Part 2).
- `2a_rag_basics_metadata.py`: RAG with metadata (Part 1).
- `2b_rag_basics_metadata.py`: RAG with metadata (Part 2).
- `3_rag_text_splitting_deep_dive.py`: Deep dive into text splitting.
- `4_rag_embedding_deep_dive.py`: Deep dive into embeddings.
- `5_rag_retriever_deep_dive.py`: Deep dive into retrievers.
- `6_rag_one_off_question.py`: Single-question RAG query.
- `7_rag_conversational.py`: Conversational RAG.
- `8_rag_web_scrape_firecrawl.py`: RAG with web scraping using Firecrawl.
- `8_rag_web_scrape.py`: RAG with general web scraping.

Explore technologies like documents, embeddings, and vector stores that enable RAG queries.

### 5. Agents & Tools
- `1_agent_and_tools_basics.py`: Introduction to agents and tools.
- **`agent_deep_dive/`**:
  - `1_agent_react_chat.py`: ReAct agent for chat.
  - `2_react_docstore.py`: ReAct agent with document store.
- **`tools_deep_dive/`**:
  - `1_tool_constructor.py`: Building tools with constructors.
  - `2_tool_decorator.py`: Using decorators for tools.
  - `3_tool_base_tool.py`: Creating tools with BaseTool.

Learn about agents, how they work, and how to build custom tools to enhance their capabilities.


## Comprehensive Documentation

Each script contains detailed comments explaining its purpose, functionality, and logic. These annotations will help you understand the flow and reasoning behind each example.


