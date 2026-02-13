# AI-Data_Analysis_Agent
 AI Data Analysis Agent that lets users analyze CSV and Excel files using natural language queries. Powered by GPT-4o and DuckDB, this tool translates plain English questions into SQL queries, making data analysis accessible to everyone – no SQL expertise required.

# AI Data Analysis Agent

Upload a CSV or Excel file and ask questions in natural language.
The system converts your question into SQL using GPT-4o and runs it using DuckDB.

## Run Locally

python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
streamlit run AI-Data_Analysis_Agent.py
