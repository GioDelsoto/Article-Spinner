# Article Spinner Project

## Overview

This project focuses on building an **article spinner**, a tool that rewrites articles by replacing words with suitable alternatives while retaining the original context and meaning. It uses a **frequentist probability model** to calculate word probabilities based on their surrounding context and generates new versions of the articles through sampling.

The project is designed to demonstrate the practical application of natural language processing (NLP) in text generation and content variation. It utilizes the [BBC Full Text Document Classification Dataset](https://www.kaggle.com/shivamkushwaha/bbc-full-text-document-classification) for training and testing the spinner.

---

## Project Structure

ArticleSpinner/
├── notebooks/
│ └── article_spinner.ipynb # Main Jupyter Notebook for building the model
├── data/
│ └── bbc_dataset/ # Folder containing the BBC dataset
├── requirements.txt # Python dependencies
└── README.md # Project overview and instructions

## Features

- **Dataset:** The BBC dataset, a collection of articles from various categories (sports, politics, etc.), is used to train and evaluate the spinner.
- **Probability Model:** A frequentist approach is applied to calculate the likelihood of a word appearing in a specific context.
- **Text Generation:** The spinner generates a rewritten version of an input article by sampling new words based on the probability model.

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook

Install the required dependencies by running:

```bash
pip install -r requirements.txt
```
