# Zepto AI/ML Engineer Capstone Project

This repository contains the end-to-end capstone project for Zepto's analytics guild, featuring a data engineering pipeline, an advanced analytics & predictive modeling pipeline, and a GenAI policy support assistant.

## Repository Structure
- `/data_pipeline`: Scrapes live product data, cleans it, applies fixed-rate currency conversion, stores it in a normalized SQLite DB, and runs analytical queries.
- `/analytics`: Profiles the Titanic dataset, builds visual data stories, trains/tunes multi-model classifiers with strict leakage prevention, handles class imbalance, evaluates regression, and saves a serialized sklearn pipeline.
- `/support_assistant`: Implements a grounded GenAI retrieval-augmented generation (RAG) service for Zepto's internal policies.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone [https://github.com/rajiycareer/zepto-ai-capstone.git](https://github.com/rajiycareer/zepto-ai-capstone.git)
   cd zepto-ai-capstone