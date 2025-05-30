# Gambling Addiction & Psychology - DSA210 Project

## Project Overview

This project explores the psychological and behavioral aspects of gambling addiction, analyzing how traits like impulsivity, risk tolerance, and conscientiousness influence gambling behavior. Using statistical techniques and data visualization, we aim to uncover patterns between personality traits, gambling activity, and socioeconomic stress factors.

The goal is to provide actionable insights that can help individuals, policymakers, and mental health professionals better understand gambling addiction.

## Motivation

Gambling addiction is a growing issue worldwide, affecting millions financially and psychologically. This project explores the psychological mechanisms behind addictive gambling behaviors using real-world behavioral, financial, and survey data.

Specifically, we aim to understand:
- Why individuals continue gambling despite significant losses (loss aversion, sunk cost fallacy)
- How personality traits (such as impulsivity and conscientiousness) correlate with gambling behavior
- How financial hardship may trigger gambling escalation or relapse

## Project Objectives

- Explore how impulsivity, risk tolerance, and conscientiousness impact gambling addiction
- Identify predictors of gambling risk using psychological and behavioral indicators
- Analyze broader socioeconomic factors (e.g., consumer debt trends) that may exacerbate gambling addiction

## Datasets Used

- **ICPSR Gambling & Mental Health Study**  
  (Gambling behavior, DSM-IV symptom counts, mental health indicators)
- **Kaggle Gambling Behavior Dataset**  
  (Gambling bets, cashouts, and profit/loss records)
- **Kaggle Big Five Personality Traits Dataset**  
  (Self-reported personality trait scores: OCEAN model)
- **Federal Reserve Consumer Debt Reports**  
  (National debt trends to assess background financial stress)

**Note**: Kaggle Big Five Personality Traits Dataset is added to data/ExternalDataLinks.md due to GitHub file size limitations.

### 🛠️ Methods

- **EDA:** Histograms, boxplots, and distribution curves for spend, DSM scores, personality traits
- **Hypothesis Testing:** Two-sample t-tests comparing problem vs. non-problem gamblers
- **Modeling:**
  - Logistic Regression
  - Random Forest Classifier
- **Model Evaluation:**
  - Confusion Matrix
  - Classification Report
  - ROC Curve & AUC Score

---

## 📈 Key Findings

- **DSM-IV Gambling Scores:** Only ~3–4% of participants met the “problem gambler” threshold (5+ DSM symptoms).
- **Personality Traits:** Conscientiousness showed significant group differences, supporting its link to self-control and risk.
- **Model Performance:** Both models struggled with classifying problem gamblers due to class imbalance (only 11 of 590 test cases). AUC scores around 0.60 reflected weak separation.
- **ROC Curves:** Despite high overall accuracy, both models failed to identify positive cases—highlighting a need for improved sampling or resampling techniques.

---

## Results

- Problem gamblers exhibited significantly higher DSM-IV symptom counts compared to non-problem gamblers.
- Personality trait analysis showed a moderate but statistically significant difference in conscientiousness scores across sampled groups.
- National debt trends suggest increasing background financial stress, potentially correlating with gambling relapse risk.
- Severe class imbalance made it difficult to train effective models for problem gambling.

