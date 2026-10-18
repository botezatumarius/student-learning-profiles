# Clustering Student Learning Profiles

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/botezatumarius/student-learning-profiles/blob/main/student_learning_profiles.ipynb)

Unsupervised analysis of how students used an online ML learning tool and how they performed on the exam (Machine Learning Techniques 43504, University of Alicante, 2026–2027).

The notebook clusters the same students twice, once on **tool use** and once on **exam performance**, and then tests whether the two partitions agree beyond chance.

## Key findings

- **Three engagement profiles:** Ghosts, Samplers and Completionists (silhouette 0.69, bootstrap stability 0.99). Study *pace* is a continuum, not a profile.
- **Engagement and performance are independent** (AMI ≈ 0, permutation p ≈ 1).
- **The exam divides on one topic:** the weaker group earns 17% of the reinforcement-learning points against 72% for the stronger group.
- **The 2nd call is a retake cohort:** 9 of 10 retakers never touched the tool again between calls.

## Contents

| Path | Description |
|---|---|
| `student_learning_profiles.ipynb` | Self-contained report: code, outputs and written analysis |
| `data/kmai-tau.csv` | Original dataset |

## Running

Click the badge above and run all cells. The dataset loads directly from this repository, and Colab already has every dependency (pandas, scikit-learn, seaborn, scipy).
