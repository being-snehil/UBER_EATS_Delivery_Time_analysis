# UBER_EATS_Delivery_Time_analysis
This project analyzes the delivery times of Uber Eats orders from various sources to destinations. The analysis includes calculating the average mean delivery time and applying statistical methods to ensure the accuracy and reliability of the results.
## Key Features
- ### Average Delivery Time Calculation:
Computed the average delivery time from different sources to destinations.
- ### Central Limit Theorem:
Applied the central limit theorem to justify the use of the normal distribution for the mean delivery time.
- ### Confidence Intervals:
Constructed confidence intervals to estimate the range within which the true mean delivery time lies.
- ### Bootstrapping:
Used bootstrapping techniques to find confidence intervals and improve the robustness of the estimates.95% Confidence Interval for 99th Percentile: Calculated the 95% confidence interval of the 99th percentile using bootstrapping.

## Practical Application:
-Suppose Uber offers a scheme of free food if they aren't able to provide the delivery within a specified time. To determine that specified time, we used our analysis to calculate the upper bound of the 99th percentile. This upper bound serves as the specified time, ensuring that the delivery performance meets the promotional promise.
## Tools and Technologies:
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

- ## How to Run:
1. Clone the repository:
   
   git clone https://github.com/being-snehil/uber-eats-delivery-time-analysis.git
   
2. Navigate to the project directory:
   
   cd uber-eats-delivery-time-analysis
   
3. Install the required dependencies:
   
   pip install -r requirements.txt
   
4. Open the Jupyter Notebook:
   
   jupyter notebook
   
5. Run the Uber_Eats_Delivery_Time_Analysis.ipynb notebook to see the analysis.

## Project Structure:
- data/: Contains the dataset used for analysis.
- notebooks/: Jupyter Notebook with the analysis.
- scripts/: Python scripts for data processing and analysis.
- README.md: Project description and instructions.
## Conclusion:
This project provides insights into the delivery times of Uber Eats orders and demonstrates the application of statistical methods to real-world data. It serves as a practical example of using data science techniques to analyze and interpret delivery performance metrics.
