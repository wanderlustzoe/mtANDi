mtANDi
======

(Machine Translation and identefication)

Most of the code was provided by Professor Petrov. The assignment was to modify the skeleton code to make something work. 

The assignment was dependent on the following Java class provided by Professor Petrov.
nlp.assignments.WordAlignmentTester

The required package for running this program has not been posted on Github.

A few words:

First off, the goal in language modeling is to assign probability to sentences. This is especially helpful in machine translation and identification, spelling correction, and speech recognition. 

For this particular assignment, we were concerned first with 
-computing the probability of a word or a sequence of words :
P(w1, w2, w3, ... wn)
and then:
-computing the probability of upcoming words
P(w3|w1,w2)

To simplify this for larger units or sequences (which are more life like) we use the Markov Assumption which looks at only the last word (unigram), two words (bigram), trigram (three words)  or more (n-gram) in the sequence.

The more words you take the longer the processing time - hence the need for simplification using the Markov Assumption.


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/wanderlustzoe/mtandi/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

