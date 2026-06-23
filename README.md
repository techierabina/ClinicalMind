# ClinicalMind 
> Multi-modal ICU Mortality Prediction using MIMIC-IV

## Overview
ClinicalMind is a clinical AI system that predicts ICU patient mortality using structured vitals, lab results, and unstructured clinical notes from the MIMIC-IV database.

## Tech Stack
- PyTorch — mortality prediction model
- BioBERT — clinical notes NLP
- ChromaDB — patient similarity retrieval (RAG)
- FastAPI — model serving endpoint

## Project Structure
- `data/` — local only, not committed
- `notebooks/` — exploration and analysis
- `src/` — model code
- `models/` — saved checkpoints

## Data Access
Data is from MIMIC-IV v3.1 via PhysioNet (credentialed access required).

Visit: https://physionet.org/content/mimiciv/3.1/

⚠️ Do NOT commit any data files.

## Author
Rabina Karki | MS Data Science, University of Central Oklahoma

GitHub: [techierabina](https://github.com/techierabina)