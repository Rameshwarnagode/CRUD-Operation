# CRUD-Operation
This Windows Forms application performs CRUD operations on a SQL Server database to manage student records. It includes features for adding, updating, deleting, and searching records, with data displayed in a DataGridView. The application ensures user-friendly interaction with clear input fields and dynamic data refresh.

The Tbl_StudInfo table should have the following structure based on the code:
<br>
Column Name     &nbsp;          Data Type	Constraints
studid	        &nbsp;          INT	Primary Key, Identity (Auto Increment)
studname        &nbsp;         	VARCHAR(100)	NOT NULL
studadd	        &nbsp;          VARCHAR(255)	NOT NULL
studmob	        &nbsp;          VARCHAR(15)	NOT NULL
studadhar  	    &nbsp;          VARCHAR(20)	NOT NULL
studstand	      &nbsp;          VARCHAR(50)	NOT NULL
CreatedDate     &nbsp;        	DATETIME	NOT NULL
UpdatedDate     &nbsp;         	DATETIME	NOT NULL
isActive	      &nbsp;              BIT	                 
