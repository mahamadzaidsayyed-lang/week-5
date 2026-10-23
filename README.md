# Week 5 Task: Research and Data-Driven Decision Making (Healthcare)

Research report that integrates a literature review (four public, peer-reviewed sources) with a **simulated** healthcare data analysis and proposes a decision-making framework. All patient data are synthetic.

## Files
| File | Purpose |
|---|---|
| `Research_Report.docx` | Main deliverable: research report |
| `research_analysis.py` | Simulated analysis, risk model, thresholds, data-quality mapping, framework diagram |
| `data/patients_week2.csv` | Simulated patient data (from Week 2) |
| `data/week1_cleaning_log.json`, `data/week3_summary.json` | Evidence from earlier weeks |
| `data/risk_threshold_table.csv` | Effect of alert thresholds |
| `charts/` | Four PNG figures |
| `results.json` | Computed values |

## Sources reviewed
1. Feltner C, et al. (2014). Transitional care interventions to prevent readmissions for persons with heart failure. *Annals of Internal Medicine*, 160(11), 774-784. https://doi.org/10.7326/M14-0083
2. Kansagara D, et al. (2011). Risk prediction models for hospital readmission: a systematic review. *JAMA*, 306(15), 1688-1698. https://doi.org/10.1001/jama.2011.1515
3. Sutton RT, et al. (2020). An overview of clinical decision support systems: benefits, risks, and strategies for success. *npj Digital Medicine*, 3, 17. https://doi.org/10.1038/s41746-020-0221-y
4. Weiskopf NG, Weng C. (2013). Methods and dimensions of electronic health record data quality assessment. *JAMIA*, 20(1), 144-151. https://pmc.ncbi.nlm.nih.gov/articles/PMC3555312

## Run
```
pip install pandas numpy scipy matplotlib
python research_analysis.py
```
