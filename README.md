# Data Science Sprint Challenge: Statistical Tests and Experiments

This project demonstrates statistical analysis and A/B testing techniques in Python. It involves analyzing skeletal remains data and evaluating a case study on A/B testing for Udacity's course enrollment process.

---

## Project Overview

### Part A: Statistical Analysis
We analyze skeletal remains data to:
- Identify missing values and clean the dataset.
- Conduct hypothesis testing on nitrogen levels in long bones.
- Calculate confidence intervals for mean nitrogen levels.
- Interpret statistical findings.

**Dataset**: [Longbones.csv](https://raw.githubusercontent.com/bloominstituteoftechnology/data-science-practice-datasets/main/unit_1/Longbones/Longbones.csv)

**Key Variables**:
- `Site`: Cemetery ID (1 or 2).
- `Time`: Years since burial.
- `Depth`: Burial depth in feet.
- `Lime`: Use of quicklime (0 = No, 1 = Yes).
- `Age`: Age at death (in years).
- `Nitro`: Nitrogen composition in long bones (grams per 100g bone).
- `Oil`: Grave site oil contamination (0 = No, 1 = Yes).

### Part B: A/B Testing
We explore an A/B test on Udacity's enrollment process:
- Determine the effect of a time commitment prompt on student enrollment behavior.
- Apply statistical tests to analyze experiment results.
- Provide actionable insights based on the data.

---

## Technologies Used
- **Python**: Core programming language.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computations.
- **SciPy**: Statistical analysis.
- **Matplotlib** / **Seaborn**: (Optional) Visualization.

---

## How to Use
1. Clone the repository and open the notebook in your Python environment.
2. Ensure the following Python packages are installed:
   - `pandas`
   - `numpy`
   - `scipy`
3. Run the notebook cells sequentially to replicate the analysis.

---

## Key Concepts Demonstrated
- Handling missing data and data cleaning.
- One-sample t-tests and interpreting p-values.
- Confidence interval calculations.
- Practical application of A/B testing principles.

---

## Results Summary
### Part A
- **Null Hypothesis**: Nitrogen levels in long bones are the same as in living individuals (4.3g/100g).
- **Conclusion**: Statistically significant difference was observed, rejecting the null hypothesis.

### Part B
- **A/B Test Outcome**: Analyzed Udacity's data to determine the effect of the time commitment prompt on enrollment behavior.

---

## Acknowledgments
- Dataset: D.R. Jarvis (1997). Forensic Science International, Vol 85, pp199-208.
- A/B Testing Case Study: Adapted from Udacity’s example project.

For questions or further collaboration, feel free to reach out!
