# Dynamic-Multi-Tenancy-Using-Java-Spring-Boot-Security-JWT-Rest-API-MySQL-Postgresql-full-example
I wanted a solution where multi-tenancy is achieved by having a database per tenant and all user information (username, password, client Id etc) for authentication and authorization stored in a user table in the respective tenant databases. It meant that not only did I need a multi-tenant application, but also a secure application like any other web application secured by Spring Security. I know how to use Spring Security to secure a web application and how to use Hibernate to connect to a database. The requirement further dictated that all users belonging to a tenant be stored in the tenant database and not a separate or central database. This would allow for complete data isolation for each tenant.
