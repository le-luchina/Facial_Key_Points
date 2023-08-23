# Facial_Key_Points
ML. Learning Facial Key Points with RezNet

## Facial Key Points Detection using ResNet
Welcome to my Facial Key Points Detection project, inspired by the Kaggle competition on this intriguing topic. In this venture, I've undertaken the task of recreating the ResNet18 architecture to tackle this challenging problem. Let's dive in and explore the journey so far.

## Project Overview
This repository is a testament to my passion for machine learning and computer vision. Drawing inspiration from the Kaggle competition, I set out to develop a model capable of accurately detecting facial key points.

## The ResNet Approach
One of the key highlights of this project is the implementation of the ResNet18 architecture. Through meticulous design, finetuning, and training, I achieved a validation accuracy of 0.77. Visualising predicted Key points it becomes obvious that most for most images they are detected nearly perfectly, although there are a few with obvious blunders. It's a testament to the power of deep learning in unraveling complex facial patterns.

## Next Steps
While I'm proud of the progress made so far, there's always room for improvement. Here are the next steps I have in mind:

Model Fine-Tuning: With further iterations and fine-tuning, I believe we can push the accuracy much higher. This involves several rounds of model fine tuning: optimizing hyperparameters, adjusting learning rates, and experimenting with various regularization techniques.

Resource Scaling: My current limitations in terms of personal hardware constrained the project's capacity. With access to a bit more computational resources, I would implement the EarlyStopping callback to prevent overfitting and extend training on each fine-tuning iteration to potentially 100 epochs.


