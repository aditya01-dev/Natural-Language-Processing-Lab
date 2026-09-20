# Natural Language Processing Laboratory

This repository contains the implementations of the practicals prescribed for the **Natural Language Processing Laboratory** course. *Natural Language Processing (NLP)* is a core area of **Artificial Intelligence** concerned with enabling machines to understand, interpret, and generate human language. This repository documents a progressive set of experiments that move from foundational text preprocessing techniques to classical machine-learning-based NLP methods and, finally, to modern **transformer-based deep learning** approaches.

---

## About the Repository

This repository serves as a structured academic record of the Natural Language Processing Laboratory. It contains step-by-step implementations of NLP concepts, primarily developed in **Python** using **Google Colab**. Each practical is self-contained, demonstrating a specific NLP technique or concept, and is accompanied by detailed documentation explaining its *objective*, *theoretical background*, *implementation approach*, and *expected outcome*. The repository is intended to serve both as a laboratory submission and as a reference for revision.

---

## Student Details

| Detail          | Information                                                         |
| --------------- | ------------------------------------------------------------------- |
| **Name**        | Aditya Kumar Singh                                                  |
| **Course**      | B.Tech CSE (Artificial Intelligence)                                |
| **Subject**     | Natural Language Processing Laboratory                              |
| **Institution** | Noida Institute of Engineering and Technology (NIET), Greater Noida |
| **University**  | Dr. A.P.J. Abdul Kalam Technical University (AKTU)                  |

---

## Course Outcomes

| CO      | Focus Area                                                                                                                                                                                                  |
| ------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **CO1** | Fundamental NLP *preprocessing* and **linguistic analysis** — tokenization, stemming, lemmatization, POS tagging, parsing, chunking, and named entity recognition.                                          |
| **CO2** | Classical NLP *representation* and **modeling** — vector space models, similarity measures, word embeddings, text classification, sentiment analysis, topic modeling, and information extraction/retrieval. |
| **CO3** | Advanced **transformer-based** NLP — BERT, GPT-2, machine translation, text summarization, conversational agents, and hybrid sequence modeling.                                                             |

> *Note: These course outcomes are presented as a summary of the practical coverage in this repository and are not to be interpreted as the official wording issued by the institution.*

---

## Technologies and Libraries

| Category                    | Tools / Libraries                                                                                                                    |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| **Programming Language**    | [Python](https://www.python.org/)                                                                                                    |
| **Development Environment** | [Google Colab](https://colab.research.google.com/)                                                                                   |
| **Text Processing**         | [NLTK](https://www.nltk.org/), [spaCy](https://spacy.io/)                                                                            |
| **Machine Learning**        | [scikit-learn](https://scikit-learn.org/)                                                                                            |
| **Word Embeddings**         | [Gensim](https://radimrehurek.com/gensim/), GloVe                                                                                    |
| **Sentiment Analysis**      | [TextBlob](https://textblob.readthedocs.io/), [VADER](https://github.com/cjhutto/vaderSentiment)                                     |
| **Deep Learning**           | [TensorFlow](https://www.tensorflow.org/), [Keras](https://keras.io/), [PyTorch](https://pytorch.org/) *(where relevant)*            |
| **Transformer Models**      | [Hugging Face Transformers](https://huggingface.co/docs/transformers), [Hugging Face Datasets](https://huggingface.co/docs/datasets) |
| **Data Handling**           | [NumPy](https://numpy.org/), [Pandas](https://pandas.pydata.org/)                                                                    |
| **Visualization**           | [Matplotlib](https://matplotlib.org/), [Seaborn](https://seaborn.pydata.org/)                                                        |

> **Note:** Not every library listed above is used in every practical. Each notebook uses only the libraries relevant to its specific implementation.

---

## Environment and Requirements

All notebooks in this repository are designed to run on **[Google Colab](https://colab.research.google.com/)**. Most notebooks *install or download* the required dependencies, datasets, and pretrained models directly within the notebook at runtime, so no separate local environment setup is strictly required. It is recommended to run each notebook **sequentially from the first cell** to ensure all dependencies are correctly installed before execution.

---

## Complete Practical Index

| S.No. | Practical                                                                          | CO  | Notebook                                                                                                                                                         |
| ----- | ---------------------------------------------------------------------------------- | --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1     | Tokenization of Sentences and Words using NLTK and spaCy                           | CO1 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_01_Tokenization.ipynb)             |
| 2     | Stemming and Lemmatization on Sample Text                                          | CO1 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_02_Stemming_Lemmatization.ipynb)   |
| 3     | Stop-word Removal from a Document                                                  | CO1 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_03_Stopword_Removal.ipynb)         |
| 4     | Part-of-Speech (POS) Tagging of a Given Sentence                                   | CO1 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_04_POS_Tagging.ipynb)              |
| 5     | Parsing and Chunking using Regex and spaCy                                         | CO1 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_05_Parsing_Chunking.ipynb)         |
| 6     | Named Entity Recognition (NER) using spaCy                                         | CO1 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_06_NER_spaCy.ipynb)                |
| 7     | Coreference Resolution using neuralcoref (or Similar)                              | CO2 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_07_Coreference_Resolution.ipynb)   |
| 8     | Bag-of-Words (BoW) Vectorization and Representation                                | CO2 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_08_Bag_of_Words.ipynb)             |
| 9     | TF-IDF Implementation and Comparison with BoW                                      | CO2 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_09_TFIDF_vs_BoW.ipynb)             |
| 10    | N-Gram Model (Uni-, Bi-, Tri-Gram) Generation from Corpus                          | CO2 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_10_NGrams.ipynb)                   |
| 11    | Cosine Similarity Computation between Text Documents                               | CO2 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_11_Cosine_Similarity.ipynb)        |
| 12    | Word2Vec Word Embeddings using Gensim on a Custom Corpus                           | CO2 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_12_Word2Vec.ipynb)                 |
| 13    | GloVe Embeddings Loading and Vector Representation                                 | CO2 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_13_GloVe.ipynb)                    |
| 14    | Text Similarity using Word Mover's Distance (WMD)                                  | CO2 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_14_WMD.ipynb)                      |
| 15    | Text Classification using Naïve Bayes/SVM with TF-IDF                              | CO2 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_15_Text_Classification.ipynb)      |
| 16    | Sentiment Analysis using TextBlob and VADER                                        | CO2 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_16_Sentiment_Analysis.ipynb)       |
| 17    | Topic Modeling using Latent Dirichlet Allocation (LDA)                             | CO2 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_17_LDA.ipynb)                      |
| 18    | Topic Modeling using Latent Semantic Analysis (LSA)                                | CO2 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_18_LSA.ipynb)                      |
| 19    | Opinion Mining on Product/Service Reviews Dataset                                  | CO2 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_19_Opinion_Mining.ipynb)           |
| 20    | Information Extraction from Structured/Unstructured Documents                      | CO2 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_20_Information_Extraction.ipynb)   |
| 21    | Information Retrieval System with Ranking using TF-IDF                             | CO2 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_21_Information_Retrieval.ipynb)    |
| 22    | Sequence Classification using RNN/LSTM (Keras/TensorFlow)                          | CO2 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_22_RNN_LSTM.ipynb)                 |
| 23    | Implementing Attention Mechanism (Basic Custom Model)                              | CO2 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_23_Attention_Mechanism.ipynb)      |
| 24    | Fine-Tuning BERT for Text Classification using Hugging Face                        | CO3 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_24_BERT_Fine_Tuning.ipynb)         |
| 25    | Sentence Embeddings using BERT and GPT-2                                           | CO3 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_25_BERT_GPT2_Embeddings.ipynb)     |
| 26    | Text Generation using GPT-2 on a Custom Dataset                                    | CO3 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_26_GPT2_Text_Generation.ipynb)     |
| 27    | Named Entity Recognition using Transformers (BERT)                                 | CO3 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_27_BERT_NER.ipynb)                 |
| 28    | Machine Translation using MarianMT or T5 (Hugging Face)                            | CO3 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_28_Machine_Translation.ipynb)      |
| 29    | Text Summarization using BART or T5                                                | CO3 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_29_Text_Summarization.ipynb)       |
| 30    | Chatbot Development using Pre-trained Transformer (DialoGPT/ChatGPT-style)         | CO3 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_30_Transformer_Chatbot.ipynb)      |
| 31    | Automatic Document Classification and Separation using ML                          | CO3 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_31_Document_Classification.ipynb)  |
| 32    | Hybrid Probabilistic + FSM-Based Sequence Modeling for Document Boundary Detection | CO3 | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_32_Hybrid_Sequence_Modeling.ipynb) |

