**Toxic Comment Classification**
This project focuses on building a model to classify toxic comments into different categories such as toxic, severe toxic, obscene, threat, insult, and identity hate. The model is built using TensorFlow and Keras.

**Table of Contents**
1. Introduction
2. Dataset
3. Model Architecture
4. Training
5. Evaluation
6. Visualization
7. Anvil Integration
8. License

**Introduction**
This project aims to classify toxic comments using deep learning techniques. The model leverages LSTM layers to understand the sequence of words and identify toxicity in comments.

**Dataset**
The dataset used in this project is taken from https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/data containing comments and their associated labels. The dataset is loaded and preprocessed using pandas and TensorFlow.

**Model Architecture**
The model architecture consists of the following layers:
1. Embedding Layer
2. Bidirectional LSTM Layer
3. Dense Layers
4. Output Layer with Sigmoid Activation
5.Training
The model is trained using a binary cross-entropy loss function and the Adam optimizer. The dataset is split into training, validation, and test sets. The model is trained for 5 epochs.

**Evaluation**
The model is evaluated using precision, recall, and accuracy metrics. These metrics help in understanding the performance of the model on the test set.

**Visualization**
The project includes a function to visualize the most common words contributing to a specific class using word clouds.

**Anvil Integration**
The project is integrated with Anvil to provide a web-based interface for predicting the toxicity of comments. The Anvil server is connected using an uplink key.

**License**
This project is licensed under the MIT License.

**Check out the anvil app**
https://uncommon-vibrant-wait.anvil.app
