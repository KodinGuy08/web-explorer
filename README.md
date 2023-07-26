## Web Explorer

This is a lightweight app using the [Web Research Retriever](https://github.com/langchain-ai/langchain/pull/8102).

You only need to supply a few things.

In `settings()` function, supply:

* Search: Select the search tool you want to use (e.g., GoogleSearchAPIWrapper). 
* Vectorstore: Select the vectorstore and embeddings you want to use (e.g., Chroma, OpenAIEmbeddings).
* Select the LLM you want to use (e.g., ChatOpenAI).

Set all API keys, e.g.:

export GOOGLE_API_KEY=xxx
export GOOGLE_CSE_ID=xxx
export OPENAI_API_KEY=xxx

Run:

```
streamlit run web_explorer.py
```

Example output:
![example](https://github.com/langchain-ai/web-explorer/assets/122662504/b2c9d671-1188-4451-b73f-37f9a321b822)
