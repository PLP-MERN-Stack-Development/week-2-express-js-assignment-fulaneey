[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=19736188&assignment_repo_type=AssignmentRepo)
# Express.js RESTful API Assignment

This assignment focuses on building a RESTful API using Express.js, implementing proper routing, middleware, and error handling.

## Assignment Overview

You will:
1. Set up an Express.js server
2. Create RESTful API routes for a product resource
3. Implement custom middleware for logging, authentication, and validation
4. Add comprehensive error handling
5. Develop advanced features like filtering, pagination, and search

## Getting Started

1. Accept the GitHub Classroom assignment invitation
2. Clone your personal repository that was created by GitHub Classroom
3. Install dependencies:
   ```
   npm install
   ```
4. Run the server:
   ```
   npm start
   ```

## Files Included

- `Week2-Assignment.md`: Detailed assignment instructions
- `server.js`: Starter Express.js server file
- `.env.example`: Example environment variables file

## Requirements

- Node.js (v18 or higher)
- npm or yarn
- Postman, Insomnia, or curl for API testing

## API Endpoints

The API will have the following endpoints:

- `GET /api/products`: Get all products
- `GET /api/products/:id`: Get a specific product
- `POST /api/products`: Create a new product
- `PUT /api/products/:id`: Update a product
- `DELETE /api/products/:id`: Delete a product

## Submission

Your work will be automatically submitted when you push to your GitHub Classroom repository. Make sure to:

1. Complete all the required API endpoints
2. Implement the middleware and error handling
3. Document your API in the README.md
4. Include examples of requests and responses



# 📦 Express.js Product API
│

│
## Prerequisites
│ - Node.js v18+
│ - npm
│
### Installation
│ - bash
│ - npm install
│   
│
### Run the Server
│ - bash
│ - node server.js
│   ```
│
## 📘 API Endpoints
│
## All requests must include a header:
│   `x-api-key: your-secure-api-key`
│
### `GET /api/products`
│   - List all products
│   - Query Parameters:
│     - `category`: Filter by category
│     - `page`: Page number
│     - `limit`: Results per page
│
**Response Example:**
│   ```json
│   {
│     "data": [
│       { "id": "1", "name": "Phone", ... }
│     ],
│     "total": 1
│   }
│   ```
│
### `GET /api/products/:id`
│   - Get product by ID
│
### `POST /api/products`
│   - Create new product
│   - Body:
│   ```json
│   {
│     "name": "Laptop",
│     "description": "High performance",
│     "price": 1500,
│     "category": "Electronics",
│     "inStock": true
│   }
│   ```
│
### `PUT /api/products/:id`
│   - Update product
│   - Body: same as POST
│
### `DELETE /api/products/:id`
│   - Delete product
│
### `GET /api/products/search?q=term`
│   - Search products by name
│
### `GET /api/products/stats`
│   - Returns count by category



## Resources

- [Express.js Documentation](https://expressjs.com/)
- [RESTful API Design Best Practices](https://restfulapi.net/)
- [HTTP Status Codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status) 