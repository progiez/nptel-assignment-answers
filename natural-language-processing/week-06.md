## Natural Language Processing Nptel Week 6 Quiz Answers (Jan-Apr 2025)

**Course Link: [**Click Here**](https://onlinecourses.nptel.ac.in/noc25_cs51/course)**

***

1. **With respect to a Dependency Structure, which of the following is not a valid criterion for a syntactic relation between a head H and a dependent D in a construction C?**

   1. H determines the syntactic category of C
   2. The form of H depends on D.
   3. H selects D and determines whether D is obligatory.
   4. The linear position of D is specified with reference to H

   [View Answer](https://my.progiez.com/courses/natural-language-processing-nptel-answers/)

***

2. **Which of the following is False about formal conditions of dependency graph?**

   1. Syntactic structure is hierarchical
   2. Some word can have more than one syntactic head
   3. There should not be any crossing of dependencies
   4. Syntactic structure is complete

   [View Answer](https://my.progiez.com/courses/natural-language-processing-nptel-answers/)

***

3. **Which of the following condition is false about directed spanning tree?** A directed spanning tree of a (multi-) digraph G = (V, A) is a subgraph G’ = (V’, A’) such that:

   1. VeV
   2. A’ is subset of A
   3. JAT = IV1-1
   4. G’ is cyclic

   [View Answer](https://my.progiez.com/courses/natural-language-processing-nptel-answers/)

***

4. **Consider the following graph with a root node and 3 other vertices. The edge weights between all the pairs of nodes have been provided. Suppose you use Chu-Liu-Edmonds algorithm to find the MST for this graph. Which pair of nodes will have to be contracted to form a single vertex during the algorithm in the 1st iteration?**

   1. (V2, V3)
   2. (V1, V3)
   3. All these pairs will get contracted at different times in the algorithm
   4. (V1, V2)

   [View Answer](https://my.progiez.com/courses/natural-language-processing-nptel-answers/)

[****See also**  **Natural Language Processing Nptel Week 3 Quiz Answers****](https://progiez.com/natural-language-processing-nptel-week-3-quiz-answers)

***

5. **Suppose you write down the sequence of actions that generate the parse tree of the sentence “I prefer NLP course” using Arc-Eager Parsing. The number of times you have to use Right Arc, Left Arc, Reduce, Shift is:** Format of the answer is **\[a, b, c, d]** corresponding to the 4 values in the order specified in the query.

   1. \[0,2,1,1]
   2. \[1,2,1,3]
   3. \[1,2,0,3]
   4. \[1,2,0,2]

   [View Answer](https://my.progiez.com/courses/natural-language-processing-nptel-answers/)

***

6. **Correct sequence of actions that generates the parse tree of the sentence “I prefer NLP course” using Arc-Eager Parsing is:** Note: Right Arc (RA), Left Arc (LA), Reduce (RE), Shift (SH)

   1. SH > LA > SH > SH > LA > RA
   2. SH > LA > SH > RE > LA > RA
   3. SH > LA > SH > SH > RA > LA
   4. SH > LA > RE > SH > SH > LA

   [View Answer](https://my.progiez.com/courses/natural-language-processing-nptel-answers/)

***

7. **Suppose you are training MST Parser for dependency and the sentence, “I like offline exam” occurs in the training set. The POS tags for these words are Pronoun, Verb, PropNoun, and Noun, respectively. Also, for simplicity, assume that there is only one dependency relation, “rel”. Thus, for every arc from word wi to wj, your features may be simplified to depend only on words wi and wj and not on the relation label.** Below is the set of features:

   1. pos(wi) = Verb and pos(wj) = Noun | Pronoun
   2. wi = Root | wi occurs before wj in the sentence
   3. wi = Root and pos(wj) = Verb
   4. wj occurs before wi in the sentence

   The feature weights before the start of the iteration are: **\[5, 20, 15, 12]** Suppose you are also given that after applying the Chu-Liu Edmonds, you get the following parse tree:\
   **{Root → like, like → I, I → offline, offline → exam}** What would be the weights after this iteration?

   1. \[6, 19, 14, 13]
   2. \[6, 19, 15, 13]
   3. \[6, 19, 13, 13]
   4. \[6, 19, 15, 12]

   [View Answer](https://my.progiez.com/courses/natural-language-processing-nptel-answers/)

[****See also**  **Natural Language Processing Nptel Week 1 Quiz Answers****](https://progiez.com/natural-language-processing-nptel-week-1-quiz-answers)

***

8. **Assume that you are learning a classifier for the data-driven deterministic parsing and the sentence “I prefer NLP course” is a gold-standard parse in your training data. You are also given that NLP and “course” are “Nouns”, “I” is a “Pronoun” while the POS tag of “prefer” is “Verb”.** Obtain the dependency graph for this sentence on your own. Assume that your features correspond to the following conditions:

   1. The stack is empty.
   2. Top of stack is Noun and Top of buffer is Verb.
   3. Top of stack is Pronoun and Top of buffer is Verb.
   4. The word at the top of stack occurs before the word at the top of the buffer in the sentence.

   The initial weights of your features are: **\[2,2,2,2 | 3,3,3,2] \[2,2,2,2 | 2,2,2,2]** where the first four features correspond to **LA**, and then to **RA, SH, and RE**, respectively. Use this gold standard parse during online learning. What will be the weights after completing two iterations of Arc-Eager parsing over this sentence?

   1. \[2,2,2,2 | 3,3,3,2] \[2,2,2,2 | 2,2,2,2]
   2. \[2,2,3,2 | 2,3,2,1] \[3,2,2,2 | 2,2,2,2]
   3. \[2,2,3,3 | 2,3,2,1] \[3,2,2,2 | 2,2,2,2]
   4. \[2,2,3,3 | 3,3,2,1] \[3,2,2,2 | 2,2,2,2]

   [View Answer](https://my.progiez.com/courses/natural-language-processing-nptel-answers/)

9.
