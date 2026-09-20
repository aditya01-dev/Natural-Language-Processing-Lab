# Natural-Language-Processing-Lab


This repository contains the implementations of practical experiments prescribed for the Natural Language Processing Laboratory course. Natural Language Processing (NLP) is an important area of Artificial Intelligence that focuses on enabling computers to process, understand, analyze, and generate human language.

The repository presents a progressive collection of practical experiments, beginning with fundamental text preprocessing and linguistic analysis, continuing through classical machine-learning approaches, and extending to neural networks and transformer-based NLP techniques.

---

About the Repository

This repository serves as a structured academic record of the Natural Language Processing Laboratory.

The practicals are primarily implemented in Python using Google Colab / Jupyter Notebook. Each practical focuses on a particular NLP concept and includes its objective, theoretical concept, implementation approach, expected output, learning outcome, and result.

The repository is intended for:

- Laboratory submission
- Practical implementation
- NLP concept revision
- Academic reference
- Understanding classical and modern NLP techniques

---

Student Details

Detail| Information
Name| Aditya Kumar Singh
Roll Number| 2401331520018
Course| B.Tech CSE (Artificial Intelligence)
Branch| AI
Section| A
Semester| 5th
Subject| Natural Language Processing Laboratory
Institution| Noida Institute of Engineering and Technology (NIET), Greater Noida
University| Dr. A.P.J. Abdul Kalam Technical University (AKTU)

---

Course Outcomes

CO| Focus Area
CO1| Fundamental NLP preprocessing and linguistic analysis including tokenization, stemming, lemmatization, POS tagging, parsing, chunking, and Named Entity Recognition.
CO2| Classical NLP representation and modeling including BoW, TF-IDF, similarity measures, word embeddings, classification, sentiment analysis, topic modeling, and information retrieval.
CO3| Advanced NLP using neural and transformer-based approaches including RNN/LSTM, attention, BERT, GPT-2, translation, summarization, conversational systems, and hybrid sequence modeling.

«Note: These course outcomes summarize the practical coverage of this repository and should not be considered the official wording issued by the institution.»

---

Technologies and Libraries

Category| Tools / Libraries
Programming Language| Python
Development Environment| Google Colab, Jupyter Notebook
Text Processing| NLTK, spaCy
Machine Learning| scikit-learn
Word Embeddings| Gensim, GloVe
Sentiment Analysis| TextBlob, VADER
Deep Learning| TensorFlow, Keras, PyTorch
Transformer Models| Hugging Face Transformers, Hugging Face Datasets
Data Handling| NumPy, Pandas
Visualization| Matplotlib, Seaborn

«Note: Individual notebooks use only the libraries required for their respective practical implementations.»

---

Environment and Requirements

The practical notebooks are designed primarily for Google Colab. Required Python packages, datasets, NLTK resources, spaCy models, and pretrained transformer models may be installed or downloaded during notebook execution.

For local execution, Python 3.x with the required libraries should be installed.

Basic installation:

pip install nltk spacy scikit-learn gensim textblob vaderSentiment numpy pandas matplotlib seaborn

Additional libraries may be required for specific transformer and deep-learning practicals.

---

Complete Practical Index

