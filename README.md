# RAG Response System

This repository contains a Jupyter Notebook (or Python script) for a Retrieval-Augmented Generation (RAG) response system. The system fetches markdown files from a GitHub repository, processes them, and provides answers based on the content.

## Prerequisites

- Python 3.x
- `pip` (Python package installer)
- Visual Studio Code with the Jupyter extension

## Setup Instructions

Follow these steps to set up and run the project:

### 1. Clone the Repository

Open up the terminal in Visual Studio Code and clone the repository to your local machine:

git clone https://github.com/ashwinknan/rag-app-v1
cd rag-app-v1

## 2. Create a Virtual Environment

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

## 3. Install Dependencies
Install the required Python packages using pip:

pip install -r requirements.txt

## 4. Set Up Environment Variables
Update your .env file with the values of the environment variables set in .env.example.

## 5. Open Jupyter Notebook in VS Code
Open Visual Studio Code.
Open the cloned repository folder (rag-app-v1).
Open the Jupyter notebook file you want to run.

## 6. Enter the Session Number
For each session, enter a unique session number. Start your session number with your name, e.g., jay0001 or shriya0001. Update the session number for each new conversation.

## 7. Enter Your Query
Replace the input_question variable with your question. You may need to specify a source if it is not provided explicitly.

## 8. For a New Question, Enter a New Session Number
Ensure that for every new question, you start a new session by updating the session number.


