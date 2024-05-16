# Monthly food price YoY inflation in selected countries

South Sudan recorded a year-over-year food price inflation of 363.1% from December 2015 to November 2016, according to the [monthly food price inflation estimates by country](https://microdata.worldbank.org/index.php/catalog/4509#study_desc1684331430702), compiled by Bo Pieter Johannes Andrée for the World Bank since 2008.

This dataset includes YoY food CPI changes from 25 fragile countries. These include Afghanistan, Burkina Faso, Burundi, Cameroon, Central African Republic, Chad, Congo Democratic Republic, Congo Republic, Gambia, Guinea-Bissau, Haiti, Iraq, Lao PDR, Lebanon, Liberia, Mali, Mozambique, Myanmar, Nigeria, Somalia, South Sudan, Sudan, Syrian Arab Republic, and Yemen.

Of these countries, Lebanon recorded the second highest estimate YoY food inflation, with 300.86% during the December 2020 and November 2021 period, followed by Sudan (262.47%, from October 2019 to September 2020).

No other country reached a **three-digit YoY food CPI change** since January 2008.

### Africa

**17 of the 25 countries are located in Africa**. Somalia almost doubled its food prices almost seventeen years ago. Below is the detail of the highest YoY increases per nation:

-	Somalia: 97.72% annual food inflation from July 2007 to June 2008.
-	Nigeria: 77.39% in 2016.
-	Myanmar: 71.26%, between July 2022 and June 2023.
-	Mozambique: 71.25%, from September 2015 to August 2016.
-	Burkina Faso: 61.76%, between August 2021 and July 2022.
-	Chad: 57.35%, from September 2007 to August 2008.
-	Central African Republic: 56.33%, between August 2013 and July 2014.
-	Niger: 42.55%, from July 2022 to June 2023.
-	Burundi: 39.84%, between May 2016 and April 2017.
-	Congo, Democratic Republic: 31.43%, from April 2008 to March 2009.
-	Gambia: 31.4% in 2020.
-	Liberia: 28.78%, between July 2017 and June 2018.
-	Guinea-Bissau: 27.58%, from March 2021 to February 2022
-	Cameroon: 12%, between October 2021 and September 2022.
-	Congo Republic: 11.04% in 2017.

### Rest of the world

Between August 2007 and July 2008, **food prices rose 96.79% in Afghanistan**, while the increase in Myanmar was 71.26% from July 2022 to June 2023. Among the Asian countries, Yemen's CPI food change from March 2021 to February 2020 was 52,32%, Laos' (39,52%, between February 2022 and January 2023), and Iraq's (12,38%, from June 2021 to May 2022).

## Highest food inflation per country (%)
<PlotlyBarChart
  data={{
    url: 'highest_inflation.csv'
  }}
  title="From January 2008 to October 2023"
  xAxis="Country"
  yAxis="Max_yoy_food_inflation"
/>

Haiti is the only country in the Americas included in the dataset. This country, which is currently on the brink of a civil war, recorded year-on-year food inflation of 91.98% in the period from December 2021 to November 2022.

**No countries from Europe or Oceania** have been included in the data compilation.

## YoY food inflation per country
<FlatUiTable
  data={{
    url: 'monthly_data.csv'
  }}
/>

## Average food inflation per country (%)
<PlotlyBarChart
  data={{
    url: 'average_inflation.csv'
  }}
  title="From January 2008 to October 2023"
  xAxis="Country"
  yAxis="Avg_food_inflation"
/>
