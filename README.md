
<img src="https://mjconroy.com/wp-content/uploads/2023/04/ATU-Logo.png" width="250" height="150">



# **Higher Diploma in Computing: Data Analytics**

### **Module: Programming for Data Analytics**
***

#### **Project:**

This project analyses the historical weather data obtained from  [Met Eireann](https://www.met.ie/climate/available-data/historical-data) for five locations across Ireland to provide an overview of weather patterns, with a specific focus on windspeed.  

#### **Method overview:**

*Data Processing and analysis:*

-   Jupyter notebook: An open source web application used for python coding in real time, text and visualisations. 

-   Pandas: An open-source python library built on top of NumPy used for data manipulation and analysis. 
    -    The CSV datasets were loaded into a pandas dataFrame using pd.read_csv(). 
    -   Data cleaning was carried out using functions like dropna() to remove missing values. 
    -   The  groupby() and resample() functions were used to group data by location or year etc splitting the data into groups allowing aggregation of data using mean() etc.
    -    For time-series analysis, the pandas datetime function was used to process dates and times. pd.to_datetime() used to convert string dates into datetime objects.

*Data Visualisation:*
   -    Matplotlib: python library used to create plots to display the data graphically for trend analysis. 
   -    Seaborn: A Python data visualization library based on matplotlib. 
   
*Machine Learning:*

-   Scikitlearn: An open-source machine learning library


#### Set-up: 

- [Anaconda](https://www.anaconda.com/download) for creating and managing Python environments
- [Visual Studio Code](https://code.visualstudio.com/download) for editing and running the code.

***

### References:

-   https://pandas.pydata.org/docs/
-   https://pandas.pydata.org/docs/user_guide/10min.html
-   https://numpy.org/doc/stable/user/whatisnumpy.html
-   https://matplotlib.org/stable/index.html
-   https://seaborn.pydata.org/
-   https://scikit-learn.org/stable/