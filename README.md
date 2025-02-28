#  Student Depression Dataset - Exploratory Data Analysis (EDA)

##  Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a **Student Depression Dataset** to uncover key insights related to **mental health, academic stress, lifestyle, and well-being**. The analysis involves data cleaning, visualization, and statistical exploration.


##  Steps of Exploratory Data Analysis (EDA)

###  1. Data Collection & Importing  
   - Loaded the dataset using `pandas`.  
   - Displayed basic info using `.info()`, `.describe()`, and `.head()`.  

###  2. Data Cleaning & Preprocessing  
   - Checked for **missing values** and handled them appropriately.  
   - Converted categorical variables into **suitable formats**.  
   - Removed **duplicates** and ensured correct data types.  

###  3. Univariate Analysis  
   - **Histograms & KDE Plots:** Examined the distribution of individual numerical features.  
   - **Count Plots:** Visualized categorical variables like gender, diet, and study satisfaction.  

### 📊 4. Bivariate & Multivariate Analysis  
   - **Correlation Matrix & Heatmap:** Identified relationships between numerical variables.  
   - **Chi-Square Tests:** Explored dependencies between categorical variables.  
   - **Pair Plots & Box Plots:** Compared multiple variables to detect trends and outliers.  

###  5. Key Feature Comparisons  
   - **Dietary Habits vs Mental Health:** Analyzed the impact of diet on depression.  
   - **CGPA vs Study Satisfaction:** Checked if academic performance affects well-being.  
   - **Academic Pressure vs Depression:** Explored how study load impacts mental health.  

###  6. Data Visualization  
   - **Bar Charts & Pie Charts:** Displayed categorical distributions.  
   - **Heatmaps & Scatter Plots:** Showed correlations between key variables.  

###  7. Insights & Findings  
 **Depression & Academic Pressure:**  
   - Students experiencing higher academic stress tend to report more mental health issues.  

 **Diet & Well-being:**  
   - A **structured diet** correlates with **lower stress levels** and **better study satisfaction**.  

 **Sleep & Performance:**  
   - Poor sleep is linked with **lower CGPA** and **higher depression scores**.  

---

##  Installation & Setup
To run the analysis, ensure **Python 3.x** is installed along with the required libraries.

### Install Dependencies
```bash
pip install pandas numpy seaborn matplotlib scipy
