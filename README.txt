
FULL MINI PROJECT: AUTH + PRODUCT INVENTORY

STEPS TO RUN

1. Extract the project
2. Open folder in VS Code
3. Run:

npm install

4. Start server:

npm start

Server runs:
http://localhost:5000


POSTMAN APIS

Register
POST /api/users/register

{
"name":"Anandhi",
"email":"test@gmail.com",
"password":"123456"
}


Login
POST /api/users/login

{
"email":"test@gmail.com",
"password":"123456"
}


Add Product
POST /api/products

{
"name":"Laptop",
"quantity":5,
"price":50000
}


Get Products
GET /api/products


Delete Product
DELETE /api/products/:id
