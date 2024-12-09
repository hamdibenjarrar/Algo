# Analyze Sentence Algorithm

## Description

This algorithm processes a sentence character by character to calculate:
1. **Total Characters**: Counts all characters in the sentence except the period (`.`).
2. **Total Words**: Counts the number of words in the sentence, assuming words are separated by single spaces.
3. **Total Vowels**: Counts the total vowels (`a, e, i, o, u`, case-insensitive) in the sentence.

It reads each character until it encounters a period (`.`), treating it as the end of the sentence. The algorithm uses three counters:
- `char_count` for characters
- `word_count` for words
- `vowel_count` for vowels

## Input

The user is prompted to enter a sentence character by character, ending with a period (`.`).

### Example Input:
`"I love algorithms."`

## Output

The algorithm displays:
1. Total number of characters (excluding the period).
2. Total number of words.
3. Total number of vowels.

