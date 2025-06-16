# INFO6105_DataScienceEngineeringMethods_SPRING2024

## Combined Data Cleaning, Feature Selection, Modeling, and Interpretability Report

This repository centers on a single Jupyter Notebook (`Assignment4_Combined_Report.ipynb`) that walks through an end-to-end machine learning workflow on a media cost prediction dataset. It demonstrates how to move from raw data to actionable insights, emphasizing clarity and reproducibility.

### Purpose

* Showcase systematic data cleaning and preprocessing steps, handling missing values and encoding.
* Illustrate feature scaling and selection methods to improve model performance.
* Train and compare models—both manual approaches (e.g., tree-based models) and an H2O AutoML run—to find the strongest predictors.
* Apply SHAP-based interpretability to explain model behavior and highlight which features drive predictions.
* Summarize findings in a concise conclusion, noting key predictors, model strengths, and potential next steps.

### Key Highlights

* **Data Cleaning & Preprocessing**: Techniques to handle missing entries, correct types, and prepare categorical/numerical variables.
* **Feature Engineering & Selection**: Exploration of feature importance to focus on variables that matter most.
* **Modeling**: Comparison between baseline models and an automated machine learning approach to select the top performer.
* **Interpretability**: Use of SHAP values to visualize and interpret how each feature influences the model output.
* **Conclusions & Insights**: A brief summary of main learnings, recommendations for further improvement, and considerations for applying similar workflows to other datasets.

### Notebook Structure (High-Level)

1. **Abstract & Objective**
   A concise statement of goals and expected outcomes.
2. **Data Exploration**
   Initial look at dataset structure, types, and missingness.
3. **Preprocessing**
   Cleaning steps and encoding strategies.
4. **Exploratory Analysis**
   Visual summaries and correlation insights.
5. **Feature Preparation**
   Scaling and selection to refine input for models.
6. **Model Training & Comparison**
   Running baseline models alongside an H2O AutoML experiment to identify the best performer.
7. **Interpretability with SHAP**
   Examining feature impacts and explaining individual predictions.
8. **Conclusions**
   Key takeaways, most influential factors, and suggestions for future iterations.

### Data Context

The example uses a media cost prediction scenario, but the notebook is structured generically so it can be adapted to other regression tasks with a similar data profile.

### Outcomes

By following this notebook, one gains a clear template for:

* Structuring an ML project from raw data to insights.
* Balancing manual modeling with automated approaches.
* Incorporating interpretability to make models more transparent.
* Drawing concise, actionable conclusions that inform decision-making.

