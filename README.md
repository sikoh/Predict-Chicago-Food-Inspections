Predict-Chicago-Food-Inspections

In this project, I developed a predictive model using data from the Chicago Department of Public Health to
anticipate whether food establishments would pass or fail inspections. The goal was to optimize inspection
resources by predicting potential failures beforehand.

I began by preparing the dataset, focusing exclusively on Chicago establishments to prevent data leakage. Key
features such as 'Risk', 'Facility Type', and 'Zip' were carefully engineered to enhance predictive accuracy using
OrdinalEncoder for categorical data.

For modeling, I utilized robust ensemble methods like Random Forest Classifier and XGBoost Classifier, chosen
for their ability to handle both numerical and categorical data effectively. These models were pivotal in
delivering reliable predictions of inspection outcomes.

Performance evaluation was conducted using metrics like accuracy, precision, recall, and F1-score. Notably, the
XGBoost Classifier achieved an impressive 88.01% validation accuracy, demonstrating its efficacy in forecasting
inspection results.

Insights gleaned from permutation importance analysis highlighted 'Serious Violations Found' as the most
influential predictor, providing critical understanding of factors driving inspection outcomes.
Visual representations such as ROC curves aided in comparative analysis and informed decision-making during
model selection, showcasing the models' performance.

This project refined my skills in data preprocessing, feature engineering, and predictive modeling while
showcasing the impactful application of machine learning in public health initiatives. It underscores my ability to
leverage advanced techniques to solve practical challenges and deliver actionable insights that optimize
operational efficiency.

