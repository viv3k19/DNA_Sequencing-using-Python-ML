# DNA Sequencing with Machine Learning

In this Data Science Project, I will apply a classification model with Machine Learning that can predict a gene's function based on the DNA sequencing of the coding sequence alone.

Treating DNA sequence as a “language”, otherwise known as k-mer counting
A challenge that remains is that none of these above methods results in vectors of uniform length, and that is a requirement for feeding data to a classification or regression algorithm.

So with the above methods you have to resort to things like truncating sequences or padding with “n” or “0” to get vectors of uniform length.

DNA and protein sequences can be viewed metaphorically as the language of life. The language encodes instructions as well as function for the molecules that are found in all life forms.

Here I am using hexamer “words” but that is arbitrary and word length can be tuned to suit the particular situation. The word length and amount of overlap need to be determined empirically for any given application.

In genomics, we refer to these types of manipulations as “k-mer counting”, or counting the occurrences of each possible k-mer sequence. There are specialized tools for this, but the Python natural language processing tools make it super easy.


## Overview

This project focuses on DNA sequencing analysis using a classification model. The goal is to predict the function of a gene based on its DNA sequence. The project utilizes a multinomial naive Bayes classifier and applies the Bag of Words approach using CountVectorizer for feature extraction.

## Files

The following files are used in this project:

- `DNA_Sequencing.ipynb`: Jupyter Notebook containing the project code.
- `human_data.txt`: Data file containing human DNA sequence coding regions and class labels.
- `chimp_data.txt`: Data file containing chimpanzee DNA sequence coding regions and class labels.
- `dog_data.txt`: Data file containing dog DNA sequence coding regions and class labels.

## Dependencies

The project requires the following dependencies:

- `numpy` 
- `pandas` 
- `matplotlib` 
- `scikit-learn` 

## Installation
You can install the required dependencies using pip:

```shell
pip install numpy pandas matplotlib scikit-learn
```

## Usage

1. Clone the repository:
```shell
git clone https://github.com/viv3k19/DNA_Sequencing-using-Python-ML.git
```

2. Open the Jupyter Notebook DNA_Sequencing.ipynb in your preferred environment (e.g., Jupyter Notebook, Google Colab).

3. Run the notebook cells to execute the code step by step.

## Results

* Confusion Matrix

![results](https://github.com/viv3k19/DNA_Sequencing-using-Python-ML/assets/82309435/c44d31dd-c4c3-4224-b4e2-aabc5c1a7700)

* Analytics

![analysis](https://github.com/viv3k19/DNA_Sequencing-using-Python-ML/assets/82309435/d02f1b3a-8e7a-4c2a-80bc-b842eba9858e)

# Project Creator
* Vivek Malam - Feel free to contact me at viv3k.19@gmail.com for any questions or feedback.
