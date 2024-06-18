# Med-BOT
A healthcare chatbot that predicts diseases based on patient symptoms.

## Overview
**Med-BOT** is an intelligent healthcare chatbot designed to assist patients by predicting potential diseases based on their symptoms. Leveraging state-of-the-art natural language processing (NLP) and machine learning technologies, Med-BOT aims to provide users with quick and reliable preliminary diagnoses.

### Technologies Used
- **Python**: The core programming language used for development.
- **Flask**: A micro web framework used to create the web application.
- **SpaCy**: An NLP library used for processing and understanding large amounts of text.
- **Scikit-learn**: A machine learning library used for building the predictive model.
- **HTML/CSS**: For frontend design and user interface.
### Features
- **Symptom Analysis**: Input your symptoms and get a list of possible diseases.
- **User-Friendly Interface**: Simple and intuitive design for easy interaction.
- **Quick Predictions**: Fast and efficient processing to provide instant results.

---

## How to Use

### Step 1: Create a Virtual Environment
First, create a virtual environment to manage your project dependencies.
```bash
virtualenv venv
```
### Step 2: Activate the Virtual Environment
Activate the virtual environment to start using it.

On Windows:
```bash
.\venv\Scripts\activate
```
### Step 3: Install Requirements
Install the necessary packages using the provided requirements.txt file.

```bash
pip install -r requirements.txt

```

### Step 4: Download SpaCy Model
Download the SpaCy English language model.

```bash
python -m spacy download en_core_web_sm
```

### Step 5: Run the Application
Finally, run the application.

```bash
python app.py
```
**Now, you should have Med-BOT up and running, ready to predict diseases based on patient symptoms.**

if you have issues setting itup locally due to some version related issues, you can dirrectly find the zipped venv file on this link https://drive.google.com/drive/folders/1daHF8yB6vB97LSpwl0b5kBWB08A2qAQj 
star it if you found it helpful ;) 

Medical DataSet available!