S.No.| Practical| CO| Notebook
1| Tokenization of Sentences and Words using NLTK and spaCy| CO1| "Open Notebook" (./NLP_Practical_01_Tokenization.ipynb)
2| Stemming and Lemmatization on Sample Text| CO1| "Open Notebook" (./NLP_Practical_02_Stemming_Lemmatization.ipynb)
3| Stop-word Removal from a Document| CO1| "Open Notebook" (./NLP_Practical_03_Stopword_Removal.ipynb)
4| Part-of-Speech (POS) Tagging of a Given Sentence| CO1| "Open Notebook" (./NLP_Practical_04_POS_Tagging.ipynb)
5| Parsing and Chunking using Regex and spaCy| CO1| "Open Notebook" (./NLP_Practical_05_Parsing_Chunking.ipynb)
6| Named Entity Recognition (NER) using spaCy| CO1| "Open Notebook" (./NLP_Practical_06_NER_spaCy.ipynb)
7| Coreference Resolution using neuralcoref or Similar Approach| CO2| "Open Notebook" (./NLP_Practical_07_Coreference_Resolution.ipynb)
8| Bag-of-Words (BoW) Vectorization and Representation| CO2| "Open Notebook" (./NLP_Practical_08_Bag_of_Words.ipynb)
9| TF-IDF Implementation and Comparison with BoW| CO2| "Open Notebook" (./NLP_Practical_09_TFIDF_vs_BoW.ipynb)
10| N-Gram Model: Uni-Gram, Bi-Gram and Tri-Gram Generation| CO2| "Open Notebook" (./NLP_Practical_10_NGrams.ipynb)
11| Cosine Similarity between Text Documents| CO2| "Open Notebook" (./NLP_Practical_11_Cosine_Similarity.ipynb)
12| Word2Vec Word Embeddings using Gensim| CO2| "Open Notebook" (./NLP_Practical_12_Word2Vec.ipynb)
13| GloVe Embeddings Loading and Vector Representation| CO2| "Open Notebook" (./NLP_Practical_13_GloVe.ipynb)
14| Text Similarity using Word Mover's Distance| CO2| "Open Notebook" (./NLP_Practical_14_WMD.ipynb)
15| Text Classification using Naïve Bayes/SVM with TF-IDF| CO2| "Open Notebook" (./NLP_Practical_15_Text_Classification.ipynb)
16| Sentiment Analysis using TextBlob and VADER| CO2| "Open Notebook" (./NLP_Practical_16_Sentiment_Analysis.ipynb)
17| Topic Modeling using Latent Dirichlet Allocation| CO2| "Open Notebook" (./NLP_Practical_17_LDA.ipynb)
18| Topic Modeling using Latent Semantic Analysis| CO2| "Open Notebook" (./NLP_Practical_18_LSA.ipynb)
19| Opinion Mining on Product/Service Reviews| CO2| "Open Notebook" (./NLP_Practical_19_Opinion_Mining.ipynb)
20| Information Extraction from Structured/Unstructured Documents| CO2| "Open Notebook" (./NLP_Practical_20_Information_Extraction.ipynb)
21| Information Retrieval with TF-IDF Ranking| CO2| "Open Notebook" (./NLP_Practical_21_Information_Retrieval.ipynb)
22| Sequence Classification using RNN/LSTM| CO2| "Open Notebook" (./NLP_Practical_22_RNN_LSTM.ipynb)
23| Implementation of Attention Mechanism| CO2| "Open Notebook" (./NLP_Practical_23_Attention_Mechanism.ipynb)
24| Fine-Tuning BERT for Text Classification| CO3| "Open Notebook" (./NLP_Practical_24_BERT_Fine_Tuning.ipynb)
25| Sentence Embeddings using BERT and GPT-2| CO3| "Open Notebook" (./NLP_Practical_25_BERT_GPT2_Embeddings.ipynb)
26| Text Generation using GPT-2| CO3| "Open Notebook" (./NLP_Practical_26_GPT2_Text_Generation.ipynb)
27| Named Entity Recognition using BERT| CO3| "Open Notebook" (./NLP_Practical_27_BERT_NER.ipynb)
28| Machine Translation using MarianMT or T5| CO3| "Open Notebook" (./NLP_Practical_28_Machine_Translation.ipynb)
29| Text Summarization using BART or T5| CO3| "Open Notebook" (./NLP_Practical_29_Text_Summarization.ipynb)
30| Chatbot using a Pre-trained Transformer| CO3| "Open Notebook" (./NLP_Practical_30_Transformer_Chatbot.ipynb)
31| Automatic Document Classification and Separation| CO3| "Open Notebook" (./NLP_Practical_31_Document_Classification.ipynb)
32| Hybrid Probabilistic + FSM Sequence Modeling| CO3| "Open Notebook" (./NLP_Practical_32_Hybrid_Sequence_Modeling.ipynb)

