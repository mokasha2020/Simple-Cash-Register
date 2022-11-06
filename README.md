# Simple-Cash-Register


This code is to program a simple register according to the dictionary below. 

mydict = {'PENNY': .01,
'NICKEL': .05,
'DIME': .10,
'QUARTER': .25,
'HALF DOLLAR': .50,
'ONE': 1.00,
'TWO': 2.00,
'FIVE': 5.00,
'TEN': 10.00,
'TWENTY': 20.00,
'FIFTY': 50.00,
'ONE HUNDRED': 100.00}

The code needs to tell the teller how many coins of each type he should give to the customer.
We want to find the biggest coin first and then the smallest and so on. 
The intuition is to calculate the change needed and then subtract it from all values in the dictionary.
Then, find the closest coin by finding the corresponding index that gives us the minimum difference between change and
values in the dict.
repeat until change value is zero.
