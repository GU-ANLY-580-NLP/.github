# ANLY-580 Natural Language Processing

### Instructors
- Chris Larson
- Trevor Adriaanse

### Teaching Assistants
- Jingson Gao
- Erocong Lou
- Linpei Zhang
- Chao Li
- Changwen Li

#
## Sections

| Section | Time | Location |
|:-----:|:-----:|:----:|
| I | Wed 3:30-6 PM EST | ICC 115 |
| II | Thurs 3:30-6 PM EST | ICC 103 |
| III | Mon 6:30-9 PM EST | ICC 101 |

#
## Course Description
Natural language processing (NLP) is a critical component of modern information systems. The confluence of deep learning base language modeling, massive datasets, and hardware accelerators is fundamentally changing the way humans interact with the world. In this course we will learn how language understanding can be framed as a tractable inference problem, state-of-the-art models and algorithms,and how NLP systems are design and evaluation. This course exposes students to the foundational math, implementation methods, practical applications, and research being conducted in NLP today. This course assumes a basic understanding of linear algebra, probability theory, and first order optimization methods.

## Reference Texts
1. <a href="https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf">Jacob Eisenstein. Natural Language Processing</a>
2. <a href="https://web.stanford.edu/~jurafsky/slp3/ed3book_dec302020.pdf">Dan Jurafsky, James H. Martin. Speech and Language Processing (3rd ed. draft)</a>

#
## Tools

This course assumes basic knowledge of Python. It is also helpful to have experience using Git and Github, though this isn't absolutely necessary as we will cover the basics in the first lab.

## Course Website

