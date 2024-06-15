# Water-Quality-Model-Clustering
### A project focusing on the segmentation of different water qualities as a function of several water parameters.
The project is centered around the assessment of water quality in catchment areas, utilizing available data such as biomes, habitats, and settlements. 

Dataset Link: [(https://www.kaggle.com/datasets/adityakadiwal/water-potability?phase=FinishSSORegistration&returnUrl=%2Fdatasets%2Fadityakadiwal%2Fwater-potability%2Fversions%2F3%3Fresource%3Ddownload&SSORegistrationToken=CfDJ8CHCUm6ypKVLpjizcZHPE72c1zmsIcdrAJw_CX81LkGRoqd8f77QrCaCu2-rLxHOKJ9iRTKXWvC5MYzut_mIWUdwk1OoV87Mgmhr-utzQP3xMsVLkniGDJ3xg8MphcWCahlphxeAO7j53ajxnoP2y3mG9OynJhgyVZn5w6SSOdqs_Zzw0aWLrujKK1qC0qK5Ce61wrxJqfdaCBOxCPZ_rbgYRFQxfMbmmYhLubYxHUs_4_73t1EE755m-MXKhxA9GlAx1j_lR-w-g7_C7kPwgmp80U8JWPNNFXp_ZX-HI1Fv0F0Q5r3VpmoliKwZk9ljG9w9B4oNBMkaJtMWcRbJ-BmbqH-oBG76rQ&DisplayName=MacDaniel+Obadiah-Onyeleonu+Ogechukwu))

## Project Introduction

This project focuses on assessing water quality in catchment areas by utilizing data from various sources such as biomes, habitats, and settlements. The primary goal is to provide comprehensive insights into the water quality data, helping municipalities enhance water quality management, optimize sampling efficiency, and prevent waterborne diseases. The project addresses ethical considerations, particularly in mitigating data bias, and tackles challenges related to data quality and potential political agendas.

## Problem Statement

South Africa faces significant challenges such as inadequate sanitation infrastructure, industrial pollution, agricultural runoff, and limited access to clean water in rural areas. These issues necessitate effective water quality monitoring to prevent health risks and outbreaks of waterborne diseases like cholera and gastroenteritis. Current methods of water quality assessment can be inefficient, leading to oversampling in certain areas while neglecting high-risk sites. A comprehensive approach leveraging available data is needed to predict water quality attributes and guide proactive management strategies.

## Objectives

### Data Understanding and Exploration
- Conduct thorough data coverage and exploratory data analysis (EDA) for each relevant dataset.
- Compile a data dictionary for each dataset to ensure comprehensive understanding.

### Data Science Specific
- Develop a dashboard to assess water quality in catchment areas, providing a user-friendly interface for stakeholders.
- Identify seasonal trends and patterns in the data to enhance predictive modeling.

### Predictive Analytics
- Use data for predictive analytics on microbial populations in specific areas, assessing their impact on downstream water quality.
- Investigate predictable attributes of catchment areas that indicate water quality before traditional sampling methods are implemented.

### Data Engineering Specific
- Establish a robust data access framework to ensure timely and efficient retrieval of relevant information.
- Develop a data strategy for modeling, outlining the approach to be taken for predictive analytics.
- Conduct data quality testing, focusing on accuracy, completeness, reliability, relevance, and timeliness.

### Contextual Information
This work is crucial for human health and well-being, particularly in regions facing challenges like inadequate sanitation infrastructure and industrial pollution. Water quality monitoring is especially relevant in South Africa, where safe drinking water is essential for preventing waterborne diseases.

## Focus of Output

The project aims to guide municipalities in better managing water systems by predicting pollution risks and optimizing sampling efforts. Dashboards based on predictive models can contribute to more informed decision-making and prevent outbreaks of waterborne diseases.

## Potential Users

Key users of the project's insights include government bodies, environmentalists, and engineers. Dashboards fed with model-driven data can enhance the decision-making process for these stakeholders.

## Team Members

- Osinachi Ezemba
- Timmy Egbe
- Damola Abiola
- Daniel Felix Macdaniel
- Ogechukwu Abdulamid Adekunle

## Notebooks

The project is structured using four different notebooks:

### 1. Data_importation.ipynb
This notebook focuses on importing the necessary datasets for the project. It includes code for loading data from various sources into the project environment, crucial for subsequent analyses and model development.

### 2. Data_joining.ipynb
The purpose of this notebook is to combine or join different datasets. It involves merging data based on common keys or attributes, ensuring that the datasets are unified and ready for further analysis. This step is essential for creating a comprehensive dataset that covers various aspects of water quality and catchment areas.

### 3. Data_Cleaning_and_Feature_Engineering.ipynb
This notebook is dedicated to cleaning the data and performing feature engineering. It includes tasks such as handling missing values, addressing outliers, and creating new features that might enhance the predictive capabilities of the model. The functions used in this notebook are likely stored in `used_functions.py`.

### 4. Interactive_Visualization.ipynb
The focus of this notebook is on creating interactive visualizations to explore the data. It may involve using tools like Matplotlib, Seaborn, or Plotly to generate visual representations of the data, making it easier for stakeholders to understand patterns and trends. The functions used in this notebook are likely stored in `used_functions.py`.

### 5. Model.ipynb
This notebook is dedicated to the development and evaluation of predictive models. It includes tasks such as splitting the data into training and testing sets, selecting and training machine learning models, tuning hyperparameters, and evaluating model performance. The goal is to create a model that can predict water quality in catchment areas based on the available data. The functions used in this notebook are likely stored in `used_functions.py`.

### 6. used_functions.py
This Python script contains functions that are utilized in the Data_Cleaning_and_Feature_Engineering.ipynb, Interactive_Visualization.ipynb, and Model.ipynb notebooks. These functions likely encapsulate common tasks and operations, promoting code modularity and reusability across different parts of the project.

### 7. Streamlit_script.py
This script involves the development of a Streamlit application. The script uses the models developed in the Model.ipynb notebook and incorporates interactive visualizations to provide a user-friendly interface for stakeholders to explore and interact with the project's findings.

## Steps Followed in Dashboard Creation

1. **Load Data**: Load the dataset into Power BI Desktop from a CSV file.
2. **Open Power Query Editor**: In the Power Query Editor, check "column distribution", "column quality", and "column profile" options.
3. **Column Profiling**: Select "column profiling based on entire dataset" to ensure profiling for all rows.
4. **Handle Missing Values**: Address missing values in the "Arrival Delay" column, ignoring null values as they account for less than 1%.
5. **Theme Selection**: Select a theme for the report in the report view under the view tab.
6. **Add Visuals for Ratings**: Add new visuals for representing various ratings such as Baggage Handling, Check-in Services, etc.
7. **Add Slicers**: Add visual filters (Slicers) for fields like "Class", "Customer Type", "Gate Location", and "Type of Travel".
8. **Card Visuals for Delays**: Add card visuals to represent average departure and arrival delays, excluding null values.
9. **Bar Chart for Customer Satisfaction**: Create a bar chart representing the number of satisfied and neutral/unsatisfied customers, segmented by gender.
10. **Create Calculated Columns and Measures**: Use DAX expressions to create calculated columns and measures for age groups, customer counts, percentage of customers, and total distance traveled.
11. **Insert Text Boxes and Images**: Add text boxes for the airline name and tagline, and insert shapes and images such as the company's logo.
12. **Publish to Power BI Service**: Publish the report to Power BI Service for broader access and utilization.

## Insights

### General Insights

- **Total Number of Customers**: 129,880.
- **Customer Satisfaction**: 43% satisfied customers, 57% neutral/dissatisfied customers.

### Average Ratings (out of 5)

- **Baggage Handling**: 3.63
- **Check-in Service**: 3.31
- **Cleanliness**: 3.29
- **Ease of Online Booking**: 2.88
- **Food & Drink**: 3.21
- **In-flight Entertainment**: 3.36
- **In-flight Service**: 3.64
- **In-flight Wifi Service**: 2.81
- **Leg Room Service**: 3.37
- **On-board Service**: 3.38
- **Online Boarding**: 3.33
- **Seat Comfort**: 3.44
- **Departure & Arrival Time Convenience**: 3.22

### Average Delays

- **Average Arrival Delay**: 15.09 minutes.
- **Average Departure Delay**: 14.71 minutes.

### Class Distribution

- **Business Class**: 47.87%
- **Economy Class**: 44.89%
- **Economy Plus Class**: 7.25%

### Age Group Distribution

- **0-25**: 21.69%
- **25-50**: 52.44%
- **50-75**: 25.57%
- **75-100**: 0.31%

### Customer Type

- **First Time**: 18.31%
- **Returning**: 81.69%

### Type of Travel

- **Business**: 69.06%
- **Personal**: 30.94%

## Conclusion

The dashboard provides valuable insights into water quality, helping stakeholders understand various factors influencing it. The comprehensive data analysis and predictive models guide municipalities in better managing water systems, optimizing sampling efforts, and preventing waterborne diseases. The project emphasizes the importance of data quality, ethical considerations, and the utility of interactive visualizations in facilitating informed decision-making.



Project Introduction:
This project is centered around the assessment of water quality in catchment areas, utilizing available data such as biomes, habitats, and settlements. The primary goal is to comprehensively understand the data sources, quality, and strategy involved in managing water systems. The intended outcome is to provide valuable insights that can guide municipalities in enhancing water quality, optimizing sampling efficiency, and preventing waterborne diseases. The project acknowledges the significance of ethical considerations, particularly in addressing bias in data, and recognizes challenges related to data quality and potential political agendas.

Problem:
The challenges faced in South Africa, including insufficient sanitation infrastructure, industrial pollution, agricultural runoff, and inadequate access to clean water sources in rural areas, highlight the pressing need for effective water quality monitoring. The current methods of water quality assessment may be inefficient, leading to potential health risks and outbreaks of waterborne diseases such as cholera and gastroenteritis. Additionally, oversampling in certain areas and overlooking high-risk sites can strain municipal resources. There is a need for a comprehensive approach that leverages available data to predict water quality attributes and guide proactive management strategies.

Objectives:
Data Understanding and Exploration:
Conduct a thorough Data Coverage and Exploratory Data Analysis for each relevant dataset.
Compile a Data Dictionary for each dataset to ensure a comprehensive understanding.
Data Science Specific:
Develop a Dashboard to assess water quality in catchment areas, providing a user-friendly interface for stakeholders.
Identify seasonal trends and patterns in the data to enhance predictive modeling.
Predictive Analytics:
Use data for predictive analytics on microbial populations in specific areas, assessing their impact on downstream water quality.
Investigate predictable attributes of catchment areas that indicate water quality before traditional sampling methods, such as the South African Scoring System, are implemented.
Data Engineering Specific:
Establish a robust Data Access framework to ensure timely and efficient retrieval of relevant information.
Develop a Data Strategy for modeling, outlining the approach to be taken for predictive analytics.
Conduct Data Quality testing, focusing on accuracy, completeness, reliability, relevance, and timeliness.
Contextual Information:
Why is this work important? The project is crucial for human health and well-being, especially in regions facing challenges like insufficient sanitation infrastructure and industrial pollution. Water quality monitoring is particularly relevant in South Africa due to various environmental challenges, making safe drinking water a priority for preventing waterborne diseases.

Focus of Output: The project aims to guide municipalities in better managing water systems by predicting pollution risks and optimizing sampling efforts. The use of dashboards based on predictive models can contribute to more informed decision-making and prevent outbreaks of waterborne diseases.

Potential Users: Government bodies, environmentalists, and engineers are identified as key users who can benefit from the insights provided by the project. The implementation of dashboards fed with model-driven data can enhance the decision-making process for these stakeholders.

Team Members:
Osinachi Ezemba
Timmy Egbe
Damola Abiola
Daniel Felix
Macdaniel Ogechukwu
Abdulamid Adekunle
Notebooks
For the entirerity of this project, the team made use of 4 different notebooks

Data_importation.ipynb: This notebook focuses on importing the necessary datasets for the project. It likely includes code for loading data from various sources into the project environment. This step is crucial for subsequent analyses and model development.

Data_joining.ipynb: The purpose of this notebook is to combine or join different datasets. It involves merging data based on common keys or attributes, ensuring that the datasets are unified and ready for further analysis. This step is essential for creating a comprehensive dataset that covers various aspects of water quality and catchment areas.

Data_Cleaning_and_Feature_Engineering.ipnyb: This notebook is dedicated to cleaning the data and performing feature engineering. It includes tasks such as handling missing values, addressing outliers, and creating new features that might enhance the predictive capabilities of the model. The functions used in this notebook are likely stored in used_functions.py

Interactive_Visualization.ipnyb: The focus of this notebook is on creating interactive visualizations to explore the data. It may involve using tools like Matplotlib, Seaborn, or Plotly to generate visual representations of the data, making it easier for stakeholders to understand patterns and trends.The functions used in this notebook are likely stored in used_functions.py

Model.ipnyb: This notebook is dedicated to the development and evaluation of predictive models. It includes tasks such as splitting the data into training and testing sets, selecting and training machine learning models, tuning hyperparameters, and evaluating model performance. The goal is to create a model that can predict water quality in catchment areas based on the available data.The functions used in this notebook are likely stored in used_functions.py

used_functions.py: This Python script contains functions that are utilized in the Data_Cleaning_and_Feature_Engineering.ipnyb, Interactive_Visualization.ipnyb, and Model.ipnyb notebooks. These functions likely encapsulate common tasks and operations, promoting code modularity and reusability across different parts of the project.

Streamlit_script.py: This script involves the development of a Streamlit application. The script use the models developed in the Model.ipnyb notebook and incorporate interactive visualizations to provide a user-friendly interface for stakeholders to explore and interact with the project's findings.

References
[1] Hassan Omer, N. (2020). Water Quality Parameters. IntechOpen. doi: 10.5772/intechopen.89657