---

## Detailed Documentation

### Practical 1 — Tokenization of Sentences and Words using NLTK and spaCy

**Theory / Concept:** *Tokenization* is the process of breaking down a stream of text into smaller units called **tokens**, which can be sentences or words. It is the first and most fundamental step in nearly every NLP pipeline, since most downstream tasks operate on tokens rather than raw text. [NLTK](https://www.nltk.org/) uses rule-based tokenizers such as the **Punkt** sentence tokenizer, while [spaCy](https://spacy.io/) uses a model-driven pipeline that also accounts for linguistic exceptions such as contractions.

| Field                       | Details                                                                                                                                              |
| --------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To perform sentence and word tokenization on a given text using NLTK and spaCy, and compare the outputs.                                             |
| **Key Topics**              | Sentence tokenization • Word tokenization • Rule-based vs model-based tokenization • Handling punctuation/contractions                               |
| **Libraries / Tools**       | [NLTK](https://www.nltk.org/), [spaCy](https://spacy.io/), Python                                                                                    |
| **Implementation Overview** | Loads sample text → applies NLTK's tokenizers → applies spaCy's tokenization pipeline → prints and compares outputs.                                 |
| **Expected Output**         | Lists of sentences/words generated separately by NLTK and spaCy for the same input text.                                                             |
| **Learning Outcome**        | Understands how raw text becomes tokens, and the differences between rule-based and model-based tokenization.                                        |
| **Result**                  | *The given text was successfully tokenized into sentences and words using both NLTK and spaCy.*                                                      |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_01_Tokenization.ipynb) |

---

### Practical 2 — Stemming and Lemmatization on Sample Text

**Theory / Concept:** **Stemming** and **lemmatization** are normalization techniques that reduce inflected words to a base form. Stemming, typically via the **Porter Stemmer**, applies heuristic suffix-stripping rules and can produce non-dictionary forms. *Lemmatization*, using resources like **WordNet** or spaCy's lemmatizer, returns the true dictionary base form (**lemma**) and is linguistically more accurate but computationally heavier.

| Field                       | Details                                                                                                                                                        |
| --------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To reduce words to their root/base forms using stemming and lemmatization, and compare the two techniques.                                                     |
| **Key Topics**              | Stemming • Porter Stemmer • Lemmatization • WordNet/spaCy lemmatization • Stemming vs lemmatization                                                            |
| **Libraries / Tools**       | [NLTK](https://www.nltk.org/) (Porter Stemmer, WordNet Lemmatizer), [spaCy](https://spacy.io/)                                                                 |
| **Implementation Overview** | Applies the Porter Stemmer, then applies WordNet/spaCy lemmatization on the same text, and compares outputs.                                                   |
| **Expected Output**         | A comparison table showing the original word, its stemmed form, and its lemmatized form.                                                                       |
| **Learning Outcome**        | Understands the conceptual and practical differences between stemming and lemmatization.                                                                       |
| **Result**                  | *The given text was successfully processed to obtain stemmed and lemmatized forms, highlighting the differences between the two techniques.*                   |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_02_Stemming_Lemmatization.ipynb) |

---

### Practical 3 — Stop-word Removal from a Document

**Theory / Concept:** **Stop words** are high-frequency words (*"the," "is," "and," "in"*) that carry little semantic meaning and are typically removed during preprocessing to reduce noise. NLTK and spaCy provide predefined stop-word lists that can be customized. This step is especially useful for **text classification**, **topic modeling**, and **information retrieval**.

| Field                       | Details                                                                                                                                                  |
| --------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To identify and remove common stop words from a document, retaining only meaningful content-bearing words.                                               |
| **Key Topics**              | Role of stop words • Predefined stop-word lists • Filtering during preprocessing • Impact on downstream tasks                                            |
| **Libraries / Tools**       | [NLTK](https://www.nltk.org/), [spaCy](https://spacy.io/)                                                                                                |
| **Implementation Overview** | Tokenizes a sample document and filters out tokens matching a predefined stop-word list.                                                                 |
| **Expected Output**         | Original tokenized document alongside a filtered version with stop words removed.                                                                        |
| **Learning Outcome**        | Learns how to identify and remove non-informative words in the preprocessing pipeline.                                                                   |
| **Result**                  | *The given document was successfully filtered to remove stop words, retaining only content-bearing tokens.*                                              |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_03_Stopword_Removal.ipynb) |

---

### Practical 4 — Part-of-Speech (POS) Tagging of a Given Sentence

**Theory / Concept:** **POS tagging** labels each word in a sentence with its grammatical category — noun, verb, adjective, adverb, etc. These tags provide essential syntactic information used in **parsing**, **chunking**, and **NER**. NLTK uses statistical taggers trained on the **Penn Treebank** tag set, while spaCy assigns POS tags as part of a broader linguistic pipeline.

| Field                       | Details                                                                                                                                             |
| --------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To assign grammatical POS tags to each word in a given sentence using NLTK and/or spaCy.                                                            |
| **Key Topics**              | Grammatical categories • Penn Treebank tag set • NLTK POS tagging • spaCy POS tagging                                                               |
| **Libraries / Tools**       | [NLTK](https://www.nltk.org/), [spaCy](https://spacy.io/)                                                                                           |
| **Implementation Overview** | Tokenizes a sentence and applies POS tagging, printing each token with its assigned tag.                                                            |
| **Expected Output**         | A list of tokens with their corresponding POS tags.                                                                                                 |
| **Learning Outcome**        | Understands how grammatical roles are assigned and how they support syntactic analysis.                                                             |
| **Result**                  | *The given sentence was successfully tagged with appropriate part-of-speech labels for each word.*                                                  |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_04_POS_Tagging.ipynb) |

---

### Practical 5 — Parsing and Chunking using Regex and spaCy

**Theory / Concept:** **Parsing** analyzes the grammatical structure of a sentence, while **chunking** (shallow parsing) groups tokens into phrases such as **noun phrases (NP)** and **verb phrases (VP)** without building a full parse tree. Regex-based chunking uses POS-tag patterns, while spaCy provides built-in **dependency parsing** and noun-chunk extraction.

| Field                       | Details                                                                                                                                                  |
| --------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To perform shallow parsing (chunking) to identify grammatical phrases such as NPs and VPs.                                                               |
| **Key Topics**              | Shallow vs full parsing • Regex-based chunking • Noun/verb phrases • spaCy dependency parsing                                                            |
| **Libraries / Tools**       | [NLTK](https://www.nltk.org/) (`RegexpParser`), [spaCy](https://spacy.io/)                                                                               |
| **Implementation Overview** | Defines regex chunk patterns via NLTK and extracts noun chunks via spaCy's dependency parser.                                                            |
| **Expected Output**         | Extracted phrase chunks along with a visual/printed parse structure.                                                                                     |
| **Learning Outcome**        | Learns how grammatical phrases are identified through pattern-based and model-based parsing.                                                             |
| **Result**                  | *The given sentence was successfully parsed and chunked to extract meaningful grammatical phrases.*                                                      |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_05_Parsing_Chunking.ipynb) |

---

### Practical 6 — Named Entity Recognition (NER) using spaCy

**Theory / Concept:** **NER** locates and classifies real-world entities in text into categories such as **PERSON**, **ORG**, **GPE**, and **DATE**. spaCy provides a pretrained statistical NER pipeline that identifies these directly from raw text, making it central to **information extraction**, **question answering**, and **knowledge graph construction**.

| Field                       | Details                                                                                                                                           |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To identify and classify named entities in a given text using spaCy.                                                                              |
| **Key Topics**              | Entity categories (PERSON, ORG, GPE, DATE) • spaCy NER pipeline • Entity visualization • Applications                                             |
| **Libraries / Tools**       | [spaCy](https://spacy.io/)                                                                                                                        |
| **Implementation Overview** | Processes text through spaCy's NER pipeline and extracts entities with their labels, optionally via `displaCy`.                                   |
| **Expected Output**         | A list of identified named entities and their entity type labels.                                                                                 |
| **Learning Outcome**        | Understands how pretrained NER models classify real-world entities in unstructured text.                                                          |
| **Result**                  | *The given text was successfully processed to extract and classify named entities using spaCy.*                                                   |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_06_NER_spaCy.ipynb) |

---

### Practical 7 — Coreference Resolution using neuralcoref (or Similar)

**Theory / Concept:** **Coreference resolution** determines when two or more expressions refer to the same real-world entity — e.g., resolving *"she"* to a previously mentioned name. It is essential for **summarization**, **QA**, and document-level coherence. This practical is implemented using **neuralcoref or a compatible alternative approach**, since neuralcoref may have compatibility limitations with modern spaCy versions.

| Field                       | Details                                                                                                                                                        |
| --------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To resolve coreferences, identifying which mentions refer to the same underlying entity.                                                                       |
| **Key Topics**              | Coreference resolution • Pronoun resolution • Entity mention clusters • Library compatibility considerations                                                   |
| **Libraries / Tools**       | [spaCy](https://spacy.io/), `neuralcoref` *(or a compatible alternative)*                                                                                      |
| **Implementation Overview** | Processes text through a coreference pipeline, clustering mentions referring to the same entity.                                                               |
| **Expected Output**         | Resolved text or entity clusters showing which mentions co-refer.                                                                                              |
| **Learning Outcome**        | Understands coreference resolution's role in coherent document-level understanding.                                                                            |
| **Result**                  | *The given text was successfully processed to identify and resolve coreferring mentions to their corresponding entities.*                                      |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_07_Coreference_Resolution.ipynb) |

---

### Practical 8 — Bag-of-Words (BoW) Vectorization and Representation

**Theory / Concept:** The **Bag-of-Words (BoW)** model represents text as a vector of word counts over a fixed vocabulary, disregarding grammar and order. Each document becomes a sparse vector, forming the foundation for classical techniques and a stepping stone toward **TF-IDF** and **embeddings**.

| Field                       | Details                                                                                                                                              |
| --------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To convert a collection of text documents into a numerical Bag-of-Words representation.                                                              |
| **Key Topics**              | Vocabulary construction • Term-frequency vectors • Sparse matrices • Limitations of BoW                                                              |
| **Libraries / Tools**       | [scikit-learn](https://scikit-learn.org/) (`CountVectorizer`), [NLTK](https://www.nltk.org/)                                                         |
| **Implementation Overview** | Builds a vocabulary from a corpus and converts documents into BoW vectors via `CountVectorizer`.                                                     |
| **Expected Output**         | A term-document matrix showing word counts per document.                                                                                             |
| **Learning Outcome**        | Learns how unstructured text becomes a numerical format suitable for ML algorithms.                                                                  |
| **Result**                  | *The given corpus was successfully converted into a Bag-of-Words representation.*                                                                    |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_08_Bag_of_Words.ipynb) |

---

### Practical 9 — TF-IDF Implementation and Comparison with BoW

**Theory / Concept:** **TF-IDF** (Term Frequency–Inverse Document Frequency) weights terms by combining how often they appear in a document (**TF**) with how rare they are across the corpus (**IDF**). Unlike BoW, it down-weights common words and up-weights distinctive, informative terms.

| Field                       | Details                                                                                                                                              |
| --------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To compute the TF-IDF representation of a corpus and compare it with BoW.                                                                            |
| **Key Topics**              | Term Frequency (TF) • Inverse Document Frequency (IDF) • TF-IDF formula • Comparison with BoW                                                        |
| **Libraries / Tools**       | [scikit-learn](https://scikit-learn.org/) (`TfidfVectorizer`)                                                                                        |
| **Implementation Overview** | Computes the TF-IDF matrix for a corpus and compares weighted values against raw BoW counts.                                                         |
| **Expected Output**         | A TF-IDF weighted matrix alongside the corresponding BoW matrix.                                                                                     |
| **Learning Outcome**        | Understands how TF-IDF improves on frequency-only representations.                                                                                   |
| **Result**                  | *The given corpus was successfully converted into a TF-IDF representation and compared against its Bag-of-Words counterpart.*                        |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_09_TFIDF_vs_BoW.ipynb) |

---

### Practical 10 — N-Gram Model (Uni-, Bi-, Tri-Gram) Generation from Corpus

**Theory / Concept:** **N-grams** are contiguous sequences of *N* words. **Unigrams**, **bigrams**, and **trigrams** capture local word-order and co-occurrence information that unigram-only models ignore — useful for **language modeling** and **text generation**, at the cost of increasing sparsity as *N* grows.

| Field                       | Details                                                                                                                                        |
| --------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To generate unigrams, bigrams, and trigrams from a given text corpus.                                                                          |
| **Key Topics**              | Unigrams/bigrams/trigrams • N-gram generation • Context windows • Sparsity trade-offs                                                          |
| **Libraries / Tools**       | [NLTK](https://www.nltk.org/), [scikit-learn](https://scikit-learn.org/) (`CountVectorizer` with n-gram range)                                 |
| **Implementation Overview** | Generates unigram/bigram/trigram sequences using NLTK utilities and/or a configurable vectorizer.                                              |
| **Expected Output**         | Lists or frequency counts of unigrams, bigrams, and trigrams.                                                                                  |
| **Learning Outcome**        | Learns how N-gram models capture local context and word order.                                                                                 |
| **Result**                  | *The given corpus was successfully processed to generate unigram, bigram, and trigram sequences.*                                              |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_10_NGrams.ipynb) |

---

### Practical 11 — Cosine Similarity Computation between Text Documents

**Theory / Concept:** **Cosine similarity** measures the angle between two vectors, indicating how similar two documents are regardless of length. It is one of the most widely used similarity metrics in NLP, particularly over **BoW** or **TF-IDF** vectors.

| Field                       | Details                                                                                                                                                   |
| --------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To compute cosine similarity between pairs of text documents represented as vectors.                                                                      |
| **Key Topics**              | Vector space representation • Cosine similarity formula • Document similarity • Applications in search/clustering                                         |
| **Libraries / Tools**       | [scikit-learn](https://scikit-learn.org/) (`cosine_similarity`, `TfidfVectorizer`), [NumPy](https://numpy.org/)                                           |
| **Implementation Overview** | Vectorizes documents (via TF-IDF) and computes pairwise cosine similarity scores.                                                                         |
| **Expected Output**         | A similarity matrix or set of pairwise similarity scores.                                                                                                 |
| **Learning Outcome**        | Learns how vector-based metrics quantify relatedness between documents.                                                                                   |
| **Result**                  | *The given text documents were successfully compared using cosine similarity to determine their degree of relatedness.*                                   |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_11_Cosine_Similarity.ipynb) |

---

### Practical 12 — Word2Vec Word Embeddings using Gensim on a Custom Corpus

**Theory / Concept:** **Word2Vec** learns dense vector representations of words such that semantically similar words are close together. It can use **CBOW** (predicts a word from context) or **Skip-gram** (predicts context from a word), capturing semantic relationships that sparse representations cannot.

| Field                       | Details                                                                                                                                          |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Objective**               | To train Word2Vec embeddings on a custom corpus and explore semantic relationships.                                                              |
| **Key Topics**              | CBOW and Skip-gram • Dense embeddings • Custom corpus training • Semantic word similarity                                                        |
| **Libraries / Tools**       | [Gensim](https://radimrehurek.com/gensim/), [NLTK](https://www.nltk.org/)                                                                        |
| **Implementation Overview** | Preprocesses a corpus, trains a Word2Vec model via Gensim, and explores similar-word queries.                                                    |
| **Expected Output**         | A trained model plus examples of semantically similar words for query terms.                                                                     |
| **Learning Outcome**        | Understands how neural embeddings are trained and capture semantic relationships.                                                                |
| **Result**                  | *Word2Vec embeddings were successfully trained on the given custom corpus, and semantically related words were identified.*                      |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_12_Word2Vec.ipynb) |

---

### Practical 13 — GloVe Embeddings Loading and Vector Representation

**Theory / Concept:** **GloVe** (Global Vectors) is a pretrained embedding technique learned by factorizing a **global word co-occurrence matrix**, in contrast to Word2Vec's local context prediction. Using pretrained GloVe vectors allows leveraging embeddings trained on massive corpora without custom training.

| Field                       | Details                                                                                                                                       |
| --------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To load pretrained GloVe embeddings and obtain vector representations of words.                                                               |
| **Key Topics**              | Pretrained embeddings • Global co-occurrence statistics • Loading GloVe vectors • Vector similarity                                           |
| **Libraries / Tools**       | [Gensim](https://radimrehurek.com/gensim/), [NumPy](https://numpy.org/)                                                                       |
| **Implementation Overview** | Loads pretrained GloVe vectors and retrieves representations/similar words for given terms.                                                   |
| **Expected Output**         | Vector representations and semantically similar words for selected terms.                                                                     |
| **Learning Outcome**        | Understands the difference between locally trained and globally trained embeddings.                                                           |
| **Result**                  | *The pretrained GloVe embeddings were successfully loaded and used to obtain vector representations for the given words.*                     |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_13_GloVe.ipynb) |

---

### Practical 14 — Text Similarity using Word Mover's Distance (WMD)

**Theory / Concept:** **Word Mover's Distance (WMD)** measures the minimum cumulative distance that embedded words of one document must "travel" to match another's, using dense embeddings like Word2Vec. This captures semantic similarity even when documents share **few or no exact words**.

| Field                       | Details                                                                                                                                     |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To measure semantic distance between two documents using WMD based on word embeddings.                                                      |
| **Key Topics**              | Embeddings as distance basis • Earth Mover's Distance concept • Semantic vs lexical similarity • Comparison with cosine similarity          |
| **Libraries / Tools**       | [Gensim](https://radimrehurek.com/gensim/) (Word2Vec, WMD)                                                                                  |
| **Implementation Overview** | Computes WMD between sample document pairs using pretrained/custom embeddings.                                                              |
| **Expected Output**         | WMD scores indicating semantic closeness between document pairs.                                                                            |
| **Learning Outcome**        | Learns how embedding-based distance captures similarity beyond lexical overlap.                                                             |
| **Result**                  | *The semantic distance between the given text documents was successfully computed using Word Mover's Distance.*                             |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_14_WMD.ipynb) |

---

### Practical 15 — Text Classification using Naïve Bayes/SVM with TF-IDF

**Theory / Concept:** **Text classification** assigns predefined labels to documents. Here, documents are converted to **TF-IDF** features and fed into a classical classifier — **Naïve Bayes** (Bayes' theorem with feature independence) or **SVM** (optimal separating hyperplane) — a strong, interpretable baseline.

| Field                       | Details                                                                                                                                                     |
| --------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To classify text documents into predefined categories using Naïve Bayes and/or SVM trained on TF-IDF features.                                              |
| **Key Topics**              | TF-IDF feature extraction • Naïve Bayes • Support Vector Machines • Train-test evaluation                                                                   |
| **Libraries / Tools**       | [scikit-learn](https://scikit-learn.org/) (`TfidfVectorizer`, `MultinomialNB`, `SVC`)                                                                       |
| **Implementation Overview** | Converts a labeled dataset to TF-IDF features, trains a classifier, and evaluates on a test split.                                                          |
| **Expected Output**         | Predicted class labels plus evaluation metrics (accuracy, precision, recall).                                                                               |
| **Learning Outcome**        | Learns how classical classifiers combine with TF-IDF for text classification.                                                                               |
| **Result**                  | *The given text dataset was successfully classified using a Naïve Bayes/SVM classifier trained on TF-IDF features.*                                         |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_15_Text_Classification.ipynb) |

---

### Practical 16 — Sentiment Analysis using TextBlob and VADER

**Theory / Concept:** **Sentiment analysis** determines the emotional tone of text. **TextBlob** uses a pattern-based approach for **polarity/subjectivity**, while **VADER** is a lexicon/rule-based model tuned for short, informal text such as social media. Comparing both highlights how rule-based approaches diverge on slang and punctuation-based cues.

| Field                       | Details                                                                                                                                                    |
| --------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To perform sentiment analysis using TextBlob and VADER, and compare their outputs.                                                                         |
| **Key Topics**              | Polarity/subjectivity scoring • Lexicon-based sentiment • TextBlob • VADER compound scoring                                                                |
| **Libraries / Tools**       | [TextBlob](https://textblob.readthedocs.io/), [NLTK VADER](https://github.com/cjhutto/vaderSentiment)                                                      |
| **Implementation Overview** | Applies TextBlob and VADER separately to sample texts and compares resulting sentiment labels.                                                             |
| **Expected Output**         | Sentiment scores and labels (positive/negative/neutral) from both tools.                                                                                   |
| **Learning Outcome**        | Learns how different lexicon-based tools compute and may diverge on sentiment.                                                                             |
| **Result**                  | *The given text samples were successfully analyzed for sentiment using both TextBlob and VADER.*                                                           |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_16_Sentiment_Analysis.ipynb) |

---

### Practical 17 — Topic Modeling using Latent Dirichlet Allocation (LDA)

**Theory / Concept:** **LDA** is a generative probabilistic model assuming each document is a mixture of a small number of **topics**, each characterized by a distribution over words. It is **unsupervised**, requiring no labeled data, and outputs both *topic-word* and *document-topic* distributions.

| Field                       | Details                                                                                                                                     |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To discover latent topics in a text corpus using LDA.                                                                                       |
| **Key Topics**              | Generative probabilistic modeling • Topic-word/document-topic distributions • Unsupervised discovery • Interpreting topics                  |
| **Libraries / Tools**       | [Gensim](https://radimrehurek.com/gensim/), [scikit-learn](https://scikit-learn.org/) (`LatentDirichletAllocation`)                         |
| **Implementation Overview** | Constructs a document-term representation, trains LDA, and displays top words per topic.                                                    |
| **Expected Output**         | A set of discovered topics with their most significant associated words.                                                                    |
| **Learning Outcome**        | Understands how LDA finds thematic structure without labeled data.                                                                          |
| **Result**                  | *The given corpus was successfully processed to discover latent topics using Latent Dirichlet Allocation.*                                  |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_17_LDA.ipynb) |

---

### Practical 18 — Topic Modeling using Latent Semantic Analysis (LSA)

**Theory / Concept:** **LSA** applies **Singular Value Decomposition (SVD)** to a TF-IDF-weighted term-document matrix to uncover latent semantic structure. Unlike LDA's probabilistic approach, LSA is a **linear algebraic** technique — computationally simpler, though generally less interpretable.

| Field                       | Details                                                                                                                                     |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To extract latent semantic topics from a corpus using LSA.                                                                                  |
| **Key Topics**              | Term-document matrix • Singular Value Decomposition (SVD) • Dimensionality reduction • Comparison with LDA                                  |
| **Libraries / Tools**       | [scikit-learn](https://scikit-learn.org/) (`TruncatedSVD`, `TfidfVectorizer`)                                                               |
| **Implementation Overview** | Constructs a TF-IDF matrix and applies Truncated SVD to extract latent semantic components.                                                 |
| **Expected Output**         | Latent semantic components/topics with their most strongly associated terms.                                                                |
| **Learning Outcome**        | Learns how linear-algebraic dimensionality reduction reveals latent semantic structure.                                                     |
| **Result**                  | *The given corpus was successfully processed to extract latent semantic topics using LSA.*                                                  |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_18_LSA.ipynb) |

---

### Practical 19 — Opinion Mining on Product/Service Reviews Dataset

**Theory / Concept:** **Opinion mining**, closely related to sentiment analysis, analyzes subjective content such as customer reviews to determine **polarity of opinion**. Applied at the review level, it supports real-world use cases like **customer feedback analysis** and **reputation monitoring**.

| Field                       | Details                                                                                                                                                                           |
| --------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To perform opinion mining on a product/service reviews dataset to determine overall sentiment.                                                                                    |
| **Key Topics**              | Review-level sentiment analysis • Opinion polarity classification • Aspect vs document-level mining • Real-world applications                                                     |
| **Libraries / Tools**       | [TextBlob](https://textblob.readthedocs.io/), [VADER](https://github.com/cjhutto/vaderSentiment), [Pandas](https://pandas.pydata.org/), [scikit-learn](https://scikit-learn.org/) |
| **Implementation Overview** | Loads a reviews dataset, applies sentiment analysis per review, and aggregates/visualizes overall opinion distribution.                                                           |
| **Expected Output**         | Sentiment/opinion labels per review, with a summary or visualization of overall distribution.                                                                                     |
| **Learning Outcome**        | Learns how sentiment techniques scale to mine opinions from real-world datasets.                                                                                                  |
| **Result**                  | *The given reviews dataset was successfully analyzed to determine the opinion polarity expressed in each review.*                                                                 |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_19_Opinion_Mining.ipynb)                            |

---

### Practical 20 — Information Extraction from Structured/Unstructured Documents

**Theory / Concept:** **Information Extraction (IE)** automatically extracts structured information — entities, relationships, fields — from unstructured or semi-structured text, building on **tokenization**, **POS tagging**, and **NER** to convert free-form text into machine-readable information.

| Field                       | Details                                                                                                                                                        |
| --------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To extract structured information from structured and/or unstructured text documents.                                                                          |
| **Key Topics**              | Structured vs unstructured documents • Entity/field extraction • Rule-based and NER-based approaches • Applications                                            |
| **Libraries / Tools**       | [spaCy](https://spacy.io/), [NLTK](https://www.nltk.org/), Python `re` module                                                                                  |
| **Implementation Overview** | Combines pattern-based rules and NER to extract structured fields/entities from sample documents.                                                              |
| **Expected Output**         | A structured set of extracted information from the input documents.                                                                                            |
| **Learning Outcome**        | Learns how multiple NLP techniques combine to extract structured information from text.                                                                        |
| **Result**                  | *The given documents were successfully processed to extract relevant structured information.*                                                                  |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_20_Information_Extraction.ipynb) |

---

### Practical 21 — Information Retrieval System with Ranking using TF-IDF

**Theory / Concept:** **Information Retrieval (IR)** finds relevant documents in response to a query. In a **TF-IDF-based IR system**, both documents and query are represented as TF-IDF vectors, and relevance is measured via **cosine similarity**, with documents ranked by descending similarity.

| Field                       | Details                                                                                                                                                       |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To implement a basic IR system that ranks documents by relevance to a query using TF-IDF.                                                                     |
| **Key Topics**              | Vector space model for IR • Query representation • TF-IDF relevance scoring • Document ranking                                                                |
| **Libraries / Tools**       | [scikit-learn](https://scikit-learn.org/) (`TfidfVectorizer`, `cosine_similarity`)                                                                            |
| **Implementation Overview** | Builds a TF-IDF representation, converts a query into the same space, and ranks documents by similarity.                                                      |
| **Expected Output**         | A ranked list of documents based on computed relevance scores.                                                                                                |
| **Learning Outcome**        | Learns how vector space models and similarity scoring underpin classical IR systems.                                                                          |
| **Result**                  | *The given document collection was successfully ranked according to relevance to the specified query using TF-IDF-based retrieval.*                           |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_21_Information_Retrieval.ipynb) |

---

### Practical 22 — Sequence Classification using RNN/LSTM (Keras/TensorFlow)

**Theory / Concept:** **RNNs** process sequential data via a hidden state capturing information from previous steps, making them naturally suited to text. **LSTM** networks are a specialized RNN variant that better capture **long-range dependencies** by mitigating the vanishing gradient problem.

| Field                       | Details                                                                                                                                          |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Objective**               | To classify text sequences using an RNN or LSTM model implemented in Keras/TensorFlow.                                                           |
| **Key Topics**              | Sequential data modeling • RNN hidden states • LSTM cells & long-range dependencies • Embedding layers                                           |
| **Libraries / Tools**       | [TensorFlow](https://www.tensorflow.org/), [Keras](https://keras.io/), [NumPy](https://numpy.org/), [Pandas](https://pandas.pydata.org/)         |
| **Implementation Overview** | Tokenizes/pads text, builds an embedding + RNN/LSTM + dense layer model, trains and evaluates it.                                                |
| **Expected Output**         | Predicted class labels plus accuracy/loss curves.                                                                                                |
| **Learning Outcome**        | Learns how recurrent architectures process sequential text for classification.                                                                   |
| **Result**                  | *The given text sequences were successfully classified using an RNN/LSTM model built with Keras/TensorFlow.*                                     |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_22_RNN_LSTM.ipynb) |

---

### Practical 23 — Implementing Attention Mechanism (Basic Custom Model)

**Theory / Concept:** The **attention mechanism** allows a model to dynamically focus on relevant parts of an input sequence rather than relying on a single fixed-size hidden state summary. Conceptually described via **query, key, and value** representations, attention later became the foundation of **transformer architectures**.

| Field                       | Details                                                                                                                                                     |
| --------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To implement a basic custom attention mechanism focusing on relevant parts of an input sequence.                                                            |
| **Key Topics**              | Motivation over fixed-context RNNs • Query/key/value intuition • Attention weight computation • Weighted context representation                             |
| **Libraries / Tools**       | TensorFlow/Keras or NumPy *(for a custom implementation)*                                                                                                   |
| **Implementation Overview** | Implements a simplified attention layer over a basic sequence model, computing weights and a context vector.                                                |
| **Expected Output**         | Computed attention weights and a resulting context-aware output.                                                                                            |
| **Learning Outcome**        | Understands the intuition behind attention and differential weighting of inputs.                                                                            |
| **Result**                  | *A basic custom attention mechanism was successfully implemented and demonstrated on a sample input sequence.*                                              |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_23_Attention_Mechanism.ipynb) |

---

### Practical 24 — Fine-Tuning BERT for Text Classification using Hugging Face

**Theory / Concept:** **BERT** (Bidirectional Encoder Representations from Transformers) learns deep bidirectional contextual representations via pretraining tasks like **masked language modeling**. **Fine-tuning** adapts this pretrained model to a downstream task, such as classification, using a smaller labeled dataset.

| Field                       | Details                                                                                                                                                  |
| --------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To fine-tune a pretrained BERT model on a text classification task using Hugging Face Transformers.                                                      |
| **Key Topics**              | Transformer architecture overview • Bidirectional pretraining • BERT tokenization • Fine-tuning for classification                                       |
| **Libraries / Tools**       | [Hugging Face Transformers](https://huggingface.co/docs/transformers), [Hugging Face Datasets](https://huggingface.co/docs/datasets), PyTorch/TensorFlow |
| **Implementation Overview** | Loads a pretrained BERT model/tokenizer, tokenizes a labeled dataset, fine-tunes, and evaluates.                                                         |
| **Expected Output**         | Predicted class labels plus fine-tuning metrics (loss, accuracy).                                                                                        |
| **Learning Outcome**        | Learns how pretrained transformers are fine-tuned for downstream NLP tasks.                                                                              |
| **Result**                  | *A pretrained BERT model was successfully fine-tuned on the given text classification dataset.*                                                          |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_24_BERT_Fine_Tuning.ipynb) |

---

### Practical 25 — Sentence Embeddings using BERT and GPT-2

**Theory / Concept:** **Sentence embeddings** are dense vectors capturing overall sentence meaning, derived by pooling hidden states from a transformer. **BERT** is encoder-only and bidirectional; **GPT-2** is decoder-only and autoregressive — comparing both highlights how architecture shapes representation.

| Field                       | Details                                                                                                                                                      |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Objective**               | To generate sentence-level embeddings using BERT and GPT-2, and compare the representations.                                                                 |
| **Key Topics**              | Transformer sentence representations • Pooling strategies • Encoder-only vs decoder-only • Embedding-space comparison                                        |
| **Libraries / Tools**       | [Hugging Face Transformers](https://huggingface.co/docs/transformers), PyTorch/TensorFlow, [NumPy](https://numpy.org/)                                       |
| **Implementation Overview** | Passes sentences through BERT and GPT-2, pools hidden states into embeddings, and compares vectors.                                                          |
| **Expected Output**         | Dense sentence embedding vectors from both models.                                                                                                           |
| **Learning Outcome**        | Learns how sentence representations are derived and how architecture affects them.                                                                           |
| **Result**                  | *Sentence embeddings were successfully generated for the given text inputs using both BERT and GPT-2.*                                                       |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_25_BERT_GPT2_Embeddings.ipynb) |

---

### Practical 26 — Text Generation using GPT-2 on a Custom Dataset

**Theory / Concept:** **GPT-2** is a decoder-only, **autoregressive** transformer trained to predict the next word given prior context, allowing it to generate coherent text continuations from a prompt.

| Field                       | Details                                                                                                                                                      |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Objective**               | To generate coherent text continuations using a pretrained GPT-2 model, optionally adapted to a custom dataset.                                              |
| **Key Topics**              | Autoregressive language modeling • Next-token prediction • Generation strategies (greedy/sampling) • Custom prompt adaptation                                |
| **Libraries / Tools**       | [Hugging Face Transformers](https://huggingface.co/docs/transformers), PyTorch/TensorFlow                                                                    |
| **Implementation Overview** | Loads GPT-2, provides sample prompts, and generates continuations via the generation utilities.                                                              |
| **Expected Output**         | Generated text continuations for the given prompts.                                                                                                          |
| **Learning Outcome**        | Learns how autoregressive models generate and can be customized for text generation.                                                                         |
| **Result**                  | *Coherent text continuations were successfully generated using the pretrained GPT-2 model on the given prompts.*                                             |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_26_GPT2_Text_Generation.ipynb) |

---

### Practical 27 — Named Entity Recognition using Transformers (BERT)

**Theory / Concept:** Transformer-based **NER** treats entity recognition as **token classification**, typically using a **BIO** tagging scheme, leveraging BERT's rich contextual embeddings for improved accuracy compared to traditional statistical NER (as seen in Practical 6).

| Field                       | Details                                                                                                                                          |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Objective**               | To perform NER on a given text using a transformer-based (BERT-style) token classification model.                                                |
| **Key Topics**              | Token classification for NER • BIO tagging scheme • BERT-based NER pipelines • Comparison with traditional NER                                   |
| **Libraries / Tools**       | [Hugging Face Transformers](https://huggingface.co/docs/transformers) (token classification pipeline)                                            |
| **Implementation Overview** | Loads a pretrained BERT-based NER pipeline and applies it to sample text, extracting entities.                                                   |
| **Expected Output**         | A list of identified named entities and their predicted labels.                                                                                  |
| **Learning Outcome**        | Learns how transformer token classification compares to traditional NER approaches.                                                              |
| **Result**                  | *The given text was successfully processed to extract named entities using a transformer-based (BERT) NER model.*                                |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_27_BERT_NER.ipynb) |

---

### Practical 28 — Machine Translation using MarianMT or T5 (Hugging Face)

**Theory / Concept:** Neural **Machine Translation** relies on **encoder-decoder (sequence-to-sequence)** transformer architectures. **MarianMT** models are pretrained for specific language pairs, while **T5** frames translation as a general text-to-text task within a unified format.

| Field                       | Details                                                                                                                                                     |
| --------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To translate text from one language to another using a pretrained MarianMT or T5 model.                                                                     |
| **Key Topics**              | Encoder-decoder architecture • Neural machine translation • MarianMT models • T5 text-to-text framing                                                       |
| **Libraries / Tools**       | [Hugging Face Transformers](https://huggingface.co/docs/transformers) (MarianMTModel/T5), PyTorch/TensorFlow                                                |
| **Implementation Overview** | Loads a pretrained MarianMT/T5 model, provides source sentences, and generates translations.                                                                |
| **Expected Output**         | Translated text outputs for the given source-language sentences.                                                                                            |
| **Learning Outcome**        | Learns how encoder-decoder transformers perform automatic translation.                                                                                      |
| **Result**                  | *The given source-language text was successfully translated into the target language using a pretrained MarianMT/T5 model.*                                 |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_28_Machine_Translation.ipynb) |

---

### Practical 29 — Text Summarization using BART or T5

**Theory / Concept:** **Text summarization** condenses a document while preserving key information. **Abstractive** summarization (paraphrasing, as opposed to *extractive* sentence selection) suits sequence-to-sequence models like **BART** (denoising pretraining) and **T5** (text-to-text framing).

| Field                       | Details                                                                                                                                                    |
| --------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To generate a concise summary of a given document using a pretrained BART or T5 model.                                                                     |
| **Key Topics**              | Extractive vs abstractive summarization • Seq2seq summarization models • BART pretraining • T5 framing                                                     |
| **Libraries / Tools**       | [Hugging Face Transformers](https://huggingface.co/docs/transformers) (BART/T5), PyTorch/TensorFlow                                                        |
| **Implementation Overview** | Loads a pretrained BART/T5 summarizer, provides an input document, and generates a summary.                                                                |
| **Expected Output**         | A generated abstractive summary of the input document.                                                                                                     |
| **Learning Outcome**        | Learns how seq2seq transformers perform automatic abstractive summarization.                                                                               |
| **Result**                  | *The given document was successfully summarized using a pretrained BART/T5 model.*                                                                         |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_29_Text_Summarization.ipynb) |

---

### Practical 30 — Chatbot Development using Pre-trained Transformer (DialoGPT/ChatGPT-style)

**Theory / Concept:** Conversational models like **DialoGPT** are pretrained on large-scale dialogue data to generate contextually appropriate responses, extending autoregressive generation (as in GPT-2) to **multi-turn dialogue**, maintaining context across turns.

| Field                       | Details                                                                                                                                                     |
| --------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To develop a basic conversational chatbot using a pretrained transformer such as DialoGPT.                                                                  |
| **Key Topics**              | Conversational language modeling • Multi-turn dialogue context • DialoGPT/ChatGPT-style architectures • Response generation                                 |
| **Libraries / Tools**       | [Hugging Face Transformers](https://huggingface.co/docs/transformers) (DialoGPT or similar), PyTorch/TensorFlow                                             |
| **Implementation Overview** | Loads a conversational transformer, accepts user input in a loop, and maintains context to generate responses.                                              |
| **Expected Output**         | Generated chatbot responses for sample user inputs across a conversation.                                                                                   |
| **Learning Outcome**        | Learns how conversational transformers power simple interactive chatbots.                                                                                   |
| **Result**                  | *A basic chatbot was successfully implemented using a pretrained transformer-based conversational model.*                                                   |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_30_Transformer_Chatbot.ipynb) |

---

### Practical 31 — Automatic Document Classification and Separation using ML

**Theory / Concept:** **Automatic document classification** extends text classification to the document level, categorizing entire documents via feature extraction (e.g., **TF-IDF**) and a classical ML classifier, then **separating** documents by predicted category — useful for document management systems.

| Field                       | Details                                                                                                                                                         |
| --------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To automatically classify and separate a document collection into predefined categories using ML.                                                               |
| **Key Topics**              | Document-level feature extraction • ML-based classification • Category-based separation • Document management applications                                      |
| **Libraries / Tools**       | [scikit-learn](https://scikit-learn.org/), [Pandas](https://pandas.pydata.org/), [NumPy](https://numpy.org/)                                                    |
| **Implementation Overview** | Extracts TF-IDF features, trains a classifier, and organizes documents by predicted labels.                                                                     |
| **Expected Output**         | Predicted category labels plus an organized grouping/separation of documents.                                                                                   |
| **Learning Outcome**        | Learns how ML techniques classify and organize document collections.                                                                                            |
| **Result**                  | *The given document collection was successfully classified and separated into categories using a machine learning approach.*                                    |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_31_Document_Classification.ipynb) |

---

### Practical 32 — Hybrid Probabilistic + FSM-Based Sequence Modeling for Document Boundary Detection

**Theory / Concept:** **Document boundary detection** identifies where one document ends and another begins within a continuous text stream. This practical combines **probabilistic sequence modeling** (estimating boundary likelihood from contextual features) with a **finite state machine (FSM)** that enforces valid structural transitions — yielding more robust detection than either approach alone.

| Field                       | Details                                                                                                                                                          |
| --------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Objective**               | To detect document boundaries in a combined text stream using a hybrid probabilistic + FSM approach.                                                             |
| **Key Topics**              | Document boundary detection • Probabilistic sequence modeling • Finite State Machines (FSM) • Hybrid modeling                                                    |
| **Libraries / Tools**       | Python, [NumPy](https://numpy.org/), [Pandas](https://pandas.pydata.org/), [scikit-learn](https://scikit-learn.org/) *(probabilistic components)*                |
| **Implementation Overview** | Computes probabilistic boundary indicators and applies an FSM to enforce valid state transitions, identifying boundaries.                                        |
| **Expected Output**         | Predicted document boundary points segmenting the stream into individual documents.                                                                              |
| **Learning Outcome**        | Learns how probabilistic models and FSMs combine for structured sequence segmentation.                                                                           |
| **Result**                  | *The given combined text stream was successfully segmented into individual documents using the hybrid probabilistic and FSM-based approach.*                     |
| **Notebook**                | [Open Notebook](https://colab.research.google.com/github/aditya01-dev/Natural-Language-Processing-Lab/blob/main/NLP_Practical_32_Hybrid_Sequence_Modeling.ipynb) |

---

## Suggested Repository Structure

```text
Natural-Language-Processing-Lab/
├── README.md
├── NLP_Practical_01_Tokenization.ipynb
├── NLP_Practical_02_Stemming_Lemmatization.ipynb
├── NLP_Practical_03_Stopword_Removal.ipynb
├── NLP_Practical_04_POS_Tagging.ipynb
├── NLP_Practical_05_Parsing_Chunking.ipynb
├── NLP_Practical_06_NER_spaCy.ipynb
├── NLP_Practical_07_Coreference_Resolution.ipynb
├── NLP_Practical_08_Bag_of_Words.ipynb
├── NLP_Practical_09_TFIDF_vs_BoW.ipynb
├── NLP_Practical_10_NGrams.ipynb
├── NLP_Practical_11_Cosine_Similarity.ipynb
├── NLP_Practical_12_Word2Vec.ipynb
├── NLP_Practical_13_GloVe.ipynb
├── NLP_Practical_14_WMD.ipynb
├── NLP_Practical_15_Text_Classification.ipynb
├── NLP_Practical_16_Sentiment_Analysis.ipynb
├── NLP_Practical_17_LDA.ipynb
├── NLP_Practical_18_LSA.ipynb
├── NLP_Practical_19_Opinion_Mining.ipynb
├── NLP_Practical_20_Information_Extraction.ipynb
├── NLP_Practical_21_Information_Retrieval.ipynb
├── NLP_Practical_22_RNN_LSTM.ipynb
├── NLP_Practical_23_Attention_Mechanism.ipynb
├── NLP_Practical_24_BERT_Fine_Tuning.ipynb
├── NLP_Practical_25_BERT_GPT2_Embeddings.ipynb
├── NLP_Practical_26_GPT2_Text_Generation.ipynb
├── NLP_Practical_27_BERT_NER.ipynb
├── NLP_Practical_28_Machine_Translation.ipynb
├── NLP_Practical_29_Text_Summarization.ipynb
├── NLP_Practical_30_Transformer_Chatbot.ipynb
├── NLP_Practical_31_Document_Classification.ipynb
└── NLP_Practical_32_Hybrid_Sequence_Modeling.ipynb
```

---

## How to Use the Repository

1. Open the required practical from the **[Complete Practical Index](#complete-practical-index)** above.
2. Open the corresponding notebook using its **Open Notebook** link to launch it directly in **Google Colab**.
3. Run the notebook cells **sequentially** from top to bottom.
4. Install or download any dependencies/pretrained models when prompted within the notebook.
5. Review the generated outputs displayed within the notebook.
6. Use the notebooks as a reference for **laboratory submission and revision**.

---

## Academic Notes

> * This repository is intended for **academic and laboratory learning** purposes.
> * Certain practical implementations may use **compatible alternative libraries or approaches** where older NLP libraries are no longer directly supported in modern environments.
> * Results may vary slightly depending on the versions of libraries/models used and the specific datasets employed at runtime.

---

## Conclusion

This repository presents a comprehensive progression through the field of **Natural Language Processing** — beginning with foundational text preprocessing (*tokenization, stemming, lemmatization, POS tagging*), advancing through classical vector-based representations (*BoW, TF-IDF, N-grams*), and exploring similarity/embedding methods (*cosine similarity, Word2Vec, GloVe, WMD*). It then applies classical machine learning to *text classification, sentiment analysis, topic modeling*, and *information extraction/retrieval*, before extending into neural sequence modeling with *RNNs/LSTMs* and *attention mechanisms*. The final practicals culminate in modern **transformer-based NLP** — *BERT, GPT-2, machine translation, summarization, conversational chatbots*, and *hybrid sequence modeling*. Together, these **32 practicals** form a complete academic journey from fundamental linguistic preprocessing to state-of-the-art transformer-based Natural Language Processing.

---

## Author

**Aditya Kumar Singh**
*B.Tech CSE (Artificial Intelligence)*

