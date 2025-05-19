# Titanic-Dataset

The visual analysis of the Titanic dataset highlights strong survival biases based on gender, class, and socio-economic status. These factors will be critical in building predictive models or performing deeper hypothesis testing.

1. Survival Distribution
Observation: More passengers did not survive than survived.
Insight: The dataset is imbalanced, with a majority of passengers perishing in the disaster. This has implications for model evaluation (e.g., use precision/recall or balanced accuracy).

2. Age & Fare Histograms
Age: Most passengers were between 20 to 40 years old, with a small number of children and the elderly.
Fare: Highly right-skewed. Most passengers paid low fares, with a few paying very high fares (likely first-class).
Insight: The age distribution suggests a younger passenger base, while the fare distribution reflects socio-economic disparity.

4. Categorical Feature Distributions
Sex: More males than females were on board.
Pclass: Most passengers were in third class.
Embarked: The majority embarked from port S (Southampton).
Insight: The majority of passengers were male, in third class, and boarded at Southampton — this demographic suffered the most.

5. Survival by Sex
Observation: Females had a much higher survival rate than males.
Insight: This supports the "women and children first" evacuation policy — gender was a key survival factor.

5. Survival by Passenger Class
Observation: Survival rate was highest in the first class, lowest in the third.
Insight: Passengers in higher classes had greater access to lifeboats, better cabin location, or were prioritized during evacuation.

6. Age Distribution by Survival
Observation: Slightly more younger passengers survived.
Insight: Younger passengers (especially children) were more likely to be rescued, though the trend is not sharply distinct.

7. Survival by Family Size
Observation: Passengers with small families (2–4 members) had higher survival rates. Solo travelers and large families had lower survival.
Insight: Being alone may reduce visibility/help during evacuation. Large families might face coordination challenges.

8. Fare by Pclass and Survival (Boxplot)
Observation: Higher fares are associated with first class and higher survival.
Insight: Socioeconomic status had a significant impact on survival. Wealthier passengers had more favorable conditions.

9. Correlation Heatmaps-
Survival positively correlates with:
Being female
Being in first class
Paying a higher fare
Weaker correlations exist with age and family members aboard.
Insight: Features like Sex, Pclass, and Fare are most predictive of survival. These should be prioritized in model building.
