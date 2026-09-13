# WordPiece Tokenization

## Overview

This project demonstrates the basic working of WordPiece Tokenization using Python.

WordPiece Tokenization is a subword tokenization technique commonly used in Natural Language Processing. It divides words into smaller meaningful tokens and can also handle unknown words using the `[UNK]` token.

## Training Words

The following words are used for training:

* book
* books
* cook

## Features

* Creates an initial vocabulary
* Splits words into subword tokens
* Calculates token frequencies
* Calculates pair frequencies
* Calculates WordPiece scores
* Finds the best token pair
* Merges the selected token pair
* Performs tokenization
* Converts tokens into token IDs
* Handles unknown words using `[UNK]`

## Technologies Used

* Python
* Jupyter Notebook
* Collections Counter

## How It Works

The implementation follows these steps:

1. Define the training words.
2. Split each word into initial subword tokens.
3. Create the initial vocabulary.
4. Calculate token frequencies.
5. Calculate pair frequencies.
6. Calculate WordPiece scores.
7. Select the best pair based on the highest score.
8. Merge the selected pair.
9. Update the vocabulary.
10. Tokenize a new word.
11. Convert tokens into token IDs.
12. Test an unknown word.

## Output

The program displays:

* Initial Vocabulary
* Training Words
* Initial Splits
* Token Frequencies
* Pair Frequencies
* WordPiece Scores
* Best Pair
* Updated Vocabulary
* Updated Splits
* Tokens
* Token IDs
* Unknown Word Result

## Conclusion

This project provides a simple implementation of WordPiece Tokenization and demonstrates how subword tokens, vocabulary, token frequencies, pair frequencies, and token IDs are generated using Python.
