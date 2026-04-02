write this with python , streamlit

program name: extract excel data

rough design:

1) Upload excel sheet: [     ]

2) textbox to choose row data with comma separate, remove whitespacing 
    example:  "total, amount to year, shipping cost"
3) get all date format by default
    [optional] plus, comma separte properties in textbox
4) output in table in web page 

Important: 
+ It should be able to go through all multiple sheets inside excel or google sheets
+ error on which row and sheet if any
+ same row with matching can be in different row number in another sheet


program is retuning 'no matching rows found across any sheet, which wrong. 
row labels, make the case insensitive. 

and give me button after columns to hit extract, then show the Results
I will give you a sample sheet1


##ORDER##
 Fuel Settlement Total, MOP Cash (Dollar), MOP Debit, MOP Credit, EBT Cash, MOP EBT Tot, 
 Cigarettes, Other Tobacco, Beer, Wine, Liquor, Packaged Beverages, Candy, Fluid Milk, Other Dairy/Deli, Packaged Sandwich, Ice Cream / Novelty, Frozen Foods, Packaged Breads, Salty Snacks, Packaged Sweet Snacks, Alternative Sweet Snacks, Perishable Grocery, Edible Grocery, Non-Edible Grocery, Health & Beauty, General Merchandise, Automotive Products, Scratch Lottery Sales, Ice, Food Service, Dispensed Hot,  Dispensed Cold/ Frozen, Bottle Deposits/ CRV, Lotto Online Sales, MOP Scratch, MOP Lotto, MOP MFG Coupons
