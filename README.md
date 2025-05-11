# Chatbot with RAG and LangChain

## Prerequisites
- Python 3.11+

## Installation

### 1. Clone the repository:
```
git clone https://github.com/pramodbaviskar/Chatbot-with-RAG-and-LangChain.git
cd Chatbot-with-RAG-and-LangChain
```

### 2. Create a virtual environment
```
python -m venv venv
```

### 3. Activate the virtual environment
```
venv\Scripts\Activate
(or on Mac): source venv/bin/activate
```

### 4. Install libraries
```
pip install -r requirements.txt
```

### 5. Add OpenAI API Key
Rename the .env.example file to .env
Add your OpenAI API Key

## Executing the scripts
- Open a terminal in VS Code
- Execute the following commands:
```
python ingest_database.py
python chatbot.py
```

Created by Pramod Baviskar