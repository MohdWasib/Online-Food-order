# Online Food Order Backend

This repository contains the backend code for the Online Food Order application. The backend is built using Node.js and Express.js, providing APIs for user management, food ordering, and more.

## Features

- User authentication and authorization
- CRUD operations for food items
- Order management
- Integration with payment gateways
- API documentation with Postman

## Getting Started

Follow these instructions to set up the project on your local machine for development and testing purposes.

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)
- MongoDB

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/MohdWasib/Online-Food-order.git
    ```

2. Navigate to the project directory:
    ```sh
    cd Online-Food-order
    ```

3. Install the dependencies:
    ```sh
    npm install
    ```

4. Create a `.env` file in the root directory and add your environment variables:
    ```env
    PORT=3000
    MONGODB_URI=mongodb://localhost:27017/online_food_order
    JWT_SECRET=your_jwt_secret
    ```

### Running the Project

1. Start the development server:
    ```sh
    npm start
    ```

2. The server will be running at `http://localhost:3000`.

### Running Tests

1. To run the tests, use the following command:
    ```sh
    npm test
    ```

## API Documentation

You can find the API documentation in the [FoodOrders.postman_collection.json](./FoodOrders.postman_collection.json) file. Import this file into Postman to view and test the API endpoints.

## Folder Structure

