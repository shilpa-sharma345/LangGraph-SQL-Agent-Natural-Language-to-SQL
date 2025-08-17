# LangGraph-SQL-Agent-Natural-Language-to-SQL
A Streamlit-based chatbot that enables users to interact with an **SQLite** or **MySQL** database using **natural language queries**.  
The system uses **LangChain** for SQL agent functionality and **Groq's LLaMA-4 model** for intelligent query interpretation.

##  Features

-  Natural language → SQL translation via **LangChain**.
-  Powered by **Groq LLMs** (`meta-llama/llama-4-scout-17b-16e-instruct`).
-  Connects to **SQLite (`student.db`)** or **MySQL** databases.
-  **Interactive chatbot UI** built with **Streamlit**.
-  Secure sidebar for API keys & DB credentials.
-  Clear chat history anytime.

Usage

Run the app

streamlit run app.py


In the Streamlit sidebar:

Choose SQLite (student.db) or enter your MySQL credentials.

Enter your Groq API key.

Start chatting with your database in natural language!

Example

Query:Show me all students who scored more than 80
SQL executed:SELECT * FROM STUDENT WHERE MARKS > 80;
Response (from sample DB):Raj | Data Science | B | 91
Ravi | DevOps | C | 80
Aryan | Data Science | A | 100
boy | DevOps | B | 95


 Technologies Used

Streamlit – interactive UI

LangChain – SQL agent

Groq – LLaMA-4 model inference

SQLite / MySQL – backend database

SQLAlchemy – DB connection
