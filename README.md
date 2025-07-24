# Final Project: Article Summarizer

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Polarity score printed with an appropriate label: 1 pt
* (Question 2) Number of sentences printed: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Histogram shown with appropriate labelling: 1 pt
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Cutoff score seems appropriate given histograms: 2 pts (1/score)
* (Question 8) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 8) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 9) Polarity score printed with an appropriate label: 1 pt
* (Question 9) Number of sentences printed: 1 pt
* (Question 10) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 10) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 11) Polarity score printed with an appropriate label: 1 pt
* (Question 11) Number of sentences printed: 1 pt
* (Question 12) Thoughtful answer based on reported polarity scores: 1 pt
* (Question 13) Thoughtful answer based on summaries: 1 pt


# 📝 Final Project: Article Summarizer

This project summarizes an online article using Natural Language Processing (NLP) techniques including tokenization, lemmatization, sentence scoring, and sentiment analysis.

---

## ✅ Project Overview

The main goals of this project were to:
- Scrape and clean an article from the web.
- Score sentences based on token and lemma frequency.
- Generate a summary based on sentence scores.
- Compare sentiment polarity between the original and the summary.

---

## 📂 Project Files

| File Name               | Description                                              |
|------------------------|----------------------------------------------------------|
| `article.html`         | The raw HTML file containing the article content         |
| `article_summarizer.py`| Python script containing all steps and logic             |
| `requirements.txt`     | A list of the Python packages required for the project   |
| `README.md`            | This file                                                |

---

## ✅ Completed Tasks

The following tasks from the rubric were completed:

1. Stored HTML in `article.html`
2. Printed polarity score and sentence count of original article
3. Printed most frequent tokens
4. Printed most frequent lemmas
5. Created histogram for token scores
6. Created histogram for lemma scores
7. Determined appropriate cutoff score
8. Generated summary using token scores (ordered, shortened)
9. Printed polarity & sentence count of token summary
10. Generated summary using lemma scores (ordered, shortened)
11. Printed polarity & sentence count of lemma summary
12. Compared polarity scores
13. Compared summary quality

---

## 📦 Dependencies

Install the required packages using:

```bash
pip install -r requirements.txt
