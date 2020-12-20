# Water Quality Prediction

### Authors
- [Shekhar Shukla](https://github.com/24sharkS)
- [Sarthak Arora](https://github.com/sarthak144)
- [Sajeel Khan](https://github.com/khansajeel)

### Introduction
The main motivation to explore this topic comes from the continuous degradation of the environment, which leads to various diseases and substandard living for people facing that degradation in their local habitats. The regular methods require lab analyses which prove to be costly and time consuming. Many countries don’t even have the required instruments to measure water quality.
By using machine learning techniques, we can save time and the cost by training the model properly with features that best predict the water quality.

### Dataset Overview
The dataset was taken from [Ministry of Environment and Forests, Govt of India](http://www.cpcbenvis.nic.in/water_quality_data.html).
Water data of rivers, drains, creeks, lakes, ponds, tanks of years 2016 to 2019. Total number of samples being 3938.
The data had 8 features, namely, Temperature, Dissolved Oxygen(DO), pH, Conductivity, Biochemical Oxygen Demand(BOD), Nitrate, Faecal Coliform and Total Coliform. Out of these 8 features we chose 6 features for further analysis namely Temperature, Dissolved Oxygen(DO), pH, Biochemical Oxygen Demand(BOD), Nitrate and Faecal Coliform.

### Dependencies
To run the scripts the following software and library dependencies must be installed:
- python 3
- jupyter
- numpy
- pandas
- matplotlib
- sklearn
- pickle

### Organization
- `/End` - This folder contains the final data and code in the form of jupyter notebook.
- `/Mid` - This folder contains the code and data used in the analysis upto mid progress report.
- `/plots` - This folder contains the plots in the following format.
	- `confusion_matrix_x.jpg` : confusion matrix for classification of water quality using x number of features.
	- `roc_plot_x.jpg` : roc plot for classification of water quality using x number of features.
	- `fitted_line_x.jpg` : fitted line plot for prediction of WQI using x number of features.
- `Weights` - This folder contains the best performing model objects for prediction of WQI and classification of water quality respectively.
	- `best_cl_x.obj` - SVM model corresponding to water quality classification using x number of features.
	- `best_reg_x.obj` - SVR model corresponding to WQI prediction using x  numbers of features.
- `Report` - This is the final report summarizing the project.


