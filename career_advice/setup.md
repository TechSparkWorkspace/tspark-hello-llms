# Setup

In this guide you will find all the instructions your need to run the llm_career_advice notebook.

- This guide explains how to create API keys for popular Large Language Model (LLM) providers and how to securely store them in a `.env` file for your projects.
- This guide provides instructions for pulling and running different LLM models locally on ollama

## 🔑 Creating API Keys for LLM Providers

### 1. OpenAI

- Go to [OpenAI API Keys](https://platform.openai.com/api-keys).
- Log in or sign up.
- Click **Create new secret key**.
- Copy and securely save your API key — you’ll use this in your .env file

_💳 Note_: You must set up billing or have free trial credits to use the API. Visit the [Billing Dashboard](https://platform.openai.com/settings/organization/billing/overview) to check your usage and add a payment method if needed.

### 2. Anthropic (Claude)

- Go to [Anthropic Console](https://console.anthropic.com/settings/keys).
- Log in or sign up.
- Click **Create Key**.
- Copy and save your API key.

_💳 Note_: Anthropic requires an active billing account or access to free credits to use their API. Visit your [account settings](https://console.anthropic.com/settings/organization) to review your quota or add a payment method.

### 3. Google Gemini

- Visit the [Google Cloud Console](https://console.cloud.google.com/welcome?inv=1&invt=Aby_hQ&project=llmlearnings)
- Create or select an existing project
- Enable the Vertex AI API for that project
- Navigate to APIs & Services > Credentials
- Click Create Credentials → API key
- Copy and securely save your API key

_💳 Note_: To use the Gemini API, you must enable billing on your Google Cloud project. Some accounts may have free trial credits, but an active billing setup is required for continued access.

### 4. Cohere

- Visit [Cohere Dashboard](https://dashboard.cohere.com/api-keys).
- Log in or sign up.
- Click **Create API Key**.
- Copy and save your API key.
