# Sign-Language-Chatbot
It's a chat-bot based on AI models (cGAN) to teach American Sign Language .

## Problem Statement
Alot of people wants to learn about ASL (American Sign Language) and less resources make it difficult .

## solution 
Chatbot try to make you learn ASL as nowadays people got used to chatgpt and its features .

## Technologies Used
Python / os / torchvision / cGAN ( discriminator , generator ) / torch .

## System Architecture
The system is based on a Conditional Generative Adversarial Network (cGAN) architecture, consisting of two deep convolutional neural networks: a Generator and a Discriminator. The Generator receives a random noise vector and a class label embedding and produces a synthetic ASL letter image. The Discriminator receives both the image and the corresponding label embedding and learns to distinguish between real and generated samples while verifying label consistency. The adversarial training process enables the Generator to learn the underlying distribution of ASL hand gestures, resulting in realistic and class-conditioned image synthesis .

(Data Layer) :

-ASL Image Dataset

-Label Encoding (A–Z)

(Model Layer) :

-Conditional Generator Network

-Conditional Discriminator Network

(Training Layer) :

-Adversarial Optimization

-BCE Loss

-Adam Optimizers

(Output Layer) :

-Generated ASL letter images

-Model checkpoints

-Epoch sample images

-Trained generator model



