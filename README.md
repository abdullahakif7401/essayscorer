**OBJECTIVE**
To develop an automated scoring algorithm for student-written essays

**PROCEDURE**
Conducted predictive analysis, through machine learning on a dataset using Python in the Jupyter Notebook environment.

- Read and descrobed the data using basic statistics and exposure to some natural language processing terms.
- Divided the dataset into multiple validation datasets, in order to conduct cross validation.
- Conducted multi-class classification using Support Vector Machine / Regression (SVM).
- Communicated the output of the analysis using Quadratic Weighted Kappa (QWK) measure.
- Experienced independent model evaluation through submission on Kaggle

**DATA**
The data provided was in a single comma seperated (CSV) file, it has been derived from a set of essays and is used to describe the essay features in numeric information. The columns are:
    • essayid - a unique id to identify the essay
    • chars - number of characters in the essay, including spaces
    • words - number of words in the essay
    • commas - numbers of commas in the essay
    • apostrophes - number of apostrophes in the essay
    • punctuations - number of punctuations (other than commas,     apostrophes, period, questions marks in the essay
    • avg_word_length - the average length of the words in the essay
    • sentences - number of sentences in the essay, determined by the period (fullstops)
    • questions - number of questions in the essay, determined by the question marks
    • avg_word_sentence - the average number of words in a sentence in the essay
    • POS - total number of Part-of-Speech discovered
    • POS/total_words - fraction of the POS in the total number of words in the essay
    • prompt_words - words that are related to the essay topic
    • prompt_words/total_words - fraction of the prompt words in the total number of words in the essay
    • synonym_words - words that are synonymous
    • synonym_words/total_words - fraction of the synonymous words in the total number of words in the essay
    • unstemmed - number of words that were not stemmed in the essay
    • stemmed - number of words that were stemmed (cut to the based word) in the essay
    • score - the rating grade, ranging from 1 – 6
