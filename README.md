# NLP-LSTM-next-word-prediction
LSTM Next Word Prediction is a Natural Language Processing application that predicts the most probable next word in a sentence using Long Short-Term Memory (LSTM) networks. It learns sequential word patterns and is widely used in autocomplete, text generation, and smart typing systems.
# NLP Next Word Prediction using LSTM

## Overview

Next Word Prediction is a Natural Language Processing (NLP) task that predicts the most likely word to follow a given sequence of words. This project uses a Long Short-Term Memory (LSTM) neural network to learn language patterns from text and generate the next word based on the input sequence. LSTMs are well-suited for this task because they can capture long-term dependencies in sequential data.

## Objective

To implement a Next Word Prediction model using TensorFlow and Keras by training an LSTM network on a text corpus and predicting the next word for a given input sequence.

## Tools and Libraries

* Python
* TensorFlow
* Keras
* NumPy
* Google Colab

## Dataset

A sample text corpus containing sentences related to Natural Language Processing, Machine Learning, and Artificial Intelligence is used to train the LSTM model.

## Implementation Steps

1. Install and import the required libraries.
2. Prepare the text corpus.
3. Tokenize the text and build the vocabulary.
4. Generate n-gram input sequences.
5. Apply sequence padding for equal-length inputs.
6. Split the data into input sequences and target words.
7. Build an LSTM model using an Embedding layer, LSTM layer, and Dense output layer.
8. Train the model on the prepared sequences.
9. Predict the next word for a given input sentence.
10. Allow users to generate multiple words interactively.

## Model Architecture

* **Embedding Layer** – Converts words into dense vector representations.
* **LSTM Layer** – Learns sequential patterns and long-term dependencies.
* **Dense Layer (Softmax)** – Predicts the probability of the next word from the vocabulary.

## Sample Output

### Input

```text
machine learning
```

### Predicted Output

```text
machine learning helps computers learn
```

### Another Example

```text
natural language
```

### Predicted Output

```text
natural language processing enables computers
```

## Applications

* Smart Keyboard Suggestions
* Gmail Smart Compose
* Search Query Autocomplete
* Chatbots
* Text Generation
* AI Writing Assistants
* Language Modeling

## Advantages

* Learns contextual relationships between words.
* Generates meaningful word sequences.
* Handles sequential data effectively using memory cells.
* Forms the foundation for advanced language models.

## Conclusion

The LSTM-based Next Word Prediction model was successfully implemented using TensorFlow and Keras. The model learned sequential patterns from text and predicted the most probable next words, demonstrating the effectiveness of LSTMs in language modeling and text generation tasks.