This course will primarily be conducted through Canvas, while all coding assignments and labs will be submitted through Github Classroom. This course also has a Discord server that will be used for common to all three sections. **Please join our [Discord](https://discord.gg/RczqzHTz) server at your earliest convenience.**

## Github
Students need to have a [Github account](https://github.com/join) to complete this course. **In order for the teaching staff to associate your Georgetown Account with your Github account, please enter your name, GU email, and Github handle in this table [table](https://docs.google.com/spreadsheets/d/1KT4qfeVM592Tq81bkqnRZD2jMTRRZKW79bnZpPpUdy0/edit#gid=0).**

## Submitting your work
This course will be conducted through Canvas and Github Classroom. You will submit assignments, labs, and the final project through Github Classroom. Quizzes will be submitted through Canvas. Links for these items will be sent out at the beginning of each Module.

#
## Grading Scale

| Score | Letter Grade |
|:-----:|:-----:|
| 92.5 $\leq$ score | A |
| 89.5 $\leq$ score $<$ 92.5 | A- |
| 87.99 $\leq$ score $<$ 89.5 | B+ |
| 81.5 $\leq$ score $<$ 87.99 | B |
| 79.5 $\leq$ score $<$ 81.5 | B- |


## Grade Components
The course grade is broken down in the table below. The course grade consists of 1000 total pts.


| Component | Weight | Format |
| :-----------: | :----: | :----------: |
| [Quiz 1](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/blob/main/quizzes/quiz-01.md) | 5% | individual |
| [Quiz 2](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/blob/main/quizzes/quiz-02.md) | 5% | individual |
| [Quiz 3](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/blob/main/quizzes/quiz-03.md) | 5% | individual | 
| [Assignment 1](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/blob/main/assignments/assignment-01.md) | 10% | groups <= 3 |
| [Assignment 2](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/blob/main/assignments/assignment-02.md) | 10% | individual |
| [Assignment 3](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/blob/main/assignments/assignment-03.md) | 10% | individual |
| [Labs](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/blob/main/labs) | 25% | individual |
| [Final Project]() | 30% | groups of <= 4 |

*Note: All submissions are due 11:59pm EST on the dates listed. Submissions turned in more than 24 hours late will be assessed a one-time 15% penalty.*

**Lab Grading**: There will be 10 graded labs each worth 2.5% of your total grade. Each lab task will be graded on a complete/incomplete basis, however incomplete tasks will not necessarily be penalized provided that effort was made to complete them (which we can glean from your git commit history and the questions you ask).

**Final Project Grading**: The rubrik for the final project will be included in the project description released during Lab-07.

#
## Course Schedule

| Section I | Section II | Section III | Event | Description | Course Materials |
| :-: | :-: | :-: | :-: | :- | :- |
| Aug 24 | Aug 25 | Aug 29 | [Lecture 01](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/lectures/lecture-01) <br/> [Lab 01](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/labs/lab-01) | **Introduction to NLP and deep learning** <br> - Course overview <br> - Math refresher <br> **Lab** <br> - Github onboarding <br> - Python environment setup | Suggested Reading: <br> [<a href="http://cs229.stanford.edu/section/cs229-linalg.pdf">Eisenstein, Appendix A, B.1, B.2</a>] <br> [<a href="http://cs229.stanford.edu/section/cs229-linalg.pdf">Linear algebra review</a>] <br> [<a href="http://www.columbia.edu/~ks20/4404-Sigman/Notes-Review-Prob.pdf">Probability theory review</a>] <br> [<a href="https://web.stanford.edu/~jurafsky/slp3/ed3book_dec302020.pdf">Jurafsky & Martin, Chp 7</a>] <br> [[Git+GitHub tutorial](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)] |
| Aug 31 | Sep 01 | Sep 06 | [Lab 01](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/labs/lab-01) due <br/> [Quiz 01](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/blob/main/quizzes/quiz-01.md) due | **11:59pm EST** <br/> **11:59pm EST**|
| Aug 31 | Sep 01 | Sep 06 | [Lecture 02](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/lectures/lecture-02) <br/> [Lab 02](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/labs/lab-02) | **Text Classification: Part I** <br> - Bag-of-words (BOW) <br> - Decision boundaries <br> - Linear classifiers <br> **Lab** <br> - Text Normalization <br> - Introduction to <a href="https://spacy.io/">Spacy</a> | Suggested Reading: <br> [<a href="https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf">Eisenstein, Chps 2.1, 2.2, 2.5</a>] <br> [<a href="https://web.stanford.edu/~jurafsky/slp3/ed3book_dec302020.pdf">Jurafsky & Martin, Chp 2.4,4</a>] <br> [<a href="https://www.aaai.org/Papers/ICML/2003/ICML03-081.pdf">Rennie et al., ICML 2003</a>] <br> [[Joachims, 1998](https://link.springer.com/content/pdf/10.1007/BFb0026683.pdf)] |
| Sep 07 | Sep 08 | Sep 12 | [Lab 02](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/labs/lab-02) due <br/> [Assignment 01]() due  | **11:59pm EST** <br> **11:59pm EST** |
| Sep 07 | Sep 08 | Sep 12 | [Lecture 03](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/lectures/lecture-03) <br/> [Lab 03](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/labs/lab-03) | **Text Classification: Part II** <br> - Maximum likelihood estimation <br> - Naive Bayes' classifier <br> - Softmax regression <br> **Lab** <br> - Linear text classification on DBpedia dataset <br> | Suggested Reading: <br> [<a href="https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf">Eisenstein, Chps 2.3, 2.4</a>] |
| Sep 14 | Sep 15 | Sep 19 | [Lab 03](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/labs/lab-03) due | **11:59pm EST** |
| Sep 14 | Sep 15 | Sep 19 | [Lecture 04](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/lectures/lecture-04) <br/> [Lab 04](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/labs/lab-04) | **Distributional Semantics: Part 1** <br> - TF-IDF, PMI <br> - Low-rank factorization <br> - Topic modeling <br> **Lab** <br> - Extracting topics from news feeds | Suggested Reading: <br> [[Ramos, 2003](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.121.1424&rep=rep1&type=pdf)] <br> [<a href="http://www2.denizyuret.com/ref/berry/berry95using.pdf">LSI overview</a>] <br> [<a href="https://davetang.org/file/Singular_Value_Decomposition_Tutorial.pdf">SVD tutorial</a>] <br> [[Lee et al., 2000](https://papers.nips.cc/paper/2000/file/f9d1152547c0bde01830b7e8bd60024c-Paper.pdf)] <br> [<a href="https://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf">Bei, et al., JMLR 2003</a>] <br> [<a href="https://radimrehurek.com/gensim/">Gensim website</a>] |
| Sep 26 | Sep 22 | Sep 26 | [Lab 04](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/labs/lab-04) due  <br/> [Quiz 02]() due | **11:59pm EST** <br> **11:59pm EST** |
| Sep 21 | Sep 22 | Sep 26 | [Lecture 05](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/lectures/lecture-05) <br> [Lab 05](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/labs/lab-05) | **Distributional Semantics: Part 2** <br> - Distributional hypothesis <br> - Skip-gram & CBOW models <br> - Word2Vec <br> **Lab** <br> - Visualizing Tweets with Word2Vec | Suggested Reading: <br> [<a href="https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf">Eisenstein, Chp 14</a>] <br> [<a href="https://arxiv.org/pdf/1301.3781.pdf">Mikolov et al., 2013</a>] <br> [<a href="https://pair-code.github.io/understanding-umap/">Blogpost on tSNE / UMAP</a>] |
| Sep 28 | Sep 29 | Oct 03 | [Lab 05](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/labs/lab-05) due <br> [Assignment 02](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/blob/main/assignments/assignment-02.md) due | **11:59pm EST** <br> **11:59pm EST** |
| Sep 28 | Sep 29 | Oct 03 | [Lecture 06](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/lectures/lecture-06) <br> [Lab 06](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/labs/lab-06) | **Language Modeling: Part 1** <br> - N-grams, sparse data & smoothing <br> - Markov models <br> **Lab** <br> - Build a semantic matching service with <a href="https://github.com/facebookresearch/StarSpace">StarSpace</a> and <a href="https://github.com/chrislarson1/virtex">Virtex</a> | Suggested Reading: <br> [<a href="https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf">Eisenstein, Chp 6.1-6.2</a>] <br> [<a href="https://web.stanford.edu/~jurafsky/slp3/ed3book_dec302020.pdf">Jurafsky & Martin, Chps 3, 8</a>] <br> [<a href="https://arxiv.org/pdf/1607.04606.pdf">Bojanowski et al., 2017</a>] <br> [<a href="https://arxiv.org/pdf/1709.03856.pdf">Wu et al., 2017</a>] <br> [<a href="https://fasttext.cc/">FastText</a>] |
| Oct 05 | Oct 06 | Oct 17 | [Lab 06](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/labs/lab-06) due | **11:59pm EST** |
| Oct 05 | Oct 06 | Oct 17 | [Lecture 07](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/lectures/lecture-07) <br> [Course Project kickoff](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/project) | **Language Modeling: Part 2** <br> - Introduction to neural language models <br> - Next word prediction <br> - Downstream tasks <br> - Evaluation metrics | Suggested Reading: <br> [<a href="https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes-10-15-2018.pdf">Eisenstein, Chp 3</a>] <br> [<a href="http://nlpprogress.com/">NLP Progress website</a>] <br> [<a href="https://huggingface.co/datasets">Huggingface Datasets</a>] <br> [<a href="https://aclanthology.org/W18-5446.pdf">Wang et al., 2018</a>] |
| Oct 12 | Oct 13 | Oct 24 | [Quiz 03](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/blob/main/quizzes/quiz-03.md) due | **11:59pm EST** |
| Oct 12 | Oct 13 | Oct 24 | [Lecture 08](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/lectures/lecture-08) <br> [Lab 08](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/labs/lab-08) | **Neural Network Architectures for Sequences: Part I** <br> - Convolutional filtering <br> - RNNs <br> - Seq2Seq models <br> **Lab** <br> - Introduction to <a href="https://huggingface.co/datasets">Huggingface</a> <br> - Train OpenNMT on en-de dataset | Suggested Reading: <br> [<a href="https://web.stanford.edu/~jurafsky/slp3/ed3book_dec302020.pdf">Jurafsky & Martin, Chp 9</a>] <br> [<a href="https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes-10-15-2018.pdf">Eisenstein, Chp 6.3</a>] <br> [<a href="https://arxiv.org/pdf/2004.03705.pdf">Review of neural network architectures</a>] <br> [<a href="https://arxiv.org/pdf/1609.04747.pdf">Overview of SGD algorithms</a>] <br> [<a href="https://arxiv.org/pdf/1508.06615.pdf">Kim et al., 2016</a>] <br> [[Minaee et al., 2020 (Sec. 2.8)](https://arxiv.org/pdf/2004.03705.pdf)] |
| Oct 19 | Oct 20 | Nov 03 | [Lab 08](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/labs/lab-08) due | **11:59pm EST** |
| Oct 19 | Oct 20 | Nov 03 | [Lecture 09](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/lectures/lecture-09) <br> [Lab 09](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/labs/lab-09) | **Neural Network Architectures for Sequences: Part II** <br> - Masked language model training <br> - Attention <br> - Transformers (BERT, GPT) <br> **Lab** <br> - Finetune BERT on DBpedia, CoNLL-2003, SQuADv2 | Suggested Reading: <br> [<a href="https://arxiv.org/pdf/1409.0473.pdf">Bahdanau et al., 2015</a>] <br> [<a href="https://arxiv.org/pdf/1609.08144v2.pdf">Wu et al., 2016</a>] <br> [<a href="https://arxiv.org/pdf/1706.03762.pdf">Vaswani et al., 2017</a>] <br> [<a href="https://arxiv.org/pdf/1810.04805.pdf">Devlin et al., 2019</a>] <br> [<a href="https://arxiv.org/pdf/2005.14165.pdf">Brown et al., 2020</a>] <br> [<a href="https://cdn.openai.com/palms.pdf">Solaiman et al., 2022</a>] |
| Oct 26 | Oct 27 | Nov 07 | [Lab 09](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/labs/lab-09) due <br> [Assignment 03](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/blob/main/assignments/assignment-03.ipynb) due | **11:59pm EST** |
| Oct 26 | Oct 27 | Nov 07 | [Lecture 10](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/lectures/lecture-10) <br> [Lab 10](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/labs/lab-10) | **Speech Processing** <br> *A Primer on Speech and Audio Applications* <br> Guest: Tarek Lahlou <br> Distinguished Data Scientist, Walmart Labs <br> **Lab** <br> - Finetune E2E RNNT on your own voice <br> | Suggested Reading: <br> [<a href="https://deepmind.com/blog/article/wavenet-generative-model-raw-audio">Deepmind blog post</a>] <br> [<a href="https://arxiv.org/pdf/2006.03575.pdf">Donahue et al., ICLR 2022</a>] <br> [<a href="https://arxiv.org/pdf/2102.04040.pdf">Luo et al., 2022</a>] <br> [<a href="https://arxiv.org/pdf/1211.3711.pdf">Graves, 2012</a>] <br> [<a href="https://arxiv.org/pdf/1811.06621.pdf">He et al., 2018</a>] |
| Nov 02 | Nov 03 | Nov 14 | [Lab 10](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/labs/lab-10) due | **11:59pm EST** |
| Nov 02 | Nov 03 | Nov 14 | [Lecture 11](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/lectures/lecture-12) | **NLP Systems** <br> - Recommender Systems <br> - Conversational Assistants | Suggested Reading: <br> [<a href="https://web.stanford.edu/~jurafsky/slp3/ed3book_dec302020.pdf">Jurafsky & Martin, Chp 24</a>] <br> [<a href="https://arxiv.org/pdf/1712.05181.pdf">Bocklisch et al., 2017</a>] |
| Nov 10 | Nov 10 | Nov 10 | [Project proposals]() due | **11:59pm EST** |
| Nov 09 | Nov 10 | Nov 21 | [Lecture 12](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/lectures/lecture-12) <br> [Lab 12](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/labs/lab-12) | **NLP System Design** <br> - Containerization & cloud deployment <br> - Kubernetes <br> - Model serving <br> **Lab** <br> - Deploy a model in a Kubernetes cluster |
| Nov 16 | Nov 17 | Nov 28 | [Lab 12](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/labs/lab-12) due | **11:59pm EST** |
| Nov 16 | Nov 17 | Nov 28 | [Lecture 13](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/tree/main/lectures/lecture-13) | **Ethics in NLP** <br> *Guest Lecture* TBD |  |
| Nov 30 | Dec 01 | Dec 05 | [Final Presentations]() | [Schedule & signup sheet]()| |


#
## Course Policies

Students are expected to adhere to all policies in the [Georgetown Honor System Handbook](https://honorcouncil.georgetown.edu/system/policies/), and be aware of [Title IX/Sexual Misconduct](https://sexualassault.georgetown.edu/resourcecenter).

Matters of academic integrity are takien seriously. All work submitted in this class is expected to be your own. In the case of code it is very common to use subroutines written by other people to perform specific tasks; this is OK but you must comment your code when doing so. Each student is required to acknowledge that they are aware of all course policies by completing the [course policy quiz](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/blob/main/quizzes/quiz-01.md).

A synopsis of these and other policies can be found [here](https://github.com/chrislarson1/GU-ANLY-580-FALL-2022/blob/main/gu-policies.md).

#
**Note**: *The course syllabus and schedule are subject to change at anytime. Changes will be communicated in advance.*