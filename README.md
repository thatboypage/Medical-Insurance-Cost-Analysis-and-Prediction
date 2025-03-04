 Medical-Insurance-Cost-Analysis-and-Prediction
 
This project analyzes medical insurance costs based on personal attributes such as age, BMI, smoking status, and region. Using data analysis and machine learning techniques, it aims to predict individual medical charges.


## Dataset Description
The dataset includes the following features:
- age: Age of primary beneficiary.
- sex: Gender of the insurance holder (male/female).
- bmi: Body mass index, used as an indicator of body weight relative to height.
- children: Number of dependents covered by insurance.
- smoker: Indicates if the individual is a smoker.
- region: Residential region of the beneficiary in the US.
- charges: Medical costs billed by health insurance.

## Project Workflow
 1. Data Understanding
- Explore dataset structure and feature distributions.
- Visualize relationships between features and medical charges.

 2. Data Wrangling
- Handle missing values (if any) and correct data types.
- Encode categorical variables.

 3. Descriptive Statistics
- Summary statistics of numerical variables.
- Distribution plots to understand feature variance.

 4. Correlation Analysis
- Identify relationships between features.
- Heatmap visualization for correlation analysis.

 5. Predictive Modeling
- Prepare data for machine learning.
- Train models to predict medical insurance costs.

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Usage
To run the notebook, install dependencies and execute the cells:
```bash
pip install -r requirements.txt
jupyter notebook
```

## Insights
- **Age and smoking status** significantly impact medical charges.
- **Higher BMI** tends to correlate with increased costs.
- **Smokers** have substantially higher medical charges compared to non-smokers.

## Contribution
Feel free to fork this repository, contribute improvements, or suggest new features!

## License
This project is open-source and available under the MIT License.

