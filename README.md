# Housing-and-Rental-Analysis
Data Challenge

Project Objective: Given the datasets from Zillow and AirBnB, identify the top five zipcodes in New York that would maximize ROI in the shortest amount of time. These zipcodes would then be recommended to purchase real estate properties that would function as rental properties on AirBnB.

Project Assumptions: 
1. Occupancy rate is capped at 75%
2. Each real estate property is available for 365 days of the year
3. The investor will pay for the property in cash (no mortgage/interest rate)
4. The time value of money discount rate is 0%
5. All properties and square feet within each locale can be assumed to be homogeneous
6. Only two bedroom properties were analyzed by request of the customer

Data: were provided by Capital One through publically available information (Zillow and AirBnB).

Data Analysis Procedure: 
1. Clean Zillow Data and focus only on NY properties
2. Clean AirBnB Data and focus only on two bedroom properties
3. Join the two datasets using zipcodes as the common factor
4. Calculate the Break-Even period and ROI timeframe
5. Identify the top five zip codes to invest in

Findings:
1. Neighborhoods in Queens (11434) Staten Island (10303, 10306, 10304) and Brooklyn (11234) were found to have the highest ROI and shortest break-even period
2. These neighborhoods were the minority and further analyses would be needed to validate our findings
3. Manhattan showed the highest density of rental properties as well as nightly prices

Next Steps:
1. Determine if the quantitative results of ROI is the sole purpose of rental properties
2. Evaluate possibility of long term investments in Manhattan 
3. Be aware that the asusmptions made in this analysis may become null in the future 
