# Predicting Depression Severity from Social Media Behavior

## Overview
This project analyzes how social media behavioral patterns such as screen time, late-night usage, and activity type predict depression severity among young adults, measured using the PHQ-9 clinical scale.

## Research Questions
- Can social media behavior patterns predict depression severity?
- Which behavioral factors (screen time, late-night usage, activity type, platform choice) have the most predictive power?

## Why This Matters
Understanding which specific behaviors are linked to depression risk can inform digital wellness tools, mental health screening, and behavioral interventions — helping identify at-risk individuals earlier.

## Dataset
Social media and mental health dataset (Kaggle) — 8,000 individual survey respondents
- **Outcome variable:** PHQ-9 depression score (range 0–27)
- **Predictors:** daily screen time, late-night usage, activity type (active vs. passive), platform, sleep duration, demographics

## Methods
- Data cleaning + preparation
- Exploratory Data Analysis (EDA)
- Linear regression, random forest regression, and classification tree modeling (R)

## Key Findings
- Late-night usage was the strongest predictor: late-night users averaged a PHQ-9 of 9.48 vs. 2.89 for non-late-night users
- Depression scores increased sharply once daily screen time exceeded ~4 hours
- Passive scrolling was associated with higher depression than active engagement, contradicting our initial hypothesis
- Platform choice and demographics were weak predictors — behavioral patterns mattered most

## About
This was a group project completed during my MSBA coursework at UC Irvine. I contributed to EDA and independently built a classification tree model in addition to the team's linear regression and random forest models.

## Files
- `depression_analysis.R` — R code with modeling workflow
- `/slides/social_media_depression_slides.pdf` — final presentation deck
