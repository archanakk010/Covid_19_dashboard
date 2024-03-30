# COVID-19 DASHBOARD
This Power BI project analyzes COVID-19 data across four pages: World, Country_Latest, Month_Overview and USA Report. Each page offers insights into cases and related aspects, enabling users to understand the pandemic's impact comprehensively.

### Steps in Creating the COVID-19 Dashboard:
#### 1. Importing COVID-19 Dataset:
Begin by importing the COVID-19 dataset from a reliable source into Power BI.

####  2. Data Cleaning:
Utilize Power Query Editor to perform essential data cleaning tasks on the COVID-19 dataset. This includes removing duplicate records, adjusting data types, and handling any missing or null values.

####  3. Establishing Relationships:
Establish relationships between different tables within the COVID-19 dataset to facilitate meaningful analysis across related data fields, such as connecting tables for cases, deaths, recoveries, and geographical regions.

#### 4. Creating Measures:
Generate calculated measures within Power BI to perform necessary calculations and aggregations on the COVID-19 data. This may include metrics such as daily new cases, fatality rates, recovery rates, and percentage changes over time.

####  5. Creating and Customizing Dashboard:
Develop the interactive dashboard with multiple pages, each focusing on different aspects of COVID-19 analysis. Customize the dashboard with appropriate visuals, such as line charts, bar graphs, and tables, to effectively convey insights into case trends, geographical distributions, demographic patterns, and other relevant aspects of the pandemic.


## Pages in Dashboard
### 1.WORLD
This page provides an overall view of world.


