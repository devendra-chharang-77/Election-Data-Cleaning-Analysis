
#  Election Data Cleaning & Analysis

This project demonstrates how real-world **election poll data** can be cleaned, processed, and analyzed using Python. It showcases the use of data preprocessing techniques, handling inconsistencies, treating missing values, and performing insightful visualizations on voter trends and results.

---

 Project Objective

To clean, structure, and analyze Indian election poll data to:

- Identify trends in voting patterns
- Standardize inconsistent data fields (e.g., party abbreviations, missing genders, etc.)
- Prepare datasets for further modeling or public reporting
- Gain actionable insights from unstructured raw data

---

 Dataset Description

The raw data consists of Indian election results including:

- Constituency Names
- Candidate Details
- Party Affiliation (often inconsistent)
- Vote Counts
- Gender and other demographics

The dataset initially had:
- Missing values
- Duplicate party names (like "BJP", "B.J.P.", "Bharatiya Janata Party")
- Formatting inconsistencies
- Nulls in gender and vote columns

---

 Tools & Libraries Used

- Python 3
- Pandas – Data manipulation & cleaning
- NumPy – Numeric operations
- Matplotlib & Seaborn– Visualizations
- Jupyter Notebook– Development environment

---

 Data Cleaning Process

- Removed irrelevant or null-heavy columns
- Filled missing values using conditional logic
- Standardized party names using frequency mapping
- Converted data types (like vote count to integers)
- Cleaned inconsistent text fields


 Exploratory Data Analysis (EDA)

Visualizations and aggregations were used to answer questions like:

- Which party had the most candidates?
- What was the average vote share?
- Gender-wise candidate participation?
- State-wise performance metrics?

Graphs Used:
- Bar charts (party-wise candidate count)
- Pie charts (gender representation)
- Histograms (vote distributions)


 Insights Gained

- Majority of top candidates came from a few major parties
- Gender representation was skewed heavily toward male candidates
- Some parties had high participation but low average votes
- Cleaning party names drastically improved clarity of EDA

---

🔗 View Notebook Online

🔍 **NBViewer Link:**  
[View Project Notebook on NBViewer](https://nbviewer.org/github/devendra-chharang-77/Election-Data-Cleaning-Analysis/blob/main/Devendra_Chharang_POLL.ipynb)

---

##  Author

Devendra Chharang
B.Tech CSE & Data Science – JECRC University, Jaipur  

