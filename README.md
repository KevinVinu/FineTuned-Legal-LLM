# Overview
This project focuses on building a domain-specific Legal AI assistant by fine-tuning a Large Language Model (LLM) on Indian legal data. The model is trained to understand legal context and generate precise, structured, and reasoning-based answers.

The system leverages LoRA-based fine-tuning (PEFT) on a lightweight LLaMA model using the Unsloth framework for efficient training and inference.

### 🧠 Key Features
* Fine-tuned LLM for Indian legal domain

* Uses LoRA (Low-Rank Adaptation) for efficient training

* Supports context-based legal question answering

* Optimized with 4-bit quantization for low memory usage

* Generates formal, reasoning-based legal responses

* Deployable via Hugging Face

### 🏗️ Tech Stack

* Model: LLaMA 3.2 (3B Instruct)

* Framework: Unsloth

* Fine-tuning: PEFT (LoRA)

* Libraries:

* Transformers

* TRL (SFTTrainer)

### Datasets (Hugging Face)

The model is trained on:

* Prarabdha/indian-legal-supervised-fine-tuning-data

 Dataset includes:

* Legal contexts

* Case-based questions

* Expert-style answers

## This project demonstrates the application of Generative AI in the legal domain by combining:

Efficient fine-tuning (LoRA)

Domain-specific datasets

Scalable LLM deployment

It showcases how LLMs can be adapted for real-world professional use cases with limited computational resources.
