# Web Scraping and NLP Analysis of Project Gutenberg eBook

This project demonstrates how to scrape an eBook (HTML format) from Project Gutenberg and apply **NLP** techniques using **NLTK** to analyze the text. The workflow includes extracting metadata, processing the first chapter, generating word frequency plots, and visualizing results with a word cloud using **BeautifulSoup**, **NLTK**, **matplotlib**, and **WordCloud** libraries.



## Steps:

End-to-end pipeline:

1. Scrape a Project Gutenberg HTML page
2. Extract metadata (Title, Author, Release Date, Language)
3. Extract and analyze Chapter I using Roman numeral detection (I, II)
4. Tokenize the chapter text using NLTK
5. Remove English stopwords
6. Generate a word frequency plot using matplotlib
7. Lemmatize the words and visualize their frequencies
8. Perform sentiment analysis on the chapter text
9. Generate and visualize a word cloud



## Files:

* ebook\_web\_scraping.ipynb
* Project Gutenberg eBook: [Artificial Light: Its Influence upon Civilization](https://www.gutenberg.org/cache/epub/17625/pg17625-images.html)
* requirements.txt



## Future Scope:

* Extend the analysis to multiple chapters or the entire book for more comprehensive insights.
* Compare sentiment trends across chapters to study emotional progression throughout the narrative.
* Enable scraping and analysis of multiple Project Gutenberg books for comparative literary analysis.
* Develop an interactive visualization dashboard using Streamlit or Dash for enhanced user engagement.
* Implement POS-aware lemmatization by assigning Part-of-Speech tags to accurately convert verbs, adjectives, and nouns to their true root forms instead of defaulting to noun-based lemmatization.
* Integrate Named Entity Recognition (NER) using the spaCy library to automatically identify and categorize entities such as historical figures, geographic locations, and dates within the text.



### License
© 2025-2026 APARNA S POPHALE. All rights reserved.

This repository is public for viewing and educational purposes only. Unauthorized reuse, modification, or redistribution of any part of this project requires explicit written permission from the author.


