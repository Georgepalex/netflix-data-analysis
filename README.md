# Netflix Data Analysis & Content Strategy 🎬

This project performs end-to-end data cleaning, feature engineering, exploratory data analysis (EDA), and visualization on the **Netflix Movies & TV Shows** dataset using Python.

The goal is to understand Netflix’s content mix, growth trends, genres, and regional patterns and to support data-driven content strategy decisions.

---

## 📂 Files in this Repository

- `Netflix Content Strategy - Comprehensive EDA.ipynb`  
  Main Jupyter Notebook with all cleaning, EDA, and visualizations.

- `netflix_cleaned_final.csv`  
  Final cleaned dataset after preprocessing.

- `visuals/`  
  Folder containing all exported charts (PNG images) used for storytelling.

---

## 🧰 Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Plotly (for interactive visuals)
- Jupyter Notebook

---

## 🔍 Key Things I Did

- Handled missing values and inconsistent entries
- Fixed misclassified ratings and durations
- Engineered features like:
  - `year_added`
  - `month_added`
  - `maturity_level`
  - `primary_country`
- Removed logically incorrect records (e.g., titles added before release year)

---

## 📊 Insights & Visuals

Some of the questions explored:

- 📌 How is Netflix content split between **Movies vs TV Shows**?
- 🗓️ How has the catalog grown **year by year**?
- 🔞 What does the **ratings / maturity level** distribution look like?
- 🌍 Which are the **top content-producing countries**?
- 🎭 What are the **top genres** on Netflix?
- ⏱️ How are **movie durations** distributed?
- 📺 How many **seasons do TV shows usually have**?
- 📆 In which **months and years** does Netflix add the most content?

All related charts are saved in the `visuals/` folder, for example:

- `MoviesVsTVshows.png`
- `Ratings_Distribution.png`
- `ContentAddedPerYear.png`
- `Top10Countries.png`
- `MovieDurationDistribution.png`
- `TVShowsNo_of_Seasons.png`
- `Top20Genre.png`
- `ContentAddedIntensityHeatmap.png`
- `GrowthOfNetflixCatalog.png`

---

## 🚀 How to Run

1. Download this repository.
2. Open the file:  
   `Netflix Content Strategy - Comprehensive EDA.ipynb`
3. Run the cells from top to bottom in Jupyter Notebook.
