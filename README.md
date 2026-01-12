### Turning Visitor Data into Marketing Impact

📊 Project Overview

This project is a pet exploratory data analysis (EDA) exercise that demonstrates how visitor-level data can be transformed into actionable insights for a marketing department. Using a mock visitor dataset, the analysis focuses on understand visitor behaviour, segmentation patterns, and seasonal spending trends to inform marketing strategy and campaign planning. 

The project emphasizes strcutured EDA, thoughtful feature selection, and careful handling of common real-world data issues such as missing values and inconsistent responses. 

🎯 Objectives

- Understand the structure, quality, and limitations of a visitor dataset
- Identify key visitor characteristics influencing travel and spending behaviour
- Develop meaningful visitor segments for marketing analysis
- Explore seasonality effects in visitor spending
- Lay the groundwork for downstream segmentation and profiling analysis

🗂 Dataset Overview

The mock dataset contains visitor-level information related to:

- Visitor demographics
- Trip characteristics
- Accommodation preferences
- Length of stay and country of residence
- Spending behaviour across different categories

A provided data dictionary is used to interpret variable definitions and ensure correct usage of each field:


🔍 Exploratory Data Analysis Approach

1. Data Understanding & Structure

The analysis begins by reviewing:
- Number of observations and variables
- Data types and formats
- Variable definitions using the data dictionary

This step helps identify relevant features for visitor profiling and ensures the dataset is suitable for behavioral analysis. 

2. Key Variables for Visitor Analysis

The following variables are prioritized due to their relevance to marketing and behavioural insights:

Purpose of visit:
- Leisure, business, events

Travel companion type:
- Solo travelers, couples, families, groups

Accommodation type
- Hotels, serviced apartments, other lodging types

Length of stay & Country of residence
- Key drivers of overall visitor spend

Spending variables
- Total expenditure and category-level spend
- Seasonal periods such as: Great Singapore Sale (June) and Formula 1 Grand Prix (September - October)

These variables collectively answer:

Who the visitors are, how they travel, where they come from, and how they spend while in Singapore. 

3. Feature Engineering & Visualization

To deepen insights, the project applies:
- Feature engineering and category standardization
- Visitor segment profiling
- Visual exploration using: Bar charts, stacked bar charts

Key relationships explored inside:
- Travel companion type vs accommodation choice
- Country of residence vs length of stay
- Purpose of visit vs spending behaviour

This step supports the identification of meaningful visitor segments and spending patterns. 

4. Data Quality & Limitations

The data reflects common real-world survey challenges:
- Missing or incomplete responses
- Uneven and highly variable spending values
- Inconsistent categorical labels

These issues are addressed by:
- Using robust summary statistics
- Treating extreme values cautiously to avoid distortion
- Grouping inconsistent responses into standardized categories
- Interpreting results with awareness of seasonal effects, given the time-based nature of data collection

This ensures insights are not misattributed to general trends when they are driven by specific time periods or events. 

🧠 Key Outcomes

- A structured EDA framework for visitor analytics
- Clear identification of variables relevant for segmentation
- Foundational insights to support: Visitor profiling, Seasonality analysis, Marketing campaign targeting

The findings informed subsequent segmentation decisions and guided variable selection for deeper behavioral analysis. 

🛠 Tools & Techniques

- Exploratory Data Analysis (EDA)
- Feature engineering
- Data cleaning and standardization
- Visual analytics (bar charts, stacked bar charts)
