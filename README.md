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

Thai-specific:
- Thai Spelling Correction and Word Normalizationon Social Text Using a Two-Stage Pipeline With Neural Contextual Attention https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9145483
- Spell Checker for Thai Document (post-process for OCR) https://ieeexplore.ieee.org/document/4085130

More techniques:
- Build a spell-checker with word2vec data (with python) https://medium.com/@thomasdecaux/build-a-spell-checker-with-word2vec-data-with-python-5438a9343afd 
- 1000x Faster Spelling Correction algorithm (2012) https://medium.com/@wolfgarbe/1000x-faster-spelling-correction-algorithm-2012-8701fcd87a5f
- Finite-State Spell-Checking with Weighted Language and Error Models—Building and Evaluating Spell-Checkers with Wikipedia as Corpus https://www.researchgate.net/publication/228543643_Finite-State_Spell-Checking_with_Weighted_Language_and_Error_Models-Building_and_Evaluating_Spell-Checkers_with_Wikipedia_as_Corpus
- Language Models: Spellchecking and Autocorrection https://towardsdatascience.com/language-models-spellchecking-and-autocorrection-dd10f739443c
- Essential text correction process for NLP tasks https://towardsdatascience.com/essential-text-correction-process-for-nlp-tasks-f731a025fcc3
- Building Real-World Finite-State Spell-Checkers With HFST https://www.computing.dcu.ie/~tpirinen/fsmnlp-2012-spelling-tutorial.pdf
- A context sensitive real-time Spell Checker with language adaptability https://arxiv.org/abs/1910.11242
- Effective Spell Checking Methods Using Clustering Algorithms https://www.aclweb.org/anthology/R13-1023/

For search/query application:
- A Frequency-based Technique to Improve the Spelling Suggestion Rank in Medical Queries https://www.ncbi.nlm.nih.gov/pmc/articles/PMC400516/
- A UMLS-based spell checker for natural language processing in vaccine safety https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/1472-6947-7-3 

Competition:
- A Basic Spell Checker https://www.hackerrank.com/challenges/basic-spell-checker/problem

N-Grams
- Parallel Spell-Checking Algorithm Based on Yahoo! N-Grams Dataset https://arxiv.org/abs/1204.0184
- Web News N-gram https://blog.gdeltproject.org/announcing-the-web-ngram-character-ngram-datasets/
- Integrating Dictionary and Web N-grams for Chinese Spell Checking https://www.aclweb.org/anthology/O13-5002/
- Thai Word Segmentation based-on GLR Parsing Technique and Word N-gram Model https://thailang.nectec.or.th/downloadcenter/index7787.html?option=com_docman&task=doc_details&gid=17&Itemid=61

Misspelling generator
- An unsupervised and customizable misspelling generator for mining noisy health-related text sources https://arxiv.org/abs/1806.00910
- Keyword Typo Generator http://tools.seobook.com/spelling/keywords-typos.cgi 

Segmentation
- TCC + TCCT https://books.google.ie/books?id=pkGpLwH70w0C&pg=PA223&lpg=PA223&dq=word+segmentation+ngram+tcc&source=bl&ots=trQtTk9s4d&sig=ACfU3U1Ht4RWtx3dtwpmF-p3F4163r-acw&hl=en&sa=X&ved=2ahUKEwjE05m5v7jqAhVRtHEKHe3AAm4Q6AEwAXoECAsQAQ#v=onepage&q=word%20segmentation%20ngram%20tcc&f=false 
- https://towardsdatascience.com/query-segmentation-and-spelling-correction-483173008981
- https://github.com/wolfgarbe/WordSegmentationTM
- https://github.com/wolfgarbe/SymSpell

## OCR
- https://source.opennews.org/articles/so-many-ocr-options/

## Analysis of errors
- อักษรกาญจน์, ส. (2016). การศึกษาลักษณะข้อผิดพลาดในการเขียนภาษาไทยของนักศึกษา ระดับปริญญาตรี คณะครุศาสตร์ มหาวิทยาลัยราชภัฏสุราษฎร์ธานี ปีการศึกษา 2558. ราชภัฏเพชรบูรณ์สาร, 18(2), 65–74.

## Uncategorized

