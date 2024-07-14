# Ramayana Chatbot using RAG Technique

Semester Project submitted for the course Natural Language Processing, PES University.

```
Ganesh Vaidyanathan K
Jyotiraditya J
Sandeep Ram
Mentor : Dr. Preethi P
```

## Overview

This project involves creating a chatbot based on the Indian epic Ramayana using the Retrieval-Augmented Generation (RAG) technique. The chatbot leverages seven different Language Learning Models (LLMs) to provide accurate and insightful responses related to the Ramayana.

We have used two different Datasets to fine tune the LLMs. These are:
- RAMAYANA retold by C. Rajagopalachari
- The RÁMÁYANofVÁLMÍKI | Translated into English Verse by Ralph T. H. Griffith, M.A

  These datasets ensure that the LLM have a  contextual as well as in-depth understanding of the epic, so as to answer both factual and inferential questions!

  
## Table of Contents

- [Introduction](#introduction)
- [Models Used](#models-used)
- [What is RAG?](#what-is-rag)
- [Installation](#installation)

## Introduction

The Ramayana is one of the two major Sanskrit epics of ancient Indian literature. This project aims to develop a chatbot that can answer questions and provide information about the Ramayana. By using the RAG technique, the chatbot can enhance its responses by retrieving relevant information from a knowledge base and generating coherent and contextually accurate answers.

## Models Used

The following table lists the seven different LLMs used in this project:

| Model Number | Model Name                |
|--------------|----------------------------|
| 1            | Gemma 2B                    |
| 2            | Llama2 7B                      |
| 3            | Mistral 7B                 |
| 4            | OpenChat 3.5B                     |
| 5            | Orca2 7B                 |
| 6            | Vicuna 7B                  |
| 7            | Zephyr 7B                |

We will also be using the DeepEval library which allows us to monitor the performance of the RAG LLM on the following parameters:
- Answer Relevancy
- Faithfulness
- Context Relevancy
- Hallucination
- Toxicity

## What is RAG?

Retrieval-Augmented Generation (RAG) is a technique that combines retrieval-based and generation-based approaches to create more powerful and accurate natural language processing models. In RAG, the model retrieves relevant documents or information from a knowledge base and uses this retrieved context to generate responses. This approach leverages the strengths of both retrieval and generation techniques, leading to improved performance in tasks such as question answering, summarization, and chatbot interactions.


![RAG](https://global-uploads.webflow.com/63f3993d10c2a062a4c9f13c/64593ba041a4ff8dfef73f30_1*LYApKuxzzmvFECqwYk61wg.png)


## Installation

To install and run the Ramayana Chatbot:

   ```bash
   git clone https://github.com/kganeshv12/Ram_GPT.git
   cd Ram_GPT
   cd Models
   ```
Next, run the model of your choice!


