# english_word_length
An analysis of English words by length and number of unique letters. (Python)

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source and Preparation](#data-source-and-preparation)
- [Findings](#findings)
  - Longest word
  - Average number of letters
  - Words with most unique letters

<img src = "https://github.com/alexberezow2024/english_word_length/blob/623d0bcad7151fd434fe3f24840ecf3cb74530af/distribution_english_words_length.png" width = "500">

## Project Overview
The goal of the project was to create two distributions: (1) Count of English words by length, and (2) Count of English words by number of unique letters. Furthermore, the goal was to explore the data set by answering questions like:
- What is the longest word in the English language? (Is it "antidisestablishmentarianism"?)
- What is the average number of letters in an English word?
- Which words have the most unique letters?

## Data Source and Preparation
The data file for this project can be found [here](words_alpha.txt). This file was originally obtained from GitHub user [dwyl](https://github.com/dwyl/english-words). The list contains 370,103 words. Note that hyphenated words (like "self-image") are excluded. 

All data cleaning and analysis occurred in a [Jupyter Notebook](word_study.ipynb) using Python. The initial cleaning steps involved eliminating missing values and checking for duplicates, among a few other minor corrections to the dataframe. The data was then ready for analysis.

## Findings

### What is the longest word in the English language? (Is it "antidisestablishmentarianism"?)
When I was in grade school, we were taught that antidisestablishmentarianism is the longest word in the dictionary. Is it true? 

Yeah, sort of. "Antidisestablishmentarianism" is 28 letters long. There are other words that are just as long or longer, but they are the technical names for chemical compounds. In my opinion, those don't really count. 

- hydroxydehydrocorticosterone (28 letters)
- cyclotrimethylenetrinitramine (29)
- trinitrophenylmethylnitramine	(29)
- dichlorodiphenyltrichloroethane	(31)

However, [Merriam-Webster](https://www.merriam-webster.com/grammar/no-antidisestablishmentarianism-is-not-in-the-dictionary) doesn't consider it a real word. Some outlets claim that "floccinaucinihilipilification" (29 letters) is the longest word, but that word didn't appear in the data set used here.

### What is the average number of letters in an English word?
I found this a bit surprising. As shown at the very top of this page in the bar graph, the average English word is 9 letters long. (This seems long to me!) Of course, we don't actually use most of those really long words (like antidisestablishmentarianism) in everyday discourse, so these long, rarely used words probably shift the distribution to the right. A distribution of the most commonly used words would certainly show that the average English word is shorter than 9 letters.

### Which words have the most unique letters?
16 letters is the record for the most unique letters, and six different English words can claim that title. They are:
- blepharoconjunctivitis
- formaldehydesulphoxylic
- pneumoventriculography
- pseudolamellibranchiata
- pseudolamellibranchiate
- superacknowledgment

Once again, these words are mostly technical, used only in chemistry, medicine, or biology. To me, these don't really count. "Superacknowledgement", however, does count, and I think it can lay claim to being the longest word in English that uses the most unique letters. Good luck using it in everyday conversation, though.

If you're curious, the distribution of English words by unique letters is shown below.

<img src = "https://github.com/alexberezow2024/english_word_length/blob/5eb6594c88f4399b951442d0bf77542e92a4d47a/distribution_english_words_unique_letters.png" width = "500">
