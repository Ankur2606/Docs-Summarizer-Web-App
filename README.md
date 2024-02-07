# Text Summarizer App

## Overview

This text summarizer app is a simple web application built using various tools and technologies to provide concise summaries of long texts. It leverages the power of the Hugging Face Inference API for natural language processing.

## Tech Stack

### API Platform
- [Postman](https://www.postman.com/): Used as the API platform for testing and development.

### Code Editor/Deployment Tool
- [Replit](https://replit.com/): Chosen as the code editor and deployment tool for the ease of use and quick deployment.

### Back End
- [Node.js](https://nodejs.org/): The server-side JavaScript runtime.
- [Express](https://expressjs.com/): A minimal and flexible Node.js web application framework.
- [Hugging Face Inference API](https://huggingface.co/): Utilized for natural language processing and text summarization.

### Front End
- HTML: Markup language for structuring the web page.
- CSS: Styling language for enhancing the visual presentation.
- JavaScript: Used for client-side scripting and interacting with the server.

## Usage

1. Paste your text into the input area.
2. Click the "Summarize" button.
3. View the summarized text in the output area.

## API Status and Key Setup

### Checking API Status

Before using the app, ensure that the Hugging Face Inference API is accessible. You can use Postman to check the API status.

1. Open Postman.
2. Create a new request.
3. Set the request type to `GET`.
4. Enter the API endpoint URL: [Endpoint URL](https://api-inference.huggingface.co/models/facebook/bart-large-cnn)
5. Click "Send" to check the API status. Ensure that you receive a successful response.

### Setting Your Private Hugging Face API Key

To use the Hugging Face Inference API, you need to set up your private API key.

1. Visit the [Hugging Face website](https://huggingface.co/) and create an account.
2. After logging in, go to your [API settings](https://huggingface.co/settings/api).
3. Copy your API key.
4. In your project directory, create a `.env` file.
5. Add the following line to your `.env` file, replacing `YOUR_API_KEY` with your actual API key: `HUGGINGFACE_API_KEY=YOUR_API_KEY`

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-text-summarizer-app.git
   ```
   
2. Navigate to the project directory:
   ```bash
    cd your-text-summarizer-app
   ```
3. Install dependencies:
   ```bash
    npm install
   ```
3. Start the server:
   ```bash
    npm start
   ```
4. Open the app in your browser:
   ```bash
    http://localhost:3000
   ```

## Contribution Guidelines

We welcome contributions to enhance the functionality and features of this text summarizer app. If you're interested in contributing, please follow these guidelines:

### Getting Started

1. Fork the repository on GitHub by clicking on the "Fork" button.
2. Clone your fork locally:

   ```bash
   https://github.com/Ankur2606/Docs-Summarizer-Web-App.git
```
