**Description:**
The City of Calgary owns thousands of buildings. But which buildings use more energy? More Green energy? (And as a result would have more infrastructure in place to support further renewable energy?). I hope to answer these questions with this simple analysis utilizing PowerBI.

**Findings**
The buildings in the North-East quadrant tended to use the most electrical energy out of all the quadrants, but at the same time used the largest proportion of renewable energy approximately 15%. With the South-West quadrant using the second largest proportion of renewable energy for electricity at approximately 12%.
Although the buildings more recently build in 2020 have had the largest sum of energy use, they have also used a much smaller proportion of natural gas compared to buildings created earlier. Possible explanations would include more buildings being built in the 2020 year as compared to prior years, or more energy usage of government-owned buildings due to our growing population or potentially the initial effects of Covid-19. Further investigation would be necessary.

**Process** 
The dataset was downloaded from the following url: https://data.calgary.ca/Environment/Building-Energy-Benchmarking-Filter-by-Year/g854-u2rj

The data was loaded into PowerBI, and the quadrant (NW,NE,SW,SE) was extracted from the address column into a new column 'quadrant' using PowerQuery.
