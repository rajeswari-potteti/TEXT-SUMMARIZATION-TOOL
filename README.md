

*COMPANY*   : CODTECH IT SOLUTIONS

*NAME*      : POTTETI RAJESWARI

*INTERN ID* : CT06DG1193

*DOMAIN*    : ARTIFICIAL INTELLIGENCE

*DURATION*  : 6 WEEKS

*MENTOR*    : NEELA SANTHOSH


# Text Summarization Tool

## About the Project

This is a generic Python based text summarisation tool written during an NLP internship. It's mainly focused on reducing large text documents to concise, coherent summaries that are created through a modern summarization technique. It's based on the facebook/bart-large-cnn model from HuggingFace Transformers and can generate summaries that express the original content in fewer words.

This project fills a genuine gap. And long articles, reports and research papers can be incredibly time-consuming to read cover-to-cover. A good summarise tool can help you save time and can still summarize the main idea of the original.

## What This Project Does

The application takes input in plain text, user input can be command line given by the user in the terminal or by moving a . txt file. The script then processes the text, and the automatic summary is generated using a pre-trained summarization model. The script also prints the original text, the summary and some basic stats – word count, compression percentage.

## Why This Was Built

The project was intended to be more than an extension of NLP methods, rather to solve a real problem. Large-volume readings are popular in academic as well as in industry, and summarizing them by hand is a cumbersome process. Automating this with machine learning is an educational experience as well as a handy tool. This acts as a stepping stone for more complex text analysis tasks that can be used as the bridge for further analysis.

## Features

- Accepts input from:
  - Manual text entry via the command line
  - External plain .txt files
- Uses the facebook/bart-large-cnn pre-trained model for summarization
- Displays:
  - Original input text
  - Summarized output
  - Word count and compression ratio
- Optionally saves the summary to a text file

## Prerequisites

The system must have Python 3.7 or later.

It also requires the use of the Python libraries below:

-transformers

-torch

These libraries are required for loading and running the pre-trained transformer model. All dependencies can be installed by running the following command in the project folder:

pip install -r requirements. txt


## Output

![Image](https://github.com/user-attachments/assets/d232e64b-d656-436a-a062-a1594eb9c083)
