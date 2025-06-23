# Quantium-Trial-Impact-Store-Level-Performance-Analysis
![20250623_1313_Quantium Trial Analysis_simple_compose_01jye4d8gre1ts4xyk1v6sw868 (1)](https://github.com/user-attachments/assets/c772aee0-6966-4c6b-a6fb-b0fa1e844f64)

## Table of Contents

1. [Introduction](#introduction)
2. [Project Objectives](#project-objectives)
3. [Tools Used](#tools-used)
4. [Full Project Notebook](#full-project-notebook)
5. [Skills Demonstrated](#skills-demonstrated)
6. [Key Findings](#key-findings)
7. [Conclusion](#conclusion)
8. [Recommendations](#recommendations)

---

## Introduction
#### Part 2 of Quantium's Retail Strategy Virtual Experience on Forage.
This project contains Part 2 of the **Quantium Retail Strategy Job Simulation**, hosted on [Forage](https://www.theforage.com). In Part 1, I analyzed customer segments and product performance to support Quantium’s retail strategy. **This second part builds on that by evaluating a real-world store trial** designed to test a new business initiative across selected locations.

Quantium selected **Stores 77, 86, and 88** as trial stores. The goal of this project is to determine whether the business strategy trial had a **statistically significant impact on performance**, by comparing the trial stores against suitable control stores.

The analysis involves selecting comparable control stores using similarity metrics, evaluating performance changes during the trial period, and delivering clear, actionable recommendations based on data-driven insights.

---

## Project Objectives

1. ### Select Suitable Control Stores.

   * Explore the pre-trial performance of all stores using metrics such as **total sales** and **number of customers**.
   * Use **correlation and magnitude distance** to score similarity between stores.
   * Develop a **reusable function** for selecting control stores and visualize the similarity for validation.

2. ### Assess Trial Store Performance.

   * Compare each **trial store's** monthly performance with its matched **control store** during the trial window.
   * Use **visual analysis** and **statistical techniques** to identify whether performance differences are meaningful.

3. ### Summarize Findings and Recommendations.

   * For each trial store, provide a **clear conclusion** on the effectiveness of the trial.
   * Support the recommendations with **data-backed evidence** and visualizations.

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

## Skills Demonstrated

* **Experimental Design** – Evaluated the impact of a business strategy using control vs. trial store comparison.
* **Data Analysis with Python** – Manipulated and analyzed structured datasets using `pandas` and `numpy`.
* **Data Visualization** – Created clear and informative charts using `matplotlib` and `seaborn` to support findings.
* **Feature Engineering** – Created custom KPIs such as average price per unit, chips per transaction, and transactions per customer to capture store performance.
* **Scaling & Normalization** – Applied scaling factors to align pre-trial values between trial and control stores, ensuring fair comparisons.
* **Similarity Scoring** – Applied correlation and magnitude distance metrics to identify suitable control stores.
* **Statistical Analysis** – Conducted pre/post-trial comparisons and assessed significance using statistical techniques.
* **Problem Solving** – Built custom functions for similarity scoring and automated parts of the trial analysis workflow.
* **Communication of Insights** – Summarized findings and made actionable recommendations based on data.

---

## Key Findings

### Store 77 vs Control Store 233

* **Total Sales:**
  Trial store 77's sales were **significantly higher** than expected in **two of the three trial months**, exceeding the 95% confidence interval, suggesting a **strong positive impact** from the trial.

  ![image](https://github.com/user-attachments/assets/1402e3fd-2c46-4328-be2c-fe94ac5f2ec1)


* **Customer Numbers:**
  There was a **consistent increase in customers** above the 95% CI in **March and April**, with only a slight dip in February. This indicates **statistically significant uplift in engagement** due to the trial.

![image](https://github.com/user-attachments/assets/2eff30d9-4f98-49db-8920-0689c7fad1e0)


---

### Store 86 vs Control Store 155

* **Total Sales:**
  Performance was **mixed**. Sales exceeded the 95% CI **only in March**, with February and April staying within or near expected levels. This suggests a **possible positive trend**, but not consistently strong across the trial.

![image](https://github.com/user-attachments/assets/895197a1-d12f-470b-977e-d47ce724706b)


* **Customer Numbers:**
  Customer counts were **consistently higher than expected** in all three trial months, lying **above the 95% confidence interval**. This reflects a **statistically significant increase in customer traffic** during the trial.

![image](https://github.com/user-attachments/assets/9c0f5457-9595-42cb-91f1-d244acec99c1)

---

### Store 88 vs Control Store 237

* **Total Sales:**
  Trial store 88’s total sales **exceeded expectations in March and April**, breaking out of the 95% CI in those months. This reflects a **statistically significant improvement**, especially in the latter part of the trial.

![image](https://github.com/user-attachments/assets/c15fb81f-e6ff-446d-962a-26e653acf887)


* **Customer Numbers:**
  A **steady rise in customer numbers** was observed during the trial. Except for a slight dip at the start of February, all other months were **above the upper CI bound**, showing the trial had a **clear, positive effect on foot traffic**.

![image](https://github.com/user-attachments/assets/1c7e3908-2c44-4f9a-90d3-8d10b26544d2)


---

## Conclusion

The analysis assessed the impact of a trial intervention across three selected stores (77, 86, and 88) by comparing their performance against similar control stores during a pre-defined trial period (February to April 2019). Total sales and customer counts were used as key metrics. The findings are summarized as follows:

* **Store 77 vs. Control Store 233:**
  The trial led to a significant uplift in both sales and customer numbers. Sales in the trial store exceeded the 95% confidence interval of the control store in two of the three trial months. Additionally, customer counts consistently remained above expectations, suggesting the trial effectively attracted more customers and increased revenue.

* **Store 86 vs. Control Store 155:**
  Results indicate a moderate positive impact. While total sales only exceeded the expected range in March, the number of customers was significantly higher in all three trial months. This suggests the trial succeeded in drawing more shoppers, though conversion into higher sales may need further evaluation.

* **Store 88 vs. Control Store 237:**
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
