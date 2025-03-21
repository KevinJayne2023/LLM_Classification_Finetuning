# LLM Classification Fine-Tuning

This project focuses on a Kaggle competition that aims to predict which responses users will prefer in a head-to-head battle between chatbots powered by large language models (LLMs). The goal is to develop a machine learning model that can evaluate and predict user preferences based on a dataset of conversations from the Chatbot Arena, where different LLMs generate answers to user prompts.

## Project Overview

The competition involves predicting user preferences between different chatbot responses. The dataset consists of conversations where various LLM-powered chatbots generate responses to the same user prompts. Your task is to build a model that can accurately predict which response users will prefer in each head-to-head scenario.

### Steps Involved:

1. **Data Exploration**:
   - Load and explore the dataset containing conversations and chatbot responses.
   - Understand the structure of the data, including features such as the generated responses, the conversation context, and the user preferences.

2. **Model Training**:
   - Develop a classification model by fine-tuning a pre-trained large language model (LLM) to predict user preferences between chatbot responses.
   - Use relevant libraries like TensorFlow, Keras, and KerasNLP to process the data and train the model.

3. **Model Evaluation**:
   - Evaluate the trained model on its ability to predict user preferences.
   - The model is evaluated based on log loss, which compares the predicted probabilities against the ground truth values.

## Evaluation Metric

Submissions are evaluated using **log loss** between the predicted probabilities and the ground truth values (with `eps=auto`).

## Requirements

To run this notebook, you'll need the following libraries installed:

- `tensorflow`
- `keras`
- `keras_nlp`
- `numpy`
- `pandas`
- `matplotlib`
- `plotly`
- `tqdm`

You can install the necessary packages via pip:

Bash
pip install tensorflow keras keras_nlp numpy pandas matplotlib plotly tqdm

## **Dataset**

The dataset is provided by the Kaggle competition and consists of conversations from the Chatbot Arena. The responses are generated by different LLMs, and the objective is to predict which response users will prefer.

## **Conclusion**

This notebook demonstrates how to fine-tune a large language model for predicting user preferences in chatbot response battles. The goal is to build a machine learning model that can help improve how chatbots interact with humans, ensuring they better align with human preferences.
