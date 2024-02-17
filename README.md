# Dictionary Word Search

## Overview
This project implements a dictionary word search using a Trie data structure and Levenshtein distance for suggestions. The system allows users to search for words in a dictionary and provides suggestions for similar words in case of a mismatch.

## Dependencies
- Levenshtein

## Usage

1. **Dictionary Building:** Load a list of words from a file and build a dictionary using a Trie data structure.

2. **Search Operation:** Allow users to input words for search.

3. **Search Result:** Display whether the entered word is found in the dictionary or provide suggestions for similar words.

4. **Exit Option:** Users can exit the search loop by typing 'no'.

## Process Explanation

1. **Dictionary Building:**
   - Load words from a file and insert them into a Trie data structure.
   - Trie provides efficient word storage and retrieval.

2. **Search Operation:**
   - Users can input a word for search.
   - The system checks for the word in the dictionary.

3. **Search Result:**
   - If the exact word is found, it is displayed as found.
   - If not found, suggestions for similar words are provided.

4. **Exit Option:**
   - Users can exit the search loop by typing 'no'.

## Note
- Ensure the file path for the dictionary list is correctly specified for successful execution.

Feel free to adapt the dictionary list and explore the search functionality.

## Author
**Kusumanjli**
**https://www.linkedin.com/in/kusumanjli-khattar-166b881b1/**
