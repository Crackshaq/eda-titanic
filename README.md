Titanic Dataset - Exploratory Data Analysis (EDA)

This project explores the Titanic dataset (`/content/Titanic-Dataset.csv`) using Python libraries such as **pandas**, **seaborn**, **matplotlib**, and **plotly**. The goal is to understand the structure of the data, identify patterns, visualize relationships, and check for missing values or outliers.

 Dataset

The dataset used is `/content/Titanic-Dataset.csv` from the Titanic Kaggle competition. It includes features like:

- Survived
- Age
- Fare
- Pclass (Passenger Class)
- SibSp (Siblings/Spouses Aboard)
- Parch (Parents/Children Aboard)
- And more...

Exploratory Data Analysis Steps

1. Basic Statistics
   - Descriptive summary using `.describe()`
   - Median values
   - Missing value counts

2. Visualizations
   - Histograms with KDE for numeric features (`Age`, `Fare`, `SibSp`, `Parch`)
   - Boxplots to detect outliers
   - Correlation Heatmap including `Survived`
   - Pairplot for numeric features with `Survived` hue
   - Countplots for:
     - Survival counts
     - Survival by Passenger Class (`Pclass`)
   - Interactive boxplot using Plotly showing Age by Class and Survival
