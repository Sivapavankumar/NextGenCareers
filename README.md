# NextGenCareers
🔍 NextGenCareers – AI-Powered Career Guidance Chatbot
NextGenCareers is an AI-based chatbot that assists students and professionals with personalized career guidance. It helps users explore job roles, skills, certifications, and online resources based on their interests using advanced AI and graph-based knowledge retrieval.

# Features

Retrieval-Augmented Generation (RAG) with LangChain

Real-time responses powered by OpenAI GPT (gpt-3.5-turbo)

Hybrid search using Neo4j AuraDB for structured graph data

Streamlit frontend for interactive user experience

Entity extraction for smart understanding of career questions

# Technologies Used
Python

LangChain

Streamlit

Neo4j AuraDB

OpenAI API

GitHub + Colab

# Setup Instructions
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/Sivapavankumar/NextGenCareers.git
cd NextGenCareers
2. Install Required Libraries
bash
Copy
Edit
pip install langchain langchain-community langchain-openai
pip install neo4j streamlit yfiles-jupyter-graphs
pip install tiktoken ctransformers
3. Set Environment Variables
Update and export your API keys:

python
Copy
Edit
import os

os.environ["OPENAI_API_KEY"] = "your_openai_key"
os.environ["NEO4J_URI"] = "your_neo4j_uri"
os.environ["NEO4J_USERNAME"] = "your_neo4j_username"
os.environ["NEO4J_PASSWORD"] = "your_neo4j_password"
4. Run the Chatbot
bash
Copy
Edit
streamlit run app.py
The Streamlit app will open in your browser. Ask your career questions!

# Try Sample Questions
“What are the best certifications for a DevOps engineer?”

“Which platforms can I use to learn machine learning?”

“Suggest a path to become a cloud architect.”

# Contributors
Siva Pavan Kumar Chava

Anjali Erupaka

Kotesh Rekha

