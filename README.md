# 🍽️ Restaurant Tips Analysis

## Project Description

This project analyzes the restaurant tips dataset to explore how various factors (such as gender, smoking status, day, time, and party size) influence the amount of tips given. The analysis includes data exploration, descriptive statistics, and visualizations to uncover patterns and insights.

## Data Description

- **Source:** [tips.csv on GitHub](https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv)
- **Description:**  
  The dataset contains information from 244 restaurant bills collected in the US in 1987. Each row represents a customer who left a tip at a restaurant, with the following columns:
  - `id`: Unique identifier for each bill
  - `total_bill`: Total bill amount
  - `tip`: Tip amount
  - `sex`: Gender of the person paying
  - `smoker`: Whether the person was a smoker
  - `day`: Day of the week
  - `time`: Time of day (Lunch or Dinner)
  - `size`: Size of the party

- **How to Access:**  
  The data is loaded directly from the URL in the notebook using:
  ```python
  df = pd.read_csv("https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv")
  ```

## Main Goals

- Explore the distribution of tips and their relationship with other variables.
- Compare tipping behavior between smokers and non-smokers, males and females, and across different days and times.
- Visualize the data using histograms and summary statistics.
- Draw insights about what factors influence tip amounts.

## Results

- **Central Tendency:**  
  The mean tip value is approximately \$3.00, with a minimum of \$1.00 and a maximum of \$10.00.
- **Smokers vs. Non-Smokers:**  
  Both groups have similar mean tip values, but the distribution differs slightly.
- **Gender:**  
  Males and females show different tipping patterns, as visualized in the notebook.
- **Day and Time:**  
  Tips tend to be higher on weekends and during dinner time.

### Key Visualizations

- **Histograms:**  
  - [Whole dataset tip values](#cell-3432)
  - [Smokers vs. Non-Smokers](#cell-3473)
  - [Males vs. Females](#cell-3731)
  - [Dinner vs. Lunch](#cell-3884)

For detailed analysis and all visualizations, see the [Practise_Restaurant_tips_analysis.ipynb](Practise_Restaurant_tips_analysis.ipynb)
