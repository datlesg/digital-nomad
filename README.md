# The Best Shelter For The Digital Nomads

With remote work on the rise, digital nomads seek destinations that offer affordability, quality of life, and reliable digital infrastructure. This project aims to rank countries based on key factors, including economic viability (GNI per capita, adjusted for purchasing power parity - PPP), well-being (life expectancy, happiness score), and digital accessibility (internet penetration). Using data-driven analysis, we will identify the top locations for digital nomads within a three-month timeframe, providing actionable insights for individuals seeking the best place to live and work remotely.


### Data Dictionary

This dataset contains information about countries that are popular among digital nomads, focusing on cost of living, quality of life, digital infrastructure, and visa policies. The dataset includes data from **2005 onward** to ensure the accountability of all row records in all the pre-merged datasets and consists of the following features:

| Feature | Type | Dataset | Description |
|---|---|---|---|
| **country** | *string* | Merged Dataset | Name of the country. |
| **year** | *integer* | Merged Dataset | Year of the recorded data. |
| **pop_value** | *integer* | Population Data | Total population of the country in the given year. |
| **life_expectancy_value** | *float* | Life Expectancy Data | The average life expectancy (in years) at birth. |
| **happiness_score_value** | *float* | Happiness Score Data | The national happiness score based on survey responses. |
| **gni_value** | *float* | GNI Data | Gross National Income per capita adjusted for Purchasing Power Parity (PPP) in international dollars. |
| **internet_users_value** | *float* | Internet Users Data | Percentage of individuals using the internet in the country. |

### **Data Source:**
- The datasets were retrieved from publicly available sources, including **[Gapminder](https://www.gapminder.org/data/)** 
- The merged dataset focuses on countries that are recognized as top destinations for digital nomads.


# Executive Summary

## Project Goals
- Identify countries with the **highest internet penetration growth**, ensuring digital nomads have reliable connectivity.
- Assess **economic well-being (GNI per capita PPP)** to determine affordability and economic stability.
- Evaluate **happiness and life expectancy trends** to identify destinations that offer both professional and personal well-being.
- Provide actionable insights for **digital nomads, policymakers, and businesses** to make informed decisions.

## Methodology
- **Data Sources**: Data was collected from **Gapminder and publicly available global development reports**.
- **Data Cleaning & Processing**: Standardized datasets, handled missing values, and converted economic data to PPP-adjusted GNI per capita.
- **Exploratory Data Analysis (EDA)**: Identified trends in internet penetration, economic growth, happiness scores, and life expectancy.
- **Statistical Correlations**: Examined relationships between key variables to understand how digital growth impacts economic well-being and quality of life.
- **Visualizations**: Created time-series plots, scatter plots, and correlation heatmaps to highlight key trends.

## Key Findings
1. **Internet Growth is a Key Driver for Digital Nomad-Friendly Countries**  
   - **Indonesia, Thailand, Vietnam, Georgia, and Costa Rica** have seen the most **significant increases in internet penetration**.
   - **Costa Rica and Thailand** were early adopters, maintaining **high digital accessibility**.
   - **Indonesia has the highest percentage growth (364%)**, but absolute penetration still lags behind Thailand and Costa Rica.

2. **Economic Development Correlates with Internet and Life Expectancy Growth**  
   - **GNI per capita strongly correlates with internet penetration (0.79) and life expectancy (0.77)**.
   - **Vietnam and Georgia** have shown **remarkable economic expansion (117% GNI growth)**.
   - **Thailand and Costa Rica offer balanced economic growth with stable digital infrastructure**.

3. **Happiness Growth Does Not Always Align with Economic Gains**  
   - **Vietnam (+26.1%) and Georgia (+22.9%) show the highest happiness growth**, despite moderate GNI per capita.
   - **Indonesia, despite rapid economic expansion, has lower happiness growth (7.75%)**, suggesting economic growth does not always translate to well-being.

4. **Top Digital Nomad Destinations Identified**  
   - **Best Digital Hubs**: **Costa Rica, Thailand, and Georgia** (Strong digital infrastructure and supportive visa policies).  
   - **Affordable & High Quality of Life**: **Vietnam and Georgia** (Affordable, growing economies with improving well-being).  
   - **Fast-Growing but Catching Up**: **Indonesia** (Rapid expansion but still developing digital and social infrastructure).  

## Conclusion & Implications
This analysis provides **data-driven insights** into the best destinations for remote work and digital nomads. The findings can help:
- **Remote workers** identify ideal countries based on affordability, digital infrastructure, and quality of life.
- **Policymakers** make informed decisions on investing in digital infrastructure and developing visa programs to attract talent.
- **Businesses** understand global trends in internet penetration and economic development, influencing market expansion strategies.

## Next Steps & Future Research
- **Visa & Tax Policies**: Conduct further research on digital nomad visa requirements and tax regulations in top-ranked countries.
- **Cost of Living Analysis**: Incorporate more detailed cost-of-living data to refine recommendations for budget-conscious nomads.
