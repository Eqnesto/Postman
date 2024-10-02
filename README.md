# API Automation with Postman

This repository contains API tests for the Simple Books API using Postman and JavaScript. It uses a Bearer Token for authentication, with dynamic pre-request scripts and assertions to validate response status, content, and reliability in both positive and negative scenarios.

## How to Run
1. Open Postman and import the collection and environment files.
2. Select the correct environment.
3. Right-click the collection and select Run Collection.
4. Review the results in the Tests tab.

## Test Cases
1. **Access Token Tests**
   * **Create Access Token**: Tests generating a valid access token.

2. **Client Creation Tests**
   * **Create Client With Existing Email**: Tests attempting to create a client with an already registered email.

3. **Book Retrieval Tests**
   * **Get Books**: Tests retrieving the list of books.
   * **Get Single Book**: Tests retrieving a specific book's details.
   * **Get Non-Existent Book**: Tests retrieving details for a book that doesn't exist.

4. **Order Creation Tests**
   * **Create Order With Unavailable Book**: Tests attempting to order an unavailable book.
   * **Create Order With Available Book**: Tests ordering an available book.
   * **Create Order With Invalid Token**: Tests ordering a book using an invalid token.

5. **Order Modification Tests**
   * **Modify Order**: Tests modifying an existing order.
   * **Modify Non-Existent Order**: Tests modifying an order that doesn’t exist.

6. **Order Deletion Tests**
   * **Delete Existing Order**: Tests deleting an existing order.
   * **Delete Non-Existent Order**: Tests deleting an order that doesn’t exist.

7. **Order Retrieval Tests**
   * **Get Orders**: Tests retrieving the list of orders.
