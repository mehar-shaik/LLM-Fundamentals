# LLM Fundamentals — Hands-on Practice

## 📌 About This Project

This repository contains my hands-on practice while learning the fundamentals of Large Language Models (LLMs). I followed a tutorial and practiced concepts related to interacting with AI models through Python.

The goal of this practice is to understand how LLMs work at a basic level and how to communicate with them using APIs.

## 🎯 Topics Covered

- **LLM Fundamentals** — Understanding the basics of Large Language Models.
- **Tokens** — Learning how text is processed by language models.
- **Prompting** — Providing instructions and questions to an AI model.
- **API Integration** — Practicing how to send requests to an AI model using Python.
- **Streaming Responses** — Receiving and displaying generated text in chunks.
- **Tool Calling** — Understanding how AI models can interact with external functions and tools.

## 🛠️ Technologies Used

- Python
- OpenAI API
- OpenAI Python SDK
- Environment variables (`.env`)

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd <your-repository-name>
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```powershell
.\venv\Scripts\Activate.ps1
```

### 3. Install the required package

```bash
pip install openai python-dotenv
```

### 4. Configure your API key

Create a `.env` file in the project directory:

```env
OPENAI_API_KEY=your_api_key_here
```

Never commit your actual API key to GitHub.

Add the following to `.gitignore`:

```gitignore
.env
venv/
__pycache__/
```

### 5. Run your practice scripts

Run the relevant Python file:

```bash
python filename.py
```

Replace `filename.py` with the name of your actual Python script.

## 💡 Key Takeaway

This practice helped me explore the fundamentals of LLMs and understand how Python can be used to interact with AI models through APIs. I also explored concepts such as streaming responses and tool calling.

## 📈 Progress

I am continuing to learn and practice AI development, building my understanding step by step through hands-on coding.

---

**Learning by building, practicing, and experimenting!** 🚀
