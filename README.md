# Pump It Up  Tanzania Water Wells



## 1. INTRDUCTION
Tanzania, as a developing country, struggles with providing clean water to its population of over 57,000,000. There is a need to improve access to clean water for the population. While there are many water points already established, some are in need of repair and others have failed altogether. The challenge is to accurately predict the condition of a water well based on factors such as the type of pump, installation date, and other relevant information. The goal of this project is to develop a classifier that can accurately predict the condition of water wells, which can be useful for NGOs looking to locate wells needing repair or the government of Tanzania trying to find patterns in non-functional wells to influence how new wells are built

## 2. BUSINESS PROBLEM
### The Problem statement
How can we accurately predict the condition of a water well in Tanzania based on factors such as type of pump, installation date, and other relevant information.

### Main Objective
Predict the condition of water wells in Tanzania, which can help an NGO or the government of Tanzania to identify wells that need repair or replacement.

### Other objectives
- To improve access to clean water by identifying wells in need of repair or replacement.
- To provide insights into patterns and trends in the functionality of wells, which can inform decision-making for future well construction.
- To promote sustainability and long-term planning for water well infrastructure in Tanzania.

## 3. NOTEBOOK STRUCTURE
The notebook is [here](https://github.com/K-made/Tanzania-well-water/blob/main/index.ipynb)
The python notebook is structured as follows:
1. Data cleaning
2. Exploratory Data Analysis
3. Feature selection 
4. Data Modelling and evaluation

## 4. DATA UNDERSTANDING
### The Data
##### The data used in this project was downloaded from [Kaggle ](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho) 

The data for this project is obtained from the Taarifa waterpoints dashboard, which has been aggregated from the Tanzania Ministry of Water and is used to track infrastructure-related issues. The data contains information on 59,400 waterpoints and is available as three datasets:

- Training set labels
- Training set values
- Test set values. 

The target variable is "status_group", which details the functionality of the waterpoints. The training data has 59,400 rows and 41 columns and contains information about the water pumps, such as the type of pump, installation date, location, etc.The test data has 40 columns and 14850 row. The data was acquired from Taarifa and the Tanzanian Ministry of Water and was downloaded from DrivenData.
- Lastly, to validate this data reference was made to github repository [here](https://github.com/MercyNgila/Tanzanian-Water-Pump-Status)

### Data Preparation
The data was checked for missing values and some columns were found to have null values.The column with higher percentage of null values was dropped with 6% and bellow of null values were dropped column wise.
Their were no duplicates
Some columns had similar value counts and one of the columns remained while the rest were dropped to remain with only.
Some columns were not in their appropriate data type so this was corrected to create a cleaner and easier to work with dataframe.
Some columns were irrelevant for prediction because they represented the same thing such as two columns showing values for region

### Exploratory Data Analysis
By carrying out EDA on the cleaned data as seen in this notebook, various patterns were discovered in the dependent and independent variables.. This analysis made it possible to understand how the value of the dependent variable changes as the value of any of the independent variables change.

### Data Interpretation ##
 
This project is going to predict the condition of a water well in Tanzania based on factors such as type of pump, installation date, and other relevant information.





## 5.CONCLUSIONS 

The final model, a Random Forest Classifier, achieved an accuracy of 80.03% and is ready for deployment. This high level of accuracy provides valuable insights into the conditions of water wells, which will greatly aid in planning, prioritizing and investment decisions. The results show that there are different water qualities in the functional pumps, with most of them having soft water. It was also noted that water wells with significant investment costs were functional. The most functional water pumps among communities were found to be gravity and hand pumps. It is concerning, however, that the number of non-functional water pumps is high, highlighting the need for continued monitoring and maintenance efforts to ensure access to clean water for communities in need.

## 6.RECOMMENDATIONS

- Repair and maintenance of existing water wells to ensure their continued functionality.
- Implementing better standards and practices for the construction and installation of new water wells.
- Increasing investment in the development and deployment of new water well technologies.
- Supporting the education and training of local communities in the operation and maintenance of water wells.
- Collaborating with NGOs, private sector organizations, and international agencies to tackle the water well crisis in Tanzania.


## 7.REPOSITORY GUIDE
- The data set used can be found [here](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/data/)
- The data report can be found [here](https://docs.google.com/document/d/1R1BRsmBP6aQKFQWkamX431vkX9ZU-B1hudQephClxj4/edit#)
- The notebook can be found [here](https://github.com/K-made/Tanzania-well-water/blob/main/index.ipynb)
- The Presentation Slides can be found [here](https://www.canva.com/design/DAFaG4R1FDM/cX2kQqkgauhNzChEr3CszQ/edit)

