# Simple-Cash-Register


This code is to program a simple register according to the dictionary below. 
PP is the purchase price
CH is the cash given to teller by customer
The code needs to tell the teller how many coins of each type he should give to the customer.
We want to find the biggest coin first and then the smallest and so on. 
The intuition is to calculate the change needed and then subtract it from all values in the dictionary
Then, find the closest coin by finding the corresponding index that gives us the minimum difference betweek change and
values in the dict.
repeat until change value is zero.
