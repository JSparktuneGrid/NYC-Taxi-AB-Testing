# NYC-Taxi-AB-Testing
# Statistics Review and A/B testing for New York City Yellow Taxi Project 

## Overview
The purpose of this project is to predict taxi cab fares before each ride. At this point, this project’s focus is to find ways to generate more revenue for New York City taxi cab drivers. This part of the project examines the relationship between total fare amount and payment type. 

## Problem 
Taxi cab drivers receive varying amount of tips. While examining the relationship between total fare amount and payment type, this project seeks to discover if customers who pay in credit card tend to pay a larger total fare amount than customers who pay in cash.

## Solution
Ran an A/B test to analyze the relationship between credit card payment and total fare amount. The key business insight is that encouraging customers to pay with credit cards will likely generate more revenue for taxi drivers. 

## Methodology
### Steps conducted in the A/B test
1. Collected sample data from an experiment in which customers are randomly selected and divided into two groups:
    **a**. Customers who are required to pay with credit card.
    **b**. Customers who are required to pay with cash.This enables us to draw causal conclusions about how payment method affects fare amount.
2. Computed descriptive statistics to better understand the average total fare amount for each payment method available to the customer.
3. Conducted a two-sample t-test to determine if there is a statistically significant difference in average total fare between customers who use credit cards and customers who use cash.

### A/B test results
There is a statistically significant difference in the average total fare between customers who use credit cards and

**The purpose** of this project is to demostrate knowledge of how to prepare, create, and analyze A/B tests. Your A/B test results should aim to find ways to generate more revenue for taxi cab drivers.

**The goal** is to apply descriptive statistics and hypothesis testing in Python. The goal for this A/B test is to sample data and analyze whether there is a relationship between payment type and fare amount. For example: discover if customers who use credit cards pay higher fare amounts than customers who use cash.
