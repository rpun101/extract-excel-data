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

EBT Cash, MOP Cash (Dollar)
, Alternative Sweet Snacks,Automotive Products,Beer,Bottle Deposits/ CRV,Candy,Cigarettes,Dispensed Cold/ Frozen,Dispensed Hot,Edible Grocery,Fluid Milk,Food Service,Frozen Foods,General Merchandise,Health & Beauty,Ice,Ice Cream / Novelty,Liquor, Wine
