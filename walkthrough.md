# Local AI/LLM Development Environment Setup Guide

This guide outlines the steps to set up a comprehensive local development environment for AI and LLM projects.

## 1. Windsurf IDE Installation
Windsurf is a specialized IDE designed for AI development:
1. Download Windsurf from the official website -> https://codeium.com/
2. Install and follow the setup wizard
3. Configure your preferred settings for AI development

## 2. Ollama Setup
Ollama allows you to run LLMs locally:
1. Visit [Ollama's website](https://ollama.ai/)
2. Download and install Ollama for your system
3. Basic usage:
   ```bash
   # Pull a model
   ollama pull llama2
   # Run the model
   ollama run llama2
   ```

## 3. LangSmith Integration
LangSmith helps debug and monitor LLM applications:
1. Sign up at [LangSmith](https://smith.langchain.com/)
2. Set up environment variables:
   ```bash
   export LANGCHAIN_TRACING_V2=true
   export LANGCHAIN_API_KEY=your_api_key
   export LANGCHAIN_PROJECT=your_project
   ```

## 4. OpenAI API Setup
1. Create an account at [OpenAI](https://platform.openai.com/)
2. Generate an API key from your dashboard
3. Set up environment variable:
   ```bash
   export OPENAI_API_KEY=your_api_key
   ```

## 5. Streamlit Installation
Streamlit is perfect for creating AI web applications:
1. Install Streamlit:
   ```bash
   pip install streamlit
   ```
2. Create a new app:
   ```bash
   touch app.py
   ```
3. Run your app:
   ```bash
   streamlit run app.py
   ```

## Development Best Practices
1. Use virtual environments for project isolation
2. Keep API keys secure and never commit them to version control
3. Monitor API usage and costs
4. Test LLM applications thoroughly
5. Document prompts and model behaviors

## Additional Resources
- [Windsurf Documentation](https://codeium.com/windsurf)
- [Ollama GitHub](https://github.com/ollama/ollama)
- [LangChain Documentation](https://python.langchain.com/docs/get_started/introduction)
- [OpenAI API Documentation](https://platform.openai.com/docs)
- [Streamlit Documentation](https://docs.streamlit.io)