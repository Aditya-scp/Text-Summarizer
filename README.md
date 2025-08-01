# Extractive Text Summarizer

A simple Python tool that summarizes long articles and text by extracting the most important sentences. This project uses the spaCy library for Natural Language Processing.

## About The Project

This script provides a function to perform extractive summarization. It works by:
* Calculating the frequency of each significant word.
* Scoring each sentence based on the importance of the words it contains.
* Selecting the top-scoring sentences to form the final summary.

### Built With

* [Python](https://www.python.org/)
* [spaCy](https://spacy.io/)

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You need to have Python and pip installed on your system.

### Installation

1.  Clone the repo: 
    ```sh
    &nbsp
    git clone [https://github.com/Aditya-scp/Text-Summarizer](https://github.com/Aditya-scp/Text-Summarizer)
    &nbsp
    ```
    &nbsp 
3.  Navigate into the project directory:
    ```sh
    cd text-summarizer
    ```
4.  Install the required Python packages:
    ```sh
    pip install -r requirements.txt
    ```
5.  Download the necessary spaCy language model:
    ```sh
    python -m spacy download en_core_web_sm
    ```

## Usage

You can modify the `summarizer.py` file to include any text you want to summarize.

Run the script from your terminal:
```sh
python summarizer.py
