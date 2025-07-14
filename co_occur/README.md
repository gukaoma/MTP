# Using co-occurences to measure similarity

Sentence co-occurence is when two words appear in the same sentence. Inuitively, we can assume that words who appear in the same sentence often have some relation to each other.

By counting the number of co-occurences of each pair of words, we can create a basic measure of the strength of a relationship between two words. One of the drawbacks of this method is that it is semantically oblivious, and doesn't take into account words that provide context such as "not," "unlike," or "different."

The following graph is a visual representation of the largeset connected component of terms from the English vocabulary set.

![Plotted Network: Main component of English Vocab terms](EngVocab%20Co-occur%20graph.png "Co-Occurence Graph")
