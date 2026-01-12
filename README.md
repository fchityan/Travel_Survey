### Turning Visitor Data into Marketing Impact

#### This is a small pet project anaylzing dataset on visitor data for marketing department. My exploratory data analysiss approach begins with understanding the structure, quality, and key characteristics of the mock dataset before deriving any behavioural insights. 

#### Firstly, i would review the overall dataset structure by examining the number of observations, data types, and variable definitions using the provided data dictionary. This helps to identify relevant variables related to visitor demographics, trip characteristics, accommodation choices, and expenditure patterns. 

#### Secondly, i would focus on key behavioural and contextual data fields that are most relevant to visitor analysis, including:
#### - Purpose of visit, to understand visitor motivation (e.g leisure, business, events)
#### - Travel companion type, such as solo travellers, couples, families, or groups
#### - Accommodation type, to capture preferences across different visitor profiles
#### - Length of stay, country of residence as a key driver of total spend
#### - Spending variables, particularly shopping and overall expenditure, with attention to seasonal periods such as Great Singapore Sale in June or F1 race between September to October

#### These fields are important as they collectively describe who the visitors are, how they travel, from which countries and how they spend while in Singapore. I would then perform feature engineering, segment profiling and visualizations (eg. bar charts and stacked bar charts) to understand distributions, identify potential outliers, and explore relationships between variables such as travel companion type and accommodation choice, country of residence or purpose of visit and spending behaviour. 
  
#### This structured approach ensures a comprehensive understanding of the dataset and provides a strong foundation for identifying meaningful visitor segments and informing subsequent analysis. The findings informed subsequent segmentation choices and guided the selection of variables used for visitor profiling and seasonality analysis. 

#### Thirdly, this mock dataset contains common issues such as missing responses and uneven spending values, as some visitors may forget or estimate their answers. These were addressed by using robust summary measures and treating extreme values cautiously to avoid distorting results. Some responses were also recorded inconsistently and were therefore grouped into broader, standardised categories for analysis. In addition, the data was collected over time, results were interpreted with consideration of seasonal effects to avoid misattributing time specific behaviour as general trends. 
