# WoC 6.0 - DL Name Generation Model (GOR-OM)

Winter of Code 6.0 Challenge: This repository hosts a name generation model utilizing advanced deep learning techniques for creating unique and customizable names.

## Overview

In this project, we aim to build a name generation model using LSTM (Long Short-Term Memory) and GRU (Gated Recurrent Unit) neural networks. The project involves training these networks on a dataset of names to learn patterns and generate new, unique names. This hands-on experience provides insights into recurrent neural network architectures, data preprocessing for natural language processing, and the intricacies of model training and evaluation.

## Why This Project/Technology?

- **Deep Learning in NLP:** Gain proficiency in handling sequential data, crucial in many NLP tasks.
- **Hands-on Experience with RNNs:** Understand the practical applications of LSTM and GRU, two powerful types of recurrent neural networks.
- **Foundation for Complex Projects:** Build a foundation in neural networks that can be extended to more complex tasks like language translation or text generation.

## Concepts Covered

- Basics of Recurrent Neural Networks (RNNs)
- LSTM and GRU architectures
- Training and evaluating neural network models
- Tuning Hyperparameters

## Overall Development Pipeline

1. **Preprocessing:** Implement functions to convert names into tensor format suitable for neural network training.
2. **Model Building:** Define LSTM and GRU models in PyTorch.
3. **Training the Models:** Train the models on the prepared dataset, adjusting parameters for optimal performance.
4. **Name Generation:** Use the trained models to generate new names.
5. **Evaluation:** Assess the performance and uniqueness of the generated names.

## Tools and Technologies

- Python Programming Language
- PyTorch for building neural networks
- Jupyter Notebook or a similar IDE for development (Google Colab is one such option)

## Learning Resources

- [Python Official Documentation](https://docs.python.org/3/)
- [PyTorch Official Tutorials](https://pytorch.org/tutorials/)
- [Natural Language Processing in Python by DataCamp](https://www.datacamp.com/community/tutorials/text-analytics-beginners-nltk)

## Phase-wise Division of the Project

### Phase 1

1. Set up the development environment (Python, PyTorch, IDE) or use Google Colab.
2. Learn basic concepts of Python and PyTorch.
3. Preprocess the dataset.
4. Read about a simple RNN and then LSTM and GRU models.

### Phase 2

1. Implement and train the LSTM and GRU models.
2. Develop the name generation functionality.
3. Evaluate and fine-tune the models by varying hyperparameters (learning rate, batch size, dropout, optimizer, etc.).
4. Document the results.

## Additional Features (Optional)

- Change the architecture of LSTM slightly and observe the results.
- Visualize the training process using TensorBoard.
- Implement different types of sorting and filter options for the explore page.
