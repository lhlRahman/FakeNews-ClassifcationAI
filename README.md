# FakeNews-ClassifcationAI
# News Title Classifier

This repository contains a script and datasets used to classify news titles as either "fake" or "real" using the Cohere API.

## Files Description

- `classify.py`: A Python script that uses the Cohere API to classify user-input news titles as either "fake" or "real".
- `Fake.csv`: A dataset containing titles that are presumably from fake news articles.
- `True.csv`: A dataset containing titles that are presumably from real news articles.

## How to Use

1. **Setup**:
    - Ensure you have the required libraries installed:
        ```bash
        pip install cohere pandas
        ```
    - Replace `'YOUR_API_KEY'` in the `classify.py` script with your Cohere API key.

2. **Run the Script**:
    - Execute the `classify.py` script:
        ```bash
        python classify.py
        ```
    - When prompted, enter a news title you wish to classify.

3. **Interpret the Results**:
    - The script will print the classification (either "fake" or "real") and the confidence level of the prediction.

## Note

Ensure you have the necessary permissions to use the Cohere API and adhere to their terms of service.
