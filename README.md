# Sentiment Analysis with BERT

This is a Streamlit-based web application that performs sentiment analysis on movie reviews using a pre-trained BERT model.

## Features
- Uses BERT for sequence classification.
- Analyzes sentiment of user-provided text (positive or negative).
- Displays confidence score for predictions.
- User-friendly web interface powered by Streamlit.

## Installation
### Prerequisites
Ensure you have Python installed along with the required libraries.

### Clone the Repository
```sh
git clone https://github.com/yourusername/your-repo.git
cd your-repo
```

### Install Dependencies
Use the following command to install the required packages:
```sh
pip install -r requirements.txt
```

### Run the Streamlit App
```sh
streamlit run streamlit-app.py
```

## Model
The application loads a pre-trained BERT model for sentiment classification. Ensure that the model and tokenizer are stored in a directory named `trained_model` within the project.

## File Structure
```
/
|-- streamlit-app.py   # Main application file
|-- trained_model/     # Directory containing the pre-trained BERT model
|-- requirements.txt   # Dependencies for the project
|-- README.md          # Documentation
```

## Troubleshooting
- If you get an error while loading the model, verify that `trained_model` exists.
- Ensure that `transformers` and `torch` are installed correctly.

