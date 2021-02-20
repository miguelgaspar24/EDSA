# Project Assignment

## Introduction

The LaGoste Stores is a well-established company operating in the fashion, sports and luxury sector. Presently they have around 300,000 registered customers and serve more than
1.000.000 consumers a year. They sell products from 5 major categories: Sneakers, Rackets, T-Shirts, Watches and Hats. These five categories can be also be divided in Premium
Brand material and more mainstream articles. The Customers can order and acquire those products through 3 channel groups: Physical stores, quaterly catalogs and the companies’
website. Globally, the company had solid revenues and a healthy bottom line in the past 5 years, but the profit growth perspectives for the next 2 years are fickle. A few
strategic initiatives are being considered to invert the situation. One of those is a Marketing efficiency program to improve marketing activities with a special focus on
boosting tremendously the efficiency of the marketing campaigns.

## Objective

The objective of the team is to build a predictive model that will produce the highest profit for the next direct marketing campaign of the company – the sixth campaign this
year that is scheduled for next month. The campaign aims at selling a new product to the customer database (potential of 250,000 customers). To be able to build the predictive
model, a pilot campaign was carried out. A sample of 2.500 customers were contacted by mail regarding the acquisition of the product. During the next 2 months, the customers
who bought the offer were tagged with a 1 whereas the non-respondents were tagged with a 0. The total cost of the sample campaign was 2.500 contacts * 4€, for a total of
10.000€. Around 12.5% of Customers accepted the offer (which is quite good), each contributing with 20€ of revenue. Overall, the campaign had a negative profit of around
-3.750€. (This can vary slightly by group dataset). The idea is to develop a model that predicts customer behavior and apply this model to the rest of the customer base.
Hopefully the model will allow the company to cherry pick the customers that are most likely to purchase the offer, while leaving out the non-responders, making the next
campaign highly profitable.

## Dataset
The dataset includes the following variables:

| Variable | Description |
| -------- | ----------- |
| AcceptedCmp1 | Flag indicating customer accepted offer in campaign 1 |
| AcceptedCmp2 | Flag indicating customer accepted offer in campaign 2 |
| AcceptedCmp3 | Flag indicating customer accepted offer in campaign 3 |
| AcceptedCmp4 | Flag indicating customer accepted offer in campaign 4 |
| AcceptedCmp5 | Flag indicating customer accepted offer in campaign 5 |
| Complain | Flag indicating if customer has complained |
| Custid | Customer ID |
| DepVar | Binary variable indicating if customer accepted (1) or not (0) a marketing offer from current campaign. Dependent variable of the problem. |
| Dt_Customer | Date of customer's enrolment with the company |
| Education | Level of education of Customer |
| Income | Yearly Income of household of Customer |
| Kidhome | Number of kids in household |
| Marital_Status | Marital Status of Customer |
| MntSneakers | Amount spent on Sneakers |
| MntRackets | Amount spent on Rackets |
| MntTShirts | Amount spent on Tshirts |
| MntWatches | Amount spent on Watches |
| MntHats | Amount spent on Hats |
| MntPremium_Brand | Amount spent on Premium material |
| NumCatalogPurchases | Number of purchases made through catalog |
| NumStorePurchases | Number of purchases made through store |
| NumDealsPurchases | Number of purchases made with discounts |
| NumWebPurchases | Number of purchases made through web |
| NumWebVisitsMonth | Average number of web visits a month to the company site |
| Recency | Number of days since last purchase |
| Teenhome | Number of teenagers in household |
| Year_Birth | Customer's Year of birth |
