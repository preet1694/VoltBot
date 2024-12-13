# VoltBot 

<img width='100px' src='https://media.giphy.com/media/6rYFu4DkdH2UyBYtYL/giphy.gif'>

VoltBot is an AI-powered assistant designed to help you with all your electrical engineering queries and tasks. Whether you're a professional electrician or a hobbyist, VoltBot is here to assist you with information, troubleshooting, and more!
## Hosted Link 
https://voltbot.onrender.com/
## Features

- **PDF Upload**: Upload PDF documents related to electrical engineering or power substations.
- **Question Submission**: Type or speak your questions using the provided microphone button.
- **Voice Recognition**: Utilizes speech-to-text technology to recognize spoken questions.
- **Answer Generation**: Provides detailed and easy-to-understand answers based on the content of uploaded documents.
- **Interactive Interface**: User-friendly interface for easy navigation and interaction.

## How to Use

1. **Upload a PDF file**: If you have a document related to electrical engineering or power substations, you can upload it to VoltBot.
2. **Ask a Question**: Type or speak your question using the provided microphone button.
3. **Get Answers**: VoltBot will provide detailed and easy-to-understand answers based on the content of the uploaded documents.

## Installation

To install and run VoltBot locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/pranjal-yadav05/VoltBot
cd VoltBot
```

2. Save your Google Generative AI api key in your system environment variable named as "GOOGLE_API_KEY".

3. Create and Run Virtual Environment
```bash
python -m venv myenv
```
```bash
myenv\Scripts\activate
``` 

4. Install dependencies:
```bash
pip install -r requirements.txt
```

5. Run VoltBot:
```bash
python app.py
```

6. How to Deactivate virtual environment
```bash
deactivate
```

## Technologies Used
- Python
- LangChain
- Google Gemini
- PyPDF2
- Flask
- HTML,CSS
- Bootstrap

## Author
Pranjal Yadav, 
Preet Brahmbhatt, 
Yug Patel, 
Kushal Zinzuvadia

## License
This project is licensed under the MIT License - see the LICENSE file for details.
