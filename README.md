# Messi-vs-Ronaldo-Goals-Season-Analysis

**Project Description:**

This project compares the yearly goal-scoring trends of Lionel Messi and Cristiano Ronaldo. Using publicly available datasets from Kaggle, we will analyze their total goals scored per season to identify similarities and differences in their goal-scoring performance over time.  We will utilize data visualization and statistical analysis techniques to understand the evolution of their goal-scoring prowess and explore potential factors that influenced their performance. This is part of the DSA210 Spring 2024-2025 term project at Sabanci University.

**Motivation:**

My journey as a professional footballer in Jordan's national team, with several appearances in the first team, instilled in me a deep appreciation for the dedication and precision required for peak performance. This project serves as a unique opportunity to combine my passion for football with my growing enthusiasm for coding and data science. I aim to use my analytical skills and knowledge of the game to uncover meaningful insights, enhancing both my understanding of football and my data analysis abilities.

**Datasets:**

* **Lionel Messi Dataset:**
    * **Name:** Lionel Messi | All Club Goals
    * **Source:** kaggle.com 
    * **Source Link:** https://www.kaggle.com/datasets/azminetoushikwasi/-lionel-messi-all-club-goals/data
    * **Download Command:** !kaggle datasets download -d azminetoushikwasi/-lionel-messi-all-club-goals

* **Cristiano Ronaldo Dataset:**
    * **Name:** Cristiano Ronaldo | All Club Goals
    * **Source:** kaggle.com
    * **Source Link:** https://www.kaggle.com/datasets/azminetoushikwasi/cr7-cristiano-ronaldo-all-club-goals-stats
    * **Download Command:** !kaggle datasets download -d azminetoushikwasi/cr7-cristiano-ronaldo-all-club-goals-stats

**Datasets' Columns**

* **Lionel Messi & Cristiano Ronaldo | All Club Goals Contain:**
    * **Season:** Which season the goal was scored
    * **Competition:** Which tournament the goal was scored
    * **Matchday:** Which phase or week was the goal scored
    * **Date:** The exact date of the goal scored
    * **Venue:** Specifies if the goal scored was in their own club's stadium (H) or the opponents (A)
    * **Club:** At which club was the goal scored
    * **Result:** The final score of the game in which they scored in
    * **Playing_Position:** Which position they were playing on the field when the goal was scored
    * **Minute:** At which minute of the game was the goal scored


**Data Collection and Preparation:**

The datasets were obtained from Kaggle using the commands shown above. Python Libraries will be used on these data like pandas, matplotlib, seaborn, scikit-learn. The data will undergo the following preparation steps:

* **Data Cleaning:** Missing values in any column will be handled by removing rows with missing data, as it is crucial for data analysis and any inconsistent formatting will be addressed by standardization
* **Data Transformation:** A new column, 'Total Goals', will be created for both datasets which will contain the sum of all goals scored in each season (e.g., UCL, Laliga, World Cup) and the opponent's column from Messi's dataset will be removed to achieve equal datasets and information
* **Data Validation:** Descriptive statistics (mean, median, standard deviation, min, max) will be calculated for the 'Total Goals' column for each player to assess the data's distribution and identify potential outliers

**Visualization:**
* **Line graphs:** Line graphs might be used to display the yearly goal-scoring trajectories of Lionel Messi and Cristiano Ronaldo. These graphs will allow for a visual examination of the evolution of their goal-scoring performance over time, highlighting periods of peak and low production and facilitating a comparison of their goal-scoring patterns
* **Box plots or Histograms:** Box plots might be used to visually compare the distribution of yearly goal totals for Messi and Ronaldo, providing insights into the variability of their goal-scoring performance over time
* **Scatter plots:** Scatter plots might help investigate the relationships between yearly goal totals and other potential influencing factors (e.g., age)

**Hypothesis Testing:** 
The following hypotheses will be tested to determine if there is a statistically significant difference in the average yearly goal totals between Lionel Messi and Cristiano Ronaldo:
* **Null Hypothesis:** There is no statistically significant difference in the average yearly goal totals between Lionel Messi and Cristiano Ronaldo.
* **Alternative Hypothesis (H₁):** There is a statistically significant difference in the average yearly goal totals between Lionel Messi and Cristiano Ronaldo.

**Trend Analysis:**
This phase will involve analyzing the yearly goal-scoring trends for Messi and Ronaldo to identify any patterns and potential peaks or valleys in their performance over time.  Line graphs will be used to visualize these trends. We will investigate whether these peaks and valleys correlate with any known events in their careers (most focused on age)

**Example:**
The analysis will begin by visualizing the yearly goal-scoring trajectories for both players using line graphs.  These graphs will clearly show the evolution of their goal-scoring performance over time.  We will then look for periods of high and low goal production for each player, identifying potential peaks and valleys in their performance. This visual inspection could reveal information on changes in goal-scoring over time and any correlation with external factors.

A key aspect of the analysis will be to explore whether any patterns in goal scoring might be associated with external factors such as age and maybe other things

**Conclusion:**
As a professional footballer, I understand the subjective nature of comparing players' abilities.  While the "Messi vs. Ronaldo" debate often relies on opinion and anecdotal evidence, this project sought to provide a more objective analysis using data. By examining their yearly goal totals, we will use statistical methods and visualization to identify key similarities and differences in their goal-scoring performance over time.  The results will provide a data-driven perspective on their goal-scoring consistency, peak performance periods, and overall career output.  This project demonstrates the power of data as a tool for understanding athletic achievement, adding an objective layer to this frequently debated topic.

**Technology Stack:**

* Python
* Pandas
* Matplotlib
* Seaborn (Optional)
* scikit-learn
* Kaggle API

**Timeline:**

* **March 10, 2025:** Project Proposal Submission (This README file)
* **April 18, 2025:** Exploratory Data Analysis and hypothesis tests on the data
* **May 23, 2025:** Apply ML methods on the dataset
* **May 30, 2025:** Final Report Submission


**Team:** Abdallah Al Homsi (Individual Project)
**Student ID** 34565


