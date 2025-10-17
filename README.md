This folder contains all the source code and documentation related to the second phase of the Mini Data Analysis Project.



### Analysis Focus and Goals Achieved:



This phase focused on **formal verification** of our core hypotheses:



1.  **Modeling (Q3 Refined):**I successfully fitted a linear regression model (`lm`) proving that **tree age is a highly significant predictor of trunk diameter** (Age Coefficient: +0.3047 cm/year, P-value: < 2.2e-16).

2.  **Spatial Analysis (Q2 & 4):** Quantified the geographic clustering of the top 5 species and visualized the rare locations of Old trees.

3.  **Data Robustness:** Demonstrated tidying principles and ensured file persistence by saving results (`.csv`, `.rds`, `.png`) to the dedicated `output` folder using the `here()` function.



### Contents:



* **`mini-data-analysis2-xiaoxi-gao.Rmd`**: The R Markdown source file containing all data processing, modeling, and plotting code.

* **`mini-data-analysis2-xiaoxi-gao.md`**: The final compiled report, viewable directly on GitHub.
