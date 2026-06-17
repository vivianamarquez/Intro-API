# Intro to APIs

A short beginner-friendly introduction to APIs with Python notebooks.

## Notebooks

1. `01_What_Is_an_API.ipynb` - requests, responses, status codes, and JSON
2. `02_URLs_Endpoints_and_Methods.ipynb` - URLs, endpoints, query parameters, and functions
3. `03_API_Keys_and_OpenAI_API.ipynb` - `.env` files, API keys, and a first OpenAI API call

## Setup

Install the packages used in the notebooks:

```bash
pip install requests python-dotenv
```

For notebook 3, create a local `.env` file with:

```text
OPENAI_API_KEY=your-key-here
```

Do not commit `.env`. Use `.env.example` as the shareable template.

## Run

Open the notebooks in Jupyter or VS Code and run them in order.
