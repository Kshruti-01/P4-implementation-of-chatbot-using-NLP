# P4-implementation-of-chatbot-using-NLP
## Project Outline
<p>This project demonstrates the creation of a simple chatbot using Natural Language Processing (NLP) techniques.It utilizes the `nltk` library for natural language processing, `scikit-learn` for machine learning, and `streamlit` for creating an interactive web interface.
 The chatbot is trained on predefined intents and responds to user queries based on pattern matching and intent classification.</p>
 <hr>
 ## Features
 <p>
   <span>
   Intent Recognition: Classifies user inputs into predefined categories (intents).
   Flexible Patterns: Matches user queries using regular expressions or word embeddings.
   Interactive: Provides meaningful responses to user queries.
   Expandable: Easily add new intents, patterns, and responses.
   </span>
 </p>
 <hr>
## Technologies used
Python: Primary programming language.
Natural Language Toolkit (NLTK): Tokenization, stemming, and lemmatization.
JSON: For storing intents and responses.
<hr>
## Installation
###1. Clone the Repository
```bash
git clone <repository-url>
cd <repository-directory>
```

### 2. Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Required Packages
```bash
pip install -r requirements.txt
```

### 4. Download NLTK Data
```python
import nltk
nltk.download('punkt')
```

---

## Usage
To run the chatbot application, execute the following command:
```bash
streamlit run app.py
```

Once the application is running, you can interact with the chatbot through the web interface. Type your message in the input box and press Enter to see the chatbot's response.

---
## How it works
<span>
Preprocessing:
Tokenize user input.
Stem or lemmatize tokens for standardization.
Convert input into a bag-of-words or embedding representation.

Intent Matching:
Compare processed input with patterns in the intents.json file.
Use a trained neural network for advanced bots.

Response Generation:
Match the intent and select a random response from the corresponding intent's responses.
</span>
## Intents Data
The chatbot's behavior is defined by the `intents.json` file, which contains various tags, patterns, and responses. You can modify this file to add new intents or change existing ones.

---

## Conversation History
The chatbot saves the conversation history in a CSV file (`chat_log.csv`). You can view past interactions by selecting the "Conversation History" option in the sidebar.

---

## Contributing
Contributions to this project are welcome! If you have suggestions for improvements or features, feel free to open an issue or submit a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
