
# Text Vectorization Techniques: BOW, TF-IDF, and Word2Vec

This repository contains a comprehensive Jupyter notebook that explores three fundamental text vectorization techniques used in natural language processing: Bag of Words (BOW), Term Frequency-Inverse Document Frequency (TF-IDF), and Word to Vector (Word2Vec). Each method is crucial for converting text data into numerical form, enabling the development of various machine learning models for tasks such as sentiment analysis, topic modeling, and document classification.

## Features

- **Bag of Words (BOW)**: Understand the simple yet powerful technique of BOW, which transforms text into fixed-length vectors by counting word occurrences.

- **TF-IDF**: Learn how TF-IDF not only takes into account the frequency of words but also how unique a word is to a document in a corpus, helping to highlight important words that are frequent in a document but not across documents.

- **Word to Vector (Word2Vec)**: Dive into Word2Vec, a more sophisticated approach that captures the semantic relationships between words by representing them in a continuous vector space.

## Contents

1. **Introduction to Vectorization**: Overview of why vectorization is essential in NLP.
2. **Implementation of BOW**: Step-by-step implementation of the Bag of Words model.
3. **Exploring TF-IDF**: Detailed exploration of the TF-IDF model with examples.
4. **Word2Vec Demonstration**: Implementation and demonstration of Word2Vec using the Gensim library.
5. **Comparison of Vectorization Techniques**: Comparative analysis of the results from BOW, TF-IDF, and Word2Vec.
6. **Applications**: Discussion on the practical applications of each vectorization technique in real-world scenarios.
7. **Conclusion**: Summary of key takeaways and potential future work.

## Installation

```bash
pip install numpy pandas matplotlib sklearn gensim
```

## Usage

This notebook is interactive and meant to be run in a Jupyter environment. Clone the repository, navigate to the directory containing the `.ipynb` file, and run the following command:

```bash
jupyter notebook
```

Select the `BOW_TFIDF_Word_to_Vec_vectorization_techniques.ipynb` file to open it and execute the cells sequentially to see each vectorization technique in action.

## Contributing

Contributions are welcome! Please read the contributing guidelines to get started.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
