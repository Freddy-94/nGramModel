# n-gram-model.  

## Description

This program implements the n-gram-model (https://en.wikipedia.org/wiki/N-gram), to study similarities between texts. In this particular example, we've selected three different texts, containing the lyrics of two nice Mexican songs, along with one poem of the Uruguayan writer Mario Benedetti, although it can be modified to pass any documents we might want to analyze. Notice that this model generalize the bag-of-words-model (https://en.wikipedia.org/wiki/Bag-of-words_model), by buidling the bag of words with words consisting with text of more than only one word (the intention behind this idea is for analyzing part of the context in the texts we're analyzing). 

## Execution of the program

In your terminal run the command: python nGramModel.py

Notice that the source code must be "outside" the folder "InputTexts" that has the texts we want to analyze.

## Relevant functions:

1. clean_data -> "clean" the input text data. Also, in this function we implement the method to obatin an "n-grammar". 
2. vectorization_frequencies -> vectorization of input texts, as vectors of frequencies (via the "n-words" obtained).
3. cos_similarities -> Computation of the cosine similarity between vectors (input texts represented by vectors, via its "n-words").

# Songs:

1. "Mi Ciudad"                                 -> https://www.youtube.com/watch?v=o-MUhCDHw98
2. "Mexico Mil Novecientos Siempre"            -> https://www.youtube.com/watch?v=XDkVxtLduJI
3. "Te quiero"                                 -> https://www.youtube.com/watch?v=o_gWW2ZwBXY


## References:
1. https://en.wikipedia.org/wiki/Vector_space_model
2. https://en.wikipedia.org/wiki/Tf%E2%80%93idf
3. https://en.wikipedia.org/wiki/Bag-of-words_model
4. https://en.wikipedia.org/wiki/Cosine_similarity
5. https://en.wikipedia.org/wiki/Information_retrieval
6. https://en.wikipedia.org/wiki/N-gram