- A Basic Spell Checker. (n.d.). HackerRank. Retrieved 8 May 2021, from https://www.hackerrank.com/challenges/basic-spell-checker/problem
- Ad Group Filter. (n.d.). Retrieved 8 May 2021, from http://tools.seobook.com/spelling/keywords-typos.cgi
- Analyizing spelling errors. (n.d.). Lexercise. Retrieved 8 May 2021, from http://support.lexercise.com/hc/en-us/community/posts/220971827-Analyizing-spelling-errors-
- Announcing The WEB-NGRAM Character Ngram Datasets – The GDELT Project. (n.d.). Retrieved 8 May 2021, from https://blog.gdeltproject.org/announcing-the-web-ngram-character-ngram-datasets/
- Arndt, E. J., & Foorman, B. R. (2010). Second Graders as Spellers: What Types of Errors Are They Making? Assessment for Effective Intervention, 36(1), 57–67. https://doi.org/10.1177/1534508410380135
- Bassil, Y. (2012). Parallel Spell-Checking Algorithm Based on Yahoo! N-Grams Dataset. ArXiv:1204.0184 [Cs]. http://arxiv.org/abs/1204.0184
- Best AI Writing Assistant Software in 2021. (n.d.). G2. Retrieved 1 April 2021, from https://www.g2.com/categories/ai-writing-assistant
- Bestgen, Y., & Granger, S. (2011). Categorizing spelling errors to assess L2 writing. International Journal of Continuing Engineering Education and Life-Long Learning, 21, 235–252. https://doi.org/10.1504/IJCEELL.2011.040201
- Blank, D. (n.d.). Spelling Checking Algorithms. 20.
- Clough, P., Gaizauskas, R., & Piao, S. L. (2002, May). Building and annotating a corpus for the study of journalistic text reuse. Proceedings of the Third International Conference on Language Resources and Evaluation (LREC’02). LREC 2002, Las Palmas, Canary Islands - Spain. http://www.lrec-conf.org/proceedings/lrec2002/pdf/218.pdf
- Crowell, J., Zeng, Q., Ngo, L., & Lacroix, E.-M. (2004). A Frequency-based Technique to Improve the Spelling Suggestion Rank in Medical Queries. Journal of the American Medical Informatics Association : JAMIA, 11(3), 179–185. https://doi.org/10.1197/jamia.M1474
- de Amorim, R. C., & Zampieri, M. (2013). Effective Spell Checking Methods Using Clustering Algorithms. Proceedings of the International Conference Recent Advances in Natural Language Processing RANLP 2013, 172–178. https://www.aclweb.org/anthology/R13-1023
- Decaux, T. (2018, July 13). Build a spell-checker with word2vec data (with python). Medium. https://thomasdecaux.medium.com/build-a-spell-checker-with-word2vec-data-with-python-5438a9343afd
- Document Details | Thai Word Segmentation based-on GLR Parsing Technique and Word N-gram Model. (n.d.). Retrieved 8 May 2021, from https://thailang.nectec.or.th/downloadcenter/index7787.html?option=com_docman&task=doc_details&gid=17&Itemid=61
- Flor, M., Fried, M., & Rozovskaya, A. (2019). A Benchmark Corpus of English Misspellings and a Minimally-supervised Model for Spelling Correction. Proceedings of the Fourteenth Workshop on Innovative Use of NLP for Building Educational Applications, 76–86. https://doi.org/10.18653/v1/W19-4407
- Fossati, D., & Di Eugenio, B. (2007). A Mixed Trigrams Approach for Context Sensitive Spell Checking. In A. Gelbukh (Ed.), Computational Linguistics and Intelligent Text Processing (pp. 623–633). Springer. https://doi.org/10.1007/978-3-540-70939-8_55
- Full Text PDF. (n.d.). Retrieved 8 May 2021, from https://www.aclweb.org/anthology/R13-1023.pdf
- Garbe, W. (2020, December 16). 1000x Faster Spelling Correction algorithm (2012). Medium. https://wolfgarbe.medium.com/1000x-faster-spelling-correction-algorithm-2012-8701fcd87a5f
- Garbe, W. (2021). Wolfgarbe/SymSpell [C#]. https://github.com/wolfgarbe/SymSpell (Original work published 2014)
- Garbe, W. (2021). Wolfgarbe/WordSegmentationTM [C#]. https://github.com/wolfgarbe/WordSegmentationTM (Original work published 2018)
- Grundkiewicz, R., & Junczys-Dowmunt, M. (2019). Minimally-Augmented Grammatical Error Correction. Proceedings of the 5th Workshop on Noisy User-Generated Text (W-NUT 2019), 357–363. https://doi.org/10.18653/v1/D19-5546
- Gupta, P. (2019). A context sensitive real-time Spell Checker with language adaptability. ArXiv:1910.11242 [Cs, Stat]. http://arxiv.org/abs/1910.11242
- H, K., M, F., K, R., & D, D.-F. (2015). An Ensemble Method for Spelling Correction in Consumer Health Questions. AMIA ... Annual Symposium Proceedings. AMIA Symposium, 2015, 727–736.
- Hagiwara, M. (00:00:00-04:00). The Unreasonable Effectiveness of the Transformer Spell Checker. Real-World Natural Language Processing. http://www.realworldnlpbook.com/blog/unreasonable-effectiveness-of-transformer-spell-checker.html
- Han, T., Am, & Hickman,  a. (n.d.). Our Search for the Best OCR Tool, and What We Found. Retrieved 8 May 2021, from https://source.opennews.org/articles/so-many-ocr-options/
- How to Write a Spelling Corrector. (n.d.). Retrieved 8 May 2021, from https://norvig.com/spell-correct.html
- Jayanthi, S. M., Pruthi, D., & Neubig, G. (2020). NeuSpell: A Neural Spelling Correction Toolkit. Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing: System Demonstrations, 158–164. https://doi.org/10.18653/v1/2020.emnlp-demos.21
- Jessica. (2020, May 20). 12 Writing Assistant Software Apps Currently Using Artificial Intelligence (AI). Scribe Syndicate. http://scribesyndicate.com/12-writing-assistant-software-apps-currently-using-artificial-intelligence-ai/
- Keras-team/keras-io. (n.d.). GitHub. Retrieved 1 April 2021, from https://github.com/keras-team/keras-io
- language agnostic—What algorithm gives suggestions in a spell checker? (n.d.). Stack Overflow. Retrieved 8 May 2021, from https://stackoverflow.com/questions/2294915/what-algorithm-gives-suggestions-in-a-spell-checker
- Languagetool-org/languagetool. (2021). [Java]. LanguageTool. https://github.com/languagetool-org/languagetool (Original work published 2013)
- Lertpiya, A., Chalothorn, T., & Chuangsuwanich, E. (2020). Thai Spelling Correction and Word Normalization on Social Text Using a Two-Stage Pipeline With Neural Contextual Attention. IEEE Access, 8, 133403–133419. https://doi.org/10.1109/ACCESS.2020.3010828
- Ma, E. (2018, November 17). Essential text correction process for NLP tasks. Medium. https://towardsdatascience.com/essential-text-correction-process-for-nlp-tasks-f731a025fcc3
- Negri, M., Turchi, M., Chatterjee, R., & Bertoldi, N. (2018, May). ESCAPE: A Large-scale Synthetic Corpus for Automatic Post-Editing. Proceedings of the Eleventh International Conference on Language Resources and Evaluation (LREC 2018). LREC 2018, Miyazaki, Japan. https://www.aclweb.org/anthology/L18-1004
- neuspell. (2021). Neuspell/neuspell [Python]. https://github.com/neuspell/neuspell (Original work published 2020)
- Patil, S. (2017, August 10). Language Models: Spellchecking and Autocorrection. Medium. https://sanketp.medium.com/language-models-spellchecking-and-autocorrection-dd10f739443c
- Pirinen, T., & Lindén, K. (2012). Finite-State Spell-Checking with Weighted Language and Error Models—Building and Evaluating Spell-Checkers with Wikipedia as Corpus.
- PubMed Central Full Text PDF. (n.d.). Retrieved 8 May 2021, from https://www.ncbi.nlm.nih.gov/pmc/articles/PMC400516/pdf/179.pdf
- PubMed Central Link. (n.d.). Retrieved 8 May 2021, from https://www.ncbi.nlm.nih.gov/pmc/articles/PMC400516/
- Query Segmentation and Spelling Correction | by Sonu Sharma | Towards Data Science. (n.d.). Retrieved 8 May 2021, from https://towardsdatascience.com/query-segmentation-and-spelling-correction-483173008981
- Sarker, A., & Gonzalez-Hernandez, G. (2018). An unsupervised and customizable misspelling generator for mining noisy health-related text sources. ArXiv:1806.00910 [Cs]. http://arxiv.org/abs/1806.00910
- Snapshot. (n.d.-a). Retrieved 8 May 2021, from https://wolfgarbe.medium.com/1000x-faster-spelling-correction-algorithm-2012-8701fcd87a5f
- Snapshot. (n.d.-b). Retrieved 8 May 2021, from https://thomasdecaux.medium.com/build-a-spell-checker-with-word2vec-data-with-python-5438a9343afd
- Spell checker. (2021). In Wikipedia. https://en.wikipedia.org/w/index.php?title=Spell_checker&oldid=1019221795
- Tolentino, H. D., Matters, M. D., Walop, W., Law, B., Tong, W., Liu, F., Fontelo, P., Kohl, K., & Payne, D. C. (2007). A UMLS-based spell checker for natural language processing in vaccine safety. BMC Medical Informatics and Decision Making, 7(1), 3. https://doi.org/10.1186/1472-6947-7-3
- White, M., & Rozovskaya, A. (2020). A Comparative Study of Synthetic Data Generation Methods for Grammatical Error Correction. Proceedings of the Fifteenth Workshop on Innovative Use of NLP for Building Educational Applications, 198–208. https://doi.org/10.18653/v1/2020.bea-1.21
- Whitelaw, C., Hutchinson, B., Chung, G. Y., & Ellis, G. (2009). Using the Web for Language Independent Spellchecking and Autocorrection. Proceedings of the 2009 Conference on Empirical Methods in Natural Language Processing, 890–899. https://www.aclweb.org/anthology/D09-1093
- Wu, J., Chiu, H., & Chang, J. S. (2013, December). Integrating Dictionary and Web N-grams for Chinese Spell Checking. International Journal of Computational Linguistics & Chinese Language Processing, Volume 18, Number 4, December 2013-Special Issue on Selected Papers from ROCLING XXV. ROCLING/IJCLCLP 2013. https://www.aclweb.org/anthology/O13-5002

