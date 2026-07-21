#  World Happiness Report - Dataset Exploration

## Dataset Overview
The World Happiness Report is an annual publication by the Sustainable Development Solutions Network that ranks countries by their citizens' perceived happiness. The dataset uses the Cantril Ladder approach where respondents rate their lives on a 0-10 scale.

**Source**: [Kaggle - World Happiness Report](https://www.kaggle.com/datasets/unsdsn/world-happiness)

**Key Columns**:
- `Overall rank`: ranking
- `Country or region`: Country or region name
- `Score`: Happiness score
- `GDP_per_capita`: GDP per capita 
- `Social_support`: Social support score
- `Healthy_life_expectancy`: Healthy life expectancy
- `Freedom_to_make_life_choices`: Freedom score
- `Generosity`: Generosity score
- `Perceptions_of_corruption`: Corruption perception score


## Business Problems

This dataset can address several business and policy-relevant problems:

1. **National Policy Planning**: Governments can identify which factors most strongly correlate with happiness and allocate resources accordingly. 

2. **Tourism & Investment Attraction**: Countries with high happiness scores attract tourists, expatriates, and foreign investment. Understanding which metrics drive happiness helps in creating targeted promotional strategies.

3. **NGO Program Targeting**: International development organizations can identify countries with low happiness despite relatively high GDP - indicating "well-being gaps" where social programs can have maximum impact.

4. **Corporate Location Decisions**: Multinational corporations can factor happiness metrics into decisions about office locations, as quality of life directly impacts talent attraction and retention.

5. **Temporal Trend Analysis**: Understanding how happiness scores change over time reveals the long-term impacts of economic crises, policy shifts, or global events (e.g., COVID-19 pandemic).

## Machine Learning Problem Framing

**Problem Type: Regression**

This is a Regression problem because the target variable that is happiness score is a continuous numerical value. And its not like classification since its not ‘happy’ or ’unhappy’…


## Target Variable & Key Features

target = 'Score'
features = [
    'GDP per capita',
    'Social support',
    'Healthy life expectancy',
    'Freedom to make life choices',
    'Generosity',
    'Perceptions of corruption'


##  Three Key Observations

1. Nordic countries have high social support, strong welfare systems, economic equality, and high life expectancy that’s why they leading at the top.

2. GDP is not a sole factor since some countries may have HNI and a lot of poverty which means its a big gap so bad score 

## Repository Contents

- `whr2019_epochsday1.ipynb` - Jupyter notebook with dataset exploration 
- `2019whr.csv` - The dataset
- `README.md` - This documentation

## Assignment Information

**Course**: #evn-ds-epochs26-day01  
**Submission**: GitHub repository link
