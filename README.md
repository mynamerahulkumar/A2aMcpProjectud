# Multi Agent-Financial Intelligent system with MCP and A2A combined
## Setup and Run with uv



https://www.datacamp.com/tutorial/python-uv

or 

**Install [uv](https://github.com/astral-sh/uv) (if not already installed):**
   ```sh
   pip install uv




Install dependencies:

uv pip install -r requirements.txt

Set up environment variables:

Make sure your .env file contains your OpenAI API key (already present).

Run the MCP servers and agents (each in a separate terminal):

uv pip run python duckduckgoMcpServer.py

uv pip run python duduckgoAgentA2AServer.py

uv pip run python yfinanceA2AServer.py

Run the Stock Financial Assistant or interactive client:

uv pip run python stockfinancialassistant.py

uv pip run python maininteractiveclient.py



