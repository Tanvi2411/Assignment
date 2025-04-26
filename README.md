
# AI Agent-based Deep Research System

## Overview

This project implements a Deep Research AI Agentic System that crawls the web for online information gathering. The system is designed with **two agents**:
- **Researcher Agent**: Gathers data by making web searches.
- **Drafter Agent**: Drafts an answer based on the collected data.

The system uses **SerpAPI** for performing web searches and **Pydantic** for managing the state and data flow. The project is built in Python.

## Features
- Search the web using **SerpAPI** for specific queries.
- Organize search results with titles, URLs, and snippets.
- Draft an answer based on the search results.
- Easily extendable with additional agents and functionality.

## Requirements

- Python 3.x
- External Libraries:
  - `requests` (for making HTTP requests)
  - `pydantic` (for data validation)

You can install the required libraries using `pip`:

```bash
pip install requests pydantic
```
