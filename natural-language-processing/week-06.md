# NPTEL Natural Language Processing Week 06 Assignment Answers

Are you looking for NPTEL Natural Language Processing Week 06 Assignment Answers? This repository will help you find your answers and solutions for Week 06 of the **Natural Language Processing** course. We provide detailed solutions to help you complete your assignments efficiently.

Natural Language Processing Nptel Week 6 Quiz Answers (Jan-Apr 2025)
Course Link: Click Here

With respect to a Dependency Structure, which of the following is not a valid criterion for a syntactic relation between a head H and a dependent D in a construction C?
H determines the syntactic category of C
The form of H depends on D.
H selects D and determines whether D is obligatory.
The linear position of D is specified with reference to H
View Answer
Which of the following is False about formal conditions of dependency graph?
Syntactic structure is hierarchical
Some word can have more than one syntactic head
There should not be any crossing of dependencies
Syntactic structure is complete
View Answer
Which of the following condition is false about directed spanning tree? A directed spanning tree of a (multi-) digraph G = (V, A) is a subgraph G’ = (V’, A’) such that:
VeV
A’ is subset of A
JAT = IV1-1
G’ is cyclic
View Answer
Consider the following graph with a root node and 3 other vertices. The edge weights between all the pairs of nodes have been provided. Suppose you use Chu-Liu-Edmonds algorithm to find the MST for this graph. Which pair of nodes will have to be contracted to form a single vertex during the algorithm in the 1st iteration?
(V2, V3)
(V1, V3)
All these pairs will get contracted at different times in the algorithm
(V1, V2)
View Answer
See also  Natural Language Processing Nptel Week 3 Quiz Answers
Suppose you write down the sequence of actions that generate the parse tree of the sentence “I prefer NLP course” using Arc-Eager Parsing. The number of times you have to use Right Arc, Left Arc, Reduce, Shift is: Format of the answer is [a, b, c, d] corresponding to the 4 values in the order specified in the query.
[0,2,1,1]
[1,2,1,3]
[1,2,0,3]
[1,2,0,2]
View Answer
Correct sequence of actions that generates the parse tree of the sentence “I prefer NLP course” using Arc-Eager Parsing is: Note: Right Arc (RA), Left Arc (LA), Reduce (RE), Shift (SH)
SH > LA > SH > SH > LA > RA
SH > LA > SH > RE > LA > RA
SH > LA > SH > SH > RA > LA
SH > LA > RE > SH > SH > LA
View Answer
Suppose you are training MST Parser for dependency and the sentence, “I like offline exam” occurs in the training set. The POS tags for these words are Pronoun, Verb, PropNoun, and Noun, respectively. Also, for simplicity, assume that there is only one dependency relation, “rel”. Thus, for every arc from word wi to wj, your features may be simplified to depend only on words wi and wj and not on the relation label. Below is the set of features:
pos(wi) = Verb and pos(wj) = Noun | Pronoun
wi = Root | wi occurs before wj in the sentence
wi = Root and pos(wj) = Verb
wj occurs before wi in the sentence
The feature weights before the start of the iteration are: [5, 20, 15, 12] Suppose you are also given that after applying the Chu-Liu Edmonds, you get the following parse tree:
{Root → like, like → I, I → offline, offline → exam} What would be the weights after this iteration?
[6, 19, 14, 13]
[6, 19, 15, 13]
[6, 19, 13, 13]
[6, 19, 15, 12]
View Answer
See also  Natural Language Processing Nptel Week 1 Quiz Answers
Assume that you are learning a classifier for the data-driven deterministic parsing and the sentence “I prefer NLP course” is a gold-standard parse in your training data. You are also given that NLP and “course” are “Nouns”, “I” is a “Pronoun” while the POS tag of “prefer” is “Verb”. Obtain the dependency graph for this sentence on your own. Assume that your features correspond to the following conditions:
The stack is empty.
Top of stack is Noun and Top of buffer is Verb.
Top of stack is Pronoun and Top of buffer is Verb.
The word at the top of stack occurs before the word at the top of the buffer in the sentence.
The initial weights of your features are: [2,2,2,2 | 3,3,3,2] [2,2,2,2 | 2,2,2,2] where the first four features correspond to LA, and then to RA, SH, and RE, respectively. Use this gold standard parse during online learning. What will be the weights after completing two iterations of Arc-Eager parsing over this sentence?
[2,2,2,2 | 3,3,3,2] [2,2,2,2 | 2,2,2,2]
[2,2,3,2 | 2,3,2,1] [3,2,2,2 | 2,2,2,2]
[2,2,3,3 | 2,3,2,1] [3,2,2,2 | 2,2,2,2]
[2,2,3,3 | 3,3,2,1] [3,2,2,2 | 2,2,2,2]
View Answer
