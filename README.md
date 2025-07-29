# Chatbot Project

This project is a simple chatbot application built using Python. It integrates **Google Gemini** for generating responses and includes tools like a calculator and a greeting function.

## Features

- **Calculator**: Perform basic arithmetic calculations.
- **Greeting Function**: Greet users with a custom message.
- **Gemini Integration**: Powered by Google's Gemini for generating responses.

## Installation

### 1. Clone the repository:
```bash
git clone https://github.com/your-username/your-repo-name.git
```
### 2. Create a virtual environment:
```bash
python -m venv venv
```
### 3. Activate the virtual environment:
##### On Windows:
```bash
.\venv\Scripts\activate
```
#### On macOS/Linux:
```bash
source venv/bin/activate
```
### 4. Install dependencies:
```bash
pip install -r requirements.txt
```
Usage
### 1. Set up environment variables:
Create a .env file and add your Gemini API key:
```bash
GEMINI_API_KEY=your_api_key_here
```
### 2. Run the application:
```bash
python main.py
```
### 3. Interact with the chatbot:
You can ask the chatbot to perform calculations or have a chat. Type quit to exit.
