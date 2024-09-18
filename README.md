# Simple Word Autocomplete / Autocorrect and Word Probability
### by Cole Chiodo

## Code Explaination
To Code this, I needed to create a couple simple functions. First I needed a function to translate a list of words to a dictionary of those words with those frequencies. Next I needed a function that took that dictionary and added the relative frequency, or the probability, or each word by dividing the frequency with the total number of words. In this project, these values are only needed for the output. In the future we will need these probabilities to make better guesses. Lastly, I get the users input. If not found in the list of words, I need to suggest the 5 closest words using Levenshtein method of the Minimum Edit Disatnce Algorithm.

## Challenges Faced
The overall project was fairly simple, so I did not enounter too many challenges. However, one problem I did run into was due to my unfamiliarity with python. I was unsure about how to sort the Levenshtein_distance dictionary from lowest score to highest. I used a couple online resources before I finally got something to work.
