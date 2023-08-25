### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
- one type of database management system

- What is the difference between SQL and PostgreSQL?
- sql is standardized querying language, and postgresql is just the system that speaks it

- In `psql`, how do you connect to a database?
- \c 'db_name'

- What is the difference between `HAVING` and `WHERE`?
- 'WHERE' refers to the first layer of filtering where you are looking for key:value. 'HAVING' refers to the next layer of grouped rows

- What is the difference between an `INNER` and `OUTER` join?
- inner join only gets data that overlaps, outer joins, gets all data that doesn't

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
- left outer join joins the tables on the left side that doesnt overlap, right outer is the other side

- What is an ORM? What do they do?
- object relational mapping refers to systems that translates/maps data between languages
- 
- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
  - ajax uses asynchronous/await to process requests, scripted cdn
  - requests is imported from python library, also used for HTTP requests

- What is CSRF? What is the purpose of the CSRF token?
- cross site request forgery, prohibits data movement from unauthorized websites/links. must be authenticated with hidden token

- What is the purpose of `form.hidden_tag()`?
- checks for csrf token to know where or not it is a POST/GET request
