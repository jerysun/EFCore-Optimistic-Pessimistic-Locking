# EFCore-Optimistic-Pessimistic-Locking

Data integrity and consistency along with locking mechanisms, when multiple users attempt to modify the same resource simultaneously, potentially causing conflicts and overwriting each other’s data.

In this project, we use Entity Framework Core as an abstraction over our data access and Testcontainers NuGet package to programmatically create an SQL Server database container.

## Prerequisites

Testcontainers requires Docker to be installed and running, as it will run a local database container.