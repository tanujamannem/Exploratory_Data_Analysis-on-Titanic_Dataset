# Exploratory Data Analysis on Titanic Dataset 🚢

### Project Overview 📝
This project performs an **Exploratory Data Analysis (EDA)** on the Titanic dataset. The dataset contains information about passengers who boarded the Titanic, including:

-  **Survival status** (whether the passenger survived or not)
-  **Class** (ticket class)
-  **Age, Sex, Fare, SibSp, Parch** (family and fare information)
-  **Embarked** (port of boarding)

The Titanic sank on **15 April 1912**, with **2,224 passengers and crew** aboard. This dataset helps us explore patterns and relationships among passengers that affected survival.

---

### Key Objectives 🎯
1. **Data Exploration and Preparation**
   -  Check for missing values and duplicate records.
   -  Identify categorical and numerical variables.
   -  Summarize key statistics: min, max, mean, median, and distributions.

2. **Data Cleaning and Transformation**
   -  Drop irrelevant columns such as `Name`, `Ticket`, and `Cabin`.
   -  Handle missing values in `Age` and `Embarked`.
   -  Convert columns to proper data types for better analysis (`int`, `category`, etc.).
   -  Identify passengers with complimentary tickets for further insights.

3. **Data Visualization**
   -  Visualize distributions of numerical variables like **Age** and **Fare**.
   -  Analyze survival patterns with respect to:
     -  Passenger Class (Pclass)
     -  Sex
     -  Age
     -  Family size (SibSp, Parch)
     -  Port of Embarkation (Embarked)
   - 📊 Use bar plots, count plots, scatter plots, boxplots, and histograms to uncover trends.

---

### Key Insights 💡
-  Survival rate: ~38% survived, ~62% did not.
- **Passenger Class Impact:**
  - Higher-class passengers had higher survival rates.
  - Most passengers were from lower class (Pclass 3).
-  **Gender Impact:**
  - Females had higher survival rates compared to males.
-  **Family Impact:**
  - Passengers traveling alone had lower survival rates than those with family.
-  **Age Distribution:**
  - Upper-class median age: 36 years
  - Middle-class median age: 29 years
  - Lower-class median age: 26 years
-  **Fare:**
  - Higher fare associated with higher-class passengers; fare affects survival probability.

---

### Tools and Libraries 🛠
-  Python for analysis
-  Pandas & NumPy for data manipulation
-  Seaborn & Matplotlib for visualization
-  Scipy.stats for statistical tests
