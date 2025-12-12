** Tokenization & Text Processing – Assignment **
This project processes an input text file and performs:
    
Text Cleaning
    Lowercase conversion
    Removal of special characters and punctuation
    Removal of extra whitespace, tabs, and newlines
    Stopwords removal using NLTK


Tokenization
    Sentence tokenization (splitting text into sentences)
    Word tokenization (splitting text into individual words)
    
    
Text Analysis
    Word frequency counting
    Display Top 10 most frequent words and their counts


Output Files
    cleaned.txt - Cleaned text with stopwords removed
    words.txt - List of tokenized words (one per line)
    top10words.txt - CSV file with top 10 most frequent words and counts
    
** Libraries used ** 
    re - Regular expressions for text cleaning
    collections.Counter - Efficient word frequency counting
    nltk (Natural Language Toolkit) - Stopwords removal
    os - File and directory management