# micro-service-shopping

## Online Household Products Order Application 

# Functional requirements:
1. Listing of Available Products
2. User Signup / Signing 
3. Add product to Cart
4. Add product to wishlist
5. Place an Order 
6. View Order to

# Architecture

## Design: Monolithic Acrhitecture

The mobile/web application will be listening to the back end system through HHP connection and
The database will be Mongo DB or SQL Server
- Customer service service: Responsible to perform task related sto sign up/in Wishlist Address
- Product Service: Listing products, Find Products and Add products
- Shopping Service: Responsible for the cart: Carts Order and payments

## Microsertvice Architecture: 

- Web/App Connects with the API Gateway
- API ga