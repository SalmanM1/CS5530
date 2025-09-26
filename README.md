# CS5530

This repository contains my coursework for CS5530. Each assignment lives in its own folder.

## Assignment 1
### What’s inside:
- **notebooks/**  
  Jupyter notebooks with all code for both problems.  
  - `Problem1_Frailty.ipynb`  
  - `Problem2_Student_Performance.ipynb`
- **reports/**  
  Written outputs and interpretations.  
  - `findings.md` (Problem 1: summary table + grip and frailty correlation)  
  - `reports.md` (Problem 2: Interpretations for the visualizations)
- **data/**  
  Input datasets and (for Problem 1) the processed CSV.  
  - `raw/` (`frailty_data.csv` and `StudentsPerformance.csv`)  
  - `processed/` (`frailty_data_processed.csv`)
- **figures/** *(Problem 2)*  
  Saved plots: `V1.png`, `V2.png`, `V3_1.png`, `V3_2.png`, `V4.png`, `V5.png`.

### Notes
- **Figure size requirement:** Per the assignment, all figures are saved at **800×600 px, 300 DPI**.  
  - Because of this constraint, some labels/ticks may appear tighter in the saved PNGs than they do in the notebook preview.  
  - **Tip:** For the best viewing experience, open the notebook and run the cells; figures render larger in the notebook.
- **Problem 1 (Frailty):**  
  - Workflow: **ingest → process → analyze**.  
  - Unit conversion (in→m, lb→kg), BMI/age-group features, binary encoding for Frailty.  
  - One-hot AgeGroup columns are included; **absent** groups are recorded as `NA` (not `0`) so they don’t inflate numeric summaries.  
  - Outputs: `frailty_data_processed.csv` and `reports/findings.md`.
- **Problem 2 (StudentsPerformance):**  
  - Preprocessing: dataset audit with missingness check (none found) and light validation.  
  - Visualizations V1–V5 produced and saved to **figures/**, with 5–8 sentence interpretations in `reports.md`.

### How to run
1. Open the notebooks in **notebooks/** (e.g., in Google Colab or locally).  
2. Ensure the datasets in **data/raw/** are present.  
3. Run top-to-bottom. Outputs (processed CSVs and figures) will appear in the corresponding folders.

---

*I’ll add similar sections for future assignments as they’re uploaded.*
