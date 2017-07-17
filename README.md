# Natural-Language-Processing
Unit 4 : DS Applications | Lesson 2 : Natural Language Processing 


**Slide deck:** [NLP with scikit-learn (PPTX)](./assets/slides/nlp.pptx)
**Notebook:** [natural-language-processing.ipynb](./natural-language-processing.ipynb)
    - No solutions needed.
    - This lesson uses the Naive Bayes model MultinomialNB, which is often used for NLP applications such as spam detection. An appendix is included at the end of the lesson for interested students. However, this model will be covered in much more detail in another lesson so the appendix is optional.


**Optional Material:**
This optional material covers Bayes Theorem and Naive Bayes. These are not the main themes of this lesson, but the Iris notebook and decks could be used to get a head start on later Bayes material, which is typically tough for students.
    - Brief slide decks:
        - [Naive Bayes (PPTX)](./assets/slides/naive_bayes.pptx)
        - [Bayes Theorem (PPTX)](./assets/slides/bayes_theorem.pptx)
    - [Exploring Bayes Theorem with Iris Notebook](./extra-materials/bayes_theorem_iris.ipynb). 



### Lesson Prework

To procede through the lesson, first install TextBlob as explained below. We tend to prefer Anaconda-based installations, since they tend to be tested with our other Anaconda packages. However, in this case TextBlob is not available on some platforms with Anaconda (e.g. Win64).


**To install textblob run:**

> `conda install -c https://conda.anaconda.org/sloria textblob`

**Or:**

> `pip install textblob`

> `python -m textblob.download_corpora lite`


### Learning Objectives
- **Discuss** the major tasks involved with natural language processing
- **Discuss**, on a low level, the components of natural language processing
- **Identify** why natural language processing is difficult
- **Demonstrate** text classification
- **Demonstrate** common text preprocessing techniques


### Lesson Guide

- [Introduction to Natural Language Processing](#intro)
- [Reading Yelp reviews with NLP](#yelp_rev)
- [Text Classification](#text_class)
- [Count Vectorization](#count_vec)
    - [Using CountVectorizer in a model](#countvectorizer-model)
    - [N-Grams](#ngrams)
    - [Stopword Removal](#stopwords)
	- [Count Vector Options](#cvec_opt)
- [Intro to TextBlob](#textblob)
	- [Stemming and Lemmatization](#stem)
- [Term Frequency Inverse Document Frequency Vectorization](tfidf)
	- [Yelp Summary using TFIDF](#yelp_tfidf)
- [Sentiment Analysis](#sentiment)
- [BONUS: Adding Features to a Document Term Matrix](#add_feat)
- [BONUS: More TextBlob Features](#more_textblob)
- [APPENDIX: Intro to Naive Bayes & Text Classification](#bayes)
- [Conclusion](#conclusion)