LSM
=============
The Lite Store Management (LSM) will be the first product that will be developed with Shift Software's framework (the framework isn't ready, but the development process has started). LSM will also be the first product that Shift Software will sell (usually the company does not sell products, instead services are provided to the clients)

# Overview

In future, LSM will be a tool for the eCommerce platform, customers who use LSM will automatically be enrolled in the eCommerce platform, and the available products in the LSM will be listed online as well. The eCommerce platform isn't ready yet, in 2021 there were attempts to build a version but then it was abandoned, now Shift Software has the opportunity to resume working on another version with eBazar or other potential clients.

As we work on the technical side of the new framework, we also need to work on the logic/business side, which can be done by studying existing softwar and reading about industry standard techniques in managing inventory and sales. This will be a very thorough and in-depth process, we need to learn about everything available in this field and consider all the asepcts.

# Test data

We need some test data to be able to perform tests/edge test cases for all possible scenarios. There is no need for large amounts of data, we can have hypothetical scenarios on a single product that has some purchases, sales, returns, etc. Each scenario should focus on a concept: Costing, Quantity tracking, FIFO, LIFO, Average value calculation, Minimum stock, etc.  

The dummy data can be found in this datasheet: 

https://docs.google.com/spreadsheets/d/19qsZwyP7YEDvDa26qabVrGRtQsX9xmYQYPGgXQkqINs/edit#gid=0


# Inventory formulas 
1. Economic order quantity (EOQ) is the optimum number of products you should purchase to minimize the total cost of ordering or holding stock. 

![alt text](https://github.com/Shift-Software/Cyber/blob/main/1.png)

2. Days inventory outstanding (DIO) formula refers to the number of days it takes for inventory to turn into sales.   

![alt text](https://github.com/Shift-Software/Cyber/blob/main/2.png)


3. Reorder point formula answers the question: When is the right time to order more stock

![alt text](https://github.com/Shift-Software/Cyber/blob/main/3.png)

4. Safety stock formula: We need to have enough safety stock to meet demand.

![alt text](https://github.com/Shift-Software/Cyber/blob/main/4.png)





# Software products

It is possible to perform the same tests on each platform to compare their functionality, here are some platforms to consider:

1. LSM by Shift Software: https://lsm-test.shift.software

               Username: Admin

               Password: aslkdfj293i8u

2. Inventory trading trial: https://drive.google.com/file/d/1Xjb4BqQZfL0EFVxEp18o6KX7B-ILFUHl/view?usp=sharing

3. AlmytaABC Inventory: http://www.almyta.com/abc_inventory_software.asp

Below are some famous sales and Customer Relationship Management (CRM) software:

1. [Nutshell](https://www.nutshell.com)
2. [HubSpot](https://www.hubspot.com/)
3. [Freshsales](https://www.freshworks.com/crm/lp/crm-customer-management/1/)

Out of the three, Freshsales is by far the best, it has so many options and in-detail management. Some options may be redundant for certain customers. 

# Industry standard techniques in managing inventory and sales
There are different inventory management techniques
- FIFO (first in first out) and LIFO (last in first out)
- ABC category
- Minimum order quantity, Economic order quantity.
- JIT (Just in Time Inventory) management.
- JIC (Just in Case Inventory) model.

### Points to consider
- Maintaining relationship with suppliers especially when orders arise
- Assessing the suppliers, how often do they miss the deadline? 
- Regularly auditing the inventory
- Tracking customer sales to see trends in customer behavior
- Predicting future demand/supply
- Store inventory in strategic locations to reduce shipping costs
- Discover trends to drive growth

How does Amazon manage its inventories? 

# References

Costing methods:
https://docs.microsoft.com/en-nz/dynamics365/business-central/design-details-costing-methods

Sales management:
https://blog.hubspot.com/sales/sales-management
