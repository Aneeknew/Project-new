# Chit-Chat AI Bot 🤖  

Chit-Chat AI is an interactive chatbot built to answer user queries based on predefined intents. It uses **Natural Language Processing (NLP)** and **Logistic Regression** to classify user inputs and respond appropriately. The interface is powered by **Streamlit**, providing a seamless web-based interaction.

---

## Features ✨  

- **Interactive Chat Interface**: Engage in real-time conversations.  
- **NLP-based Intent Classification**: Understands and categorizes user inputs.  
- **Dynamic Response Generation**: Fetches responses from a JSON dataset.  
- **Conversation Logging**: Records chat history in a CSV file.  
- **Customizable Design**: Extendable intents and responses for scalability.  

---

## Technologies Used 🛠️  

### **Programming Language**  
- Python  

### **Libraries and Frameworks**  
- **Streamlit**: For building the user interface.  
- **NLTK**: For text processing and NLP tasks.  
- **Scikit-learn**: For implementing TfidfVectorizer and Logistic Regression.  

### **File Handling**  
- **JSON**: To store intents and responses.  
- **CSV**: To log chat history.  

---

## Project Structure 📂  


```plaintext
Chit-Chat-AI/
│
├── intents.json                # JSON file with intents, patterns, and responses
├── nltk_data/                  # NLTK data folder for text processing
├── chat_log.csv                # CSV file logging conversation history
├── logo.png                    # Logo used in the Streamlit sidebar
├── README.md                   # Project documentation
├── requirements.txt            # Required Python libraries
└── chatbot.py                  # Main Python script
```

## How to Run the Project 🚀
### **1. Clone the repository:**

```https://github.com/Aneeknew/Project-new.git```
### **2. Install dependencies:**
```pip install -r requirements.txt```
### **3. Run the Streamlit app:**
```streamlit run chatbot_app.py```
### **4.Open the provided URL (e.g., http://localhost:8501) in your browser and start chatting!**

## How It Works 🔍
1. The user inputs a query in the chatbot interface.
2. The query is vectorized using **TfidfVectorizer**.
3. A **Logistic Regression** model predicts the intent of the query.
4. A random response is selected from the corresponding intent in the `intents.json` file.
5. The conversation is displayed on the interface and logged in a CSV file.

## Customization 🛠️

1. **Add New Intents**
    - Update the `intents.json` file with new intents, patterns, and responses.

2. **Improve NLP Model**
    - Replace Logistic Regression with more advanced machine learning or deep learning models.

3. **Add New Features**
    - Integrate API support, voice capabilities, or multi-language processing.

## Screenshots 🖼️

### 1. **Home Page**
- The main chatbot interface where users interact.
![image](https://github.com/user-attachments/assets/a71b58a9-e037-47b0-86ec-e85d3aae4675)

### 2. **Conversation History**
- Displays all logged conversations with timestamps.
- ![image](https://github.com/user-attachments/assets/6367ab78-ff38-4caf-bc1d-cea54666f337)

## Limitations ⚠️

- Supports only the English language.
- Requires predefined intents for responses.

## Future Enhancements 🔮

- Introduce multi-language support.
- Integrate with external APIs for real-time data.
- Implement a voice-based chatbot.

## Author 🙋‍♂️

Developed by **Aneek Nath**. Contributions are welcome!

Feel free to fork this repository, report issues, or suggest new features.







