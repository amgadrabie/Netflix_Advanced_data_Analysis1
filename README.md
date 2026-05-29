# Netflix Advanced Data Analysis & Engineering Pipeline

An end-to-end Data Analytics and Engineering project on the Netflix dataset, demonstrating advanced data cleaning, dynamic data pipelines, and high-quality insights visualization using Python (Pandas, Seaborn) and Tableau.

## 🛠️ Key Data Engineering Features (What Makes This Project Unique)
Unlike standard linear notebooks, this project implements production-grade programming standards:
* *Dynamic Variable & File Generation:* Implemented a reusable pipeline function leveraging Python's globals() and string formatting to dynamically split, reset indices, and export isolated, clean datasets for individual top countries.
* **Fair Geographical Representation (.explode()):** Deconstructed multi-country production partnerships to properly weight and evaluate each country's actual contribution, rather than lazily counting only the first country in the list.
* *Robust Bug Fixing & Shifting Treatment:* Built dynamic data masking queries to automatically capture and fix shifted fields (such as movie durations erroneously written in the maturity rating column), avoiding fragile hard-coded index patches.

## 📈 Key Insights Captured
* *The Real Growth Trend:* Constructed a seamless, smooth timeline using verified platform addition dates (to_datetime), avoiding the common mistake of dragging the timeline back to 1940.
* *Content Strategy Shift:* Visualized a clear part-to-whole ratio using Seaborn palettes showing a heavy global focus on Movies over TV Shows.
* *Regional Dominance:* Captured how South Korea and Japan dominate global TV Shows production while India heavily leads the international Movies sector.