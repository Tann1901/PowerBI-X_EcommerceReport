# PowerBI-X_EcommerceReport

## I. INTRODUCTION
In this report, I present an overview of the business performance within the multi-sector E-commerce division spanning from 2016 to September 2018. The report delves into intricate details concerning services, products, customer demographics, and provides an encompassing assessment of the division's activities. 
Additionally, I shall proffer recommendations for areas within the company that warrant improvement and enhancement.
## II. QUESTIONS
Graph for questions
![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/5cf348a1-2440-47f4-b295-f5c0a5833bfd)

## III. DATA UNDERSTANDING
### Entity Table
![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/f4b9ee5b-466f-46fc-af95-ea14478a592e)
![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/7aa62606-f2b7-4307-8a2a-9c6674c82704)

### Attribute
![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/2a9039a5-3111-44cc-b79e-9c8c526607f4)
![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/d6336c60-e1e3-4ebd-bb23-dad7a0579344)
![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/461559d8-677c-4746-9916-c014e6856ca4)

### Entity Diagram
![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/d0eecaca-4917-403b-8d53-23d0df2bb38b)
![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/2687cd52-2abd-427b-8963-627786424460)

## IV. DATA CLEANING

1. Create dataframe
2. Combine tables
3. Check for null and duplicate values
4. Compare the Attribute table to see if there are attribute violations
5. Consider whether eliminating null and duplicate values ​​will affect the payment analysis results
6. Remove values ​​when not affected
7. Combine product and translation tables for analysis in English

![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/5707f976-f1bc-4efe-b95f-a0cb37e2916f)
![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/acb7b344-2458-4864-bb02-97e6072d6eaa)
![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/f4dac6b1-021f-4076-a8cf-402aec18cabf)
![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/e7657721-37c3-4db6-a51c-9bda7b4838ea)
![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/87edab31-c5ea-44f9-b4ed-ce5916de8090)
![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/6da64e76-594a-47f7-9f61-6e500ed0c6d7)
![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/131fc507-e340-498a-84c8-aabc1a78b0dc)
![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/3898d262-d5e4-4a14-889b-aec5767d0ff3)
![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/fa65cc8d-83ee-4a65-8dd0-0bb3070e0512)
![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/9369d33b-a07c-472d-b5a6-67a7fe20e664)
![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/796be6dd-2307-4db7-9a44-bfb3ea564552)


## V. VISUALIZATION AND DATA ANALYZATION
![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/edfacd78-651e-4852-8276-750dbcbf9354)

The chart shows that the product group with a high proportion ranges from 7.06%-8.76%. Reciprocal in value, these groups belong to the average low price level and the payment period is at 3 times. These groups also have high installment rates with an average of 2-4 payments. Average shipping costs range from $16-18.89.

On the contrary, groups with high average prices such as computers, small_appliance_home_oven_and_coffee, home_appliance_2 have a low sales proportion of less than 1%. These groups have an average of 5.5 - 6 payments. Shipping costs range from $36-48

The graph shows highest proportion product group are: health_beauty, bed_bath_table, watch_gifts, computers_accessories, sport_leisure ranging from 7.06%-8.76%. Regarding value, these groups belong to low - medium price group and with average payment settlement at 2-4 times. Average delivery fee at $16-18.9.

In contrast, the group with high value like computers, small_appliance_home_oven_and_coffee, home_appliance_2 having low selling rate at below 1%. Delivery fee is in range $36-48.

![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/e8401573-fa9e-45ab-9d88-78e99d7e91d2)
The chart shows that SP is the leading state with a total order value of 7,546,092, followed by RJ, MG with values ​​of 2,744,633.48 and 2,309,697.32. Top sales with payment value > 1 million are in Brazil, followed by Barinas state of Venezuela and South Carolina in the US with values ​​of 788,505.45 and 778,699.09 respectively. Customers with the highest number of purchases are also located in Brazilian states, corresponding to the above statement about the distribution of order value.

However, regarding the time of the most recent purchase, the parameters show that more than 60.35% of the most recent purchases were over 6 months ago, with only 5.66% of the purchases being made within the last 1 month.

![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/b6bcb60c-b7f9-4a53-8aad-0bfd4e614d03)
Regarding payment services, credit cards account for the highest share with 76.84%. This plan also has many payment installments. Other options include cash, debit and vouchers with rates of 19.92%, 1.99% and 1.24%. These options only apply to 1 payment.

Regarding delivery service, the time from purchase to shipping to customers will mostly be about 2 weeks with 38.5%, 1 week, ... however there are still 4.49% of orders with more than 60 days of delivery.

Correlating with the 1-star rating, we can see that delivery time from 30-60 days has a very high 1-star rate (53.91%), > 60 days will lead to 59.46%.

Unavailable orders belong to the electronics industry, which is also an area that needs attention

![image](https://github.com/Tann1901/PowerBI-X_EcommerceReport/assets/108020327/72ed20fe-f0a9-4010-96d5-8661ae83ef88)
**BUSINESS SITUATION**
- From August 2017 until now, the business situation has developed and grown steadily. Average revenue reaches 1-1.2 million per month.

- The product groups with a high proportion belong to health_beauty, bed_bath_table, watch_gifts, computers_accessories, sport_leisure ranging from 7.06%-8.76%

- On the contrary, groups with high average prices such as computers, small_appliance_home_oven_and_coffee, home_appliance_2 have a low sales proportion of less than 1%.

**OPERATE**
- The operating process has all the basic steps. purchase _ approve_delivery to carrier_ ship to customer.

- Payment services are quite diverse, meeting customer needs

- Delivery time needs to be improved, as 4.49% of orders have more than 60 days of delivery.
## VI. RECOMMENDATIONS
- Customers who bought more than 6 months ago account for the highest rate - 60%. We need to consider these customers and ask the customer service department to investigate to find the cause.
- Focus on developing products with low and medium price segments, because customers in these two segments account for a large proportion. High value items will come with high shipping costs and slower payback times (longer payment phasing)
- Focus on market development and implementing marketing campaigns in South America to create a loyal customer network in this region.
- Minimize Cash in payment to ensure safety in shipping. Focus more on one-time payments or online payments to ensure capital recovery.
- Can improve shipping (cooperating with many shipping companies, adding transit warehouses for items with high transit times) thereby helping to improve delivery times to increase customer satisfaction
