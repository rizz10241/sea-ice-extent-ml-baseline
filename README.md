# Sea Ice Extent ML Baseline
This project uses a publicly available dataset from NOAA to explore whether machine learning models can predict Arctic sea ice extent using only 'Year' as a feature.

# Motivation
Topics like Arctic monitoring, Climate, Environment, Sustainability, Biodiversity, Green Energy interests me. So I tried making a model on predicting Ice Cover Extent with time

#Dataset
Source: NOAA  
`n_iceextent.mon.csv` — Monthly sea ice extent (1978 onward)  
Note: Missing values (-9999) were cleaned.

#Models Used
- Linear Regression
- Random Forest
- Gradient Boosting

#Results

 Model | R² Score 

 Linear Regression = -0.04 
 Random Forest     = -0.04 
 Gradient Boosting = 0.16 

   -->Conclusion: A single feature (Year) is not sufficient for accurate predictions. Seasonal, temperature, and climate-based variables were needed.

# Future Work
- Add seasonal features (month, sin/cos encoding)
- Merge with CO2 or temperature datasets
- Use LSTM for time-series modeling


This project reflects an honest attempt to learn and build real-world ML skills. It is not a perfect model but I tried working on a real world dataset. Since I found a csv file on the NOAA website, 
I thought of applying different ML models to see if sea ice extent can pe predicted with just the given feature i.e., Year
