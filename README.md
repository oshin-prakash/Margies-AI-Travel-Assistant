# Margies-AI-Travel-Assistant
A Streamlit-powered AI travel assistant built using Azure OpenAI and Azure Cognitive Search. This application delivers intelligent, context-aware responses using Retrieval-Augmented Generation (RAG) to answer customer queries about Margie’s Travel services.

**✨ Features**

🔍 RAG-based search using Azure Cognitive Search vector index

🤖 Azure OpenAI Chat Completion for conversational answers

🔡 Automatic embeddings generation

🧠 Contextual multi-turn conversation

🖥️ Streamlit UI with chat-style interface

🔐 Secure environment variable configuration

⚡ Optimized with st.cache_resource for fast API client loading

**🛠️ Tech Stack**

Python

Streamlit

Azure OpenAI (Chat + Embeddings)

Azure Cognitive Search (Vector RAG)

dotenv

**Structure**

Margies-AI-Travel-Assistant/
│
├── app.py
├── README.md
├── requirements.txt
├── .env.example
└── assets/
    └── screenshot.png

🧪 requirements.txt (Use This)
streamlit
python-dotenv
openai>=1.0.0

🧩 .env.example
OPEN_AI_ENDPOINT="https://ai-hub56778191521132562128.openai.azure.com/"
OPEN_AI_KEY="94MGNzFjiy5mXwGxkrnW3zJ92YLk84z5X0BrJwSwDX6Vfj2f2wMSJQQJ99BKACfhMk5XJ3w3AAAAACOGYfYh"
CHAT_MODEL="gpt-4o"
EMBEDDING_MODEL="text-embedding-ada-002"
SEARCH_ENDPOINT="https://aisearch56778191.search.windows.net"
SEARCH_KEY="GCUzefHDs8Bvn0JKJupHX5XEtzb6qu6VYl7kstef6CAzSeD4JkTP"
INDEX_NAME="brochures-index"



