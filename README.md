##﻿# cold-email-generator


## Description

The Cold Email Generator is a Streamlit-based web application that automatically generates personalized cold emails for job applications. It uses AI to analyze job postings, match them with your portfolio, and create tailored email content.

## Features

- Web scraping of job postings
- AI-powered job description analysis
- Automatic skill matching with your portfolio
- Personalized cold email generation
- User-friendly web interface

## Installation

1. Clone the repository:
2. Install the required dependencies:
3. Set up your environment variables:
Create a `.env` file in the root directory and add your API key:

## Usage

1. Run the Streamlit app:

2. Open your web browser and go to `http://localhost:8501`

3. Enter the URL of a job posting in the input field and click "Submit"

4. The app will generate a personalized cold email based on the job description and your portfolio

## Project Structure

- `app/`
- `main.py`: Main Streamlit application
- `chains.py`: LLM chain definitions for job extraction and email generation
- `portfolio.py`: Portfolio management and skill matching
- `utils.py`: Utility functions
- `resource/`: Contains portfolio data
- `vectorstore/`: Chroma vector database for efficient skill matching

## Dependencies

- Streamlit
- LangChain
- Groq
- ChromaDB
- pandas

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

## Acknowledgements

- [Streamlit](https://streamlit.io/)
- [LangChain](https://python.langchain.com/)
- [Groq](https://www.groq.com/)
- [ChromaDB](https://www.trychroma.com/)
"""

