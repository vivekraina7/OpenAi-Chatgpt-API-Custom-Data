# OpenAi-Chatgpt-API-Custom-Data
# Conversational Chatbot using OpenAI ChatGPT API

This project demonstrates the development of a conversational chatbot using the OpenAI ChatGPT API. The chatbot is trained on a custom dataset that is scraped from various websites, allowing it to generate responses based on the information obtained.
![image](https://github.com/vivekraina7/OpenAi-Chatgpt-API-Custom-Data/assets/87175291/dbcb873b-9c82-467e-abea-60d4e4de35ab)

## Features

- Utilizes the OpenAI ChatGPT API to generate conversational responses
- Scrapes relevant data from websites to create a custom dataset
- Supports interactive conversations with users
- Seamless integration with the command line interface

## Prerequisites

Before running the chatbot, ensure you have the following:

- OpenAI API key: Sign up for an API key from OpenAI and add it to the project configuration file.
- Python 3: Make sure you have Python 3 installed on your system.
- Required libraries: Install the necessary libraries by running the command `pip install -r requirements.txt`.

## Usage

1. Set up the environment:
   - Clone this repository: `git clone https://github.com/vivekraina7/OpenAi-Chatgpt-API-Custom-Data.git`
   - Install dependencies: `pip install -r requirements.txt`
   - Add your OpenAI API key to the configuration file (`Openai_Chatgpt_API_app.ipynb`).

2. Scrape data:
   - Add your desired website to the url section in the code
   - The scraped data will be saved to a file in the desired format (e.g., CSV, JSON).

3. Train the chatbot:
   - Prepare the dataset for training by processing and cleaning the scraped data.
   - Use the OpenAI API to train the chatbot on your custom dataset.
   - Save the trained model for future use.

4. Run the chatbot:
   - Execute the chatbot script: `Openai_Chatgpt_API_app.ipynb`
   - Start an interactive conversation with the chatbot via the command line interface or the Gradio webapp.
   - Enjoy chatting with the conversational chatbot powered by the OpenAI ChatGPT API!

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request.
