# HealthBot EVE: Your Personal Health and Wellness Assistant 🤖💼  

HealthBot EVE is a comprehensive AI-powered chatbot designed to assist with **health and wellness guidance**, **mathematical evaluations**, and seamless **user interaction management**. It combines the power of artificial intelligence with a user-friendly interface to make health support and calculations accessible anytime, anywhere.

---

## 📸 Preview  

![EVE Interface](./EVE%20Interface.jpg)
##
*Figure 1.1: EVE's intuitive interface ensures smooth and effective user interactions.*

---

## 🌟 Features  

### 1. **Health and Wellness Advice**  
EVE provides expert, evidence-based health tips and answers to health-related queries, empowering users to make better decisions about their well-being.

### 2. **Mathematical Calculations**  
EVE supports quick evaluations of mathematical expressions, making it an efficient tool for users needing precise calculations.

### 3. **User Interaction Management**  
Handle common interactions such as:  
- Greetings and farewells  
- Command-based navigation  
- Chat session management, including clearing history  

### 4. **Help Command**  
A detailed help feature is available, guiding users through EVE's commands and functionalities.

### 5. **Custom Knowledge Base**  
EVE leverages a structured JSON-based knowledge base to provide targeted and helpful responses.  

---

## 🖥️ System Requirements  

Before setting up, ensure the following are met:  

1. **Python**: Version 3.6 or higher.  
2. **Dependencies**:  
   - Flask (web framework)  
   - ChatterBot (chatbot engine)  
   - NLTK (natural language processing)  
   - SymPy (symbolic mathematics)  
3. **Knowledge Base**:  
   - `knowledge_base.json`, structured with training data for health-related responses.  

---

## 🛠️ Installation Guide  

Follow these steps to set up EVE on your system:  

### 1. **Clone the Repository**  

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

### 2. **Set Up a Virtual Environment**  

```bash
# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

### 3. **Install Dependencies**  

```bash
pip install -r requirements.txt
```

Dependencies in `requirements.txt` include:  
- Flask  
- ChatterBot  
- nltk  
- sympy  

### 4. **Download NLTK Data**  

Run the following commands in a Python shell:  

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('averaged_perceptron_tagger')
```

### 5. **Prepare the Knowledge Base**  

Ensure a file named `knowledge_base.json` exists in the root directory. Example structure:  

```json
{
  "training_data": [
    {"question": "What are some tips for staying healthy?", "answer": "Eat balanced meals, exercise regularly, and stay hydrated."},
    {"question": "How can I lose weight?", "answer": "Maintain a calorie deficit through proper diet and exercise."}
  ]
}
```

### 6. **Run the Application**  

Start the application using:  

```bash
python eve.py
```

EVE will be available at: [http://localhost:5000](http://localhost:5000).  

---

## 💻 User Guide  

### Getting Started  

1. Open the chatbot interface in your browser at the provided URL.  
2. Type your query or command in the input box and press "Send" to interact with EVE.  

### Common Commands  

- **Ask Questions**: Enter any health-related question, and EVE will respond with expert advice.  
- **Perform Calculations**: Type mathematical expressions like `3 + 7`, and EVE will evaluate them.  
- **Exit the Session**: Use commands such as `stop`, `exit`, `quit`, or `bye` to end the session.  
- **Help**: Type `help` to display a list of available commands.  

---

### Example Interactions  

| **User Input**                  | **EVE Response**                                           |  
|----------------------------------|-----------------------------------------------------------|  
| Hi, how are you?                 | Hello! How can I assist you today?                        |  
| What are some tips for fitness?  | Exercise daily, eat a balanced diet, and get enough sleep.|  
| What is 12 * 8?                  | The answer is 96.                                         |  
| bye                              | Goodbye! Stay healthy!                                    |  

---

## 🛠️ Troubleshooting  

If you encounter any issues:  

1. **Check Dependencies**: Ensure all required packages are installed.  
2. **Correct Spelling**: Verify your input is clear and correctly spelled.  
3. **Rephrase Queries**: Use alternative phrasing for your questions.  
4. **Internet Connectivity**: Ensure your device is connected to a stable network.  

---

## 📋 Developer Information  

| **Developer**         | **Email**                     |  
|------------------------|-------------------------------|  
| John Maina Wambui     | [wambuijonmaina@gmail.com](mailto:wambuijonmaina@gmail.com) |  
| Joyita Mithamo Njoki  | [Joyritanjoki061@gmail.com](mailto:Joyritanjoki061@gmail.com) |  
| Dwayne Masinde Lawrence | [maslawayne@gmail.com](mailto:maslawayne@gmail.com) |  
| Isaac Maina Muraya    | [Isaacmuraya254@gmail.com](mailto:Isaacmuraya254@gmail.com) |  

---

## 📅 Version & Updates  

- **Version**: 1.0  
- **Last Updated**: November 30, 2024  

---

## 📬 Contact Us  

We value your feedback!  
For inquiries, suggestions, or technical support, please email any of the developers listed above.  

---

Thank you for choosing **HealthBot EVE**
