# Swagger Petstore API Tests (Postman)

This project contains API tests for the [Swagger Petstore](https://petstore.swagger.io).

## Covered Tests
### User
- Create a new user
- Get user by username
- Update user info
- Delete user

### Pet
- Add a new pet
- Get pet by ID
- Update pet status (available → sold)
- Delete pet

### Store/Order
- Place an order for a pet
- Get order by ID
- Delete order

## How to Use
1. Import `Swagger_Petstore_API.postman_collection.json` into Postman.
2. Run the requests manually or in Collection Runner.
3. Observe responses (201 created, 200 OK, 404 after delete, etc.).
