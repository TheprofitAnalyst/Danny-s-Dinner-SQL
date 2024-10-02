#  Danny-s-Dinner Analysis | SQL challenge project
## Introduction
Danny seriously loves Japanese food so in the beginning of 2021, he decides to embark upon a risky venture and opens up a cute little restaurant that sells his 3 favourite foods: sushi, curry and ramen.

Danny’s Diner is in need of your assistance to help the restaurant stay afloat - the restaurant has captured some very basic data from their few months of operation but have no idea how to use their data to help them run the business.
## Problem Statement
Danny wants to use the data to answer a few simple questions about his customers, especially about their visiting patterns, how much money they’ve spent and also which menu items are their favourite. Having this deeper connection with his customers will help him deliver a better and more personalised experience for his loyal customers.

He plans on using these insights to help him decide whether he should expand the existing customer loyalty program - additionally he needs help to generate some basic datasets so his team can easily inspect the data without needing to use SQL.
## Data Sources
### This repository contains three key datasets provided by Danny for the case study. _The datasets are_:
### 1. Sales Table
  * Description: The sales table captures all customer_id level purchases with an corresponding order_date and product_id information for when and what menu items were ordered.
### 2. Menu Table
  * Description: The menu table maps the product_id to the actual product_name and price of each menu item.
### 3. Members Table
  * Description: The final members table captures the join_date when a customer_id joined the beta version of the Danny’s Diner loyalty program.
## Case Study Questions
1.  What is the total amount each customer spent at the restaurant?
2.  How many days has each customer visited the restaurant?
3.  What was the first item from the menu purchased by each customer?
4.  What is the most purchased item on the menu and how many times was it purchased by all customers?
5.  Which item was the most popular for each customer?
6.  Which item was purchased first by the customer after they became a member?
7.  Which item was purchased just before the customer became a member?
8.  What is the total items and amount spent for each member before they became a member?
9.  If each $1 spent equates to 10 points and sushi has a 2x points multiplier - how many points would each customer have?
10. In the first week after a customer joins the program (including their join date) they earn 2x points on all items, not just sushi - how many points do customer A and B have at the end of January?
11. Determine the name and price of the product ordered by each customer on all order date and find out whether the customer was a member on the order date or not.
12. Rank the previous output from Q. 11 based on the order date for each customer. Dispaly NULL if customer was not a member on the ordered date.

## Data Analysis and Results
1.  What is the total amount each customer spent at the restaurant?
  ![1](https://github.com/user-attachments/assets/859af596-32d8-4efe-98bb-012d57d26b26)

3.  How many days has each customer visited the restaurant?
  ![2](https://github.com/user-attachments/assets/6fc51192-5b5c-4ba1-84aa-e67ca410b298)

4.  What was the first item from the menu purchased by each customer?
   ![3a](https://github.com/user-attachments/assets/1de3532c-6348-49d7-981c-0678a6bde373)

5.  What is the most purchased item on the menu and how many times was it purchased by all customers?
   ![4](https://github.com/user-attachments/assets/18771932-f59a-4a5e-8c8c-670dc96d4051)

6.  Which item was the most popular for each customer?
   ![5](https://github.com/user-attachments/assets/c3899d39-7212-4eb5-9701-f188582a76dc)

7.  Which item was purchased first by the customer after they became a member?
   ![6](https://github.com/user-attachments/assets/3b038be4-af4d-4985-b47a-91b7016c5e7d)

8.  Which item was purchased just before the customer became a member?
   ![7](https://github.com/user-attachments/assets/eee73600-a7f1-44fa-a346-353c2e04e165)

9.  What is the total items and amount spent for each member before they became a member?
   ![8](https://github.com/user-attachments/assets/48a7f33a-384a-4b5a-8d49-cd9b34a0b5b6)

10.  If each $1 spent equates to 10 points and sushi has a 2x points multiplier - how many points would each customer have?
![9](https://github.com/user-attachments/assets/da89ff3b-f389-419b-b681-4bd8644cd82d)

11. In the first week after a customer joins the program (including their join date) they earn 2x points on all items, not just sushi - how many points do customer A and B have at the end of January?
  ![10](https://github.com/user-attachments/assets/8e7ca941-faf8-419a-bbcd-289c215636aa)

12. Determine the name and price of the product ordered by each customer on all order date and find out whether the customer was a member on the order date or not.
![11](https://github.com/user-attachments/assets/546f016f-a61a-49bc-abf6-f8eae16340ed)

13. Rank the previous output from Q. 11 based on the order date for each customer. Dispaly NULL if customer was not a member on the ordered date.
![12](https://github.com/user-attachments/assets/828e314c-8843-4717-a381-0bd12c0e3935)
