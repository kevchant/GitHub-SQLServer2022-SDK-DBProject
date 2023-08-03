Example of a SQL Server Database Project that performs CI/CD for a SQL Server 2022 Database using GitHub Actions. Based on a blog post I wrote called '[CI/CD for SQL Server 2022 using GitHub Actions](https://www.kevinrchant.com/2023/03/07/ci-cd-for-sql-server-2022-using-github-actions/)'.

A brief overview is below. 

It contains a YAML pipeline, which is also known as a workflow in GitHub. You can find the file in the /.github/workflows folder of the repository.

In order to use it with GitHub Actions in your own account you can either import or fork this repository into another GitHub repository.

You MUST have two secrets specified for this to work:

* SQLDB_SERVER - Name of your SQL Server instance.
* SQLDB_CONNECTION_STRING - Connection string to your SQL Server 2022 database.

This repository is provided "as is" based on the MIT license (https://opensource.org/licenses/MIT). Basically, I am not responsible for your use of it.