---

Detailed Documentation

Practical 1 — Tokenization of Sentences and Words using NLTK and spaCy

Theory / Concept:
Tokenization divides text into smaller units called tokens. Tokens may represent complete sentences or individual words and form the foundation of most NLP pipelines.

Field| Details
Objective| To perform sentence and word tokenization using NLTK and spaCy.
Key Topics| Sentence tokenization, word tokenization, punctuation handling, contractions
Libraries / Tools| NLTK, spaCy, Python
Implementation Overview| Input text is processed using NLTK tokenizers and the spaCy pipeline, followed by comparison of outputs.
Expected Output| Tokenized sentences and words.
Learning Outcome| Understands how raw text is converted into NLP tokens.
Result| Text was successfully tokenized using NLTK and spaCy.

---

Practical 2 — Stemming and Lemmatization

Theory / Concept:
Stemming and lemmatization normalize words into base forms. Stemming generally removes word suffixes, whereas lemmatization attempts to produce a linguistically meaningful dictionary form.

Field| Details
Objective| To perform stemming and lemmatization and compare their outputs.
Key Topics| Porter Stemmer, WordNet, lemmatization, normalization
Libraries / Tools| NLTK, spaCy
Implementation Overview| Sample words are processed using stemming and lemmatization techniques.
Expected Output| Original, stemmed, and lemmatized forms.
Learning Outcome| Understands the difference between stemming and lemmatization.
Result| Words were successfully normalized using both approaches.

---

Practical 3 — Stop-word Removal

Theory / Concept:
Stop words are frequently occurring words that often contribute limited semantic information in specific NLP tasks. Removing them can reduce preprocessing noise.

Field| Details
Objective| To identify and remove stop words from text.
Key Topics| Stop words, token filtering, preprocessing
Libraries / Tools| NLTK, spaCy
Implementation Overview| Text is tokenized and common stop words are filtered.
Expected Output| Original and filtered text.
Learning Outcome| Understands stop-word filtering in NLP preprocessing.
Result| Stop words were successfully removed from the sample document.

---

Practical 4 — Part-of-Speech Tagging

Theory / Concept:
POS tagging assigns grammatical categories such as noun, verb, adjective, and adverb to individual tokens.

Field| Details
Objective| To assign POS tags to words in a sentence.
Key Topics| Nouns, verbs, adjectives, adverbs, POS tags
Libraries / Tools| NLTK, spaCy
Implementation Overview| Sentence tokens are processed through POS tagging tools.
Expected Output| Tokens accompanied by grammatical tags.
Learning Outcome| Understands grammatical classification of words.
Result| POS tags were successfully generated.

---

Practical 5 — Parsing and Chunking

Theory / Concept:
Parsing analyzes sentence structure, while chunking identifies meaningful groups such as noun phrases and verb phrases.

Field| Details
Objective| To perform parsing and shallow chunking.
Key Topics| Regex chunking, noun phrases, verb phrases, dependency parsing
Libraries / Tools| NLTK, spaCy
Implementation Overview| POS-tag patterns are used for chunking and spaCy is used for syntactic analysis.
Expected Output| Extracted grammatical chunks and parse information.
Learning Outcome| Understands shallow and dependency-based parsing.
Result| The input sentence was successfully parsed and chunked.

---

Practical 6 — Named Entity Recognition using spaCy

Theory / Concept:
NER identifies real-world entities such as people, organizations, locations, and dates from text.

Field| Details
Objective| To identify and classify named entities using spaCy.
Key Topics| PERSON, ORG, GPE, DATE, NER
Libraries / Tools| spaCy
Implementation Overview| Text is processed through a pretrained spaCy NER pipeline.
Expected Output| Entity names and their labels.
Learning Outcome| Understands entity extraction from unstructured text.
Result| Named entities were successfully identified and classified.

---

Practical 7 — Coreference Resolution

Theory / Concept:
Coreference resolution identifies expressions that refer to the same entity, such as connecting a pronoun with the person or object it represents.

