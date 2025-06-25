# 🧠 GPT-CLI

A simple and fast CLI tool to chat with the Groq LLaMA3 model straight from your terminal.
Type a prompt, get a response. That's it.

---

## ⚡ Features

- **Minimal and fast** - No bloat, just pure functionality
- **Powered by Groq's `llama3-70b-8192` model** - Lightning-fast AI responses
- **Works directly from your terminal** - No need to leave your workflow
- **Simple setup** - Get started in minutes

---

## 🛠️ Installation

### 1. Clone the repository
```bash
git clone https://github.com/0xkevindev/gpt-cli.git
cd gpt-cli
```

### 2. Set your API key
Set your Groq API key as an environment variable:
```bash
export API_KEY=your_groq_api_key
```

To make this permanent, add it to your shell profile:
```bash
echo 'export API_KEY=your_groq_api_key' >> ~/.bashrc
source ~/.bashrc
```

### 3. Create an alias
Add an alias to your `.bashrc` file for easy access:
```bash
echo "alias gpt='/home/kevin/coder/node/gpt'" >> ~/.bashrc
source ~/.bashrc
```

---

## 🚀 Usage

Once installed, simply use the `gpt` command followed by your prompt:

```bash
gpt "What is the meaning of life?"
```

```bash
gpt "Write a Python function to calculate fibonacci numbers"
```

```bash
gpt "Explain quantum computing in simple terms"
```

---

## 📋 Requirements

- Node.js (v12 or higher)
- A valid Groq API key
- Unix-like system (Linux, macOS, WSL)

---

## 🔧 Getting Your Groq API Key

1. Visit [Groq's website](https://groq.com)
2. Sign up for an account
3. Navigate to the API section
4. Generate your API key
5. Copy and use it in the installation step above

---
