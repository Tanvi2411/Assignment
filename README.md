
# Deep Research Simulation Agent

This project simulates the process of gathering and summarizing online research for a given query. It uses mock functions to simulate web searches and generate detailed summaries based on the query.

## Features

- **Simulated Web Search**: `mock_tavily_search` function simulates a web search for a given query and returns results from multiple sources like academic papers, news, and industry insights.
- **Research Summary Generation**: `mock_answer_agent_fn` summarizes the research findings and creates a detailed, structured answer.
- **Modular Workflow**: The research process is split into nodes (`research_node` and `answer_node`) that handle information gathering and answer generation.
- **Comprehensive Answer**: `run_deep_research` orchestrates the entire process, generating a final summary of the research findings.

## Files

- **mock_tavily_search**: Simulates search results by generating mock research data.
- **mock_answer_agent_fn**: Generates a detailed summary using the simulated research results.
- **research_node**: Calls `mock_tavily_search` to gather information for the query.
- **answer_node**: Uses the gathered information to draft a final, structured answer.
- **run_deep_research**: The main function that processes the research and returns a complete summary.

## Usage

1. Define a query for which you want to gather and summarize research:
   ```python
   query = "AI in agriculture 2025"
   ```

2. Run the research process using the `run_deep_research` function:
   ```python
   result = run_deep_research(query)
   ```

3. The `result` will contain a detailed summary of the research findings for the given query.

