# JSON-SERVER
Implementation of json server  fake api

to run the server 

cmd = npm run start-json

to run on port 

cmd = npm run start-server -- --port 4000

for getbyId 
you will use id from json server
http://localhost:4000/products/a66e     

for data filter
you will use query parameter
http://localhost:4000/products?brand=ViewMore 

multiple filter
use &amperson
http://localhost:4000/products?brand=ViewMore&price=1799

for sorting
use _sort this bydefault set ascending
http://localhost:4000/products?_sort=price

for desc
http://localhost:4000/products?_sort=price&_order=desc


pagination using limit how much limit we want to show on basis of that
http://localhost:4000/products?_page=1&_limit=3