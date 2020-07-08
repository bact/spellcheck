# spellcheck
Spellchecker experiment

Goal:
- Application: preprocess text to improve search and classification/clustering performance
- Good enough for classification (where the whole system does not depend only on the accuracy of spell checker)
- Good enough for search (where other edit distance and proximity search can be applied to improve usability)
- Fast enough to process large amount of text (corpus of 1 GB text in couple minutes)

Non-goal (yet):
- Good enough for linguistic analysis

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

- Parallel Spell-Checking Algorithm Based on Yahoo! N-Grams Dataset https://arxiv.org/abs/1204.0184
- An unsupervised and customizable misspelling generator for mining noisy health-related text sources https://arxiv.org/abs/1806.00910
- Keyword Typo Generator http://tools.seobook.com/spelling/keywords-typos.cgi 

- TCC + TCCT https://books.google.ie/books?id=pkGpLwH70w0C&pg=PA223&lpg=PA223&dq=word+segmentation+ngram+tcc&source=bl&ots=trQtTk9s4d&sig=ACfU3U1Ht4RWtx3dtwpmF-p3F4163r-acw&hl=en&sa=X&ved=2ahUKEwjE05m5v7jqAhVRtHEKHe3AAm4Q6AEwAXoECAsQAQ#v=onepage&q=word%20segmentation%20ngram%20tcc&f=false 
