# Semantic-Similarity

This is a semantic descriptor tester, which is used to find words of similar meaning to a given word (synonyms). You can calculate the similarity of words by calculating how many times they appear in the same sentence.

In this code, to measure the semantic similarity of a pairs of words, first you have to compute a semantic descriptor vector of each of the words, and then taking the similarity measure (cosine similarity) between the two vectors.

A semantic descriptor is a long dictionary of test words as keys with another dictionary as its value. The inner dictionary contains words as keys and numbers as values, with the values corresponding to how many times the two keys appear in the same sentence. For example, if the semantic descriptor were sd = {...."fly":{"chicken": 2,..... "bird": 3}.....} then "fly" would have appeared in the same sentence as "bird" 3 times. 

To build a semantic descriptor, a sufficiently long text file with enough data has to be used There is a score that represents the correlation between two words, and that can be computed from many different formulas such as the cosine similarity and the Euclidean space formula.

Skeleton code from Michael Guerzhoy. 
