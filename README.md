🛠 Technologies Used
SQL Server (T-SQL)

Data Normalization: 1NF, 2NF, 3NF
Advanced SQL: CTEs (Common Table Expressions), Window Functions, Case Statements, RFM Analysis.

🏗 Data Architecture & Normalization

To ensure data integrity and query efficiency, the initial flat dataset was decomposed into 4 relational tables (Star Schema approach):
Customers: Detailed by segments.
Products: Categorized by hierarchy.
Locations: Organized by regions and countries.
Orders: The central Fact Table containing transactional data.


🛠 გამოყენებული ტექნოლოგიები

SQL Server (T-SQL)
Data Normalization (1NF, 2NF, 3NF)
Advanced SQL: CTEs, Window Functions, Case Statements, RFM Analysis.

🏗 მონაცემთა არქიტექტურა (Normalization)

პროექტის დასაწყისში ერთიანი ბრტყელი ცხრილი დაიშალა 4 ძირითად ცხრილად მონაცემთა მთლიანობისა და ეფექტურობისათვის:
Customers (სეგმენტებით)
Products (კატეგორიებით)
Locations (რეგიონებით)
Orders (ფაქტების ცხრილი)

before <img width="1035" height="557" alt="optimization1" src="https://github.com/user-attachments/assets/d6f397e0-b52c-4cb2-be9a-c73bf8e1c586" />
<img width="1033" height="553" alt="opt4" src="https://github.com/user-attachments/assets/cf82d682-84f7-4035-81b8-d07cea59186a" />

after <img width="1033" height="548" alt="opt3" src="https://github.com/user-attachments/assets/b417486e-ba13-43d3-95cf-6df022e4aca4" />
<img width="1043" height="550" alt="opt2" src="https://github.com/user-attachments/assets/fec1eb63-589c-423e-9827-faf1aa9b6310" />


