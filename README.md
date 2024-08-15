# NLP_Tech_Talk
# Program 1
## English to Tamil & Hindi Translator with Python

This repository contains a Python script that translates English text to Tamil and Hindi using Google Translate API.

**Functionality:**

* The script defines two functions:
    * `translate_english_to_tamil(text)`: Takes English text as input and returns the translated Tamil text.
    * `translate_english_to_hindi(text)`: Takes English text as input and returns the translated Hindi text.

**How it Works:**

1. The script utilizes the `requests` library to make API calls to Google Translate.
2. Each function constructs a URL with the desired language pair (English to Tamil or Hindi) and the text to be translated.
3. The function sends a GET request to the URL and retrieves the JSON response.
4. The script parses the JSON response to extract the translated text.
5. In case of any errors during the translation process, the script catches the exception and prints an error message.

**Example Usage:**

The script includes an example demonstrating how to use the functions:

* Defines an English text variable `english_text`.
* Calls `translate_english_to_tamil` and `translate_english_to_hindi` functions with the English text.
* Prints the translated Tamil and Hindi text.

**Requirements:**

* Python 3
* `requests` library (install using `pip install requests`)

**Running the Script:**

1. Save the code as a Python file (e.g., `translator.py`).
2. Install the `requests` library using `pip install requests` in your terminal.
3. Run the script from the command line: `python translator.py`

**Disclaimer:**

This script uses Google Translate API for translation.  Please remember Google Translate's limitations and potential inaccuracies, especially for complex or nuanced text.

**Feel free to modify the script to translate between other languages supported by Google Translate API.** You can find information about supported languages in the Google Translate documentation: [https://cloud.google.com/translate/docs](https://cloud.google.com/translate/docs)

----------------------------------------------------------------------------------------------------------------------

# Program 2
## Text Processing with NLTK - Basic Analysis

This repository contains Python code that demonstrates basic text processing techniques using the Natural Language Toolkit (NLTK) library.

**Functionality:**

* The script performs tokenization, stop word removal, and frequency analysis on a sample corpus of sentences.
* It showcases how to break text into words, eliminate common words (stop words), and calculate word frequencies.

**How it Works:**

1. The script imports necessary NLTK functionalities for tokenization, n-grams, and frequency distribution.
2. It defines a sample corpus containing several sentences.
3. The code tokenizes each sentence, breaking it down into individual words.
4. Words are converted to lowercase for a consistent analysis.
5. Stop words (common words like "the" or "a") are removed using NLTK's stopword list.
6. Word frequencies are calculated using the `FreqDist` function.
7. The code can be further extended to analyze n-grams (sequences of words) or perform other text processing tasks.

**Running the Script:**

1. Save the code as a Python file (e.g., `text_analysis.py`).
2. Make sure you have NLTK installed (`pip install nltk`).
3. Run the script from the command line: `python text_analysis.py`

**Output:**

The script will print the following:

* Number of unique words in the corpus (after stop word removal).
* Most common words in the corpus (top 10 by frequency).

**Note:**

This is a basic example to illustrate fundamental NLP concepts. You can modify it to explore different functionalities of NLTK, including analyzing n-grams, stemming/lemmatization, or other text processing tasks.

**Additional Resources:**

* NLTK Documentation: [link to NLTK documentation]
* NLTK Stopwords: [link to NLTK stopwords documentation]
  
 -----------------------------------------------------------------------------------------------------------------------
# Program 3

## N-Gram Analysis with NLTK

This repository contains Python code that explores n-gram generation and frequency analysis for a sample corpus using the Natural Language Toolkit (NLTK) library.

**Functionality:**

* The script extracts unigrams (single words), bigrams (two-word sequences), and trigrams (three-word sequences) from each sentence in a corpus.
* It calculates the frequency distribution of bigrams to analyze word co-occurrence patterns.

**How it Works:**

1. The script leverages NLTK functions for tokenization and n-gram generation.
2. It iterates through each sentence in the corpus and generates unigrams, bigrams, and trigrams using the `ngrams` function.
3. N-grams represent sequences of words that can provide insights into language patterns and word co-occurrence.
4. The code calculates the frequency distribution of bigrams using `FreqDist`, indicating how often each bigram appears in the corpus.

**Running the Script:**

1. Save the code as a Python file (e.g., `ngram_analysis.py`).
2. Make sure you have NLTK installed (`pip install nltk`).
3. Run the script from the command line: `python ngram_analysis.py`

**Output:**

The script will print:

* The total number of unigrams, bigrams, and trigrams extracted from the corpus.
* A list of all generated unigrams, bigrams, and trigrams.
* The frequency distribution of bigrams, showing the number of times each bigram appears.

**Understanding N-Grams:**

* Unigrams represent single words in the text.
* Bigrams capture the relationship between two consecutive words.
* Trigrams consider the relationship between three consecutive words.

**Applications of N-Grams:**

* N-gram analysis helps understand language patterns and word co-occurrence.
* It finds applications in tasks like language modeling, speech recognition, and machine translation.

**Additional Resources:**

* NLTK Documentation: [link to NLTK documentation]
* NLTK N-grams: [link to NLTK ngrams documentation]

This code provides a basic example of n-gram analysis. You can further explore building language models or using n-grams for other NLP tasks.
---------------------------------------------------------------------------------------------------------------------

This README provides a basic explanation of the script and its functionality. You can further enhance it by adding:

