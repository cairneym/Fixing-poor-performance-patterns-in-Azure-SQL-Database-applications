# Fixing poor performance patterns in Azure SQL Database applications

This repo contains the slide deck and demo samples for my session at NDC Sydney 2020.

You will need at least 2 Azure SQL Databases for the demos:
* the N-Plus1DB is populated from the SchoolDB.bacpac file 
* the CacheDB is created from the SQL Server database created by the HammerDB application
* the LogRateDB databases can be any sufficienty large database to cause log generation from a `SELECT INTO` statement. I got this from the StackOverflow data exports.

Update the database context for the **EF6-DBFirst-Demo-master** to point to your database.
