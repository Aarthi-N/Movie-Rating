# Movie-Rating-Analysis

_COMPANY_: CODTECH IT SOLUTIONS

_NAME_: AARTHI N

_INTERN ID_: CT04DY248

_DOMAIN_: DATA ANALYTICS

_DURATION_: 4 WEEKS

_MENTOR_: NEELAM SANTOSH

**PROJECT DESCRIPTION**:

This project focuses on analyzing **Rotten Movies Dataset**, which contains information such as movie title, genre, critic consensus, audience rating and tomatometer rating. The main goal is to explore **patterns in film ratings, sentiment in critic reviews, and differences between audience and critic opinions.**

**TOOLS AND TECHNOLOGIES USED**:

* **Python** - core programming language used for data analysis.\
* **Pandas** - For data cleaning, manipulation, handling missing values, grouping and aggregation.\
* **Matplotlib** - For creating data visualizations such as bar chart, pie chart and stacked bar plots.\
* **NLTK(Natural Language Toolkit)** - For text preprocessing, stopword removal and sentiment lexicons.\
* **VADER Sentiment Analyzer (from NLTK)** - To classify critics consensus into positive, negative and neutral sentiments.

**PLATFORM USED**:

* The analysis was performed in a **jupyter notebook (.ipynb)** environment.\
* Executed on **Google Colab**, which provides interactive environment for combining python code, outputs and visualizations.

**KEY STEPS IN THE PROJECT:**

1. **Data Loading & Cleaning**:

   * Read Rotten Tomatoes dataset.
   * Checked for missing values and handled them (e.g., filling genre with mode, dropping missing critic consensus).
   * Extracted **primary genre** (first genre based) analysis.

2. **Exploratory Data Analysis (EDA)**:

   * Distribution of films by **Tomatometer rating** and **genre**.
   * Calculated the % of **Certified Fresh** vs **Rotten** movies.
   * Compared average **Tomatometer ratings by studio**.

3. **Critics vs Audience Comparison**:

   * Computed discrepancies between **Tomatometer** and **Audience** ratings.
   * Identified movies with the **largest disagreements** (critics loved but audiences didn't and vice-versa).
   * Created plots to visualize critic vs audience alignment.
