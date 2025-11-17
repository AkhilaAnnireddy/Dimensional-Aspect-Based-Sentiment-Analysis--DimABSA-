# Dimensional Aspect-Based Sentiment Analysis (DimABSA)

**SemEval-2026 Task 3 - Track A - Subtask 1**

## Project Overview

This project implements a solution for **Dimensional Aspect Sentiment Regression (DimASR)**, which predicts continuous Valence and Arousal scores for aspects mentioned in laptop reviews.

## Team Members

- Developer A: Akhila Annireddy
- Developer B: Vikash Babu

## Task Description

Given a text review and aspects (e.g., "battery", "screen"), predict:

- **Valence**: How positive/negative (1-9 scale)
- **Arousal**: How intense the emotion (1-9 scale)

**Example:**

- Input: "The battery life is amazing" + Aspect: "battery"
- Output: Valence: 8.5, Arousal: 7.2

## Dataset

- **Domain**: Laptop reviews
- **Language**: English
- **Training samples**: 4,076
- **Dev samples**: 200

## Project Structure

```
DimABSA-Project/
├── datasets-subtask-1/           # Data files
├── DimABSA2026_TrackA_subtask1_starter_kit.ipynb  # Baseline notebook
├── requirements.txt              # Dependencies
└── README.md                     # This file
```

## Getting Started

### 1. Install Dependencies

```bash
pip install -r requirements.txt
```
