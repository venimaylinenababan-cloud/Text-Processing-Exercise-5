Exercise Analysis

Three ways of turning text into numbers:

- TF-IDF: gives each word a score based on how special it is in a review.
- Word2Vec: learns a vector for each word from the words around it (1,199 words, 100 numbers each).
- FastText: like Word2Vec, but it also looks at pieces of words, so it can handle words it has not seen before.
- 
In Word2Vec, the words most similar to game are play, get, candi, booster, like and level. These words show up in the same kinds of sentences. But all the similarity scores are close to each other (about 0.81 to 0.88), so the exact ranking is not exactly reliable. The dataset is small.


UMAP plots
We only plotted the top 50 words. At first, we tried plotting all the words, but there were too many points, and the labels covered each other. Plotting only the most frequent words made the plot easier to read.

