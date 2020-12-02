---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Sql
  platforms: java
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

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/master/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/master/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/sql-database-java-manage-sql-server-dns-aliases.git

    cd sql-database-java-manage-sql-server-dns-aliases

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.