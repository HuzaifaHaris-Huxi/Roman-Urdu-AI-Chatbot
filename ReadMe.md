# AI Chatbot for Roman Urdu

<br>
This project focuses on building a chatbot that understands and generates responses in Roman Urdu using Generative AI techniques, specifically within a Retrieval-Augmented Generation (RAG) framework.
<br>
## Introduction
<br>
Roman Urdu, a variant of Urdu written using the Roman alphabet, is widely used in digital communication. Traditional chatbots struggle with Roman Urdu due to spelling variability and code-switching. This project leverages a RAG framework with GPT to enhance chatbot accuracy and usability for Roman Urdu speakers.
<br>
<br>
## Technologies Used<br>
Python<br>
LangChain for workflow management<br>
OpenAI Embedding Model for text embeddings<br>
GPT (Generative Pre-trained Transformer) for language generation<br>
Chroma for vector database storage<br>
Flask for API development<br>
Dataset<br>

<br>
## Data collected from:<br>
Social media platforms<br>
Hugging Face datasets<br>
User-generated content<br>
Includes preprocessing steps like normalization, tokenization, and embedding generation.<br>
<br>
## Architecture<br>
The chatbot uses the Retrieval-Augmented Generation (RAG) model:<br>
<br>
Retrieval: Retrieves relevant Roman Urdu data using Chroma.<br>
Generation: GPT generates responses based on retrieved context.<br>
LangChain Integration: Manages interaction between retrieval and generation components.
<br>
<br>
<br>
<img src ="image.png">
