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



 
