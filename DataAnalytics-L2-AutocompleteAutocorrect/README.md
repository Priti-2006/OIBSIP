# Autocomplete and Autocorrect Data Analytics

## Oasis Infobyte Data Analytics Internship
**Name:** Priti Ranjit
**Track:** Data Analytics
**Task:** Level 2 - Task 5 (Autocomplete & Autocorrect)

## Objective
Analyse the efficiency and accuracy of autocomplete and 
autocorrect algorithms using NLP techniques. Implement and 
compare multiple approaches for text prediction and spelling 
correction on a real text dataset.

## Tools Used
- Python 3.11
- NLTK (Gutenberg Corpus, Tokenization, N-grams)
- Pyspellchecker (Edit Distance Autocorrect)
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook (VS Code)

## Dataset
NLTK Gutenberg Corpus (Built-in classic books corpus)

## Steps Performed
1. Load Text Corpus (Gutenberg Books)
2. NLP Preprocessing Pipeline
3. Top 20 Most Frequent Words Analysis
4. Autocomplete with Bigram + Trigram N-gram Model
5. Test Autocomplete on 10 Input Prefixes
6. Autocorrect with Edit Distance (pyspellchecker)
7. Test Autocorrect on 20 Misspelled Words
8. Performance Metrics (Precision, Recall, F1)
9. Algorithm Comparison (Bigram vs Trigram)
10. Performance Visualization

## Key Insights
- Trigram model gives more contextually relevant predictions
- Combined Bigram + Trigram approach gives best coverage
- Pyspellchecker handles common typos effectively
- Production systems use neural models trained on 
  billions of documents

## Files
- PritiRanjit_L2Task5_AutocompleteAutocorrect.ipynb
- top_20_words.png
- performance_summary.png
