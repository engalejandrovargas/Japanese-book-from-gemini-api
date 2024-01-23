# Japanese books using google gemini-api

### Overview

This repository contains a couple of notebooks. Where Japanese Grammar conatins the code needed to create a whole book of grammar tailored to my own needs based just on a few words or the specific patterns of Japanese Grammar.
The notebook related with voabulary, takes images from a book, extract the words and then the words are translated in a specific format.

### Features

* Data Import and Cleaning: The notebook begins by importing Japanese language data from an Excel file, ensuring a clean and usable dataset by removing any missing values.
* AI-Generated Grammar Explanations: Utilizing Google's generative AI (google.generativeai), the notebook employs a model named "gemini-pro" to generate comprehensive explanations of Japanese words and grammar points.
* Custom Function for Content Generation: A custom Python function prompt_words takes Japanese words as input and produces detailed content including grammar explanations, usage cases, user demographics, examples, synonyms, and antonyms.
* Hiragana Readings and English Translations: Each entry is accompanied by hiragana readings and English translations.
* Interactive and Extensible: Users can input new Japanese words or grammar points to generate new content, making the notebook an evolving resource for Japanese language learning.
