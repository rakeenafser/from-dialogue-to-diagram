# From Dialogue to Diagram

### Structuring and Visualising Data Analysis with Large Language Models

This project investigates how Human–LLM data analysis conversations can be transformed into structured visual representations that make analytical reasoning easier to inspect.

The framework separates an LLM interaction into two layers:

- **Behavioural layer** — what the LLM actually says and does during the analytical conversation.
- **Cognitive layer** — a structured, self-reported representation of the reasoning steps, summaries, explanations and intended next actions.

These layers are converted into graph structures and compared to investigate alignment, reasoning drift, omissions and differences between intended and observed analytical behaviour.

## Problem

Human–LLM analytical conversations are usually presented as long linear chat logs, making it difficult to inspect how an analysis develops, whether planned analytical steps are actually followed, and where reasoning may diverge or drift.

This project addresses that problem by converting analytical conversations into structured visual representations that make the relationship between an LLM's **self-reported reasoning** and its **observable behaviour** easier to inspect.

## Project Pipeline

Raw Human–LLM Conversations  
→ JSON Extraction & Cleaning  
→ Cognitive and Behavioural Graph Construction  
→ Interactive Visualisation  
→ Alignment & Divergence Evaluation

## Key Results

Using the Heart Disease analysis as the main evaluated case study:

- Most cognitive reasoning nodes showed **90–100% semantic alignment** with the corresponding behavioural output.
- Despite the high overall alignment, the analysis revealed **localised divergence** between stated reasoning and observed behaviour.
- Divergence appeared through **expansion, compression and omission** of analytical steps.
- The visual comparison helped identify examples of **reasoning drift**, showing that the LLM's stated analytical plan acted more like a flexible guide than a strict execution sequence.


## Technologies

- Python
- JSON
- NLTK
- JavaScript
- D3.js
- Observable
- Jupyter Notebook
- Visual Analytics


## Repository Structure

- `notebooks/01_data_cleaning.ipynb` — cleans and structures the raw Human–LLM conversation logs.
- `notebooks/02_evaluation.ipynb` — evaluates alignment between the cognitive and behavioural reasoning representations.
- `data/raw/` — contains the original Human–LLM conversation logs used in the project.
- `data/processed/` — contains cleaned JSON graph data used for visualisation and evaluation.

## Interactive Visualisation

An interactive version of the graph visualisation is available on Observable.

https://observablehq.com/@rakeens-workplace/from-dialogue-to-diagram-structuring-and-visualizi

## MSc Data Science Dissertation

City St George's, University of London  
MSc Data Science, 2024–2026
