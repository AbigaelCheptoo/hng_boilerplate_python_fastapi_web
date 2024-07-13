# Swagger HNGBoilerplate - OpenAPI 3.0


This repository contains the OpenAPI 3.0 documentation for the HNGBoilerplate Server, used for stage 3 tasks.

## Introduction

This API documentation outlines endpoints for user authentication, user management, organisation operations, and basic home functionalities.

## Endpoints

### Home

- Endpoint: `/`
- Method: `GET`
- Summary: Home page
- Description: Welcomes you to the Home page

### Authentication

- Endpoint: `/auth/register`
- Method: `POST`
- Summary: Registering new user

- Endpoint: `/auth/login`
- Method: `POST`
- Summary: Login for users

- Endpoint: `/auth/logout`
- Method: `POST`
- Summary: Logout for users

- Endpoint: `/auth/forgot-password`
- Method: `POST`
- Summary: Send reset password email

- Endpoint: `/auth/reset-password`
- Method: `PUT`
- Summary: Reset the user password

### Users

- Endpoint: `/users/me`
- Method: `PUT`
- Summary: Update the currently logged in user

- Endpoint: `/users/me`
- Method: `DELETE`
- Summary: Delete the currently logged in user

- Endpoint: `/users/{id}`
- Method: `GET`
- Summary: Get a user by ID

### Organisations

- Endpoint: `/organisations`
- Method: `GET`
- Summary: Get organisations

- Endpoint: `/organisations`
- Method: `POST`
- Summary: Create new organisation

- Endpoint: `/organisations/{orgId}`
- Method: `GET`
- Summary: Get organisation by ID

- Endpoint: `/organisations/{orgId}`
- Method: `PUT`
- Summary: Update organisation by ID

- Endpoint: `/organisations/{orgId}`
- Method: `DELETE`
- Summary: Delete organisation by ID

- Endpoint: `/organisations/{orgId}/users`
- Method: `PUT`
- Summary: Add user to organisation

## Security

This API uses JWT (JSON Web Token) for authentication. Bearer tokens are required to access protected resources.

## Link to the Database Design
  [Database](https://dbdiagram.io/d/66917c429939893daecc150e)
## Link to the API design
  [API](https://app.swaggerhub.com/apis-docs/KAMAUFNJERI2019/Hng_Kenyan_buddies/1.0.0)



## External Documentation

- [Swagger Documentation](http://swagger.io) - Find out more about Swagger

## License

This project is licensed under the Apache 2.0 License. See the [LICENSE](http://www.apache.org/licenses/LICENSE-2.0.html) file for details.
