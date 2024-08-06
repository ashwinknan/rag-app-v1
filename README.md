# RAG Response System

This repository contains a Jupyter Notebook (or Python script) for a Retrieval-Augmented Generation (RAG) response system. The system fetches markdown files from a GitHub repository, processes them, and provides answers based on the content.

## Prerequisites

- Python 3.x
- `pip` (Python package installer)
- Jupyter Notebook (if using a Jupyter Notebook)

## Setup Instructions

Follow these steps to set up and run the project:

### 1. Clone the Repository

Open up the terminal. Clone the repository to your local machine:

git clone https://github.com/ashwinknan/chatbotv1.git
cd chatbotv1

### 2. Clone the Repository
Setup a virtual environment to manage dependencies:

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

### 3. Install Dependencies
Install the required Python packages using pip:

pip install -r requirements.txt

### 4. Set Up Environment Variables
Update your .env file with the values of the environment variables set in .env.example

### 5. Enter the session number
For each session enter the session number. Let your session number start with your name - E.g jay0001 or shriya0001
For each new conversation, update the session number

### 6. Enter your query in the input_question
Replace this with your question. You may have to ask it for a source if it does not provide that to you explicitly. 

### 7. For a new question, enter a new session number 

