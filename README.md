# Series Analyzer with NLP & LLMs

## 🚀 Project Overview
This project leverages Natural Language Processing (NLP) and Large Language Models (LLMs) to analyze your favorite TV series. It involves building datasets, training various NLP models, extracting insights, and deploying an interactive chatbot—all packed into a web-based interface using Gradio.

By working on this project, you will gain hands-on experience with data scraping, named entity recognition, text classification, and chatbot development. This end-to-end NLP project is a great addition to your portfolio and will significantly enhance your resume.

---

## 🔍 Key Features
### ✅ **Data Collection & Scraping**
- Utilizes Scrapy to extract and compile relevant data about the series.
- Builds a structured dataset for further NLP processing.

### 📊 **Character Network Analysis**
- Identifies and maps relationships between characters using Named Entity Recognition (NER) with SpaCy.
- Visualizes character connections using NetworkX and PyViz.

### 🎭 **Theme Classification**
- Implements a Zero-Shot Classifier to detect major themes and categorize text into multiple topics.

### 🏷 **Text Classification**
- Trains a robust text classifier to categorize series-related content effectively.

### 💬 **Character Chatbot**
- Builds an LLM-powered chatbot that enables conversations with characters from the series.

### 🌐 **Web Interface with Gradio**
- Provides a user-friendly web-based interface to interact with the models.

---

## 📂 Project Structure
```
series_analyzer_nlp/
│── character_chatbot/      # Chatbot implementation using LLMs
│── character_network/      # Character relationship mapping with NER & NetworkX
│── crawler/                # Web scraping scripts using Scrapy
│── data/                   # Dataset storage
│── stubs/                  # Placeholder files
│── text_classification/    # Text classification model
│── theme_classifier/       # Theme classification using Zero-Shot Learning
│── utils/                  # Utility functions
│── .env                    # hugging face environment configuration
│── .gitignore              # Ignored files
│── README.md               # Project documentation
│── index.html              # Web interface template
│── gradio_app.py           # Gradio-based web application
│── requirements.txt        # Required dependencies
```

---

## 🛠 Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-repo/series-analyzer-nlp.git
cd series-analyzer-nlp
```

### 2️⃣ Install Dependencies
Make sure you have Python installed, then run:
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Web Application
To launch the Gradio interface, execute:
```bash
python gradio_app.py
```

---

## 🚀 Technologies Used
- **Python** 🐍
- **Scrapy** 🕷 (Web Scraping)
- **SpaCy** 🔎 (NER for Character Network)
- **NetworkX & PyViz** 📊 (Character Graph Visualization)
- **Transformers (Hugging Face)** 🤗 (LLMs for Chatbot & Classifier)
- **Gradio** 🌐 (Web UI)




