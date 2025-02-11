**Project Overview:**
This project explores how military service status, and role (combat vs. non-combat)—affect psychological resilience. The main components of the analysis include:

Descriptive Statistics: Calculating mean, median, standard deviation, and group size for each subgroup.
Data Visualization: Creating QQ-plots, boxplots, and bar plots with confidence intervals to illustrate the distribution of resilience scores.
Correlation & Regression Analysis: Investigating the relationship between age and resilience.
Hypothesis Testing: Conducting t-tests to compare the mean resilience scores among:
Men who served versus men who did not serve.
Women who served versus women who did not serve.
Men in combat roles versus men in non-combat roles.
The analysis aims to provide insights into the impact of military service and other demographic factors on resilience.

---

**Installation:**
This project requires R along with the following R packages:

kableExtra
ggplot2
shadowtext
To install these packages, you can run the following commands in R:

install.packages("kableExtra")
install.packages("ggplot2")
install.packages("shadowtext")
Alternatively, you can use the provided code chunks in the R Markdown file to automatically install the necessary packages.

---

**Usage:**
To reproduce the analysis and generate the HTML report:

Clone or Download the Repository.
Open the R Markdown File: Open the Final_Project_Statistics.Rmd file in RStudio.
Update Data Path (if necessary): The dataset is loaded from a local file (e.g., "C:/Josh/Hebrew University/Year2/intro Statistics/Final_project/Statistics_Final_Project.csv"). Ensure that the file path matches the location of your dataset.
Knit the Document: Click the "Knit" button in RStudio to compile the document into an HTML report.

---

**Project Structure:**
Final_Project_Statistics.Rmd: Main R Markdown file containing all analysis, visualizations, and interpretations.
Statistics_Final_Project.csv: CSV file containing the dataset. (Update the file path in the R Markdown file as needed.)
README.md: This README file, which provides an overview and instructions for the project.

---

**Data:**
The dataset includes:

Resilience Scores: Measured using the CD-RISC-10 scale (with a squared transformation applied to improve normality).
Demographic Information: Age, gender.
Military Service Information: Whether the participant served, and if applicable, whether they were in a combat or non-combat role.
Only participants aged between 18 and 30 were included in the analysis.

---

**Analysis Summary:**
Descriptive Statistics:

Computed mean, median, standard deviation, and group size for five groups: Men (Not Served), Men (Combat), Men (Non-Combat), Women (Served), and Women (Not Served).
Data Visualization:

QQ-Plots: To assess normality before and after the squared transformation.
Boxplots: To visualize the distribution of CD-RISC-10-Squared scores across different groups.
Bar Plots with Error Bars: To display average scores with 95% confidence intervals, enhanced with shadowed text for clarity.
Correlation & Regression:

Investigated the relationship between age and resilience scores.
Conducted regression analysis only if a significant correlation was detected.
Hypothesis Testing:

T-Tests: Performed one-tailed t-tests to compare groups:
Men who served vs. men who did not serve.
Women who served vs. women who did not serve.
Men in combat vs. men in non-combat roles.

---

**Results & Conclusions:**
Military Service Impact:
Both men and women who served in the military during the war demonstrated significantly higher resilience scores compared to their non-serving counterparts.

---

**Role Comparison:**
No significant difference was found between men in combat and non-combat roles, suggesting that the overall military experience, rather than the specific role, may contribute to increased resilience.

---

**Age Effect:**
Within the 18–30 age group, age did not significantly correlate with resilience scores.

The findings underscore the potential resilience-building effects of military service while also highlighting areas for further research.

---

**Limitations:**
Response Bias:
The voluntary nature of the survey might have led to response bias.

Sample Sizes:
Some groups had smaller sample sizes, which may affect the statistical power of the tests.

Pre-Existing Differences:
Participants who chose to serve might differ inherently from those who did not, which could influence the results.

Contextual Constraints:
The study was conducted within a relatively homogeneous population from a specific school and geographic area.

---

**Future Work:**
Potential areas for future research include:

Diverse Populations:
Replicating the study in different regions and among more diverse populations.

Pre-Service Characteristics:
Collecting baseline data on resilience and other psychological factors prior to military service.

Expanded Variables:
Including additional factors such as family background, educational history, and mental health.

Civilian Applications:
Exploring how structured environments outside the military could similarly foster resilience.

---

**Authors:**
Itamar Lev Ari - itamarlevari2000@gmail.com
Joshua Kolodny - kolodnyjoshua@gmail.com
For further information, questions, or collaboration opportunities, please feel free to contact the authors.
