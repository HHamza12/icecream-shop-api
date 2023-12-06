![Icecream Shop API](icecream-shop-api.png)

# Icecream Shop API

Code for an Icecream Shop's REST API, containing some example vulnerabilities.

## Tasks for week 9
Found SQL injection vulnerability
There was an sql query
 "SELECT * FROM Customers WHERE Email='{email}'" 
it is creating vulnerbility in this application attacker can do sql injection method +OR+1=1-- 
to get all records from customer table which is vunernability in this api code that needs to be fixed
