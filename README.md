The program we create for Ayesha Beauty creation was divided into five modules.

The first module named PointOfSale( ) contains two functions. The first function Purchase( ) allows the cashier to enter the details of a purchase and the function would also calculate the change that is due to the customer and print the sales receipt for the customer. The second function RecordSales( ) stores the data of the purchases made on a text file titled Sales.txt.

The second Module Inventory( ) contains two functions. The first function RecordStock( ) allows the stocktaker to enter the details and the amount of the items that are available for sale in the warehouse a d store the details on a textfile titled stocklist.txt. The second function StockList( ) opens the stocklist.txt file to view the amount of items currently in the inventory.

The third Module HumanRecource( ) which is a security module meaning that the human recource administrator has to login first in order to call the functions belonging to the module. The module contains the functions NewEntry( ) and ViewHR( ). The function NewEntry( ) allows the human resource administrators to enter employee records and store the records on the textfile titled employee.txt. The function ViewHR( ) opens the textfile employee.txt so the human recource administrator view the current employee records.

The fourth Module Customer( ) allows the user to enter customer details and stores the details on a customer table titled customer.dbo which is in the customer database.

The fifth Module ManagerView( ) which is a security module meaning that the manager has to login first to innorder to call the function bellonging to the module. The module contains the function ViewFiles( ) which allows the manager to view any of the text files that have used in the application as well as the customer table.
