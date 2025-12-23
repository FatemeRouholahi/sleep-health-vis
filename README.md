**Sleep Health & Lifestyle — Data Visualization**

Brief: A concise exploratory data visualization project analyzing the Sleep Health and Lifestyle dataset to reveal patterns and relationships between sleep, activity, and wellbeing.

**Goals**
- **Insight:** Summarize relationships between sleep duration, sleep quality, stress, and activity.
- **Compare:** Visualize sleep quality across BMI categories and occupations.
- **Explore:** Show distributions and trends using clear, reproducible plots.

**Dataset**
- **Source file:** [Sleep_health_and_lifestyle_dataset.csv](Sleep_health_and_lifestyle_dataset.csv)
- **Key fields:** sleep duration, sleep quality, stress level, physical activity, BMI, blood pressure, heart rate, daily steps, age, gender, occupation

**Quick Start**
- **Install dependencies:** `pip install -r requirements.txt`  (or `pip install pandas matplotlib seaborn numpy`)
- **Open the notebook:** [01-exploration.ipynb](01-exploration.ipynb) and run cells to reproduce the analysis and figures.

**What you'll find**
- **EDA notebooks:** Interactive exploration and reproducible plots.
- **Visual types:** histograms, KDEs, boxplots, bar charts, pairwise plots.
- **Outputs:** Exported figures are placed under `figures/visual_outputs/` by the notebook when enabled.

**Project Structure**
- **data/**: raw and prepared CSVs
- **01-exploration.ipynb**: primary analysis notebook
- **figures/visual_outputs/**: generated plots and images
- **README.md**: this file

**Dependencies**
- Python 3.8+; main libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`
- See `requirements.txt` for exact pins.

**Usage tips**
- Run notebook cells sequentially to ensure data preprocessing steps execute first.
- To reproduce figures outside the notebook, run the relevant notebook cell code in a script, ensuring file paths match.

**Contributing**
- Small fixes, improved visualizations, or clearer documentation are welcome. Open an issue or submit a pull request.

**License & Contact**
- This repository includes a `LICENSE` file; please review it before contributing or reusing content.
- For questions, open an issue or contact the project owner via the repository.

----

This README is intentionally concise to keep the project lightweight and easy to reuse for small exploratory work.
