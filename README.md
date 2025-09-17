# Simple LLM API Web Form

A minimal, self-contained HTML page that sends a prompt to the OpenAI API and displays the response.

## How to Run

1.  **Get an API Key:** Sign up for an account at [OpenAI's platform](https://platform.openai.com/) and generate an API key.
2.  **Edit the File:** Open `index.html` in a code editor. Find the line `const API_KEY = 'sk-...';` and replace `sk-...` with your actual API key.
3.  **Run it:** Open the `index.html` file directly in your web browser.

## Live Demo

A live demo cannot be fully provided because exposing the API key in public front-end code is a security risk. To see it work, you must run it locally with your own key.

## How It Works

- The user enters a prompt in the text box and clicks "Send".
- The script sends a request to the OpenAI API (`gpt-3.5-turbo` model).
- The AI's response is displayed on the page below the form.

**Note:** This is a client-side-only implementation for simplicity. In a real-world application, the API key would be secured on a backend server to prevent theft and misuse.