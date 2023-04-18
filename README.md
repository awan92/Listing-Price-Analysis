# Listing Price in Kuala Lumpur Analysis
Variabel data that be used are Price, rooms, bathrooms, car parks and size (numeric data) because all those variables will describe how properties vary between neighborhood and also to know distribution properties prices and size in KL
- Tools : Google Sheets

## Descriptive Analysis
Create statistical Meauserement to know the data distribution :

![Statistic meauserement](https://user-images.githubusercontent.com/100940506/232831527-d05b841e-acff-4885-8941-b91f1a254314.PNG)

- **Price:** High and positively skew data, range is to high and no missing data anymore.
- **Rooms:** No missing data anymore.
- **Bathrooms:** No missing data anymore.
- **Car Parks:** High and positively skew data and no missing data anymore.
- **Size:** High and positively skew data and no missing data anymore.

## Exploratory Data Analysis, Insight and Recommendation
**Top 3 Listings based on Numbers of Properties in Kuala Lumpur

![Top 3 listings based on number](https://user-images.githubusercontent.com/100940506/232835657-c0d54986-4dea-4fc8-bb8c-a45ce00a6766.PNG)

Top 3 Location (Based on the **Number of Properties**) in Kuala Lumpur are **Mont Kiara**, **KLCC** and **Bukit Jalil**.
- **Mont Kiara** : This location have 378 properties in total, Avg. Price of the properties in here is 1,805,915 RM. Avg. rooms 4, Avg. bathrooms 4, Avg. Car Parks 2, majority property are condominium type, most of the area still built up, Avg. size in this area 2,218 sq.ft. and most of the properties still in partly furnished. 
- **KLCC** : This location have 310 properties in total, Avg. Price of the properties in here is 2,064,280 RM. Avg. rooms 3, Avg. bathrooms 3, Avg. Car Parks 2, majority property are serviced recidence type, most of the properties still built up, Avg. size in this area 1,626 sq.ft. and most of the properties has been furnished.
- **Bukit Jalil** : This location have 177 properties in total, Avg. Price of the properties in here is 994,838 RM. Avg. rooms 4, Avg. bathrooms 3, Avg. Car Parks 2, majority property are condominium type, most of the properties still built up, Avg. size in this area 1,552 sq.ft. and most of the properties still in partly furnished. 

**Insight and Recommendation:**
- Customers can buy properties in Mont Kiara, KLCC and Bukit Jalil if You want to have lots of neighbor (have much property listing)
- Customers can buy properties in Bukit Kiara, Chan sow lin and Pandan indah if you need quiet place (seldom of property listing)
- Total property in Top 3 based on number of properties from 177 - 378 property
- Total property in Bottom 3 based on number of properties only 1, all of them have 1 property listing in Kuala Lumpur 

**Top 3 Listings based on the Highest Price in Kuala Lumpur

![Top 3 Properties based on the highest price](https://user-images.githubusercontent.com/100940506/232838125-696a3a96-bb8e-4c6a-bb97-89a4f182bd06.PNG)

Top 3 Location (Based on the **Highest Price**) in Kuala Lumpur are **Bukit Kiara**, **Sri Hartamas** and **Mid Valley City**.
- **Bukit Kiara** : This location have 1 properties in only, Avg. Price of the properties in here is 4,467,122 RM. Avg. rooms 5, Avg. bathrooms 5, Avg. Car Parks 4, The property still built up, Avg. size in this area 4,422 sq.ft. and the property are 4-sty Terrace/Link House (Intermediate) type. 
- **Sri Hartamas** : This location have 36 properties in total, Avg. Price of the properties in here is 3,141,111 RM. Avg. rooms 5, Avg. bathrooms 5, Avg. Car Parks 3, Most of the properties still built up, Avg. size in this area 3,713 sq.ft. and majority property are Semi-detached House type. 
- **Mid Valley City** : This location have 2 properties in total, Avg. Price of the properties in here is 2,175,000 RM. Avg. rooms 4, Avg. bathrooms 4, Avg. Car Parks 1, The property still built up, Avg. size in this area 2,250 sq.ft. and the property are condominium type. 

**Insight and Recommendation:**
- Customers can buy properties in Bukit Kiara, Sri Hartamas and Mid Valley City to get the highest average price properties in Kuala Lumpur
- Customers can buy properties in Desa Petaling,Pandan perdana and Jinjang  to get the lowest average price properties in Kuala Lumpur
- Range price of Top 3 properties based on average price from RM 2,000,000 - RM 4,500,000
- Range price of Bottom 3 properties based on average price from RM 240,000 - RM 300,000

## Correlation

![Correlation](https://user-images.githubusercontent.com/100940506/232840383-5bcb6a5f-a09b-492d-96c9-e6595437b22f.PNG)

**Result and Insight:**
- Variable **Size** has the strongest correlation to **Price** with 0.9
- All variables have very strong correlation each other from 0.74 - 0.9
- All variables are significant between each other variable in the population because all of them have **p-value** 0 and **correlation** ≠ 0

## Regression

![Regression](https://user-images.githubusercontent.com/100940506/232842381-598325d2-e09d-4a5e-a41d-e2d878075e7e.PNG)

**Result and Insight:**
- **Partial Test:** Bathrooms, Car Parks and Size have **significant coefficient** indicated by the **p-value** < 5%
- **Partial Test:** Rooms **does not have significant coefficient** indicated by the **p-value** > 5%
- **Simultaneous Test:** However, the overall effect is significant, meaning that the 4 independent variables together have significant coefficient in explaining Price, which is indicated by the p-value of F-test < 5%
- The **R Square** is 96.68%, meaning there are 96.68% variation of residual price data can be explained by its 4 predictor variables

**Regression Model:**

**Price:** 2033.8641367923**Rooms** + 55070.4379189503**Bathrooms** + 103645.34868642**Car Parks** + 609.263631905788**Size**
