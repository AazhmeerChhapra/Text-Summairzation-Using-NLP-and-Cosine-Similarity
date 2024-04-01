# Automatic Text Summarization using TextRank Algorithm

This repository contains Python code for generating automatic summaries of text documents using the TextRank algorithm, a graph-based algorithm for keyword extraction and summarization. TextRank is widely used for extractive text summarization, where important sentences are identified and extracted to form a concise summary of the input text.

# Features:
Text Preprocessing: The code preprocesses the input text by tokenizing sentences, converting words to lowercase, and removing stopwords and non-alphabetic characters.
Sentence Similarity: It calculates the similarity between sentences using cosine distance based on their word vectors.
Graph-based Ranking: The code constructs a similarity matrix and then builds a graph from it. It applies the PageRank algorithm to rank the sentences based on their importance.
Summary Generation: Finally, it generates a summary by selecting the top-ranked sentences according to their PageRank scores.
# How to Use:
Clone the repository to your local machine.
Ensure you have NLTK installed (pip install nltk) and download the required stopwords (nltk.download("stopwords")).
Provide the path to your text file as input to the generate_summary() function.
Adjust the top_n parameter to specify the number of sentences you want in the summary.
Run the script, and the summary will be printed to the console.
Feel free to contribute, report issues, or suggest improvements!
