Assignment Title: AI-Powered Chatbot for Supplier and Product Information
Objective:
Develop a chatbot that allows users to query a product and supplier database using natural language. The chatbot should interact with an open-source LLM and utilize LangGraph framework for agent workflows to fetch relevant information from a MySQL/PostgreSQL database and summarize the data using LLM.
Assignment Deliverables:
1. Frontend (React):
o Create a responsive web interface to interact with the chatbot.
o Provide a text input for users to enter their queries.
o Display chatbot responses in a conversational format.
o Provide a history of recent queries.
2. Backend (Python & LangGraph):
o Implement a chatbot using LangGraph and Python.
o Use LangGragh node to retrieve supplier and product information from MySQL/PostgreSQL.
o Supplier data should be summarized using LLM
o Use any open-source LLM (e.g., Hugging Face's GPT-2, GPT-3, or LLaMA 2) for summarization
3. Database (MySQL/PostgreSQL):
o Design an efficient schema for storing:
▪ Products (ID, name, brand, price, category, description, supplier ID).
▪ Suppliers (ID, name, contact info, product categories offered).
o Populate the database with sample data.
o Implement queries to fetch relevant information based on chatbot requests.
