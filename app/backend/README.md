# Backend

This directory contains the backend services for the Azure Search OpenAI Demo application.

## Structure

- `api/` - API endpoints and business logic
- `services/` - Integration with Azure services (Search, OpenAI, etc.)
- `utils/` - Utility functions and helpers

## Requirements

- Python 3.8+
- [pip](https://pip.pypa.io/en/stable/)

## Setup

1. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

2. Set environment variables:
    - `AZURE_SEARCH_KEY`
    - `AZURE_SEARCH_ENDPOINT`
    - `OPENAI_API_KEY`
    - (See `.env.example` for details)

3. Run the backend server:
    ```bash
    uvicorn main:app --reload
    ```

## Features

- REST API for search and chat
- Integration with Azure Cognitive Search
- Integration with OpenAI GPT models

## License

MIT License