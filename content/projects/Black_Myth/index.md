---
title: Social Media Sentiment Analysis Project
summary: This project builds an end-to-end pipeline to analyze public sentiment on Chinese social media posts using an English sentiment model.
date: '2024-07-28'
image:
  focal_point: 'Smart'
  preview_only: false
---

This project builds an end-to-end pipeline to **analyze public sentiment on Chinese social media posts** using an English sentiment model.  
We collect posts, translate key content, score each entry with probabilistic sentiment metrics, and map them into five categories to support quick diagnostic insight.

---

## What the Notebook Does (2 Parts)

1. **Data Collection & Preprocessing**
   - Scrapes/loads recent posts with metadata (date, text, likes).
   - Adds English translation for each post.
   - Applies a sentiment model to generate:
     - `p_neg`, `p_neu`, `p_pos` — negative/neutral/positive probabilities  
     - `p_comp` — compound sentiment score
   - Stores everything in a structured table for inspection.

2. **Sentiment Classification & Summary**
   - Maps scores into **five classes**: `extremely positive`, `positive`, `neutral`, `negative`, `extremely negative`.
   - Aggregates counts to show the overall mood in the dataset.
   - Provides a basis for downstream visualization (time series, distribution charts, keyword analysis, etc.).

---

## Visual Overview

```md
![Labeled sample posts with sentiment scores](images/sentiment_table.png)

![Distribution of sentiment categories](images/sentiment_distribution.png)