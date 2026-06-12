# LangSum 🦜

A Streamlit app that summarizes content from **YouTube videos** or **websites** using LangChain and Groq's LLaMA 3.1 model.

## Features

- 🎥 Summarize YouTube video transcripts
- 🌐 Summarize content from any website URL
- ⚡ Powered by Groq's `llama-3.1-8b-instant` for fast inference
- 🔒 Bring your own Groq API key (entered securely in the sidebar)

## Demo

Enter a YouTube or website URL, click **Summarize**, and get a concise 300-word summary of the content.

## Tech Stack

- [Streamlit](https://streamlit.io/) — Web interface
- [LangChain](https://www.langchain.com/) — Summarization chain
- [Groq](https://groq.com/) — LLM inference (LLaMA 3.1 8B Instant)
- [YoutubeLoader](https://python.langchain.com/) / [UnstructuredURLLoader](https://python.langchain.com/) — Content loaders

## Installation

1. Clone the repository
```bash
   git clone https://github.com/your-username/langsum.git
   cd langsum
```

2. Create a virtual environment and install dependencies
```bash
   pip install -r requirements.txt
```

3. Run the app
```bash
   streamlit run app.py
```

## Usage

1. Get a free Groq API key from [console.groq.com](https://console.groq.com)
2. Enter your API key in the sidebar
3. Paste a YouTube or website URL
4. Click **"Summarize the Content from YT or Website"**
5. View the generated summary

## Requirements
