# Natural Language Processing 2024 – Exercise 2

## Introduction

Welcome to our project on Natural Language Processing (NLP), a fascinating field that bridges computer science, artificial intelligence, and linguistics. This project is part of our coursework for the NLP 2024 class, aimed at exploring the nuances of processing and understanding human languages through computational methods.

In this exercise, we embark on a journey to understand the intricacies of text data, starting from the very basics of downloading and cleaning datasets, to the more complex tasks of tokenizing texts, performing analyses, and finally, training sophisticated neural network models to comprehend and generate language constructs.

## Project Structure

### Data Download and Cleaning

The foundation of any NLP project lies in its dataset. In this section, we delve into the process of acquiring our dataset from a reputable source, followed by a series of steps designed to clean and preprocess the text. This involves removing irrelevant characters, correcting typos, and standardizing text format to ensure consistency across the dataset.

### Tokenization

Tokenization is a critical process in NLP where we break down text into smaller units, such as words or phrases. This section explains our approach to tokenization, the tools and libraries used, and how this process facilitates the subsequent analysis and machine learning tasks.

### Basic Analysis

Before diving into complex NLP models, we perform a basic analysis of our dataset. This includes statistical analysis of word frequencies, sentence lengths, and other textual characteristics that provide insights into the composition and complexity of our text data.

### Preparing the Dataset for Training

Training machine learning models requires meticulously prepared data. This section covers how we format our dataset into a structure that is compatible with neural network models. We discuss splitting the dataset into training, validation, and test sets, and the rationale behind our choices.

### Training a Feed Forward Neural Network

We begin our modeling journey with a feed forward neural network, one of the simplest forms of neural networks. This section provides an in-depth look at the network architecture, the training process, hyperparameter tuning, and the evaluation of the model's performance on our NLP task.

### Training a BiDir LSTM Neural Network

To tackle more complex NLP challenges, we advance to a bidirectional LSTM network. This section details the architecture of a BiDir LSTM, its advantages over simpler models, the training regimen we followed, and a thorough analysis of the model's performance, including challenges faced and how we overcame them.

## Installation and Setup

Ensure you have Python 3.x installed on your machine. You will also need Jupyter Notebook or Jupyter Lab to run the notebook. The project depends on several Python libraries, which can be installed using the following commands:

```bash
pip install numpy pandas matplotlib scikit-learn keras tensorflow
```

## Running the Project

Open your terminal or command prompt, navigate to the project directory, and run:

```bash
jupyter notebook ex02-Liron_Farzam_Hila_Saadon.ipynb
```

This will open the notebook in your default web browser, where you can run the cells sequentially to replicate our results or modify the code to experiment with your own ideas.

## Contributing

We welcome contributions from fellow students and NLP enthusiasts. Whether it's adding new analysis, improving the models, or fixing bugs, your insights are valuable to us. Please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

This detailed README provides a comprehensive overview and guide for users interested in your NLP project. Adjustments and expansions have been made to offer deeper insights into each project phase, setup instructions, and how users can contribute. Feel free to tweak any sections to better fit your project's needs or add any additional information you deem necessary.
