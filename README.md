# Capital Bikeshare Data Analysis and Bike Demand Prediction at Rush hour Project
## Description
An analysis of mobility datasets provided by Capital Bikeshare, a bike-sharing company in Washington DC. For an overview of the techniques employed and results, download the [EDA Presentation]([url](https://github.com/Paul-Sabin/Capital-Bikeshare/blob/main/EDA%20Presentation%20for%20Capital%20Bikeshare.pptx)) and [Machine Learning Presentation]([url](https://github.com/Paul-Sabin/Capital-Bikeshare/blob/main/Machine%20Learning%20Presentation%20for%20Capital%20Bikeshare.pptx)) (Powerpoint) 

## Features
* * * Full Dataset
*  ride_id 
*  rideable_type       
*  started_at        
* ended_at          
* start_station_name  
*  start_station_id   
*  end_station_name    
*  end_station_id     
*  start_lat          
*  start_lng           
*  end_lat            
* end_lng            
*  member_casual

* * *  Hourly dataset
*  Casual                   
*  Date                   
*  Hour                   
*  Member                   
*  Total_rides             
*  relativehumidity_2m (%)  
*  temperature_2m (°C)      
*  weathercode (wmo code)  
*  windspeed_10m (km/h)    

## Key Highlights
+  Conducted thorough data wrangling and data cleaning to ensure data quality and accuracy.
* Performed exploratory data analysis (EDA) to uncover patterns, trends, and relationships within the dataset.
*  Utilized machine learning algorithms to develop predictive models to forecast bike demand during rush hours, enhancing resource allocation and operational efficiency.
*  Created visually appealing and informative geographical visualizations to better understand the data and consumer behavior.
*  By applying these techniques, we gained valuable insights into bike usage patterns, user preferences, and other important factors that can drive business decisions for Capital Bikeshare.
*  Several models were used ranging from Linear regression, Polynomial regression, Random Forest, etc. And evaluation metrics used for models were MSE and R2.
* Polynomial regression, due to the fact that it understands non-linearity between features as well as complex patterns, performed better than Linear regression.  

* It was discovered that the new Generation E-Bike that was launched  in the spring of 2023 influenced The growth rate of ride likewise increased the rides made by registered bike users

## Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Folium
