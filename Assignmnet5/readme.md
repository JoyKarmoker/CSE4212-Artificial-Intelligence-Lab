# Transfer Learning for Binary Classification

## Overview

This repository contains the code, data, and report for the assignment on the effect of transfer learning on binary classification using a custom model trained on a private dataset.

## Dataset

The dataset used for this project is located in the `thumbsup_peace` directory. It consists of labeled images for binary classification tasks, specifically distinguishing between images of peace signs and thumbs-up signs.

#### Binary Classification and Sign Language

The binary classification task involves distinguishing between peace and thumbs-up signs, two widely recognized hand gestures in sign language. This project explores the application of transfer learning techniques to improve the model's ability to recognize these gestures.

## Code

The code for training the model, performing transfer learning, and evaluating the model is provided in the `Group6_Assignment5` file.

### Transfer Learning Models

The project uses two popular pre-trained models for transfer learning: VGG16 and ResNet-50. Both models are fine-tuned on the private dataset to leverage their pre-trained weights and improve classification performance.

## Report

The report detailing the experimental setup, methodology, results, and analysis can be found in the `report` file.

### Key Highlights

- **Binary Classification:** The report delves into the binary classification task of distinguishing peace signs from thumbs-up signs and explores the significance of this task in sign language applications.

- **Transfer Learning Comparison:** The performance of VGG16 and ResNet-50 in the transfer learning process is thoroughly compared. The report provides insights into the strengths and weaknesses of each model in the context of the binary classification task.

- **Evaluation Metrics:** Detailed evaluation metrics, including test loss, test accuracy, validation loss, and validation accuracy, are presented to provide a comprehensive understanding of the models' performance.

- **Significance in Sign Language:** The report discusses the practical implications of achieving accurate binary classification in sign language applications, emphasizing the potential impact on communication accessibility.
