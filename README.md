# Media ROI Analysis with Power BI

![Status](https://img.shields.io/badge/status-concluído-brightgreen)

> Portfolio project demonstrating the creation of an executive dashboard for analyzing Return on Investment (ROI) across different marketing channels.

![ROI Analysis Dashboard](https://i.imgur.com/hKIlbl3.png)

---

## 🎯 Business Problem

A company's board of directors needed clarity on the effectiveness of its advertising investments, which were historically allocated based on tradition rather than data. The goal of this project was to answer the following business questions:

* What is the relationship between investment in each media channel (TV, Radio, Newspaper) and sales?
* Which channel is the most efficient in generating return and which is the least efficient?
* How should the marketing budget be reallocated to maximize future sales?

---

## 📊 Data Source

The data used in this project is a classic public dataset on advertising, containing investments in three different media channels and the resulting sales. The dataset is available on Kaggle.

* **Link to the data:** [Advertising Kaggle Dataset](https://www.kaggle.com/datasets/ashydv/advertising-dataset)

---

## 🛠️ Tools Used

*   **Microsoft Power BI:** Main tool for ETL, modeling, creating measures, and data visualization.
*   **DAX (Data Analysis Expressions):** Used to create key metrics and KPIs, such as:
*   `Total Investment`
*   `Total Sales`
    *   `Cost per Sale`
*   **Power Query:** Used for data ingestion and quality verification.

---

## 💡 Analysis, Insights, and Recommendations

The dashboard analysis allowed us to extract actionable insights that can guide the company's marketing strategy much more efficiently.

### 1. TV: The Main Sales Driver
* **Insight:** The scatter plot reveals a **strong and clear positive correlation** between TV investment and sales. The upward trend line shows that, consistently, the more you invest in TV, the more sales increase.
*   **Recommendation:** Maintain TV as the pillar of the media strategy and the main channel for robust investments, given its predictable and large-scale return.

### 2. Newspapers: The Ineffective Channel
*   **Insight:** The analysis shows a **very weak or non-existent correlation** between newspaper advertising spending and sales. The scatter plot is extremely dispersed and the trend line is almost flat, indicating that increasing the budget for this channel does not generate a significant or reliable increase in sales.
*   **Strategic Recommendation:** **Completely reevaluate the Newspaper budget.** We suggest reallocating 90% to 100% of this budget to channels with proven superior performance (TV and Radio) in order to avoid wasting resources and maximize total ROI.

### 3. Radio: The Hidden Opportunity
*   **Insight:** Despite receiving the smallest share of total investment (approximately 11%), Radio shows a **positive correlation that is stronger than that of Newspapers**. This indicates that, although on a smaller scale than TV, Radio is an efficient channel.
*   **Recommendation:** Radio represents the greatest **opportunity for optimized growth**. It is recommended to experimentally increase investment in this channel, using part of the budget reallocated from newspapers. Radio is likely to generate a higher return on investment than is currently observed.

---

## 🖱️ Dashboard Interactivity

The dashboard features **interactive filters (sliders)** for each of the three media channels. This functionality allows executives and marketing managers to explore different investment scenarios in real time, observing the direct impact on total sales and cost per sale for different budget ranges.

---

## 👨‍💻 Author

*   **[Flávio Sales]**
*   **LinkedIn:** [https://www.linkedin.com/in/flávio-sales-a67663266/](https://www.linkedin.com/in/flávio-sales-a67663266/)
*   **GitHub:** [https://github.com/FLS-7](https://github.com/FLS-7)
