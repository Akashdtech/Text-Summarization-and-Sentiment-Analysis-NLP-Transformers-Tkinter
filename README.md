# Text-Summarization-and-Sentiment-Analysis-NLP-Transformers-Tkinter
This Python project provides functionality for news article extraction, summarization, and sentiment analysis. It leverages several libraries to parse articles, generate summaries, and analyze text sentiment. Additionally, it includes optional code for a graphical user interface (GUI) using tkinter.

News Article Extraction:

    Fetches and processes articles using the newspaper3k library.
    Extracts article metadata such as title, authors, published date, and summary.

Sentiment Analysis:

    Uses the TextBlob library to calculate sentiment polarity for both the full text and the summary.

Advanced Summarization:

    Implements a transformer-based summarizer (using Hugging Face's facebook/bart-large-cnn model) for high-quality, customizable text summarization.

GUI (Optional):

    Provides a basic interface to input a URL and display extracted metadata, summaries, and sentiment analysis.

Dependencies:

    lxml_html_clean: For cleaning HTML content (used with newspaper3k).
    newspaper3k: For article scraping and processing.
    TextBlob: For sentiment analysis.
    nltk: For natural language processing (required by newspaper3k).
    transformers: For using advanced summarization models.
    Optional: tkinter for GUI implementation.

This project showcases the integration of NLP tools for processing and analyzing online news content, suitable for developers exploring text mining and analysis workflows.
