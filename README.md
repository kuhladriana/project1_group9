# **Global Air Quality Index (AQI) EDA Project**

![Image Alt](https://github.com/kuhladriana/project1_group9/blob/main/Neelam_work/hq720.jpg)

## **Project Overview**

This project explores the distribution of key air pollutants (NO₂, CO, Ozone, and PM2.5) across the globe, analyzes how air quality (AQI) correlates with geographical location (latitude and longitude), and provides valuable insights into global air pollution. The increasing concerns over air quality, the availability of global environmental datasets, and the need for data-driven solutions to improve public health and environmental policy motivated this analysis. The project uses data from multiple cities and countries to evaluate air quality based on various pollutant values, presenting visualizations to understand global pollution patterns and explore how geographical factors influence air quality.

## **Table of Contents**
- [Project Structure]
- [Data Description]
- [Exploratory Data Analysis]
- [Key Findings]
- [Visualizations]
- [Conclusion]


## **Project Structure**

The project directory structure is as follows:

```
global-air-quality-index-EDA/
├── data/
│   ├── AQI and Lat Long of Countries.csv                      
│   ├── Countries by continents.csv           
│   └── cleaned_data.csv        
├── notebooks/                  
│   ├── data_visualization_Adriana.ipynb 
│   └── data_visualization_Val.ipynb
│   └── data_visualization_Neelam.ipynb 
│   └── data_visualization_Misha.ipynb          
├── Project Proposal -World Air Quality Index.pdf
├── Project Presentation-World Air Quality Index .pdf
├── Project Technical Writeup -World Air Quality Index            
├── README.md                 

```

## **Data Description**

The dataset used in this project includes the following columns:

1. **Country**: The country where the city is located.
2. **City**: The name of the city.
3. **Overall_AQI_Value**: The overall AQI value for the city.
4. **Overall_AQI_Category**: The air quality category for the overall AQI (e.g., "Good", "Moderate", "Unhealthy").
5. **CO_AQI_Value**: AQI value for Carbon Monoxide.
6. **CO_AQI_Category**: AQI category for Carbon Monoxide.
7. **Ozone_AQI_Value**: AQI value for Ozone.
8. **Ozone_AQI_Category**: AQI category for Ozone.
9. **NO2_AQI_Value**: AQI value for Nitrogen Dioxide.
10. **NO2_AQI_Category**: AQI category for Nitrogen Dioxide.
11. **PM2.5_AQI_Value**: AQI value for Particulate Matter (PM2.5).
12. **PM2.5_AQI_Category**: AQI category for Particulate Matter.
13. **Latitude**: Latitude of the city.
14. **Longitude**: Longitude of the city.
15. **Continent**: The continent where the city is located.

## **Exploratory Data Analysis**

In this project, we conduct exploratory data analysis (EDA) to understand how pollutants are distributed globally, the relationship between AQI and geographical location, and the correlation between different pollutants.

### **Key Research Questions:**
1. **What are the effects on the Air Quality Index(AQI) value by the pollutants?**
2. **How are the four key pollutants (CO, Ozone, NO₂, and PM2.5) distributed across the globe?**
3. **Is there a relationship between geographical location (continent, country, city) and AQI values across different regions?**

### **Analysis Steps:**
1. **Distribution of Pollutants**: We analyze the distribution of each pollutant using various visualizations such as bar graphs, pie charts, and line charts. The goal is to observe how each pollutant contributes to the global AQI levels.
2. **Geographical Influence**: By analyzing AQI values against geographical locations (latitude and longitude), we explore whether there is a discernible pattern in how pollutants vary across regions and continents.
3. **Outlier Detection**: We identify outliers in AQI values, focusing on cities or regions with extreme pollution levels.

## **Key Findings**

1. **Pollutant Distribution**: 
   - **PM2.5** was identified as the most prevalent pollutant across the globe, with high concentrations in industrialized and rapidly urbanizing regions, especially in parts of **Asia**.
   - **CO and NO2 are mostly concentrated in the Good category, whereas Ozone and especially PM2.5 have more cities in moderate to unhealthy categories based on this dataset.**

2. **Geographical Patterns**: 
   - The analysis showed that **Asia** and **Africa** had the highest AQI values, particularly in countries like **India**, **China**, and **Pakistan**.
   - **Europe** and **Oceania** displayed relatively lower AQI values, with stricter environmental regulations.

3. **Outliers**: Several cities were identified as outliers, exhibiting extreme AQI values that deviate significantly from the regional averages. This highlights the need for further investigation into local pollution sources.

## **Visualizations**

The following visualizations were created to better understand the findings:

1. **Map with Pollution Levels**:
   - A geographical map showing circles representing pollution levels at different locations. The color of the circles indicates pollutant concentration.
   
2. **Bar Graph**:
   - Bar Plot to show countries, cities contributing to the AQI Value.

3. **Donut/Pie Chart**:
   - A donut chart showing the percentage contribution of each pollutant to global air quality.

4. **Scatter Plot**:
   - A scatter plot mapping **latitude vs. longitude** with pollutant concentrations or AQI values, visualizing geographical pollution patterns.

5. **Linear Regression**:
   - A linear regression model comparing **latitude and longitude** against pollutant levels, to examine the relationship between geographical location and air quality.

6. **Box Plot**
   - Box Plot for the top 10 countries with most outliers for AQI value.

7. **Violin Plot**
   - Violin plot to compare the AQI values for the continents.

8. **Histogram**
   - Histogram to show Air quality variation in Northern and Southern Hemispheres

## **Conclusion**
   -The findings support the hypothesis that geographical location has a relationship with AQI values, but this relationship is more complex than a direct connection to latitude, longitude, or even hemisphere.
Several key factors influence AQI values across different regions:
   - Urbanization and Industrialization: Countries with large, densely populated urban areas, such as China and India, tend to have poorer air quality. High industrial activity, transportation emissions, and limited green spaces contribute significantly to elevated AQI values in these regions.
   - Environmental Policies and Regulations: Countries with stricter environmental regulations and lower industrial activity, such as those in Europe and Oceania, tend to have better air quality. This indicates the role of governmental policies in managing air quality.
   - Climate and Geography: Climate conditions and geographical features also play a role. For example, cities in valleys or areas prone to temperature inversions often experience worse air quality due to trapped pollutants. On the other hand, cities with favorable climatic conditions for dispersing pollutants (e.g., coastal cities) tend to have better air quality.


