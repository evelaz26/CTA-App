## CTA-App
A Windows Forms Application that displays information about the Chicago Transit Authority L-lines. Utilizes dynamic SQL queries in C# and ADO.NET objects to access the CTA database.
This data-driven application uses N-tier Design where:
*  **BusinessTierLogic.cs** &  **BusinessTierObjects.cs** support the security, business rules, and data processing needed by this project
*  **DataAccessTier.cs** acts as the interface between business tier and data storage
*  **Form1.cs** represents the UI
The database file **CTA.mdf** can be found in bin>Debug folder alongside with its associated log file **CTA_log.ldf**. THe application accesses this database by typing **|DataDirectory|\CTA.mdf** as the filepath.
