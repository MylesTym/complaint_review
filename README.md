# CFPB Complaint Analysis: Servicemember vs Non-Servicemember

This project provides a comprehensive analysis of consumer complaints submitted to the Consumer Financial Protection Bureau (CFPB) over the past five years, with a special emphasis on those tagged as 'servicemember.' The workflow demonstrates advanced data science and NLP techniques, robust data cleaning, and interpretable visualizations.

## Project Highlights
- **Data Cleaning & Segmentation:** Isolates servicemember complaints for fair comparison with the general population.
- **Exploratory Data Analysis:** Visualizes complaint volume, product and issue frequency, and seasonal patterns (e.g., PCS season).
- **Comparative Analysis:** Normalizes complaint rates to account for group size differences, revealing issues and companies disproportionately represented among servicemember submissions.
- **Advanced NLP:** Topic modeling (LDA), n-gram frequency analysis, and semantic clustering using sentence embeddings.
- **Interpretable Visualizations:** t-SNE cluster plots with sample complaint context, company-level breakdowns, and seasonal highlights.
- **Portfolio-Ready Documentation:** Professional markdown summary and clear code structure for easy review.

## Technologies Used
- Python (pandas, numpy, matplotlib, seaborn)
- scikit-learn (KMeans, LDA, CountVectorizer, TfidfVectorizer)
- sentence-transformers (MiniLM)

## How to Run
1. Clone the repository and install dependencies (see below).
2. Place the CFPB complaint CSV file in the `data/` directory.
3. Run the notebook in `Data_Processing/clean_data.ipynb` for full analysis and visualizations.

## Installation
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## File Structure
- `data/complaints-csv.csv` — Raw CFPB complaint data
- `Data_Processing/clean_data.ipynb` — Main analysis notebook
- `Data_Processing/analysis_summary.md` — Professional summary of findings

## Example Visualizations
- Complaint rates by company and issue
- Seasonal complaint volume (PCS season)
- t-SNE cluster plots of complaint narratives

## About
This project demonstrates a robust approach to regulatory data analysis, modern NLP, and actionable insights for consumer protection stakeholders. It is portfolio-ready and competitive for data science roles.

---

© 2025 MylesTym. For questions, contact via [LinkedIn](https://www.linkedin.com/in/myles-tym/) or [GitHub](https://github.com/MylesTym).
