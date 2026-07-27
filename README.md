# Job Skills Extractor for German and English Job Descriptions

## Problem

Students and early-career applicants often need to compare their current skills with the technical requirements in internship and working-student job descriptions. Doing this manually across many job ads is slow and inconsistent.

## Project Goal

This project analyses German and English job descriptions to:

- Extract requested technical skills and tools
- Classify job descriptions into broad role categories
- Compare extracted requirements with a candidate skill profile
- Identify frequently requested skills across a collection of job ads

## Initial Approach

The first version uses a transparent rule-based baseline:

1. Clean raw job-description text
2. Match skills using predefined keyword and regex rules
3. Assign role categories using keyword rules
4. Analyse skill and role frequencies with pandas and simple charts

Later versions may add spaCy patterns, a machine-learning classifier, and a Streamlit interface.

## Planned Stack

- Python
- pandas
- Regular expressions (`re`)
- matplotlib and seaborn
- Streamlit
- Git and GitHub

## Data

The initial dataset will contain a small, manually created and anonymised set of German and English internship and working-student job descriptions. Public datasets may be added later, subject to their licence and terms of use.

## Status

Work in progress. The current phase is repository setup and preparation of a small test dataset.
