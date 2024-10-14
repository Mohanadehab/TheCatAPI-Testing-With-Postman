
# TheCatAPI - Testing With Postman

## Overview
This project provides a comprehensive Postman collection for testing various API functionalities of TheCatAPI. It covers retrieving data, submitting votes, and uploading images, ensuring the API responses meet expected behavior.

## Project Structure
- **Postman Collection**: Contains all API requests categorized by the functionality being tested.
- **Postman Environment**: Allows running tests with environment-specific variables.

## Features
1. **GET /breeds**:
   - Retrieves the list of all cat breeds.
   - Validates the response status code and ensures the breed information is correct.

2. **GET /categories**:
   - Fetches all image categories.
   - Confirms the presence of specific categories and verifies the response structure.

3. **POST /votes**:
   - Submits a vote for a specific cat image.
   - Ensures the voting functionality works correctly by checking status codes and response bodies.

4. **POST /images/upload**:
   - Uploads a new cat image to the server.
   - Verifies the image upload process, response time, and correct storage of the image.

## Tools & Technologies
- **Postman**: API testing tool used to create and execute the test collection.
- **JavaScript**: Used for test scripts and assertions within Postman.
- **Newman** (optional): Command-line tool for running Postman collections (not the focus here).

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Mohanadehab/TheCatAPI-Testing-With-Postman.git
   ```
2. Open Postman and import the collection and environment files.
3. Run the collection in **Postman** by clicking on the "Run" button in the Collection Runner.
4. Review the test results within Postman to verify API functionality.

## Test Cases
Each endpoint has test cases validating:
- Status codes (e.g., 200 OK, 201 Created).
- Data correctness (e.g., breed names, vote submission confirmation).
- Response times to ensure performance metrics are met.

## Future Enhancements
- Expand test coverage for handling edge cases and error scenarios (e.g., invalid image upload, incorrect vote submission).
- Integration of the collection with CI/CD pipelines using **Newman** for automated test execution.
