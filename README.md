# Parti Pris Digital Archive

This repository contains code and data for the text extraction adn analysis of the *Parti Pris* magazine corpus (1963–1968).

## Project Overview

- **Corpus:** Digitized PDFs of all 42 issues of *Parti Pris*, sourced from the Bibliothèque et Archives Nationales du Québec [(BAnQ)](https://numerique.banq.qc.ca/rechercheExterne/encoded/Kg==/false/D/asc/W3sibm9tIjoiY29ycHVzIiwidmFsZXVyIjoiUGF0cmltb2luZSUyMHF1w6liw6ljb2lzIn0seyJub20iOiJ0eXBlX2RvY19mIiwidmFsZXVyIjoiUmV2dWVzJTIwZXQlMjBqb3VybmF1eCJ9LHsibm9tIjoibnVtZXJvX25vdGljZSIsInZhbGV1ciI6IjAwMDAxNjMxMjIifV0=/Toutes%20les%20ressources/true/false/).
  
- **Goals:**
  - Extract individual articles, authors, and metadata from each issue using OCR and LLM-based methods.
  - Convert extracted data into CSV format for further analysis.
  - Identify and fix extraction mistakes using automated and manual quality checks.
  - Run text analysis on the cleaned dataset.

- **Methods:**
  - Automated extraction using Gemini 2.5 API
  - Structured output in JSON format
  - Quality control via article counts, token usage, and table of contents comparison
  - Data cleaning and conversion to CSV
  - Text analysis using Python notebooks

## Folder Structure

- `notebooks/` — Jupyter notebooks for text extraction with quality checks, cleaning/preprocessing, and analysis
- `data/` — Contains example PDFs, full transcriptions, and metadata
- `img/` — Example covers, screenshots, and figures

## References

- [Parti Pris on The Canadian Encyclopedia](https://www.thecanadianencyclopedia.ca/en/article/parti-pris)
