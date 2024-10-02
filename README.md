# API Automation with Postman

This repository contains API tests for the Simple Books API, implemented in Postman. It covers scenarios like client profile creation, book acquisition, and order management, using a Bearer Token for secure authentication.

Tests include dynamic pre-request scripts for automatic setup and assertions to validate response status, content, and reliability across various scenarios, including both positive and negative cases.

## How to Run
1. Clone the repository.
2. Open Postman and import the collection and environment files.
3. Select the correct environment.
4. Right-click the collection and select Run Collection.
5. Review the results in the Tests tab.

## Test Cases
1. **Access Token Tests**
   * **Create Access Token**: Tests generating a valid access token. Asserts the token is created successfully.

2. **Client Creation Tests**
   * **Create Client With Existing Email**: Tests attempting to create a client with an already registered email. Asserts an error message is displayed for duplicate email.

3. **Book Retrieval Tests**
   * **Get Books**: Tests retrieving the list of books. Asserts the list is returned successfully.
   * **Get Single Book**: Tests retrieving a specific book's details. Asserts the correct book details are returned.
   * **Get Non-Existent Book**: Tests retrieving details for a book that doesn't exist. Asserts an error message is returned.

4. **Order Creation Tests**
   * **Create Order With Unavailable Book**: Tests attempting to order an unavailable book. Asserts an error message is returned.
   * **Create Order With Available Book**: Tests ordering an available book. Asserts the order is created successfully.
   * **Create Order With Invalid Token**: Tests ordering a book using an invalid token. Asserts an authentication error message is returned.

5. **Order Modification Tests**
   * **Modify Order**: Tests modifying an existing order. Asserts the order is modified successfully.
   * **Modify Non-Existent Order**: Tests modifying an order that doesn’t exist. Asserts an error message is returned.

6. **Order Deletion Tests**
   * **Delete Existing Order**: Tests deleting an existing order. Asserts the order is deleted successfully.
   * **Delete Non-Existent Order**: Tests deleting an order that doesn’t exist. Asserts an error message is returned.

7. **Order Retrieval Tests**
   * **Get Orders**: Tests retrieving the list of orders. Asserts the list is returned successfully.
