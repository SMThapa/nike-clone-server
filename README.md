
# Nike Clone Server API Documentation

This repository contains the documentation for the Nike Server API, which serves as the backend infrastructure for the Nike ecommerce application. The API enables clients to interact with the server and perform various operations related to product management, user authentication, shopping cart management, and order processing.


## Base URL

- The base URL for accessing the Nike Server API is: https://nike-clone-server.onrender.com
## Authentication

To access protected endpoints, clients must include a valid authentication token in the request headers. Authentication tokens can be obtained by logging in to the application using the provided authentication endpoint.



## Endpoints

The Nike Server API provides the following endpoints:

- `/products`: Retrieve a list of Nike products, including shoes, apparel, and accessories.
- `/products/{id}`: Retrieve detailed information about a specific Nike product by its ID.
- `/orders`: Retrieve a list of user orders and their status.
- `/users`: Retrieve a list of user and their status.

- Use json-server-auth for authentication.
## Testing

The API endpoints can be tested using tools like Postman or by making HTTP requests directly from your client application.
## Contributing

Contributions to the Nike Server API documentation are welcome. If you find any issues or would like to suggest improvements, feel free to submit a pull request. Please ensure that the documentation stays up-to-date with any changes made to the API.

