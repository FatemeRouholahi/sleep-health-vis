**Sleep Health & Lifestyle — Data Visualization**

Brief: A concise exploratory data visualization project analyzing the Sleep Health and Lifestyle dataset to reveal patterns and relationships between sleep, activity, and wellbeing.

**Goals**
- **Insight:** Summarize relationships between sleep duration, sleep quality, stress, and activity.
- **Compare:** Visualize sleep quality across BMI categories and occupations.
- **Explore:** Show distributions and trends using clear, reproducible plots.

**Dataset**
- **Source file:** [https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset](Sleep_health_and_lifestyle_dataset.csv)
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
- **figures/**: generated plots and images
- **README.md**: this file

**Key Findings**

Normal-weight individuals showed lower MAP levels and a lower prevalence of sleep disorders.

Overweight individuals exhibited higher rates of sleep disorders, and among them, those with sleep apnea had higher MAP levels compared to those with insomnia.

Higher sleep quality was associated with lower heart rate.

Individuals with sleep apnea formed two distinct clusters:

One cluster had lower sleep quality and shorter sleep duration.

The other cluster had high sleep quality (score ~9) and longer sleep duration.

Individuals with insomnia generally had poor sleep quality and shorter sleep duration.

MAP tended to increase with age.

Heart rate and sleep duration were inversely correlated, with a correlation coefficient of approximately -0.5.

Physical activity levels and the proportion of people with sleep disorders by occupation were also analyzed.


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
