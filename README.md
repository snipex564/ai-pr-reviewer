# 🤖 AI PR Reviewer

An AI-powered GitHub Action that reviews pull requests for **code quality, bugs, and security issues**.

## 🚀 How it Works
- Triggers on pull requests.
- Uses OpenAI API to analyze the code.
- Posts comments directly on the PR with suggestions.

## 🔑 Setup
1. Add your **OpenAI API key** to the repo secrets:
   - Go to: Repo → Settings → Secrets and variables → Actions → New repository secret
   - Name: `OPENAI_API_KEY`
   - Value: your API key (starts with `sk-...`)
2. The GitHub Action will run automatically on every pull request.

## 📄 License
MIT License
