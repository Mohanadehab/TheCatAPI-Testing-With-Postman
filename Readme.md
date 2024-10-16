
# TheCatAPI - Testing With Postman

## Overview
This project provides a comprehensive Postman collection for testing various API functionalities of TheCatAPI. It covers retrieving data, submitting votes, and uploading images, ensuring the API responses meet expected behavior.

## Project Structure
- **Postman Collection**: Contains all API requests categorized by the functionality being tested.
- **Postman Environment**: Allows running tests with environment-specific variables.

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
