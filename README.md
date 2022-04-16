# Amazon_Vine_Analysis
## Project Overview
The project we will use Pyspark to perform ETL process to get data that we chose to analyze from amazon database. I chose the video games database and provide some analysis. Based on the reviews given, I would like to determind if there is favorable review bias from vine members. 

## Results
- How many Vine reviews and non-Vine reviews were there?
We have total 40,565 reviews of the video games dataset. There are 40,471 are non-vine reviews and 94 are vine reivews. 

![vine-review](https://user-images.githubusercontent.com/94089680/163692287-3dcee08f-f90c-466c-af68-4f6ff019fddb.png)

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
The total five stars reviews are 15,711. We have 48 vine reviews are 5 starts and 15,663 reviews are non-vine reviews. 

![five-star](https://user-images.githubusercontent.com/94089680/163692230-c515599b-33dc-4645-9b74-e79ac329bf9e.png)

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
In this dataset, we have about 38.73% 5 stars reviews in total reviews. About 51.06% are vine reviews and 38.70% are non-vine reviews. 

![percentage](https://user-images.githubusercontent.com/94089680/163692283-9de183bf-534c-4398-bfb5-6ccbc1de94b6.png)


## Summary
After analyzed this project. There are about 51.06% reviews in the vine program. Meanwhile only 38.70% reviews are not in the vine program. In this case, we have positivity bias for the Vine program. 
In addition to the analysis, we could use some machine learning apply to the analysis by calculating the p-value and statistical distrubution of the 5 stars reviews between the vine program and non-vine program.

