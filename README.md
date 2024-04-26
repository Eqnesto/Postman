# Postman - API Automation

This repository contains a collection of API tests implemented in Postman using Simple Books API. It addresses multiple scenarios such as initiating client profiles, book acquisition, order management, amongst others.

It integrates a Bearer Token for authentication, ensuring each API request is securely authorized as it would be in a production environment. The test suite includes dynamic pre-request scripts that automatically set up necessary variables before each test, optimizing the configuration for accurate execution.

The test scripts in this collection are equipped with assertions that validate response status codes, content integrity, and other crucial metrics to confirm the API performs reliably under various scenarios. Additionally, the suite thoroughly tests both positive and negative scenarios to ensure a comprehensive coverage and robust error handling.

## How to Execute
1. **Get the Tools**: Clone this repository to get the Postman collection and environment files.
2. **Launch Postman**: Fire up Postman on your machine.
3. **Import with Ease**: Click the 'Import' button at the top left corner and select the downloaded files.
4. **Set the Environment**: Ensure the correct environment is selected for the collection.
5. **Run the Collection**: Right click on the collection folder and choose 'Run Collection' to watch the tests in action.
6. **Review Test Outcomes**: Postman will present the test results in the 'Tests' tab corresponding to each request.
