---
page_type: sample
languages:
- java
products:
- azure
extensions:
- services: Sql
- platforms: java
---

# Getting Started with Sql - Manage Sql Server Dns Aliases - in Java #


  Azure SQL sample for managing SQL Server DNS Aliases.
   - Create two SQL Servers "test" and "production", each with an empty database.
   - Create a new table and insert some expected values into each database.
   - Create a SQL Server DNS Alias to the "test" SQL database.
   - Query the "test" SQL database via the DNS alias and print the result.
   - Use the SQL Server DNS alias to acquire the "production" SQL database.
   - Query the "production" SQL database via the DNS alias and print the result.
   - Delete the SQL Servers
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/sql-database-java-manage-sql-server-dns-aliases.git

    cd sql-database-java-manage-sql-server-dns-aliases

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.