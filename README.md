# Smoking Health Risk Analysis Dashboard — Power BI

An interactive **Power BI** dashboard built to analyze the impact of smoking on different organs and health risks across age groups and gender.
This project focuses on **health data storytelling**, **organ-based analysis**, and **scenario comparison (Healthy vs Damaged)** using intuitive visuals.

---

## What this dashboard does

The dashboard helps explore smoking-related health risks by allowing users to filter insights based on **organs** and **health condition**.

It answers questions like:

* How does smoking status vary by gender?
* How do smoking duration and daily intake change across age groups?
* How do cholesterol and hypertension risks increase with age?
* How do patterns differ when an organ is **healthy vs damaged**?

---

## Key insights & visuals

* Patient overview with key health indicators
* Smoking status distribution (Never / Current / Former)
* Gender-wise smoking status comparison
* Smoking duration (YOS) and daily intake (CPD) across age groups
* Cholesterol and hypertension risk analysis by age group
* Organ-based filtering for focused health insights
* Healthy vs Damaged scenario toggle for comparison

---

## How the interactivity works (important)

* **Organ filters (Heart, Lungs, Liver, Kidney, Human Body)** allow users to focus on smoking-related risk indicators most relevant to the selected organ.
* The **Healthy / Damaged toggle** works as a scenario switch to compare how risk patterns change when an organ is affected.
* All visuals are cross-filtered for smooth and intuitive exploration.

---

## How I built this project

* **Data cleaning & transformation:** Used **Power Query** in Power BI to clean, transform, and prepare the dataset.
* **Visual design & modeling:** Created measures and visuals to highlight health risks clearly and consistently.
* **Custom visuals:** Generated **PNG images of human organs** using **ChatGPT** and **Gemini (Nano Banana)** and integrated them into the dashboard.
* **Advanced slicers:** Learned and implemented a **Chiclet Slicer** for organ-based navigation.
* **Design focus:** Paid attention to layout, spacing, and color harmony to keep the dashboard readable and engaging.

---

## Repository structure

```
/Images/
│  ├─ Damaged body anatomy.png     → Damaged human body anatomy image
│  ├─ Damaged heart.png             → Damaged heart organ image
│  ├─ Damaged kidney.png           → Damaged kidney organ image
│  ├─ Damaged liver.png            → Damaged liver organ image
│  ├─ Damaged lungs.png            → Damaged lungs organ image
│
│  ├─ Healthy body anatomy.png     → Healthy human body anatomy image
│  ├─ Healthy heart.png            → Healthy heart organ image
│  ├─ Healthy kidney.png           → Healthy kidney organ image
│  ├─ Healthy liver.png            → Healthy liver organ image
│  └─ Healthy lungs.png            → Healthy lungs organ image

Smoking Analysis dashboard.pbix    → Main Power BI report file
Dashboard snapshot.png             → Screenshot of the final dashboard

condition.csv                      → Condition mapping (Healthy / Damaged)
health_dataset.csv                 → Main health dataset
Image Dataset.csv                  → Image mapping dataset used for visuals
Organs.csv                         → Organ reference dataset

README.md                          → Project documentation

```
---

## How to use the dashboard

1. Download and open the `.pbix` file using **Power BI Desktop**.
2. The report contains Power Query steps and a saved data snapshot.
3. If you want to refresh the data:

   * Ensure the Excel dataset is available.
   * Open **Power Query Editor** and update the data source path if required.
   * Click **Refresh** in Power BI Desktop.
4. Use the organ slicers and Healthy/Damaged toggle to explore different scenarios.

---

## Notes & limitations

* This dataset is used for **learning and demonstration purposes**.
* Health insights shown are **not medical advice**.
* Image visuals may require an active internet connection.
* If source paths change, Power Query will prompt you to update them.

---

## Why I made this

This project helped me improve:

* Power Query data cleaning skills
* Dashboard storytelling for healthcare data
* Using slicers beyond basic filters
* Designing dashboards that guide users instead of overwhelming them

---

## Demo

▶️ **

---

## Contact

If you’d like to share feedback, ideas, or collaborate:

**Ashutosh Kumar Jalan**
🔗 GitHub: *[Add your GitHub profile link]*
🔗 LinkedIn: *[Add your LinkedIn profile link]*
