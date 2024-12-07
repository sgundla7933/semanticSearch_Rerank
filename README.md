# Enhanced Search and Reranking with Cohere and Weaviate

This project demonstrates how to integrate **Cohere** and **Weaviate** to build an efficient search system. By combining dense retrieval, keyword search, and reranking, the system improves the relevance and accuracy of search results for complex queries.

---

## Features

1. **Dense Retrieval**: Retrieve semantically relevant documents using Weaviate's vector-based search.
2. **Keyword Search**: Retrieve results based on specific properties.
3. **Reranking**: Use Cohere's NLP models to refine search results and reorder them by relevance.
4. **Modular Design**: Reusable and well-structured utility functions.

---

## Prerequisites

1. **Python** (3.7 or later)
2. **API Keys**:
   - Cohere API Key
   - Weaviate API Key and URL

3. Install the required libraries:
   pip install cohere weaviate-client python-dotenv
**
Getting Started**
**1. Environment Setup**
Create a .env file in the project root and add the following:

COHERE_API_KEY=your_cohere_api_key
WEAVIATE_API_KEY=your_weaviate_api_key
WEAVIATE_API_URL=your_weaviate_url
**Install the dependencies:**

pip install -r requirements.txt
**2. Project Structure**

project/
├── main.py               # Main script
├── utils.py              # Utility functions for search and retrieval
├── .env                  # Environment variables
├── README.md             # Project documentation
└── requirements.txt      # Required libraries
**3. Running the Code**
Run the main.py file to execute the search and reranking pipeline:

python main.py
Goog;e slide presentation - https://docs.google.com/presentation/d/1ZCBzty0B3-VT0myroZakQ3SpJJQSusWSCIC8tpxzV3g/edit?usp=sharing

