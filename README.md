# Analysis of Insurance: Charges and Influencing Factors (DSC 205)

Youssef Rafik

## Overview
This project investigates the main factors that influence **medical insurance charges** using statistical and visual analysis. We focus on how **age, BMI, region, and smoking status** relate to charges, and we surface patterns through an interactive Streamlit interface.

## Dataset
Source: Kaggle (insurance dataset)

Columns used:
- `age`
- `bmi`
- `children`
- `smoker`
- `region`
- `charges`

## Streamlit App
Live app: https://insurance-hxycnaepkrrbntxkpgx4l2.streamlit.app/

## Interactive Filters (App Interface)
The app supports filters to explore specific subgroups:
- Region
- Smoker status
- BMI category
- Number of children 

These filters help reveal trends that may look different across populations. 

## Visual Analyses Included
- **Demographics overview**: smoker vs. non-smoker distribution  
- **Drivers of costs**: relationships between charges vs. age/BMI, split by smoker status 
- **Correlation heatmap**: correlation between numeric features and charges  
- **Lifestyle & geography**: comparing charges across regions and by number of children 

## Key Findings (from the presentation)
- **Smoker distribution**: ~20.5% smokers vs. ~79.5% non-smokers. 
- **Smoking is the biggest cost amplifier**: charges rise sharply with age for smokers, and higher BMI is associated with higher charges especially among smokers.   
- **Correlation results**:
  - Charges vs. age: ~0.3 (strongest)
  - Charges vs. BMI: ~0.2 (moderate)
  - Children count shows minimal correlation with charges 
- **Regional differences**: median charges are fairly close across regions (~$8,000–$10,000). 
- **Children**: families with no children showed the highest charges in this dataset (as observed in our analysis). 

## Insights / Takeaways
- Smokers face significantly higher charges due to elevated health risks. 
- Age and BMI are critical drivers, with higher costs for older and obese individuals. 
- Regional and family-related patterns suggest opportunities for tailored strategies and policies. 

## Future Work
(Planned extensions will be added here, such as deeper subgroup analysis, improved modeling, and expanded app features.) 
