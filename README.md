# Analysis of Insurance: Charges and Influencing Factors (DSC 205)

Youssef Rafik

## Overview
This project investigates the main factors that influence **medical insurance charges** using statistical and visual analysis. We focus on how **age, BMI, region, and smoking status** relate to charges, and we surface patterns through an interactive Streamlit interface. :contentReference[oaicite:2]{index=2}

## Dataset
Source: Kaggle (insurance dataset) :contentReference[oaicite:3]{index=3}

Columns used:
- `age`
- `bmi`
- `children`
- `smoker`
- `region`
- `charges` :contentReference[oaicite:4]{index=4}

## Streamlit App
Live app: https://insurance-hxycnaepkrrbntxkpgx4l2.streamlit.app/ :contentReference[oaicite:5]{index=5}

## Interactive Filters (App Interface)
The app supports filters to explore specific subgroups:
- Region
- Smoker status
- BMI category
- Number of children :contentReference[oaicite:6]{index=6}

These filters help reveal trends that may look different across populations. :contentReference[oaicite:7]{index=7}

## Visual Analyses Included
- **Demographics overview**: smoker vs. non-smoker distribution :contentReference[oaicite:8]{index=8}  
- **Drivers of costs**: relationships between charges vs. age/BMI, split by smoker status :contentReference[oaicite:9]{index=9}  
- **Correlation heatmap**: correlation between numeric features and charges :contentReference[oaicite:10]{index=10}  
- **Lifestyle & geography**: comparing charges across regions and by number of children :contentReference[oaicite:11]{index=11}  

## Key Findings (from the presentation)
- **Smoker distribution**: ~20.5% smokers vs. ~79.5% non-smokers. :contentReference[oaicite:12]{index=12}  
- **Smoking is the biggest cost amplifier**: charges rise sharply with age for smokers, and higher BMI is associated with higher charges especially among smokers. :contentReference[oaicite:13]{index=13}  
- **Correlation results**:
  - Charges vs. age: ~0.3 (strongest)
  - Charges vs. BMI: ~0.2 (moderate)
  - Children count shows minimal correlation with charges :contentReference[oaicite:14]{index=14}  
- **Regional differences**: median charges are fairly close across regions (~$8,000–$10,000). :contentReference[oaicite:15]{index=15}  
- **Children**: families with no children showed the highest charges in this dataset (as observed in our analysis). :contentReference[oaicite:16]{index=16}  

## Insights / Takeaways
- Smokers face significantly higher charges due to elevated health risks. :contentReference[oaicite:17]{index=17}  
- Age and BMI are critical drivers, with higher costs for older and obese individuals. :contentReference[oaicite:18]{index=18}  
- Regional and family-related patterns suggest opportunities for tailored strategies and policies. :contentReference[oaicite:19]{index=19}  

## Future Work
(Planned extensions will be added here, such as deeper subgroup analysis, improved modeling, and expanded app features.) :contentReference[oaicite:20]{index=20}
