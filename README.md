# SMS Spam Classification

This project is a machine learning model to classify SMS messages as spam or not spam. The model is deployed using Streamlit.

## Deployed App

You can access the deployed app [here]([http://your-streamlit-app-url](https://spam-detection-uvlvma2g6kjvfazvv7nlce.streamlit.app/)).

## Features

- Preprocesses SMS text messages
- Classifies messages as spam or not spam
- Interactive user interface with Streamlit

## Installation

To run this project locally, you will need to install the necessary dependencies.

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/sms-classification.git
    cd sms-classification
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Download NLTK data:
    ```python
    import nltk
    nltk.download('punkt')
    ```

## Usage

To run the app locally, use the following command:

```bash
streamlit run app.py