Field| Details
Objective| To identify and resolve coreferent mentions.
Key Topics| Pronoun resolution, entity mentions, coreference clusters
Libraries / Tools| spaCy, neuralcoref or compatible alternatives
Implementation Overview| Text is passed through a coreference-resolution approach.
Expected Output| Resolved mentions or entity clusters.
Learning Outcome| Understands document-level entity references.
Result| Coreferent mentions were identified using the selected approach.

---

Practical 8 — Bag-of-Words Representation

Theory / Concept:
Bag-of-Words represents documents using word-frequency vectors while ignoring word order.

Field| Details
Objective| To convert text documents into numerical BoW vectors.
Key Topics| Vocabulary, word counts, sparse vectors
Libraries / Tools| scikit-learn, NLTK
Implementation Overview| CountVectorizer creates a vocabulary and document-term matrix.
Expected Output| Numerical word-count matrix.
Learning Outcome| Understands basic numerical representation of text.
Result| The corpus was successfully converted into BoW representation.

---

Practical 9 — TF-IDF and BoW Comparison

Theory / Concept:
TF-IDF assigns higher importance to terms that are frequent in a document but relatively uncommon across the complete corpus.

Field| Details
Objective| To generate TF-IDF vectors and compare them with BoW.
Key Topics| TF, IDF, TF-IDF, BoW
Libraries / Tools| scikit-learn
Implementation Overview| TF-IDF vectors are generated and compared against raw word counts.
Expected Output| TF-IDF matrix and BoW matrix.
Learning Outcome| Understands weighted text representation.
Result| TF-IDF representation was successfully generated and compared.

---

Practical 10 — N-Gram Model

Theory / Concept:
An N-gram is a contiguous sequence of N tokens. Unigrams, bigrams, and trigrams capture increasingly larger local contexts.

Field| Details
Objective| To generate unigram, bigram, and trigram sequences.
Key Topics| N-grams, context, word order
Libraries / Tools| NLTK, scikit-learn
Implementation Overview| N-gram sequences are generated from a sample corpus.
Expected Output| Lists or frequency counts of N-grams.
Learning Outcome| Understands local contextual information in text.
Result| Required N-gram sequences were successfully generated.

---

Practical 11 — Cosine Similarity

Theory / Concept:
Cosine similarity measures similarity between vector representations based on the angle between the vectors.

Field| Details
Objective| To calculate similarity between text documents.
Key Topics| Vector space, TF-IDF, cosine similarity
Libraries / Tools| scikit-learn, NumPy
Implementation Overview| Documents are converted to vectors and pairwise similarity is calculated.
Expected Output| Similarity matrix or similarity scores.
Learning Outcome| Understands vector-based document comparison.
Result| Document similarity was successfully calculated.

---

Practical 12 — Word2Vec

Theory / Concept:
Word2Vec produces dense word vectors that capture relationships between words using contextual information.

Field| Details
Objective| To train and explore Word2Vec word embeddings.
Key Topics| CBOW, Skip-gram, embeddings, semantic similarity
Libraries / Tools| Gensim, NLTK
Implementation Overview| A corpus is prepared and a Word2Vec model is trained.
Expected Output| Word vectors and similar-word results.
Learning Outcome| Understands dense semantic word representations.
Result| Word embeddings were successfully trained and explored.

---

Practical 13 — GloVe Embeddings

Theory / Concept:
GloVe creates word representations using global word co-occurrence information.

Field| Details
Objective| To load and use pretrained GloVe embeddings.
Key Topics| Word vectors, global co-occurrence, similarity
Libraries / Tools| Gensim, NumPy
Implementation Overview| Pretrained GloVe vectors are loaded and queried.
Expected Output| Word vectors and similar-word information.
Learning Outcome| Understands pretrained embedding representations.
Result| GloVe vectors were successfully loaded and utilized.

---

Practical 14 — Word Mover's Distance

Theory / Concept:
Word Mover's Distance compares documents by calculating the semantic movement required between their word embeddings.

