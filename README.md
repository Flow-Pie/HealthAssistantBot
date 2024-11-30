# HealthBot EVE: Your Personal Health and Wellness Assistant

## Features
HealthBot EVE is a comprehensive, intelligent chatbot designed to provide health and wellness advice, facilitate mathematical evaluations, and manage user interactions. It integrates various capabilities into one seamless platform:

- **Health and Wellness Advice:** EVE provides expert health tips and answers to health-related questions, empowering users to make informed decisions about their well-being.
  
- **Mathematical Evaluation:** EVE can evaluate mathematical expressions and return accurate results, offering additional functionality for users needing quick calculations.
  
- **User Interaction:** EVE handles common user commands, including greetings, farewells, and exit commands.
  
- **Help Command:** Users can access a detailed help message outlining available commands, ensuring they can make full use of EVE’s features.
  
- **Session Management:** EVE allows users to manage their session, including clearing chat history and navigating to login or registration pages.

## System Requirements
Before getting started with EVE, ensure you meet the following system requirements:

- **Python:** Version 3.6 or higher
- **Dependencies:**
  - Flask (for web framework)
  - ChatterBot (for chatbot functionality)
  - NLTK (Natural Language Toolkit for processing language data)
  - SymPy (for symbolic mathematics)
- **Additional Files:**
  - A `knowledge_base.json` file containing structured health-related training data.

## Installation Guide

### Clone the Repository
Start by cloning the repository to your local machine:

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
Set Up a Virtual Environment
Create a virtual environment to manage dependencies:

bash
Copy code
python -m venv venv
Activate the virtual environment:

On Windows:
bash
Copy code
venv\Scripts\activate
On macOS/Linux:
bash
Copy code
source venv/bin/activate
Install Dependencies
Install the required packages by running the following command:

bash
Copy code
pip install -r requirements.txt
Ensure that your requirements.txt includes the following libraries:

Copy code
Flask
ChatterBot
nltk
sympy
Download NLTK Data
EVE relies on the NLTK library for natural language processing. Run the following commands to download necessary NLTK data:

python
Copy code
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('averaged_perceptron_tagger')
Prepare the Knowledge Base
Ensure you have a knowledge_base.json file in the root directory of the project. This file should contain structured training data in the following format:

json
Copy code
{
    "training_data": [
        {"question": "What are some tips for staying healthy?", "answer": "Here are some tips..."},
        {"question": "How can I lose weight?", "answer": "Try these strategies..."}
    ]
}
Running the Application
Once everything is set up, run the application with the following command:

bash
Copy code
python eve.py
The application will be available at http://localhost:5000.

User Guide
Welcome to EVE, your personal health and wellness assistant. EVE is designed to help you with health-related questions and provide useful, expert advice on a variety of topics.

Getting Started
Open the chat interface in your browser at [your chatbot URL] (e.g., http://localhost:5000).
Type your message in the input box and click "Send" to begin interacting with EVE.
Basic Commands
Asking Questions: Type any health-related question directly in the chat, and EVE will respond with information from the knowledge base.

Exiting the Chat: To end the chat session, type any of the following: 'stop', 'exit', 'quit', or 'bye'.

Help Command: Type 'help' to display a list of commands and instructions on how to use EVE.

Special Features
EVE supports a variety of interactions, including:

Greetings: EVE will respond to common greetings such as "hello", "hi", or "hey".

Farewells: If you want to end the conversation, use phrases like "goodbye", "see you", or "take care".

Mathematical Queries: EVE can perform basic calculations. Simply enter a mathematical expression (e.g., "2 + 2"), and EVE will evaluate it.

Example Interaction:
User: "Hi there!"

EVE: "Hello! How can I assist you today?"
User: "What are some tips for staying healthy?"

EVE: [Provides health tips from knowledge base]
User: "What is 3 * 5?"

EVE: "15"
Additional Functions
Clear Chat History: Click the 'Clear' button to erase the chat history and start fresh.
Troubleshooting
If you experience issues with EVE, here are some troubleshooting steps:

Check for Typos: Ensure that your question is properly spelled.
Phrase Your Question Clearly: EVE performs best when queries are clear and concise.
Internet Connection: Ensure that you have a stable internet connection.
Developer Information
Developers:

John Maina Wambui
Joyita Mithamo Njoki
Dwayne Masinde Lawrence
Isaac Maina Muraya
Version: 1.0

Last Updated: July 17, 2024

Contact Information
For feedback or suggestions, please reach out to us at:

John Maina Wambui: wambuijonmaina@gmail.com
Joyita Mithamo Njoki: Joyritanjoki061@gmail.com
Dwayne Masinde Lawrence: maslawayne@gmail.com
Isaac Maina Muraya: Isaacmuraya254@gmail.com
Thank you for using EVE!
