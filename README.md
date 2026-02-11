# VPS Support Ticket Clustering

NLP-based clustering and topic modeling of VPS hosting support tickets using LDA and BERTopic. Analysis of 2700+ multilingual customer support conversations.

## Overview

This project applies unsupervised machine learning to customer support chat logs from a VPS hosting provider to identify recurring issues and improve service efficiency.

**Goal:** Reduce repetitive ticket workload and improve response times by identifying common support topics through text analytics.

## Methodology

- **Data:** 5000+ anonymized chat logs and email tickets (2021-2025)
- **Preprocessing:** Text cleaning, language detection, lemmatization, anonymization
- **Models:** Latent Dirichlet Allocation (LDA) and BERTopic clustering
- **Validation:** Coherence score 0.63, manual review by support team

## Key Findings

Identified 15 main topics including:
- Billing & payments (14%)
- Trial period requests (10%)
- Server access issues (12%)
- Technical configuration (18%)
- Control panel errors (8%)


## Technologies

Python • scikit-learn • gensim • BERTopic • pandas • matplotlib • pyLDAvis

## Note on Data

Due to GDPR compliance, the original dataset cannot be shared. The notebook includes all outputs (visualizations, metrics, results) to demonstrate the methodology.

## Documentation

Comprehensive project documentation is available in the `/docs` folder:

- **Project Overview** – business context, problem statement, and KPIs
- **Solution Design** – data science approach and methodology
- **Data Evaluation** – data sources, quality assessment, and preprocessing
- **Ethics Assessment** – privacy, GDPR compliance, and responsible AI practices


