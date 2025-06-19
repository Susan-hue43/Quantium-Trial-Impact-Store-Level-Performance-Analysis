# Quantium-Trial-Impact-Store-Level-Performance-Analysis

## Introduction
### Part 2 of Quantium's Retail Strategy Virtual Experience on Forage.
This project contains Part 2 of the **Quantium Retail Strategy Job Simulation**, hosted on [Forage](https://www.theforage.com). In Part 1, I analyzed customer segments and product performance to support Quantium’s retail strategy. **This second part builds on that by evaluating a real-world store trial** designed to test a new business initiative across selected locations.

Quantium selected **Stores 77, 86, and 88** as trial stores. The goal of this project is to determine whether the business strategy trial had a **statistically significant impact on performance**, by comparing the trial stores against suitable control stores.

The analysis involves selecting comparable control stores using similarity metrics, evaluating performance changes during the trial period, and delivering clear, actionable recommendations based on data-driven insights.

---

## Project Objectives

1. ### Select Suitable Control Stores

   * Explore the pre-trial performance of all stores using metrics such as **total sales** and **number of customers**.
   * Use **correlation and magnitude distance** to score similarity between stores.
   * Develop a **reusable function** for selecting control stores and visualize the similarity for validation.

2. ### Assess Trial Store Performance

   * Compare each **trial store's** monthly performance with its matched **control store** during the trial window.
   * Use **visual analysis** and **statistical techniques** to identify whether performance differences are meaningful.

3. ### Extract Key Insights

   * Look for any additional trends such as seasonality or anomalies that could influence interpretation.
   * Highlight any unexpected findings that could be useful for future experiments.

4. ### Summarize Findings and Recommendations

   * For each trial store, provide a **clear conclusion** on the effectiveness of the trial.
   * Support the recommendations with **data-backed evidence** and visualizations.

5. ### Ensure Clarity and Reproducibility

   * Structure the analysis in a way that’s easy to follow, with clean, well-documented code.
   * Include markdown explanations, visual outputs, and modular functions to promote transparency.

---

## Tools Used

* **Python** – for data manipulation, analysis, and visualization.
* **Jupyter Notebooks** – for interactive coding, documentation, and step-by-step presentation of insights.
* Libraries used include:

  * `pandas` for data handling.
  * `numpy` for numerical operations.
  * `matplotlib` and `seaborn` for data visualization.
  * `scipy.stats` for statistical testing.

---

## Full Project Notebook

You can view the complete analysis and code in the Jupyter Notebook below:

🔗 **[Quantium\_task2.ipynb](./Quantium_task2.ipynb)**

This notebook walks through the full process from control store selection and performance comparison to visualizations and final recommendations. Each step is documented to ensure clarity and reproducibility.

---

## Conclusion

The analysis assessed the impact of a trial intervention across three selected stores (77, 86, and 88) by comparing their performance against similar control stores during a pre-defined trial period (February to April 2019). Total sales and customer counts were used as key metrics. The findings are summarized as follows:

* **Store 77 vs. Control Store 233**
  The trial led to a significant uplift in both sales and customer numbers. Sales in the trial store exceeded the 95% confidence interval of the control store in two of the three trial months. Additionally, customer counts consistently remained above expectations, suggesting the trial effectively attracted more customers and increased revenue.

* **Store 86 vs. Control Store 155**
  Results indicate a moderate positive impact. While total sales only exceeded the expected range in March, the number of customers was significantly higher in all three trial months. This suggests the trial succeeded in drawing more shoppers, though conversion into higher sales may need further evaluation.

* **Store 88 vs. Control Store 237**
  A strong positive impact was observed. Total sales significantly surpassed the expected range in March and April, and customer counts remained consistently above the upper confidence limit, indicating that the trial boosted both customer engagement and sales performance.

---

## Recommendations

1. **Roll Out Trial Strategy to Similar Stores:**
   The consistent improvements in customer numbers and sales especially in Stores 77 and 88 suggest the trial strategy was effective and should be considered for expansion to other stores with similar profiles.

2. **Further Analysis on Conversion Rates (Store 86):**
   While customer footfall increased for Store 86, the inconsistent sales uplift suggests a need to evaluate in-store conversion, product placement, or pricing strategies to better capitalize on the higher traffic.

3. **Monitor Long-Term Performance:**
   To validate the sustainability of the observed improvements, post-trial data should be collected and analyzed. This would help assess whether the positive impacts were temporary or part of a lasting shift in customer behavior.

4. **Tailor Implementation by Store Type:**
   Since the degree of impact varied by store, it would be beneficial to consider store-specific characteristics when applying the trial strategy more broadly.

---
