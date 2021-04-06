# PyBer Analysis Overview
PyBer is a ride sharing company looking to improve access to their services and determine affordability for underserved neighborhoods. To that end, I have analyzed all rides taken from January through May of 2019 to look for trends in available drivers and fares charged in rural, suburban, and urban cities.

## Results
We can see an overview of the data in a scatterplot where the size of the circles indicates the number of rides taken in the city.
![Fig1](https://github.com/kaileymd/PyBer-Analysis/blob/main/analysis/Fig1.png)

This is a lot to take in, so let's break it down.

### Number of Rides

<img src="https://github.com/kaileymd/PyBer-Analysis/blob/main/analysis/Fig2.png" width="400"/> <img src="https://github.com/kaileymd/PyBer-Analysis/blob/main/analysis/Fig6.png" width="500"/>

As we might expect, the urban cities have the highest number of rides taken, and rural cities have the fewest. However, while the median of the urban and suburban cities is roughly in the middle of their data, indicating a fairly symmetric distribution of the data, that is not true for the rural communities. The location of its median tells us that most of the rural cities have 6 or fewer rides taken during this time.

### Fare Rates

<img src="https://github.com/kaileymd/PyBer-Analysis/blob/main/analysis/Fig3.png" width="400"/> <img src="https://github.com/kaileymd/PyBer-Analysis/blob/main/analysis/Fig5.png" width="500"/>

The box and whisker chart shows us that the fare rates across cities are similar, with urban rates averaging slightly lower and rural rates slightly higher.

### Number of Drivers

<img src="https://github.com/kaileymd/PyBer-Analysis/blob/main/analysis/Fig4.png" width="400"/> <img src="https://github.com/kaileymd/PyBer-Analysis/blob/main/analysis/Fig7.png" width="500"/>

Especially when compared to the percentage of total rides and percentage of fares, the number of urban drivers both outnumbers and exceeds expectations for total percentage of drivers. The size of the boxes in the box and whisker chart show that suburban and rural cities tend to have similar numbers of drivers across their city type, whereas the number of drivers in the urban city can vary a lot more - from the average amount of drivers a rural city has up to 7x a rural city's maximum driver number.

## Conclusion
<img src="https://github.com/kaileymd/PyBer-Analysis/blob/main/analysis/PyBer_City_types.png" width="600"/>

Considering the disproportionately high number of urban drivers, we can conclude that the average fare per driver for urban cities is so low because of market competition. However, with such disparate average fares per driver, how does average fare per ride maintain its consistency across city type? We can conclude that rural and suburban drivers provide more rides than the average urban driver while charging roughly the same price, thus increasing their personal gain while not impacting the fare per ride.

#### What are possible ways to increase affordability in underserved cities?

1. Hire more drivers in those areas. More drivers increased competition in urban cities, which have the lowest average ride fare.
2. Set a standard ride fare and compensate drivers per hour independently. If the goal is to lower the rate without harming drivers, an alternative payment scheme like this may be necessary.
3. Offer a special program to urban drivers to pay them more to provide services to an underserved city. Since the average fare per driver is so low amongst urban drivers, this has the potential to be a popular way for them to make more money and increase driver availability in other city types.
