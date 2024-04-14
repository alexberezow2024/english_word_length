# english_word_length
An analysis of English words by length and number of unique letters. (Python)

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source and Preparation](#data-source-and-preparation)
- Findings
  - Longest word
  - Average number of letters
  - Words with most unique letters

![Number of English words by length](https://github.com/alexberezow2024/english_word_length/blob/623d0bcad7151fd434fe3f24840ecf3cb74530af/distribution_english_words_length.png)

## Project Overview
The goal of the project was to create two distributions: (1) Count of English words by length, and (2) Count of English words by number of unique letters. Furthermore, the goal was to explore the data set by answering questions like:
- What is the longest word in the English language? (Is it "antidisestablishmentarianism"?)
- What is the average number of letters in an English word?
- Which words have the most unique letters?

## Data Source and Preparation
The data file for this project can be found [here](words_alpha.txt). This file was originally obtained from GitHub user [dwyl](https://github.com/dwyl/english-words). The list contains 370,103 words. Note that hyphenated words (like "self-image") are excluded. 

All data cleaning and analysis occurred in a [Jupyter Notebook](word_study.ipynb) using Python. The initial cleaning steps involved eliminating missing values and checking for duplicates, among a few other minor corrections to the dataframe. The data was then ready for analysis.

## Findings
