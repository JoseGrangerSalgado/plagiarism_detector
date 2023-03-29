# Reto

# Identify the problem

**Plagiarism** detection is a process of **identifying instances** of **copying** or **using someone else's work** without **proper attribution.** It tries to solve the problem of **academic dishonesty** and **intellectual property theft** by helping educators, researchers, and publishers to **detect and prevent plagiarism.** 

With the help of sophisticated **algorithms** and **tools,** plagiarism detection software can scan through large databases of text to compare them against a given document, highlighting any similarities and potential instances of plagiarism. By identifying and flagging instances of plagiarism, this technology can promote academic integrity, protect the originality of ideas and works, and help maintain the credibility of academic institutions and publishing industries.

# Concepts

- **Intrinsic Plagiarism Detection** - Detecting plagiarism using only data within the document.
- ************************************************************External Plagiarism Detection************************************************************ - Comparing the suspected document with possible sources

# Kinds of Plagiarism

The different kinds of plagiarism are:

- **Exact Copy**. The passage is copied word for word, without citation.
- **Paraphrasing**. The text is modified, but the idea and part of the words remain the same.
- **Plagiarism of ideas**. The idea is copied using different words and language.

# Solutions

## Text Mining

In the context of plagiarism detection, **text mining algorithms compare the text of a given document with a database of previously published works and other sources.** The algorithms then search for similarities and matches between the two sets of texts, identifying instances of potential plagiarism. Some text mining techniques also take into account variations in sentence structure, synonyms, and paraphrasing to identify instances of disguised plagiarism.

### Quotes in favor

> The main goal is to discover deviations in the style, looking for segments of the document that could have been written by another person. [1]
> 

## Natural Language Processing (NLP)

In the context of plagiarism detection, NLP can be used to **analyze written text and identify instances of plagiarism.** This is achieved through various techniques, such as syntactic analysis, semantic analysis, and text similarity analysis. Syntactic analysis involves analyzing the structure of the text to identify patterns and similarities between different sentences and phrases. Semantic analysis, on the other hand, focuses on the meaning of the text, identifying similarities in the underlying concepts and ideas.

### Quotes in favor

## Current Pick - Text Mining

Text mining is generally **faster** and **more efficient** than NLP in terms of processing large amounts of text data, which can be useful when dealing with large databases or multiple documents. Additionally, text mining **can identify exact matches of text,** which can be more effective in detecting instances of plagiarism than NLP.

# Questions

- What do we compare the text we receive to
- Can we use intrinsic plagiarism detection to find problem areas and then use external plagiarism detection with the problem areas?
- Can we somehow link our project with new NLP tools such as GPT-4 and help solve the problematic of plagiarism using them.
- For [1] we might need very large documents to be order to detect styling changes

# Sources of interest

1. [https://www.sciencedirect.com/science/article/abs/pii/S0957417412013231](https://www.sciencedirect.com/science/article/abs/pii/S0957417412013231)
    1. This research uses Text Mining to detect plagiarism by detecting variations in the writing style. It does not require extra data to compare.
    2. Full Paper: [https://moscow.sci-hub.se/2088/104faa5a24c00d1cdebe0e900b38fb1f/oberreuter2013.pdf?download=true](https://moscow.sci-hub.se/2088/104faa5a24c00d1cdebe0e900b38fb1f/oberreuter2013.pdf?download=true)