# Naïve Bayes Classification

## Task 1: Mushroom Classification

**Objective:** Classify mushrooms as *edible* or *poisonous* using a Naïve Bayes classifier.

- **Dataset:** Mushroom dataset (categorical features)
- **Train–Test Split:** 80% training, 20% testing (random, without replacement)
- **Class Balance:** Maintained using stratified sampling
- **Models Implemented:**
  - Naïve Bayes **without Laplace smoothing**
  - Naïve Bayes **with Laplace smoothing**

**Evaluation:**
- Confusion Matrix (plotted)
- Precision
- Recall
- F1-score

---

## Task 2: Sentiment Classification (Movie Reviews)

**Objective:** Classify movie reviews as *positive* or *negative* sentiment using Naïve Bayes.

- **Dataset:** Movie reviews text dataset
- **Preprocessing:** Tokenization and frequency-based text representation
- **Train–Test Split:** 70% training, 30% testing (random, without replacement)
- **Class Balance:** Maintained using stratified sampling
- **Models Implemented:**
  - Naïve Bayes **without Laplace smoothing**
  - Naïve Bayes **with Laplace smoothing**

**Evaluation:**
- Confusion Matrix (plotted)
- Precision
- Recall
- F1-score

---

## Laplace Smoothing

Laplace smoothing is used to handle zero-probability issues for unseen features. Results are reported **with and without smoothing** to compare performance.

---

## Dataset Link 
Mushroom Dataset : https://drive.google.com/file/d/14kqJdXpuJzC0dLRk5ndHnNZc2osMdtmj/view?usp=sharing
Movie Reveiws    : https://drive.google.com/file/d/11D4lT4Q22vGkYysO7fuyhPfLvm-glNk-/view?usp=sharing

---

## Notes
- Random sampling is done **without replacement**
- Class distribution is balanced in all splits
- Results are reproducible using a fixed random seed (if set)

---

**End of README**
