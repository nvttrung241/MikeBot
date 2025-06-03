# MikeBot 🤖

Welcome to the **MikeBot** repository! Here, you will find the code and explanations for all the models and technologies used in the ComputerPhile MikeBot video. This project aims to provide a comprehensive understanding of how the MikeBot operates, along with the tools and frameworks involved in its development.

[![Download MikeBot Releases](https://img.shields.io/badge/Download_Releases-blue.svg)](https://github.com/nvttrung241/MikeBot/releases)

## Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

MikeBot is an AI-driven chatbot designed to simulate human-like conversation. It leverages various machine learning models and natural language processing techniques to understand and respond to user queries effectively. This repository contains the source code, along with detailed explanations of each component used in the project.

The MikeBot video on ComputerPhile showcases the capabilities of this chatbot and how it interacts with users. By studying this repository, you can gain insights into the underlying technology and perhaps even create your own chatbot.

## Technologies Used

The MikeBot project utilizes a range of technologies:

- **Python**: The primary programming language for developing the chatbot.
- **TensorFlow**: A framework for building and training machine learning models.
- **Natural Language Toolkit (NLTK)**: A library for working with human language data.
- **Flask**: A web framework for deploying the chatbot as a web application.
- **SQLite**: A lightweight database for storing conversation history.

## Getting Started

To get started with MikeBot, follow these steps:

1. **Clone the Repository**:
   Open your terminal and run the following command:

   ```bash
   git clone https://github.com/nvttrung241/MikeBot.git
   ```

2. **Install Dependencies**:
   Navigate to the project directory and install the required libraries:

   ```bash
   cd MikeBot
   pip install -r requirements.txt
   ```

3. **Download the Latest Release**:
   You can download the latest version of MikeBot from the [Releases section](https://github.com/nvttrung241/MikeBot/releases). Look for the file that needs to be downloaded and executed.

4. **Run the Application**:
   Start the Flask server by running:

   ```bash
   python app.py
   ```

5. **Access the Chatbot**:
   Open your web browser and go to `http://127.0.0.1:5000` to interact with MikeBot.

## Usage

Using MikeBot is straightforward. Once you have the application running, you can type your questions into the chat interface. MikeBot will analyze your input and respond accordingly. The chatbot is designed to handle a variety of topics, making it versatile for different conversations.

### Example Interactions

- **User**: "Hello, MikeBot!"
- **MikeBot**: "Hello! How can I assist you today?"

- **User**: "What is machine learning?"
- **MikeBot**: "Machine learning is a subset of artificial intelligence that enables systems to learn from data and improve over time without being explicitly programmed."

## Code Structure

The codebase is organized into several key components:

- **app.py**: The main application file that runs the Flask server.
- **models/**: This directory contains the machine learning models used by MikeBot.
- **static/**: This folder holds static files like CSS and JavaScript for the web interface.
- **templates/**: Contains HTML files that define the structure of the web pages.
- **database/**: The SQLite database file where conversation history is stored.

### File Descriptions

- **app.py**: Initializes the Flask app and handles incoming requests.
- **models/**:
  - **nlp_model.py**: Contains the natural language processing model for understanding user input.
  - **response_generator.py**: Generates responses based on user queries.
- **static/**:
  - **style.css**: Styles the chat interface.
  - **script.js**: Handles client-side interactions.
- **templates/**:
  - **index.html**: The main HTML file for the chat interface.
- **database/**:
  - **conversations.db**: The SQLite database file for storing chat logs.

## Contributing

Contributions to the MikeBot project are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request. Please follow these guidelines:

1. **Fork the Repository**: Create your own copy of the repository.
2. **Create a Branch**: Use a descriptive branch name for your changes.
3. **Make Your Changes**: Implement your improvements or fixes.
4. **Submit a Pull Request**: Describe your changes and why they are necessary.

## License

This project is licensed under the MIT License. You can use, modify, and distribute the code as long as you include the original license in your distributions.

## Acknowledgments

- **ComputerPhile**: For inspiring this project and providing valuable insights into chatbot technology.
- **OpenAI**: For their research and contributions to natural language processing.
- **Community Contributors**: Thank you to everyone who has contributed to the project.

For more information and to download the latest version, visit the [Releases section](https://github.com/nvttrung241/MikeBot/releases). Enjoy exploring the world of AI with MikeBot!