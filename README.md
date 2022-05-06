# BERT-Question-Answering

## Introduction

The purpose of this project was to fine-tune and cross-evaluate bert-base-uncased model in the following 4 Question Answering datasets:

1. [SQuAD 2.0](https://rajpurkar.github.io/SQuAD-explorer/)
2. [TriviaQA](https://nlp.cs.washington.edu/triviaqa/)
3. [QuAC](https://quac.ai/)
4. [NewsQA](https://github.com/Maluuba/newsqa)

More specifically, i had to first fine-tune and evaluate the BERT model on SQuAD 2.0 dataset and then do the on the other 4 and after that cross-evaluate between each model and dataset by calculating the corresponding f1 scores. 

In other words, the task was to reproduce the table 3 of the paper [What do Models Learn from Question Answering Datasets?](https://arxiv.org/pdf/2004.03490.pdf).

This project is a university assignment for the course Deep Learning for Natural Language Processing.

## Results

The paper equivalent table with the f1 scores I got is the following:

|          | SQuAD  | TriviaQA | NQ     | QuAC   | NewsQA |
| -------- | ------ | -------- | ------ | ------ | ------ |
| SQuAD    | 31.7 % | 19.8 %   | 26.3 % | 12.5 % | 16.2 % |
| TriviaQA | 18.5 % | 28.6 %   | 21 %   | 8.5 %  | 13 %   |
| QuAC     | 18.0 % | 11.7 %   | 18.6 % | 18.9 % | 7.7 %  |
| NewsQA   | 25.1 % | 15.1 %   | 29.9 % | 9.8 %  | 30.8 % |
