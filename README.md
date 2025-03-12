# Browser-Use Hello World

A simple example of using browser-use to automate browser tasks with AI.

## Setup

1. Install the requirements:
   ```
   pip install browser-use langchain-openai python-dotenv
   ```

2. Install Playwright:
   ```
   playwright install
   ```

3. Add your OpenAI API key to the `.env` file:
   ```
   OPENAI_API_KEY=your_openai_api_key_here
   ```

## Running the example

Run the main script:
```
python main.py
```

This will open a browser window and use an AI agent to compare the prices of GPT-4o and DeepSeek-V3.

## UI Demo

To run the Gradio UI demo:
```
pip install gradio
python -m browser_use.ui
```# browserUseExp
