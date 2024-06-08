Agricultural Yield Analysis and Visualization
Project Overview
In this project, I aimed to analyze and visualize agricultural yield data for barley and wheat in Saskatchewan from the year 2000 to 2023. The primary objectives were to identify yield trends, detect outliers, perform clustering analysis, and explore potential future features such as creating an interactive Tableau dashboard.

Objectives
Data Cleaning and Preprocessing: Ensure the data is clean and suitable for analysis by handling missing values, standardizing formats, and removing outliers.
Trend Analysis: Identify and visualize the trends in barley and wheat yields over the specified period.
Clustering Analysis: Use machine learning algorithms to cluster the data and identify patterns.
Future Work: Plan to create an interactive dashboard using Tableau to present the findings in an engaging and informative manner.
Data Sources
RM Yields Data: A comprehensive dataset containing yield data for various crops, including barley and wheat, across different rural municipalities (RMs) in Saskatchewan.
GIS Data: Shapefiles representing the geographical boundaries of the RMs.
Analysis Workflow
Data Cleaning:

I read the original RM yields data and filtered it for the years 2000 to 2023.
I handled missing values and standardized the format of the 'RM' column.
I merged the GIS shapefiles with the yields data to create a geospatial dataset.
Outlier Detection:

I used box plots to identify and remove outliers from the barley yield data.
I visualized the data before and after outlier removal to ensure accuracy.
Trend Analysis:

I calculated the mean yields for barley and wheat for each year.
I visualized the trends using line plots to identify any significant changes over time.
Clustering Analysis:

I scaled the barley yield data and applied the K-Means clustering algorithm.
I determined the optimal number of clusters using the Elbow method.
I visualized the clustering results on a map to identify geographical patterns.
Comparative Analysis:

I compared the distribution and trends of barley and wheat yields.
I visualized the comparative analysis using histograms and line plots.
Key Findings
Trend Analysis:
Barley and wheat yields show distinct trends over the period, with certain years exhibiting significant deviations.
Clustering Analysis:
Clustering revealed distinct groups of RMs with similar yield patterns, indicating potential geographical and climatic influences on crop yields.
Future Work
Incorporate Additional Variables:
Include weather data, soil health metrics, and economic factors to enhance the analysis.
Create an Interactive Dashboard:
Plan to use Tableau to create an interactive dashboard for dynamic visualization of the findings.
Extend the Analysis:
Apply the methodology to other crops and regions for broader agricultural insights.
Conclusion
This project provided valuable insights into the agricultural yield patterns in Saskatchewan. By leveraging data analysis and visualization techniques, I gained a better understanding of the factors influencing crop yields, which can help in making informed decisions for future agricultural planning.

Repository Structure
data/: Contains the original and processed datasets.
notebooks/: Jupyter notebooks with the analysis and visualization code.
visualizations/: Generated plots and visuals.
README.md: Project overview and instructions.
How to Use
Clone the Repository:
bash
Copy code
git clone https://github.com/yourusername/agricultural-yield-analysis.git
Install Dependencies:
bash
Copy code
pip install -r requirements.txt
Run the Notebooks:
Open and run the Jupyter notebooks in the notebooks/ directory to reproduce the analysis.
