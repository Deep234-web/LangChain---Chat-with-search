# 🔎 LangChain - Chat with Search

This is a simple chatbot that allows users to interact with various search APIs using LangChain and Streamlit. The chatbot can retrieve information from Arxiv, Wikipedia, and DuckDuckGo Search, utilizing a conversational agent powered by Groq's LLM (Llama3-8b-8192).

## Features

- Interactive chatbot interface built with Streamlit
- Powered by LangChain and Groq's LLM (Llama3-8b-8192)
- Supports querying from Arxiv, Wikipedia, and DuckDuckGo Search
- Real-time response streaming and callback handling with `StreamlitCallbackHandler`

## Installation

### Prerequisites

- Python 3.8 or higher
- Install required dependencies

### Environment Variables
Make sure to create a .env file in the root directory with your Groq API key:
GROQ_API_KEY=your_groq_api_key

### Running the App
To run the app, use the following command:

### streamlit run app.py

This will open the Streamlit app in your browser.

### Usage
Enter your Groq API key in the sidebar.
Chat with the assistant by typing questions in the chat box. You can ask about academic papers, Wikipedia content, or general search queries.
The assistant will respond with the best available results from Arxiv, Wikipedia, or DuckDuckGo.


### Tools Used
ArxivAPIWrapper: Retrieves information from Arxiv academic papers.
WikipediaAPIWrapper: Retrieves content from Wikipedia.
DuckDuckGoSearchRun: Retrieves results from DuckDuckGo Search.


### Future Improvements
Add more APIs or data sources.
Implement more advanced features like document summarization or citation generation.
Add user authentication for personalized searches.
