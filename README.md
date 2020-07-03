# spellcheck
Spellchecker experiment

Goal:
- Application: preprocess text to improve search and classification/clustering performance
- Good enough for classification (where the whole system does not depend only on the accuracy of spell checker)
- Good enough for search (where other edit distance and proximity search can be applied to improve usability)
- Fast enough to process large amount of text (corpus of 1 GB text in couple minutes)

## Some links on spell checking

Basics:
- How to Write a Spelling Corrector https://norvig.com/spell-correct.html
- Spelling Checking Algorithms https://cs.brynmawr.edu/Courses/cs330/spring2012/SpellingCheckers.pdf
- Spell checker https://en.wikipedia.org/wiki/Spell_checker

Discussions:
- What algorithm gives suggestions in a spell checker? https://stackoverflow.com/questions/2294915/what-algorithm-gives-suggestions-in-a-spell-checker

More techniques:
- Build a spell-checker with word2vec data (with python) https://medium.com/@thomasdecaux/build-a-spell-checker-with-word2vec-data-with-python-5438a9343afd 
- 1000x Faster Spelling Correction algorithm (2012) https://medium.com/@wolfgarbe/1000x-faster-spelling-correction-algorithm-2012-8701fcd87a5f
- Finite-State Spell-Checking with Weighted Language and Error Models—Building and Evaluating Spell-Checkers with Wikipedia as Corpus https://www.researchgate.net/publication/228543643_Finite-State_Spell-Checking_with_Weighted_Language_and_Error_Models-Building_and_Evaluating_Spell-Checkers_with_Wikipedia_as_Corpus
- Language Models: Spellchecking and Autocorrection https://towardsdatascience.com/language-models-spellchecking-and-autocorrection-dd10f739443c
- Essential text correction process for NLP tasks https://towardsdatascience.com/essential-text-correction-process-for-nlp-tasks-f731a025fcc3
- Building Real-World Finite-State Spell-Checkers With HFST https://www.computing.dcu.ie/~tpirinen/fsmnlp-2012-spelling-tutorial.pdf
- A context sensitive real-time Spell Checker with language adaptability https://arxiv.org/pdf/1910.11242.pdf
- Effective Spell Checking Methods Using Clustering Algorithms https://www.aclweb.org/anthology/R13-1023.pdf

For search/query application:
- A Frequency-based Technique to Improve the Spelling Suggestion Rank in Medical Queries https://www.ncbi.nlm.nih.gov/pmc/articles/PMC400516/
- A UMLS-based spell checker for natural language processing in vaccine safety https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/1472-6947-7-3 

Competition:
- A Basic Spell Checker https://www.hackerrank.com/challenges/basic-spell-checker/problem
