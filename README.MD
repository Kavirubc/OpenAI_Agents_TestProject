# OpenAI Agents

This project is a news aggregation and article generation tool that utilizes OpenAI's GPT-4o model to scrape the web for the latest news articles on a given topic, summarize them, and then write a coherent news article based on those summaries.

## Features

- **Web Scraping**: Automatically searches for and summarizes news articles related to a specified topic.
- **Article Generation**: Creates a well-structured news article in Markdown format based on the summaries obtained.
- **Environment Configuration**: Uses environment variables to securely manage API keys.

## Requirements

- Python 3.7 or higher
- `asyncio` library
- `python-dotenv` for loading environment variables
- OpenAI API key

## Setup

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Create a `.env` file in the root directory and add your OpenAI API key:
   ```plaintext
   OPENAI_API_KEY=your_openai_api_key_here
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Running the Application

To run the application, execute the following command in your terminal:
 ```python
python main.py
```




