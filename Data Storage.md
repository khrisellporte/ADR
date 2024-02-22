# Data Storage: SQL or NoSQL?

## Decision
We're going with a **SQL database** like PostgreSQL for structured data.

## Rationale
SQL databases are great for structured data, like user profiles and order history. For storing data on the client-side in web apps, we could use localStorage.

## Consequences
Choosing a SQL database means we'll have to design our database schema carefully to ensure it can handle all our data needs. We'll also have to learn SQL if we don't know it already.