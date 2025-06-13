n this project, you'll be given a simple Content Management System (CMS) for articles, where a user can log in, view published articles, and publish new articles. An article consists of a title, author, and body of text (to be stored in an Azure SQL Server) along with an image (to be stored in Azure Blob Storage).

The CMS includes the following components:
- A webapp using Python with the Flask framework.
- A SQL database that contains a user table and an article table for the webapp to query.
- A Blob Storage container where images are stored.
- It will be up to you to create and manage the resources necessary to fully deploy both the necessary storage and compute resources for the app to Azure. 

As part of the project, you'll also need to analyze which resource best fits for app deployment between a VM or App Service. Lastly, you'll add an authentication option to Sign in with Microsoft, as well as logging for successful and unsuccessful logins.