Field| Details
Objective| To calculate semantic distance between documents.
Key Topics| Word embeddings, semantic distance, WMD
Libraries / Tools| Gensim, Word2Vec
Implementation Overview| Document pairs are compared using embedding-based distance.
Expected Output| WMD scores.
Learning Outcome| Understands semantic similarity beyond exact word matching.
Result| Semantic distance was successfully calculated.

---

Practical 15 — Text Classification using Naïve Bayes/SVM

Theory / Concept:
Text classification assigns predefined categories to documents using extracted numerical features and machine-learning classifiers.

Field| Details
Objective| To classify documents using TF-IDF with Naïve Bayes/SVM.
Key Topics| TF-IDF, Naïve Bayes, SVM, classification
Libraries / Tools| scikit-learn
Implementation Overview| Text is converted into TF-IDF features and supplied to a classifier.
Expected Output| Predicted classes and evaluation metrics.
Learning Outcome| Understands classical machine-learning-based text classification.
Result| Text documents were successfully classified.

---

Practical 16 — Sentiment Analysis

Theory / Concept:
Sentiment analysis determines the emotional orientation of text, commonly represented as positive, negative, or neutral.

Field| Details
Objective| To analyze sentiment using TextBlob and VADER.
Key Topics| Polarity, subjectivity, sentiment scores
Libraries / Tools| TextBlob, VADER
Implementation Overview| Sample text is processed using both sentiment-analysis approaches.
Expected Output| Sentiment scores and labels.
Learning Outcome| Understands lexicon-based sentiment analysis.
Result| Sentiments were successfully analyzed using both tools.

---

Practical 17 — Topic Modeling using LDA

Theory / Concept:
Latent Dirichlet Allocation is an unsupervised probabilistic technique used to discover hidden topics within a collection of documents.

Field| Details
Objective| To identify latent topics in a text corpus.
Key Topics| Topic modeling, LDA, topic-word distributions
Libraries / Tools| Gensim, scikit-learn
Implementation Overview| Documents are represented numerically and an LDA model is trained.
Expected Output| Topics and their important words.
Learning Outcome| Understands unsupervised topic discovery.
Result| Latent topics were successfully extracted from the corpus.

---

Practical 18 — Topic Modeling using LSA

Theory / Concept:
Latent Semantic Analysis uses dimensionality reduction, commonly through Singular Value Decomposition, to identify latent semantic relationships.

Field| Details
Objective| To extract latent semantic topics using LSA.
Key Topics| TF-IDF, SVD, dimensionality reduction
Libraries / Tools| scikit-learn
Implementation Overview| A TF-IDF matrix is generated and reduced using SVD.
Expected Output| Semantic components and important terms.
Learning Outcome| Understands algebraic topic modeling.
Result| Latent semantic components were successfully extracted.

---

Practical 19 — Opinion Mining

Theory / Concept:
Opinion mining analyzes subjective text such as product or service reviews to determine the polarity of opinions.

Field| Details
Objective| To perform opinion mining on review data.
Key Topics| Review sentiment, opinion polarity, sentiment distribution
Libraries / Tools| TextBlob, VADER, Pandas, scikit-learn
Implementation Overview| Reviews are loaded, analyzed, and aggregated according to sentiment.
Expected Output| Opinion labels and sentiment distribution.
Learning Outcome| Understands sentiment analysis on review datasets.
Result| Review opinions were successfully analyzed.

---

Practical 20 — Information Extraction

Theory / Concept:
Information Extraction converts unstructured or semi-structured text into structured information such as entities, fields, and relationships.

Field| Details
Objective| To extract useful structured information from documents.
Key Topics| Entity extraction, patterns, NER, structured information
Libraries / Tools| spaCy, NLTK, Python regex
Implementation Overview| Pattern matching and NLP techniques are combined to extract information.
Expected Output| Structured information extracted from text.
Learning Outcome| Understands conversion of free text into structured data.
Result| Relevant information was successfully extracted.

---

Practical 21 — Information Retrieval using TF-IDF

Theory / Concept:
Information Retrieval identifies relevant do
