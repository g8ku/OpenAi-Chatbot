# OpenAI Chatbot 💬

A simple terminal chatbot built using Python and OpenAI's GPT-3.5-Turbo model.

## 🔧 Features
- Conversation loop
- Exit with `bye`, `quit`, or `exit`
- Uses secure environment variable for API key

## 🚀 How to Run

```bash
# Set your API key
export OPENAI_API_KEY=your-key-here   # or use PowerShell: $env:OPENAI_API_KEY="..."

# Run the chatbot
python main.py

## Project Structure
main.py        → Chatbot logic
.gitignore     → Ignores .env, __pycache__, etc.
README.md      → You're reading it

*Disclaimer*: This project uses OpenAI's API so Make sure you manage your billing & quota before you run this!


