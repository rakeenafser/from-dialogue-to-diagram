# From Dialogue to Diagram

### Structuring and Visualising Data Analysis with Large Language Models

This project investigates how Human–LLM data analysis conversations can be transformed into structured visual representations that make analytical reasoning easier to inspect.

The framework separates an LLM interaction into two layers:

- **Behavioural layer** — what the LLM actually says and does during the analytical conversation.
- **Cognitive layer** — a structured, self-reported representation of the reasoning steps, summaries, explanations and intended next actions.

These layers are converted into graph structures and compared to investigate alignment, reasoning drift, omissions and differences between intended and observed analytical behaviour.

## Project Pipeline

Raw Human–LLM Conversations  
→ JSON Extraction & Cleaning  
→ Cognitive and Behavioural Graph Construction  
→ Interactive Visualisation  
→ Alignment & Divergence Evaluation

## Technologies

- Python
- JSON
- NLTK
- JavaScript
- D3.js
- Observable
- Jupyter Notebook
- Visual Analytics

## Current Repository Contents

- `01_data_cleaning.ipynb` — cleans and structures the raw conversation logs
- `02_evaluation.ipynb` — evaluates cognitive and behavioural reasoning alignment

## Interactive Visualisation

An interactive version of the graph visualisation is available on Observable.

https://observablehq.com/@rakeens-workplace/from-dialogue-to-diagram-structuring-and-visualizi

## MSc Data Science Dissertation

City St George's, University of London  
MSc Data Science, 2024–2026
