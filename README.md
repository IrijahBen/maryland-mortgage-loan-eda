# maryland-mortgage-loan-eda
This provides an in-depth exploration of the Maryland Mortgage Loan data spanning fiscal years 2011 to 2023. 
Data Loading and Initial Inspection
The first step in the analysis involves loading the dataset and performing an initial inspection. This allows us to understand the structure and content of the data. The dataset includes columns for fiscal year (FY), county, total loan amount, DPA loan amount, and the number of mortgages financed. Displaying the first few rows of the dataset helps verify that it has been loaded correctly and provides a preview of the data.

Data Overview
After loading the data, it is essential to take a closer look at the last few rows and generate summary statistics. Viewing the last few rows ensures the dataset's consistency and completeness. Summary statistics provide an overview of the data by calculating metrics such as the mean, standard deviation, minimum, and maximum values for numerical columns. This helps identify the overall range and distribution of the data.

Correlation Analysis
Understanding the relationships between different variables is crucial for data analysis. Calculating the correlation matrix allows us to see how variables such as total loan amount, DPA loan amount, and the number of mortgages financed are related to each other. Correlation values range from -1 to 1, where values closer to 1 indicate a strong positive relationship, values closer to -1 indicate a strong negative relationship, and values around 0 indicate no relationship.

Data Visualization
Visualizations are powerful tools for understanding the distribution and relationships between different variables. Various types of visualizations were employed in this analysis, including bar plots, scatter plots, histograms, pair plots, and 3D scatter plots.

Predictive Analysis
Data Splitting
For predictive analysis, the dataset was split into training and testing sets. This process involves dividing the data into two parts: one for training the model and the other for evaluating its performance. This ensures that the model can be tested on unseen data to assess its accuracy and generalizability.
