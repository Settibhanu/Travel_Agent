# Watsonx.ai Travel Agent

This project is a Jupyter notebook that demonstrates how to build a conversational travel agent using IBM's watsonx.ai, LangGraph, and a suite of integrated tools. The agent can answer travel-related questions by leveraging tools like Google Search, Wikipedia, and a weather API.

## Features

*   **Conversational AI:** A friendly travel buddy interface.
*   **Powered by watsonx.ai:** Uses IBM's powerful foundation models for natural language understanding and generation.
*   **LangGraph Integration:** Built on the LangGraph framework for creating robust and stateful AI agents.
*   **Tool-Augmented:** The agent can use the following tools to answer questions:
    *   Google Search
    *   Wikipedia
    *   Weather
    *   DuckDuckGo
    *   Web Crawler
*   **Model:** Utilizes the `mistralai/mistral-large` model.

## Requirements

*   Python 3.10+
*   `langchain_ibm`
*   `ibm_watsonx_ai`
*   `langgraph`
*   `requests`
*   `jupyter`

## Setup & Usage

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2.  **Install dependencies:**
    ```bash
    pip install langchain_ibm ibm_watsonx_ai langgraph requests jupyter
    ```

3.  **Open the Jupyter notebook:**
    ```bash
    jupyter notebook notebook_Travel_Agent-wxnotebook__da__1igj2z56u0.ipynb
    ```

4.  **Provide API Key:** When you run the cell under the "watsonx API connection" section, you will be prompted to enter your IBM Cloud API key.

5.  **Run the cells:** Execute the notebook cells sequentially.

6.  **Ask a question:** In the final cell, you will be prompted to ask a question. The agent will use its tools to find an answer and respond.

## License

This project is licensed under the ILAN License. See the notebook for more details.
