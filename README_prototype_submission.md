# Scrolling Through Change: Detecting How Major Societal Events Reshape Instagram Language

## Authors
Maya Patel & Vyshu Telukuntla

## Overview
This Applied Machine Learning Project examines whether language models can detect shifts in Instagram captions before vs. after the **2016 U.S. Presidential elections**, and whether detection differs between politicians and influencers.

## Research Question
Can a language model detect belief shifts in Instagram captioning before versus after major political events, focusing on the 2016 U.S. election, and does the detection of belief shifts differ between influencer accounts and political figure accounts? 

Note: We may expand beyond the 2016 United States presidential election to include additional events (e.g., COVID-19) to see how belief shifts vary across contexts.

## Dataset
- 800 captions from 40 accounts (20 politicians, 20 influencers)
- Balanced: pre (2014–2015) vs. post (2017–2018)

## Methods
- **Baseline:** TF-IDF + Logistic Regression  
- **Model:** Fine-tuned BERT (bert-base-uncased)  
- Split: 70% train, 10% validation, 20% test (by username)

## Files
- Prototype_Scrolling_Through_Change.pdf - full write-up
- project_prototype_code.py - code
- captions.csv - dataset
