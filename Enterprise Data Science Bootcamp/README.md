# Project Assignment

## Introduction

Recommender systems are one of the most prominent examples of machine learning nowadays. They determine what shows up in your Facebook news feed, in what order products appear
on Amazon, what videos are suggested in your Netflix account, as well as countless other examples. Recommendation Systems are used in a variety of areas including movies,
music, news, books, research articles, search queries, social tags, and products in general. The goal of a recommendation engine is to recommend relevant items to a user, based
on historical data.

## Objective

The customer we are working with is a multi-national company that works on the health sector. They want to predict what products their customers shall need the most, based on
their past purchases but also on other variables that could be interesting (this would be part of your research).

## Data

Given the data restrictions from our customer, we are not allowed to share internal data. We have created a fictional dataset that tries to recreate the real scenario.
The dataset consists in two different files with the following variables:

• stock.csv - transactional information about sales of products
| **Variable** | **Description** |
| ------------ | --------------- |
| country_code | Code of the country |
| cac | customer |
| product_code | product sold |
| month_code | year and month of the sale |
| currency_code | currency |
| invoiced_sales | sales |
| volume_primary_units | number of sold units |
| inventory_cost | cost of the product for the company (unitary cost multiplied by volume) |

• product_master.csv - To complement the file above with more details about
the product.
| **Variable** | **Description** |
| ------------ | --------------- |
| bravo_ww_fran_name | company designation for the global group |
| bravo_fran_name | company designation for a region of the group |
| bravo_sub_fran_name | company area |
| bravo_major_name | product family |
| bravo_minor_name | product sub-family |
| product_code | product code |
