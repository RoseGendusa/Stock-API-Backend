
# Django Backend API

This repository contains the backend code for a web application. The backend is built using Django, a high-level Python web framework. It provides a set of models and APIs to support the functionality of the application.

## Prerequisites
Before running the backend project, make sure you have the following installed:

Python (version 3.6 or higher)
Django (version 3.0 or higher)
Django REST Framework (version 3.0 or higher)

## API Endpoints
The backend provides the following API endpoints:

### /api/categories/: GET, POST - Get a list of categories or create a new category.
### /api/brands/: GET, POST - Get a list of brands or create a new brand.
### /api/products/: GET, POST - Get a list of products or create a new product.
### /api/firms/: GET, POST - Get a list of firms or create a new firm.
### /api/purchases/: GET, POST - Get a list of purchases or create a new purchase.
### /api/sales/: GET, POST - Get a list of sales or create a new sale.


![api](https://github.com/gulfidanozturk/Stock-API-Backend/blob/main/img.jpg?raw=true)



## Frontend Integration
To integrate the backend with a frontend application, you can make HTTP requests to the API endpoints mentioned above. You can use a frontend framework like React to build the user interface and consume the backend APIs.

### Here is an example of how to make a GET request to fetch the list of categories using the Fetch API in JavaScript:

fetch('http://localhost:8000/api/categories/')
  .then(response => response.json())
  .then(data => {
    // Process the received data
    console.log(data);
  })
  .catch(error => {
    // Handle any errors
    console.error(error);
  });

