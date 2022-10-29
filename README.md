# Citibike 2022 Middle of Winter vs. Middle of Summer Analysis

## William Vann 

### Description and Methodology

For this project I was interested in analyzing Citibike NYC data for the middle of winter vs. the middle of summer 2022. As such, I sampled 100,000 ride observations from January 2022 and 100,000 ride observations from July 2022.  In both cases, I limited my sample to cleaned data with no missing values.  

Each month's csv was loaded into a Jupyter notebook and rendered into a pandas dataframe. NA values were dropped along the index axis, categorical-friendly columns were cast as category data types, and datetime-friendly columns were cast as datetime64 and timedelta64 data types.  

This data wrangling enabled interesting Tableau visualizations of total rides, average ride length, and ride start hour distribution. Differences based on bike type and membership status were included in the visualizations.  Maps of all bike stations - and the most popular bike stations for the month analyzed - were generated. Each month analyzed includes a dashboard and a story.   

### Principal Findings

#### 1. Classic bikes vs. Electric bikes

My analysis reveals that **electric bikes are more popular in January than in July** (about 43% of total rides in January vs. only 24% of total rides in July). One reason could be the colder temperatures, leading riders to choose a faster mode of transportation and one less likely to result in a sweaty arrival at their destination. 

#### 2. Member vs. Non-member

The data suggest that while members are responsible for the overwhelming majority of rides in each month analyzed, **non-members take longer duration trips on average**. This may be due to a greater share of bike commuters with "regular routes" being members, and perhaps more tourists and sight-seers with "irregular wanderings" in the non-member category.   

#### 3. Start Hours

The busiest start hours are consistent among both months (noon-7pm in January, and noon-8pm in July). Curiously, there is a sizeable swath of riders starting their journeys in the **8am hour in January**. I speculate that this may be due to a bike commuter effect.  

#### 4. Top Stations

While in general most of the busiest stations are in the Midtown and Downtown sectors of the city, it is interesting that **in July stations nearer to the Hudson River become much more active**.  This is most likely explained by the appeal of the riverfront parklands and trails for summer riders. 


### Files

```JANUARY 2022 CITIBIKE.twbx```

```JULY 2022 CITIBIKE.twbx```
