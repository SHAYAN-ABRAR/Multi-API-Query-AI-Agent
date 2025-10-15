# Multi-API Query AI Agent

**Multi-API Query AI Agent** is an intelligent assistant designed to process user queries and retrieve real-time information from multiple APIs. The assistant can fetch data such as:

- Weather information
- Currency exchange rates
- Random facts
- Current time across different time zones

The agent integrates Groq's LLM and LangGraph to handle multiple queries, making it a versatile and efficient solution for various information needs.

## Features

- **Weather Info**: Get current weather details for any city.
- **Currency Exchange**: Retrieve the latest exchange rates between different currencies.
- **Random Facts**: Fetch interesting and fun facts from various categories.
- **Current Time**: Get the current time in any given timezone.
- **Tool Integration**: Multiple tools are dynamically invoked based on the user's request.

## How it Works

The agent utilizes multiple APIs and Groq's LLM to process and handle queries:

1. **User Input**: User provides a query (e.g., "What's the weather in London?").
2. **Query Processing**: The LLM decides whether to call an external API or respond directly.
3. **API Calls**: Based on the query, the agent fetches data from relevant APIs.
4. **Response**: The processed data is returned to the user.


