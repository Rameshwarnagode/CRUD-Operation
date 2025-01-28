# CRUD-Operation
This Windows Forms application performs CRUD operations on a SQL Server database to manage student records. It includes features for adding, updating, deleting, and searching records, with data displayed in a DataGridView. The application ensures user-friendly interaction with clear input fields and dynamic data refresh.

The Tbl_StudInfo table should have the following structure based on the code:
<br>
CREATE TABLE Tbl_StudInfo (
    studid INT IDENTITY(1,1) PRIMARY KEY,
    studname VARCHAR(100) NOT NULL,
    studadd VARCHAR(255) NOT NULL,
    studmob VARCHAR(15) NOT NULL,
    studadhar VARCHAR(20) NOT NULL,
    studstand VARCHAR(50) NOT NULL,
    CreatedDate DATETIME NOT NULL,
    UpdatedDate DATETIME NOT NULL,
    isActive BIT DEFAULT 1
);
       
