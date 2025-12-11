# Sales-Analysis
Excel Functions (Basic to Advanced)


## Sales Target Vs Bonus

![Excel IF Function Example](https://raw.githubusercontent.com/Morsshed/Excel-Sales-Analysis/main/ExcelImages/IF.png)

### Excel Functions Applied: 

###### Total sales
                          SUM(F5:F10)
###### Average Sales
                          AVERAGE(F5:F10)
###### Maximum Sales
                          MAX(F5:F10)
###### Minimum Sales
                          MIN(F5:F10)                        
###### Was goal met?
                          IF(F5>=$I$12,"Goal Met", "Not Met")
###### Bonus Amount 
                          IF(H5="Goal Met",F5*$I$13,0)
###### Department Bonus of 10,000
                          IF(AND(F12>M12, F13>M14),"10K Bonus Team Bonus", "No Bonus")

## Expense Report
![Excel IFS Function Example](https://raw.githubusercontent.com/Morsshed/Excel-Sales-Analysis/main/ExcelImages/Database%20Ifs.png)

### Excel Functions Applied: 

###### Count the # of logged Expenses
                           COUNTIF(C6:C50,"Technical Support")
###### Total Expenses for Office Supplies
                          SUMIF(C6:C50,G14,D6:D50)
###### Average Cost per Meal Expense
                          AVERAGEIF(C6:C50,G18,D6:D50)
###### Total  for Meals in Midtown
                          SUMIFS(D6:D50,B6:B50,G22,C6:C50,H22)


## Emplyee Check-in
![Excel XLOOKUP Function Example](https://raw.githubusercontent.com/Morsshed/Excel-Sales-Analysis/main/ExcelImages/XLookUp.png)

## Order Form
![Excel Column Joins with XLOOKUP Example](https://raw.githubusercontent.com/Morsshed/Excel-Sales-Analysis/main/ExcelImages/Column%20Joins%20with%20XlookUp.png)



                          
