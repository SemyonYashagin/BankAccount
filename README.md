# BankAccount
Personal account for bank's clients
![image](https://github.com/SemyonYashagin/BankAccount/assets/17547459/a8d6c9f1-ed6a-4d42-9402-efcf759e5fc5)

🔭 Web client: React

When the page is opened, the client’s login form into his personal account, if the client is found and authenticated, his full name and a list of his accounts are displayed.

⚡ Web Gateway: ASP.NET Core

It is only a gateway and does not implement any logic or data storage. When receiving requests, the Web Gateway requests data from the Business Logic Service via gRPC. Provides a REST API for external requests (including from the Web client).

🌱 DataBase: DBMS PostgreSQL

Interacts with the database via Entity Framework Core.
