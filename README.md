# Health-Insurance-Charges-Analysis-and-Predictive-Modeling

## Project Overview
This project involves a statistical analysis of a health insurance dataset. It explores regional variations, demographic factors, and health-related variables that influence insurance charges. The aim is to identify key predictors and provide insights into how factors such as age, BMI, smoking status, and number of children impact insurance costs.

## Contents
- **Introduction**: Overview of project objectives and data.
- **Dataset Description**: Summary and structure of the dataset used.
- **Problem Statements**: Five statistical questions explored in-depth.
- **Statistical Analysis Methods**: Techniques applied include correlation analysis, Fisher's Exact Test, Wilcoxon Rank Sum Test, Kruskal-Wallis Test, Random Forest, and Linear Regression modeling.
- **Results and Insights**: Key findings from statistical tests and models.
- **Conclusion**: Summary of insights gained and implications for insurance pricing.

## Dataset
The dataset used contains 1,338 entries with demographic and health variables:
- **Age**: Age of the insured individual
- **Sex**: Gender of the insured (male/female)
- **BMI**: Body Mass Index, a measure of body fat based on height and weight
- **Children**: Number of children/dependents covered by the insurance
- **Smoker**: Whether the insured is a smoker (yes/no)
- **Region**: Residential area in the US
- **Charges**: Total medical charges billed to health insurance

## Project Structure
- **Data Preprocessing**: Cleaning and organizing the data for analysis.
- **Statistical Analysis**: Exploration of relationships between variables using correlation and independence tests.
- **Predictive Modeling**: Building models to predict insurance charges based on predictors.
  - **Linear Regression**: Examines how each variable contributes to insurance charges.
  - **Random Forest Model**: Provides a more complex analysis with higher accuracy.
- **Visualization**: Histograms, scatter plots, and box plots are used to visualize distributions and relationships.

## Key Findings
1. **Correlation Analysis**: Shows a moderate positive correlation between age and charges, and a weak correlation for other factors.
2. **Predictive Models**: The Random Forest model explains over 90% variance in charges, indicating it is the best model for prediction.
3. **Regional Analysis**: Kruskal-Wallis and Dunn’s test indicate significant regional differences in BMI but no notable impact on charges.

## Technologies and Libraries
- **Programming Language**: R
- **Libraries**:
  - **ggplot2** for data visualization
  - **dplyr** for data manipulation
  - **randomForest** for predictive modeling
  - **rpart** for decision trees

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/NeethushreeKumar/Health-Insurance-Charges-Analysis-and-Predictive-Modeling.git
