# Customer Acceptance of Coupons

Location of Pratcical Application 1 Repository: [https://github.com/sushikshit79/MLAIPA1/blob/main](https://github.com/sushikshit79/MLAIPA1/blob/main)

## Goal
The goal of this application is to determine whether a customer will accept or reject a specific type of coupon based on various criteria.

## Data
This data is from the UCI Machine Learning Repository and was collected via a survey on Amazon Mechanical Turk. This data sheet is obtained through **Practical Appliction 1** resource link.

### Summary of Data
The coupons data sheet has 12684 entries and 26 columns.

The data provides information on below coupons with various acceptance criteria and the decision of the customer. 
- Coffee House
- Restaurant(<20)
- Carry out & Take away
- Bar                   
- Restaurant(20-50)

Several factors can influence the customers decision to accept coupons. Like the destination direction and distance of destination, income, age , marital status, temperature and type of passengers they are travelling with.

## Data clean up
The dataset contains 12,684 records. The Cars column has 12,576 missing values, making it largely inconsequential for analysis. Hence I removed the column from data

Columns such as Bar, Coffeehouse, Carryaway, RestaurantLessThan20, and Restaurant20To50 together account for 794 missing values, which is about 6% of the dataset.Hence deleted the entries that has missing values.

## Data Observation

### High Level observations

 - After cleaning the number of entries are: 12079
 - Number of accepted coupons: 6877
 - Proportion of accepted coupons: 56.93%
 - Total number of rejected coupons: 5202
 - Accepted 788 Bar coupons from 1913 with acceptance rate of 41.19%
 - Accepted 1682 Carry out & Take away coupons from 2280 with acceptance rate of 73.77%
 - Accepted 1894 Coffee House coupons from 3816 with acceptance rate of 49.63%
 - Accepted 632 Restaurant(20-50) coupons from 1417 with acceptance rate of 44.6%
 - Accepted 1881 Restaurant(<20) coupons from 2653 with acceptance rate of 70.9%The 
 - The highest rate of acceptance is for coupons **Carry out & Take away** & **Restaurant(<20)**

##### Visualizations for High Level observations
![Coupon counts for different coupons](https://github.com/sushikshit79/MLAIPA1/blob/e10a92badddefdd89009e1cb0007c749d50c4772/images/couponcount.png)


![https://github.com/sushikshit79/MLAIPA1/blob/78c4d993f65ecf710ef330c0b30c1018e5edc976/images/coupons_presented_accepted_Rejected.png](https://github.com/sushikshit79/MLAIPA1/blob/78c4d993f65ecf710ef330c0b30c1018e5edc976/images/coupons_presented_accepted_Rejected.png)

#### Visulization of temperature column
![https://github.com/sushikshit79/MLAIPA1/blob/bec640ed02e1ad8c11737f89a2cae32a30351df2/images/temperature.png](https://github.com/sushikshit79/MLAIPA1/blob/bec640ed02e1ad8c11737f89a2cae32a30351df2/images/temperature.png)

### Subplots

#### Bar Coupon observations
- Bar coupons are mostly accepted by drivers who are travelling alone and between ages 21 and 35
- Bar coupons are accepted more when the distance is less than 5 mins and 15mins
- [Subplot for Bar Coupon](https://github.com/sushikshit79/MLAIPA1/blob/main/images/Bar_coupons_subplot.png) (Image inline)


#### Carry out and Take away coupon observations
- Carry out and Take away are the coupons that are accepted the most
- Bar coupons are mostly accepted by drivers who are travelling alone and also friends are accompanying as passengers
- [Subplot for Carry out & Take away coupon](https://github.com/sushikshit79/MLAIPA1/blob/main/images/Carry%20out%20%26%20Take%20away_coupons_subplot.png) (Image inline)

#### Coffee House Coupon observations
 -  Coffee house coupons acceptance is much higher when temperatures are high as compared to low and moderate temperatures
 -  Driver mostly accept coupons when they are alone or having friends as passengers
 - [Subplot for Coffee House Coupon](https://github.com/sushikshit79/MLAIPA1/blob/main/images/Coffee%20House_coupons_subplot.png) (Image inline)

#### Restaurant(<20) coupon observations
- Restaurant(<20) are coupons that are accepted the most after carry out and take away coupons
- Acceptance rate for drivers riding alone is very high compared to when drivers have passengers
- [Subplot for Restaurant(<20) Coupon](https://github.com/sushikshit79/MLAIPA1/blob/main/images/Restaurant(%3C20)_coupons_subplot.png) (Image inline)

#### Restaurant(<20) coupon observations
- Acceptance rate for drivers riding alone is very high compared to when drivers have passengers
- [Subplot for Restaurant(20-50) Coupon](https://github.com/sushikshit79/MLAIPA1/blob/main/images/Restaurant(20-50)_coupons_subplot.png) (Image inline)
