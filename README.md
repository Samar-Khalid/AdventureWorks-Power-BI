# -AdventureWorks-Power-BI

@@ AdventureWorks
- Data Source: OLTP
https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms

Conductivity Mode => DirectQuery

Tables:
Sales.SalesOrderHeader 
Sales.vSalesPerson (view)  
Sales.SalesTerritory 
Purchasing.ShipMethod 

Status (Add based on ufnGetSalesOrderStatusText function)
Dates (DAX) 

-Rename Tables, columns
-Remove unused columns 

Modelig:
Create Relationships 

Measures
- # Orders Measure 
- Total SubTotal Measure 
- Total Tax Measure 
- Total Freight Measure 
- Total Due Measure  

create DAX table that contains all measures 

Visuals: (Use Measures)

- Drill Down  
- Drill Through 


- # Orders Card
- Total SubTotal Card    
- Total Tax Card        
- Total Freight Card    
- Total Due Card        
 
# Orders by Status        
# Orders by Shipmethod   
# Orders by FlagOnlineOffline 
# Orders vs. TotalDue by Territory
# Orders by CountryRegionCode

-- Good Colors, Layout and Chart Titles (Meaningful)
