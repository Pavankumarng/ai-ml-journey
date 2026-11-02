# Project 2 – Students Performance EDA

A completed exploratory data analysis (EDA) project using the **Students Performance in Exams** dataset. The analysis uses Python to explore score distributions, compare student groups and examine relationships among Mathematics, Reading and Writing scores.

## Project at a glance

- **Dataset:** 1,000 student records and 8 columns
- **Data quality:** No missing values in the supplied dataset
- **Main tools:** Python, Pandas, NumPy, Matplotlib and Seaborn
- **Notebook:** `students_performance_eda.ipynb`

## What the analysis covers

- Dataset structure, data types and summary statistics
- Distribution of Mathematics, Reading and Writing scores
- Comparison of scores across student and family-background categories
- Relationships between the three subject scores
- Score differences by test-preparation status and parental education

## Selected findings

- Reading had the highest overall average score (**69.17**), followed by Writing (**68.05**) and Mathematics (**66.09**).
- Reading and Writing had the strongest positive correlation (**r = 0.955**).
- Students in the test-preparation-completed group had higher average scores in all three subjects than students in the group with no test preparation.
- The master's-degree parental-education group had the highest average score in each of the three subjects in this dataset.

These are descriptive findings from this dataset. They show patterns and associations; they do not establish that any one factor caused a change in scores.

## Project files

- `students_performance_eda.ipynb` — the analysis notebook
- `StudentsPerformance.csv` — the dataset supplied with this project in CSV format

**The dataset is included in this folder. You do not need to download it separately from Kaggle.** Keep the notebook and CSV file in the same directory.

## Run the project

1. Clone or download this project folder.
2. Install the required libraries if they are not already installed:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Open `students_performance_eda.ipynb` in Jupyter Notebook or JupyterLab.
4. Run the notebook cells from top to bottom.

## Skills demonstrated

Data loading, data inspection, exploratory analysis, descriptive statistics, group-wise comparisons, correlation analysis and data visualization.
