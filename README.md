# Final Project: Article Summarizer

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
    * Extracted article text from https://www.realcleardefense.com/articles/2025/04/08/navigating_a_changing_military_recruitment_environment_1102614.html and stored as a file named: article_text.pkl
* (Question 2) Polarity score printed with an appropriate label: 1 pt
    * Created Python code to produce the following results:  Polarity Score:  0.063
* (Question 2) Number of sentences printed: 1 pt
    * Created Python code to produce the following results:  Number of Sentences:  34
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
    * Created Python code to produce the following results:  5 Most Frequent Tokens and Their Frequencies:
Token:  'recruiting' - Frequency:  14
Token:  'military' - Frequency:  10
Token:  'recruits' - Frequency:  6
Token:  'research' - Frequency:  6
Token:  'services' - Frequency:  5
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
    * Created Python code to produce the following results:  5 Most Frequent Lemmas and Their Frequencies:
Lemma:  'recruit' - Frequency:  11
Lemma:  'recruiting' - Frequency:  11
Lemma:  'military' - Frequency:  10
Lemma:  'meet' - Frequency:  9
Lemma:  'service' - Frequency:  6
* (Question 5) Histogram shown with appropriate labelling: 1 pt
    * Token Histogram Created
* (Question 6) Histogram shown with appropriate labelling: 1 pt
    * Lammas Histogram Created
* (Question 7) Cutoff score seems appropriate given histograms: 2 pts (1/score)
    * Cutoff Score (tokens):  0.1 - Cutoff Score (lemmas):  0.1
* (Question 8) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
    * Token Summary Complete
* (Question 8) Summary sentences are in the same order as they appeared in the original article: 1 pt
    * See Above
* (Question 9) Polarity score printed with an appropriate label: 1 pt
    * Summary Polarity Score:  0.213
* (Question 9) Number of sentences printed: 1 pt
    * Number of Sentences in the Summary:  8
* (Question 10) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
    * Lammas Summary Complete
* (Question 10) Summary sentences are in the same order as they appeared in the original article: 1 pt
    * See Above
* (Question 11) Polarity score printed with an appropriate label: 1 pt
    * Summary Polarity Score (Lemmas):  0.180
* (Question 11) Number of sentences printed: 1 pt
    * Number of Sentences in the Summary (Lemmas):  8
* (Question 12) Thoughtful answer based on reported polarity scores: 1 pt
    * The polarity scores of both the token-based (0.213) and lemma-based (0.180) summaries are noticeably higher (more positive) than the polarity score of the original article (0.063). This indicates that the summaries tend to focus on sentences with more positive sentiment, likely because of the cutoff thresholds I applied when selecting sentences. The original article tries to maintain a neutral stance, and does a good job of that based on what the histograms show.
* (Question 13) Thoughtful answer based on summaries: 1 pt
    * I think the token-based summary is better because it captures the original tone, even if more positive, and focuses on key topics within the article. Also, while the lemma-based summary is similar in content and tone, it is less accurate since it is based on simplified versions of the original words within the sentences.
