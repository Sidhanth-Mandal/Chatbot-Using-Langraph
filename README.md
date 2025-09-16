# 💬 LangGraph Chatbot (Gemini + Streamlit)

A multi-threaded conversational chatbot built using **LangGraph** and **Streamlit**, powered by **Google Gemini API** as the LLM backend.  
Each conversation thread is saved in a **SQLite** database for persistent chat history.

---

## ⚙️ How It Works
- Uses **LangGraph** to build a state graph for conversation flow
- Stores message history and threads using **SqliteSaver**
- Gemini API (via `langchain-google-genai`) is used as the chat model
- **Streamlit** provides an interactive chat UI
- **.env** file is used for secure API key management

---

## 🏗 Tech Stack
- LangGraph  
- LangChain  
- Google Gemini API  
- Streamlit  
- SQLite  
- Python dotenv

---

## 🚀 Usage
```bash
# install dependencies
pip install -r requirements.txt

# set your Gemini API key in .env
echo "GEMINI_KEY=AIza-your_api_key_here" > .env

# run the app
streamlit run frontend.py
