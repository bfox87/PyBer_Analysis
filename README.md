# Analysis of PyBer Rideshare Data by City Type

## Overview:
PyBer, a ride sharing company, has collected ride and city data from the markets they serve. The purpose of this analysis is to summarize how the data differs by city type (urban vs. suburban vs. rural) and describe how these insights can be used by upper management at PyBer. The plan is that upper management will use this analysis and the accompanying visualizations to help improve access to ride-sharing services and determine affordability for under-served neighborhoods.

## Results:
- **Total Rides**:
    - With 1,625 rides, urban markets/cities comprise a little over two-thirds of PyBer's business. Suburban cities take a little over a quarter with rural markets just 5% with only 125 rides.
- **Total Drivers**:
    - Urban cities take an even larger share of PyBer's drivers (81%) than they do with rides. Suburban cities and rural cities have much smaller driver counts with 490 (16.5% of total) and 78 drivers (2.6% of total) respectively.
    - This means the driver imbalance between city type is much greater than it is for rides.
- **Total Fares**:
    - The breakdown of total fares by city type is somewhat similiar to that of total rides. Urban markets have a little under $40k in fares which takes 63% of the total.
    - Suburban total fares ($19.3k) are roughly 30% of the total with rural fares ($4.3k) coming in around 7% of the overall total.
    - This means that while the imbalance between urban, suburban, and rural still exists for total fares, the percentages are not as imbalanced as they are for total rides or total drivers.
- **Average Fare per Ride**:
    - Rural markets have the highest avg fare per ride at $34.62 followed by suburban markets at $30.97 and urban cities at $24.53
    - It makes logical sense that cities/towns classified as rural or suburban are more spread out meaning the average ride distances are likely greater.
    - Longer ride distances should translate to more costly rides so higher fares.  
- **Average Fare per Driver**:
    - Like with average fare per ride, rural markets lead with a $55.49 average fare per driver, followed by suburban at $39.50 and urban at $16.57
    - This difference between city types is even more pronounced than it was for average fares per ride.
    - This more pronounced difference is due to the lack of drivers, particularly in rural markets.

![PyBer_city_type_summary](https://github.com/bfox87/PyBer_Analysis/blob/main/analysis/PyBer_city_type_summary.png)

- **Total Fare by City Type**:
    - Total fares by week in urban cities mostly ranges betwen $2,000-$2,500; suburban markets between $1,000-$1,500 with a few exceptions; and rural markets between $50-$500.
      - There were a few weeks where rural markets had total fares less than $100. 
    - As the chart below shows, weekly total fares by city type never once cross paths. For example, suburban cities always had more fares than rural cities from January 1, 2019 through April 28, 2019.
    - While there are similarities in weekly trends between city types, its hard to pinpoint much beyond a week in mid-February where total fares in each city type spiked, but then dropped back down a week later.

![PyBer_fare_summary](https://github.com/bfox87/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary:
As one would expect, PyBer's rideshare business is centered in the urban markets. Urban cities often have higher population densities and lower personal car use, meaning a higher need for rideshare services. However, PyBer needs to focus on improving accessibility to rural and suburban markets if the company wishes to grow.

### First Recommendation:
Offer drivers in rural areas a financial incentive to offset for the low number of rides they'll have. Some sort of base compensation or a higher per ride cut should entice more drivers to join and remain despite fewer customers and increased competition from other new drivers. Our analysis is revealing we have a lack of drivers in these markets. PyBer cannot get more demand in these cities if customers don't see available drivers nearby when they open our app.
### Second Recommendation:
Offer riders in rural and even suburban markets a discount on ride fees. These riders likely have longer ride distances and the costs of these longer rides could be a disincentive to repeat business. PyBer will make less money per ride, but increased overall revenues is the goal.
### Third Recommendation:
Conduct an advertising campaign in rural and suburban markets to highlight our push to increase access and affordability to customers while also highlighting our plan to help driver compensation. The campaign should result in more driver supply and ride demand. This will be a financial investment, but worth it when driver supply and ride demand increase. Then at that point, PyBer will have some momentum due to word-of-mouth advertising amongst people.
