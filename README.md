# Sentence Analysis Algorithm

## Overview

This algorithm works with a sentence to determine:

1. The total number of characters in the sentence.
2. The total number of words in the sentence.
3. The total number of vowels in the sentence.

## How It Works

The algorithm performs the following steps:

1. **Length Calculation**: It counts every character in the sentence, including spaces and punctuation marks.
2. **Word Count**: It counts the number of words by identifying spaces that separate words.
3. **Vowel Count**: It counts the number of vowels (a, e, i, o, u) in both uppercase and lowercase.

## Special case; last word

- **Last Word**: The algorithm ensures that the last word is counted by checking if the last character is not a space after processing the entire sentence.
