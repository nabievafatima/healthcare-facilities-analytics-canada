📄 Healthcare Facilities Analytics Project (Canada)
📊 Project Overview
This project analyzes the distribution of healthcare facilities across Canada using Python, Machine Learning, Power BI, and Generative AI support tools.
The main goal is to explore healthcare facility distribution geographically, identify patterns across provinces, and evaluate healthcare accessibility relative to population.
🎯 Project Objectives
The project was designed to:
clean and prepare healthcare facility data
analyze facility distribution across Canada
integrate population data for deeper analysis
calculate healthcare accessibility metrics
apply machine learning clustering
build an interactive Power BI dashboard
demonstrate the use of generative AI tools
📁 Dataset
The main dataset used is the Open Database of Healthcare Facilities (ODHF) for Canada.
It includes:
facility name
facility type
provider
city
province
latitude
longitude
postal code
Additionally, a population dataset by province was used to calculate accessibility metrics.
🛠️ Tools and Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn (K-Means Clustering)
Jupyter Notebook
Visual Studio Code (AI-assisted development)
Power BI
Generative AI tools
⚙️ Project Workflow
1. Data Loading
Loaded the healthcare dataset using pandas
Reviewed dataset structure, columns, and data types
Checked dataset size and content
2. Data Cleaning and Preparation
Performed in Python using Jupyter Notebook and Visual Studio Code:
handled missing values
converted latitude and longitude to numeric
removed invalid or incomplete records
standardized province names
prepared a clean dataset
3. Exploratory Data Analysis (EDA)
Performed analysis to understand the dataset:
number of facilities by province
distribution of facility types
top cities by healthcare facilities
geographic visualization using coordinates
4. Population Data Integration
To improve analysis, a population dataset was added:
collected population data for each province
cleaned and standardized province names
prepared data for merging
5. Data Merging
merged healthcare dataset with population dataset using province
validated merge results
created a unified dataset with facilities and population
6. New Dataset Creation
saved the merged dataset as a new file
ensured it is ready for analysis in Power BI
7. Machine Learning Analysis
Applied K-Means clustering:
used latitude and longitude as features
applied clustering algorithm
used Elbow Method to determine optimal clusters
visualized clusters
8. Healthcare Accessibility Metric
Created a key metric:
👉 Facilities per 100,000 population
This was used to:
normalize the data
allow fair comparison between provinces
evaluate accessibility instead of raw counts
9. Dashboard Development in Power BI
Built an interactive dashboard including:
KPI Cards
Total Facilities
Total Hospitals
Total Nursing Facilities
Total Ambulatory
Map Visualization
geographic distribution across Canada
Bar Charts
facilities by province
top cities
Scatter Plot
Population vs Facilities per 100k
shows accessibility differences
Filters
province
facility type
🤖 Use of Generative AI
Generative AI tools were used to support the workflow:
generating Python code
debugging errors
explaining machine learning concepts
assisting development in Visual Studio Code
helping structure analysis and documentation
AI was used as a support tool, while all analysis, validation, and interpretation were completed independently.
📈 Key Insights
Healthcare facilities are unevenly distributed across Canada
Larger provinces (Ontario, Quebec) have more facilities overall
Smaller provinces (e.g., Prince Edward Island) have better accessibility per capita
Population-adjusted metrics reveal insights not visible in raw counts
Machine learning clustering shows geographic grouping patterns
📦 Project Outputs
Python analysis notebook
cleaned dataset
merged dataset
Power BI dashboard (.pbix)
dashboard screenshots
project documentation
📂 Files Included
📂 Files Included
capstone_project.ipynb — main analysis notebook
healthcare_population.ipynb — population data preparation
odhf_v1.csv — original healthcare dataset
canada_population.csv — population dataset
clean_healthcare_facilities.csv — cleaned dataset
merged_data.csv — merged dataset (facilities + population)
Healthcare dashboard.pbix — Power BI dashboard
dashboard.jpg — dashboard preview
README.md — project documentation
✅ Conclusion
This project demonstrates that combining healthcare data with population data provides deeper and more meaningful insights.
While larger provinces have more healthcare facilities, smaller provinces often provide better access when adjusted for population.
The Facilities per 100,000 population metric highlights regional disparities and allows fair comparison.
By integrating Python, Machine Learning, Power BI, and Generative AI, this project delivers a comprehensive and practical analysis of healthcare accessibility in Canada.

Если хочешь последний шаг:
🚀 я могу сделать тебе
GitHub title + описание + LinkedIn пост (чтобы тебя заметили)