![Screenshot (716)](https://github.com/archanakk010/Covid_19_dashboard/assets/132830280/d4a22197-324c-4b03-8bb3-67e59ae200b0)


#### ✅ Slicer

Slicer is provided on this page based on Country/Region


#### ✅ Cards

Cards provide the simplest method for representing individual aggregate values. Here, cards displaying Total Confirmed Cases, Total Deaths, Critical Cases, Active Cases, Cases per Million, Deaths per Million, Total Tests, Tests per Million, and Total Recovered are provided.

#### ✅ Donut Charts

The dashboard features two interactive donut charts that visually represent the distribution of 'Active Cases By Continent' and 'Critical Cases By Continent'. These charts offer insights into the geographic distribution of active and critical COVID-19 cases across different continents. Users can interact with the charts to explore the proportion of cases in each continent, helping to understand the regional impact of the pandemic. By visualizing this data, the dashboard facilitates a clearer understanding of how the pandemic is affecting various parts of the world.


#### ✅ Clustered Column Chart

This clustered column chart visualizes COVID-19 data across continents, displaying total cases, total recovered, and total deaths. It provides a comparative view of these metrics, enabling users to understand the distribution of cases, recoveries, and fatalities across different continents.

#### ✅ Clustered Bar Chart

This clustered bar chart presents the number of COVID-19 tests conducted across different continents. Each bar represents a continent, and the height of the bar corresponds to the total number of tests conducted in that continent. This visualization offers a comparative analysis of testing efforts globally, allowing users to discern testing trends and disparities across continents.



#### ✅ Map

This map visually illustrates the spread of COVID-19 cases across continents, with each continent represented by bubbles whose sizes indicate the total number of cases recorded in each region. This visualization provides an intuitive overview of the global distribution of COVID-19 cases, enabling users to quickly discern regions with higher or lower case counts.


### 2.COUNTRY_LATEST
This page provides an overall view of Country_Latest.


![Screenshot (713)](https://github.com/archanakk010/Covid_19_dashboard/assets/132830280/8203246a-1f46-438c-a31e-4890e1fa4266)


#### ✅ Cards

Cards offer a straightforward way to present individual aggregate values. In this dashboard, cards display the following COVID-19 metrics: Confirmed Cases, New Cases, Deaths, Fatality Rate, New Deaths, Recovered, Recovery Rate, and New Recovered.



#### ✅ Clustered Column Chart

This clustered column chart visualizes COVID-19 cases analysis by country/region, displaying the metrics of Confirmed, Recovered, and Deaths. Each country/region is represented by a clustered column, allowing for easy comparison of these key metrics across different regions. This visualization provides insights into the distribution and impact of COVID-19 across various countries/regions.



#### ✅ Area Chart

This area chart illustrates the progression of recoveries and deaths among confirmed COVID-19 cases over time. The chart tracks the number of recovered cases and deaths as a proportion of confirmed cases, providing insights into the recovery and mortality rates associated with COVID-19 infections.



#### ✅ Donut Charts

'Death by WHO Region': This donut chart visualizes the distribution of COVID-19-related deaths across different WHO regions. Each segment represents a WHO region, with the size of the segment proportional to the number of deaths recorded in that region. This visualization offers insights into the regional impact of COVID-19 mortality.

'Recovered by WHO Region': This donut chart illustrates the distribution of COVID-19 recoveries across WHO regions. Similar to the previous chart, each segment represents a WHO region, with the size of the segment indicating the number of recoveries in that region. This visualization provides an overview of the regional recovery rates from COVID-19.

#### ✅ Table

This table presents COVID-19 cases in various countries, featuring columns for Country/Region, Confirmed Cases, Recovered Cases, Deaths, and WHO Region. It offers a comprehensive overview of key COVID-19 statistics across different regions, facilitating easy comparison and analysis of case counts, recoveries, and fatalities.

####  ✅ Map

This map visualizes COVID-19 deaths by country/region, with the size of each bubble representing the number of deaths recorded in that area. The visualization offers a clear and intuitive overview of the distribution of COVID-19 fatalities globally, enabling users to quickly identify regions with higher or lower mortality rates.

### 3.MONTH_OVERVIEW
This page provides an overall view of Month_overview.


![Screenshot (714)](https://github.com/archanakk010/Covid_19_dashboard/assets/132830280/a2b8176c-6de5-4010-b686-85e29da39bbc)


#### ✅ Cards

In this dashboard features cards displaying key COVID-19 metrics for monthly analysis. These include Confirmed Cases, New Cases, New Deaths, Fatality Rate, New Recovered, and Recovery Rate. 

#### ✅ Tables

This table presents COVID-19 cases recorded in different months. It contains columns for the month, along with the number of confirmed cases, recoveries, and deaths. This tabular representation allows users to easily compare and analyze COVID-19 data across various months, providing insights into the progression of the pandemic over time.



#### ✅Line Chart

The "Deaths and Recoveries by Confirmed Cases" line chart provides a visual representation of how the number of deaths and recoveries in COVID-19 cases evolves over time in relation to confirmed cases.

#### ✅Stacked Column Chart

This stacked column chart presents an analysis of COVID-19 cases over different months, displaying the metrics of confirmed cases, recoveries, and deaths. Each column represents a month, with segments stacked on top of each other to depict the distribution of confirmed cases, recoveries, and deaths within that month. This visualization offers insights into the monthly trends of COVID-19 cases, highlighting the progression of the pandemic and the outcomes over time.


#### ✅Area Chart

This area chart visualizes the daily analysis of new COVID-19 cases, recoveries, and deaths. Each day is represented on the x-axis, with the corresponding number of new cases, recoveries, and deaths depicted on the y-axis. The chart's area plot provides a clear comparison of the daily fluctuations in new cases, recoveries, and deaths, offering insights into the progression of the pandemic over time.


### 4.USA REPORT
This page provides an overall view of USA Report.


![Screenshot (715)](https://github.com/archanakk010/covid_19_test/assets/132830280/bee82947-a35b-4173-b17b-052a2c061dd8)

#### ✅ Cards

In this dashboard, cards are used to display key metrics regarding COVID-19 such as fatality rate, total deaths, and confirmed cases.


#### ✅ Donut Chart

his donut chart visually illustrates the distribution of death cases across various Province/State regions in the USA. Each segment of the donut corresponds to a specific Province/State, with the size of the segment indicating the number of deaths recorded in that region. By providing a succinct overview of the distribution of death cases, this visualization enables users to swiftly identify regions with varying mortality rates.


#### ✅ Table

This table presents COVID-19 cases across the United States, displaying data for each province/state. The table includes columns for Province/State, Confirmed Cases, and Deaths, providing a detailed breakdown of COVID-19 statistics within the USA.

#### ✅ Line Chart

This line chart illustrates the trend of confirmed COVID-19 cases and deaths across different provinces/states. This visualization provides insights into the progression of the pandemic within specific geographical areas, highlighting variations in case counts and mortality rates over time.



####  ✅ Map

This map visually depicts the distribution of confirmed COVID-19 cases and deaths across various provinces/states. The size of each bubble on the map represents the number of deaths recorded in that particular province/state, providing a clear visualization of the severity of the pandemic in different regions.
