# Titanic Survival Analysis

## Objective

The goal of this project is to analyze the Titanic dataset and identify the factors that influenced passenger survival rates. By exploring variables such as class, age, gender, and family size, we aim to uncover key patterns that contributed to the likelihood of survival during the Titanic disaster.

## Dataset

The Titanic dataset provides information on passengers aboard the Titanic, including features such as age, sex, class, family size, and survival status. Key columns include:

-   **`PassengerId`**: Unique ID for each passenger.
-   **`Pclass`**: Class of the passenger (1, 2, 3).
-   **`Sex`**: Gender of the passenger (male/female).
-   **`Age`**: Age of the passenger.
-   **`SibSp`**: Number of siblings/spouses aboard.
-   **`Parch`**: Number of parents/children aboard.
-   **`Fare`**: Fare paid for the ticket.
-   **`Embarked`**: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).
-   **`Survived`**: 0 = No, 1 = Yes (whether the passenger survived).

## Libraries Used

-   **Pandas**: For data manipulation and analysis.
-   **Numpy**: For handling arrays and numerical operations.
-   **Seaborn**: For visualizations and statistical plots.
-   **Matplotlib**: For creating static, animated, and interactive visualizations.

## Methodology

1.  **Data Collection**: The Titanic dataset was downloaded from Kaggle and contains detailed passenger information.
2.  **Data Cleaning**: Missing values in columns like `Age` were imputed. Categorical variables like `Sex` and `Embarked` were encoded numerically for analysis.
3.  **Exploratory Data Analysis (EDA)**: Various visualizations were used to understand survival patterns, including histograms, countplots, boxplots, and heatmaps to examine the relationships between different variables.

## Key Findings

-   **Class and Wealth**: Wealthier passengers in first class had the highest survival rates.
-   **Gender**: Women had a significantly higher chance of survival compared to men.
-   **Family Size**: Passengers traveling with smaller families or children had a slight survival advantage.

These findings reflect historical accounts, where first-class passengers, women, and children were more likely to survive.

## Conclusion

This analysis shows that class, gender, and family size were important factors in determining whether passengers survived the Titanic disaster. The project highlights how wealth and gender influenced survival rates, confirming historical narratives about the prioritization of women and children during the evacuation.

## Visualizations

The project includes several key visualizations:

-   **Histograms**: Displayed the distribution of `Age` and `Fare`.
-   **Countplots**: Analyzed survival rates based on gender, class, and embarkation port.
-   **Heatmaps**: Showed correlations between features like `Age`, `Fare`, and `Pclass`.

## References

-   Titanic Kaggle Dataset
