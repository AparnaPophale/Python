# Web Scraping and NLP Analysis of a Project Gutenberg eBook

## Overview
This project demonstrates an end-to-end Python workflow for **web scraping and natural language processing (NLP)** applied to a **public-domain eBook from Project Gutenberg**. Using open-source tools, the project extracts bibliographic metadata and performs exploratory text analysis on the first chapter of the book, including word frequency analysis, sentiment analysis, and visualization.

The project highlights how computational text analysis techniques can be applied in **digital humanities, library analytics, educational research, and applied NLP workflows**.

---

## Objectives
- Scrape and process HTML-based public-domain text data  
- Perform NLP preprocessing and analysis using Python  
- Visualize linguistic patterns and sentiment trends  
- Demonstrate a reproducible and instructional text-analysis pipeline  

---

## Data Source
- **Project Gutenberg** (public-domain content)  
- eBook analyzed: *Artificial Light: Its Influence upon Civilization*

---

## Methods & Tools

### Programming & Environment
- Python 3.12+ 
- Jupyter Notebook  

### Libraries Used
- **Web Scraping:** BeautifulSoup  
- **Natural Language Processing:** NLTK  
- **Data Processing:** pandas  
- **Visualization:** matplotlib, WordCloud  

---

## Workflow (End-to-End Pipeline)
1. Scrape an HTML-formatted eBook from Project Gutenberg  
2. Extract bibliographic metadata (Title, Author, Release Date, Language)  
3. Identify and extract Chapter I using Roman numeral detection  
4. Tokenize chapter text using NLTK  
5. Remove English stopwords  
6. Generate word frequency distributions and plots  
7. Apply lemmatization to normalize word forms  
8. Perform sentiment analysis on the chapter text  
9. Visualize results using frequency plots and a word cloud  

---

## Project Structure
  ```text
  ├── ebook_web_scraping.ipynb   # Complete analysis workflow
  ├── requirements.txt           # Project dependencies
  ├── README.md                  # Project documentation
  └── LICENSE                    # MIT License
  ```
---

## Results & Insights
- Identified dominant terms and themes within the selected chapter  
- Visualized word frequency distributions and lexical emphasis  
- Assessed overall sentiment trends in the text  
- Demonstrated how NLP techniques can support exploratory literary and textual analysis  

---

## Practical Applications
- Digital humanities and computational text analysis  
- Library-led workshops on text mining and open data  
- Educational demonstrations of NLP workflows  
- Foundational preprocessing pipeline for document analytics and ML tasks  

---

## How to Run the Project
1. Clone the repository:  *git clone https://github.com/yourusername/your-repo-name.git*
2. Install dependencies: *pip install -r requirements.txt*
3. Open the notebook: *jupyter notebook ebook_web_scraping.ipynb*
4. Run the cells sequentially to reproduce the analysis

---

## Future Enhancements
- Extend analysis to multiple chapters or full-text analysis
- Compare sentiment trends across chapters
- Enable batch analysis of multiple Project Gutenberg books
- Develop interactive dashboards using Streamlit or Dash
- Implement POS-aware lemmatization for improved linguistic accuracy
- Integrate Named Entity Recognition (NER) using spaCy


### License
This project is licensed under the MIT License.

**Ethical Use Notice:**
This project is intended for educational, research, and professional learning purposes.
Misrepresentation of authorship or deceptive use is unethical. Attribution is required under the MIT License.








