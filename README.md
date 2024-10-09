
# Engagement API Project

## Overview
This project involves creating an Engagement API that manages video posts, story content, products, and collections for a company. The API allows for the retrieval of posts, products, and collections, as well as creating new products and collections.

## Tables
The following tables are included in the PostgreSQL database:
1. **engagement_post**: Contains information about the posts (videos, stories) for a company.
2. **engagement_post_content**: Stores URLs of the content attached to each post.
3. **engagement_post_product_mapping**: Maps products to each post.
4. **engagement_post_product**: Contains details about the products including name, image, and SKU.
5. **collection**: Represents a collection of engagement posts.
6. **engagement_post_collection**: Maps engagement posts to collections, including the duration watched.

## API Endpoints
1. **GET /posts/:tenant_id**: Fetch a list of posts, including all content and products attached to it for a given tenant_id.
2. **POST /products**: Create a new product.
3. **POST /collections**: Create new collections and save post IDs in each collection.
4. **GET /top-posts/:tenant_id**: List the top 5 viewed engagement posts for a given tenant_id.
5. **GET /top-products/:tenant_id**: List the top 5 products viewed most frequently for a given tenant_id.

## Getting Started
1. **Install PostgreSQL 13.X** and set up the database.
2. **Create Roles** as specified in the project requirements.
3. **Run SQL Queries** to create the necessary tables in your database.
4. **Implement API Endpoints** in your Node.js application using the provided code snippets.
5. **Test the API** using tools like Postman or curl.

## License
This project is licensed under the MIT License.

## Author
[Your Name]
