# surfs_up
## Introduction
Purpose of this analysis was to determine if the surf and ice cream shop business is sustainable year-round. To find this solution I queried the temperatures for the months of June and December from 2010 to 2017, using the hawaii.sqlite file. Then I saved the results into a dataframe and use .describe() to get the statistics of the temperatures for those months.
## Results

![june_temp](https://user-images.githubusercontent.com/56700719/155850907-ebfcdf9e-f31a-4d91-9674-4960b32a9394.JPG)
![dec_temp](https://user-images.githubusercontent.com/56700719/155850910-8cba4ba2-fa46-448a-a4c2-513f89e3f619.JPG)



- The difference between the mean temperatures for June (74.94 degrees) and December (71.04 degrees) is only 3 degrees.
- Lowest temperature recorded in December was 56 degrees, making too cold for surfing.
- On the other hand, the lowest 25 percentile for December temperatures is 69 degrees, warm enough for surfing and ice cream.
## Summary
Looking at these results, the surf and ice cream shop business would be sustainable year-round. While the temperature does drop in December, it remains relatively warm enough for people to go out for ice cream and surfing at the beach, but there are a couple more concerns that I wanted to consider.

![avg_dec_temp](https://user-images.githubusercontent.com/56700719/155850838-93e03524-c211-4035-ad57-202dc191ad98.JPG)

With the differences in the December percentile and the min and max I wanted to take a closer look at the average temperature in December for each year. For each year, the average temperature in December is consistently around 70 degrees.

![avg_dec_precip](https://user-images.githubusercontent.com/56700719/155850937-f9915124-5ac5-45fa-8e3a-8c938958e5f4.JPG)
![avg_june_precip](https://user-images.githubusercontent.com/56700719/155850943-d8a8ef82-eeaa-4c40-8e9e-c2a6867f1750.JPG)

Then I took a closer look at the precipitation for each year in December and comparied it to the precipitation for each year in the month of June. Some years there appears to be more precipitation in December and in other years there appears to be more precipitation in the month of June.

Overall I would determine that the surf and ice cream shop business would be sustainable year-round.

