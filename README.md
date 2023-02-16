# Topic-Modeling---LDA---WANA-Cannabis-Customer-Reviews

**Wana Gummies Reviews Analysis**
This project is a data analysis of customer reviews for multiple Wana gummies, which were extracted from the iHeartJane website. The goal of this project is to perform topic modeling on the reviews and identify the most commonly discussed topics.

**Contents**

1.	Introduction
2.	Import Dataset
3.	Tokenize Sentences and Clean
4.	Build the Bigram, Trigram Models and Lemmatize
5.	Build the Topic Model and Optimizing it using coherence
6.	Presenting the Results
    - What is the Dominant topic and its percentage contribution in each document?
    - The most representative sentences for each topic
    - Frequency Distribution of Word Counts in Documents
    - Word Clouds of Top N Keywords in Each Topic
    - Word Counts of Topic Keywords
    - Sentence Chart Colored by Topic
    - What are the most discussed topics in the documents?
    - t-SNE Clustering Chart
    - pyLDAVis Visualization
7.	Conclusion

**Requirements**
To run the analysis, you will need to have the following installed:
1.	Python 3
2.	Jupyter Notebook
3.	Pandas
4.	NLTK
5.	Gensim
6.	pyLDAvis

**Data**
The data used in this analysis consists of customer reviews for multiple Wana gummies. The data was extracted from the iHeartJane website using web scraping techniques.

**Analysis**
The analysis is performed using Jupyter Notebook and the Python programming language. The notebook is provided in the analysis directory and contains the following sections:
1.	**Introduction**: This section provides an overview of the project and the data.
2.	**Import Dataset**: This section imports the data and prepares it for analysis.
3.	**Tokenize Sentences and Clean**: This section tokenizes the sentences in the customer reviews and performs cleaning operations, including removing stop words and punctuation.
4.	**Build the Bigram, Trigram Models and Lemmatize**: This section builds bigram and trigram models to identify frequently occurring phrases and lemmatizes the text to reduce inflectional forms to a common base form.
5.	**Build the Topic Model and Optimizing it:** This section builds an LDA (Latent Dirichlet Allocation) topic model to identify the most discussed topics in the customer reviews. The model is optimised using jaccard score and coherence score.
6.	**Presenting the Results**: This section presents the results of the analysis, including:
    - What is the Dominant topic and its percentage contribution in each document?
    - The most representative sentences for each topic
    - Frequency Distribution of Word Counts in Documents
    - Word Clouds of Top N Keywords in Each Topic
    - Word Counts of Topic Keywords
    - Sentence Chart Colored by Topic
    - What are the most discussed topics in the documents?
    - t-SNE Clustering Chart
    - pyLDAVis Visualization
7.	**Conclusion**: This section summarizes the main findings of the analysis and discusses potential next steps

**Results**
The main findings of the analysis are presented in the analysis/Topic Modleing - LDA - Wana Gummies Reviews Analysis.ipynb Jupyter Notebook. The analysis identified several key topics discussed in the customer reviews, including the taste of the gummies and the effectiveness of the product. 

**Contributing**
Contributions to the project are welcome! If you would like to contribute, please create a new branch and submit a pull request.

**Acknowledgment**s
•	The NLTK and Gensim libraries were used for natural language processing and topic modeling.
•	The iHeartJane website was used as the data source for the project.
•	The pyLDAvis library was used for interactive visualization of



