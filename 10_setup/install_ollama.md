# 🐏 Run LLM Locally with Ollama

This guide walks you through setting up and running LLM model's on your local machine using **[Ollama](https://ollama.com)** — a lightweight framework to run large language models effortlessly.

## 🛠️ Step 1: Install Ollama

```bash
curl -fsSL https://ollama.com/install.sh | sh
```

ℹ️ You can also download installers manually: https://ollama.com/download

## 📦 Step 2: Pull the Model of your choice

```bash
ollama pull llama3
```

_Note_ This will download the llama3 8B model to your local machine.

## ▶️ Step 3: Run the Model

```bash
ollama run llama3
```

This starts a conversational session with the model in your terminal.

## 🧼 List All Models

```bash
ollama list
```

## 🧼 Remove models

```bash
ollama rm llama2:latest
```
