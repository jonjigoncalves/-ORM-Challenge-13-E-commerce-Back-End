# -ORM-Challenge-13-E-commerce-Back-End

## Overview

This project aims to build the back end for an e-commerce website by configuring a functional  API to interact with a MySQL database using Sequelize. The application should allow managers at an internet retail company to perform CRUD operations on categories, products, and tags, enabling them to manage their online store efficiently.

## User Story

As a manager at an internet retail company, I want a back end for my e-commerce website.

## Acceptance Criteria

- I can connect to the database using Sequelize by providing the database name, MySQL username, and MySQL password through an environment variable file.
- By entering schema and seed commands, a development database is created and seeded with test data.
- The server starts and the Sequelize models are synced to the MySQL database.
- API GET routes for categories, products, and tags display data in a formatted JSON when tested using Insomnia.
- API POST, PUT, and DELETE routes for categories, products, and tags work successfully in Insomnia.


## Getting Started

To run the application, follow these steps:

1. Clone the GitHub repository.
2. Install the required npm packages using `npm install`.
3. Set up environment variables to store sensitive data like the MySQL username, password, and database name using the `dotenv` package.
4. Use the `schema.sql` file in the `db` folder to create the database with MySQL shell commands.
5. Define the four models (`Category`, `Product`, `Tag`, and `ProductTag`) with the specified column requirements.
6. Execute association methods on Sequelize models to establish the relationships between them.
7. Fill out the API routes (`product-routes.js`, `tag-routes.js`, and `category-routes.js`) to perform RESTful CRUD operations on the data.
8. Seed the database using `npm run seed`.
9. Sync Sequelize to the database on server start using  `node server.js`.

## Walkthrough Video

Please refer to the provided walkthrough video for a comprehensive demonstration of the application's functionality and the fulfillment of all acceptance criteria. The video should include the following:

- Connecting to the database and seeding it with test data.
- Starting the server and syncing Sequelize models.
- Testing API GET routes for categories, products, and tags in Insomnia.
- Testing API GET routes for a single category, a single product, and a single tag in Insomnia.
- Testing API POST, PUT, and DELETE routes for categories, products, and tags in Insomnia.


## Review

The submission for this project should include the following:

1. A walkthrough video demonstrating the application's functionality and meeting all acceptance criteria.
2. The URL of the GitHub repository with a descriptive README.
---


