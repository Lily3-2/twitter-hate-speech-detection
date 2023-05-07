# Twitter Hate Speech Detection

## Introduction
Hate speech is defined as the use of aggressive, violent, or abusive language directed at a certain group of individuals who share a common property, such as their gender (sexism), ethnic group or race (racism), beliefs, or religion, among other things. In this project, Recurrent Neural Network (RNN) is used along with LSTM, including a method shown on how to use a method called **DistilBERT** to pre-train a smaller general-purpose language representation model that can subsequently be fine-tuned to perform well on a wide range of tasks, just like its larger counterparts.

This project shows the use of knowledge distillation during the pretraining phase can reduce the size of a BERT model by 40% while retaining 97% of its language understanding capabilities and being **60%** faster. DistilBERT uses a triple loss that combines language modelling, distillation, and cosine-distance losses to use the inductive biases gained by larger models during pre-training.
