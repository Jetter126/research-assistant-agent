# Developer Tools Research Assistant

## Overview

The Developer Tools Research Assistant is a Python-based AI agent designed to extensively research and analyse various developer tools, their key features, and their alternatives. Using Firecrawl for data crawling, LangGraph to assemble a stateful workflow, and structured outputs to deliver clean, formatted data, the agent extracts tools from the internet, researches them, and provides the user with a detailed analysis.

### Key Features

The agent provides data related to tools'

- Pricing model
- Licensing
- Compatible tech stack
- Competitors
- API availability
- Language support
- Integration capabilities
- Developer ratings

## Quick Start Instructions

- Create a `.env` file in the root directory containing your Anthropic API key, e.g.:
  `ANTHROPIC_API_KEY=your_anthropic_api_key_here`
- Navigate to the project's root directory in your terminal and run `py main.py`
- When prompted, enter the name of the tool you want to research.
