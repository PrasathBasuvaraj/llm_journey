# Hello LLM

In this guide you will find all the instructions your need to run the llm_career_advice notebook. This guide explains how to create API keys for popular Large Language Model (LLM) providers and how to securely store them in a `.env` file for your projects.

---

## 🔑 Creating API Keys for LLM Providers

### 1. OpenAI

- Go to [OpenAI API Keys](https://platform.openai.com/api-keys).
- Log in or sign up.
- Click **Create new secret key**.
- Copy and save your API key.

### 2. Google Gemini (Vertex AI)

- Visit [Google Cloud Console](https://console.cloud.google.com/).
- Create/select a project.
- Enable the **Vertex AI API**.
- Go to **APIs & Services > Credentials**.
- Click **Create Credentials** > **API key**.
- Copy and save your API key.

### 3. Anthropic (Claude)

- Go to [Anthropic Console](https://console.anthropic.com/settings/keys).
- Log in or sign up.
- Click **Create Key**.
- Copy and save your API key.

### 4. Cohere

- Visit [Cohere Dashboard](https://dashboard.cohere.com/api-keys).
- Log in or sign up.
- Click **Create API Key**.
- Copy and save your API key.

---

## 🗝️ Storing API Keys in a `.env` File

1. Create a file named `.env` in your project root (do **not** commit this file to version control).
2. Add your API keys in the following format:

   ```env
   # .env
   OPENAI_API_KEY=your_openai_api_key_here
   GOOGLE_API_KEY=your_google_api_key_here
   ANTHROPIC_API_KEY=your_anthropic_api_key_here
   COHERE_API_KEY=your_cohere_api_key_here
   ```

3. Save the file.

> **Note:** Never share your `.env` file or API keys publicly.

---

## ✅ Next Steps

- Use a library like `python-dotenv` to load these keys in your Python code.
- Refer to each provider’s documentation for usage examples.

---
