**Overview**

This repository contains the code for a chatbot powered by UNH student as a final project for the Fall semester, 2023. The chatbot is fine-tuned for improved conversational experiences and utilizes a sophisticated memory storage and retrieval system. The README provides an overview of the project, instructions for usage, and additional information.

**Table of Contents**

- Introduction

- Features

- Usage

- Model Fine-Tuning

- Test Dataset

- Evaluation Metrics

- Results

- Contributing

**Introduction**

Many conversational chatbots struggle with context awareness and personalization, leading to generic responses. This project aims to enhance the chatbot experience by implementing an advanced memory storage and retrieval system within the GPT-2 architecture. The result is a more dynamic and engaging conversational AI.

**Features**

GPT-2-based chatbot with advanced memory storage.
Fine-tuned model for improved conversational responses.
Evaluation metrics include BLEU score and accuracy.
User-friendly interface for generating responses.

**Usage**

**Environment Setup:**

Ensure you have Python installed (python>=3.6).
Install required packages: pip install -r requirements.txt

**Model Loading:**

Load the fine-tuned GPT-2 model and tokenizer.

**Generate Responses:**

Use the generate_response function to interact with the chatbot.

**Evaluate:**

Evaluate the chatbot on a test dataset using BLEU score and accuracy metrics.

**Test Dataset**

The test_intent_data.json file contains a sample test dataset with intents, patterns, and reference responses. Modify or replace this file with your own dataset for evaluation.

**Evaluation Metrics**

The chatbot's performance is evaluated using BLEU score and accuracy. BLEU score measures the similarity between generated and reference responses, while accuracy checks for correct responses against the reference.

**Results**

The average BLEU score and accuracy are displayed after evaluating the chatbot on the test dataset.

**Contributing**

Feel free to contribute to the project by opening issues or submitting pull requests. Your feedback and enhancements are valuable!
