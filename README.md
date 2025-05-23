# Math_Problem_Solver

Text to Math Problem Solver and Data Search Assistant
This Streamlit application combines the power of large language models and external data tools to help users solve mathematical problems and retrieve factual information in real time. Powered by Groq's Gemma2-9b-It model, it provides logical, point-wise explanations for math-related questions and offers intelligent search assistance using Wikipedia.

Description
The app acts as an intelligent assistant that can:

Interpret and solve natural language math problems

Retrieve information from Wikipedia on various topics

Provide step-by-step logical reasoning for complex queries

It utilizes multiple tools within a LangChain agent framework to offer seamless integration of arithmetic processing and external data search, wrapped in a clean and interactive interface.

How It Works
Users input their Groq API key in the sidebar to activate the model.

A natural language question is entered into the text area.

When the user clicks the button, the app:

Determines whether the question requires mathematical computation, logical reasoning, or a search query.

Routes the query to the appropriate tool:

A math chain for solving equations

A reasoning chain for logical breakdowns

Wikipedia search for factual queries

The agent compiles the response using the appropriate tools and presents the result with clear formatting and detailed explanation.

The app uses LangChain’s agent-based framework with tools like LLMMathChain, WikipediaAPIWrapper, and custom reasoning prompts, making it an effective hybrid solution for both numerical and informational tasks.

