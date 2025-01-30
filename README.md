# MultiSearch AI Agent

This project implements a Multi-Search AI Agent designed to effectively retrieve and synthesize information from various sources. It utilizes Llama 3.2 for chat generation, OpenAI's function calling mechanism for tool selection, and LangChain for agent execution.

## Features
- Diverse Search Capabilities: Integrates specialized tools for searching:
   - Wikipedia
   - Web Search (e.g., using Google Search API)
   - arXiv Research Papers
   - FAISS Vector Database (for semantic search)

- Intelligent Tool Selection: Employs OpenAI's function calling to dynamically choose the most appropriate tool(s) based on the user's query.
- Llama 3.2 Integration: Leverages the advanced text generation capabilities of Llama 3.2 to provide comprehensive and informative responses.
- LangChain Framework: Utilizes LangChain for streamlined agent creation, tool management, and execution.
- Extensible Architecture: Designed for easy addition of new search tools and customization of the agent's behavior.

## Install dependencies (replace with your actual dependencies)
- pip install -r requirements.txt
- Run the Agent: Execute the main script to interact with the agent.

## Provide Queries: 
Input your queries through the invoke function. The agent will intelligently select the appropriate tools and generate a response.

## Example
User Query: What is Machine Learning?
Tool Selection: The OpenAI function calling mechanism, guided by the Llama 3.2 model, determines which tool(s) are best suited to answer the query.
Tool Execution: The selected tool(s) are executed, retrieving relevant information.
Response Generation: The Llama 3.2 model synthesizes the retrieved information and generates a natural language response.
Output: Machine learning (ML) is a subfield of artificial intelligence (AI) that enables computers to learn from data without being explicitly programmed.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any bug fixes, feature requests, or improvements.

## License
MIT License

## Acknowledgements
Llama 3.2:1b
Ollama
Hugging Face Embeddings
LangChain
FAISS
Arxiv
