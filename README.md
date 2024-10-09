# TheCatAPI-Testing-With-Postman

This project is focused on testing The Cat API using Postman. It includes a comprehensive set of API tests that cover various functionalities provided by the API, such as fetching images, voting on images, adding favorites, and uploading images.

Table of Contents
Project Overview
Postman Collection
Environment Setup
Run Results
Installation
Usage
Technologies Used
Project Overview
This project tests key features of The Cat API using Postman. It covers:

Fetching random images of cats.
Searching for cat breeds.
Voting on your favorite cat images.
Uploading images to The Cat API.
Managing favorite cat images.
Deleting images.
Each API call includes assertions on the response status, body structure, and content to ensure that the endpoints are working correctly.

Postman Collection
The Postman collection used for this project includes requests that hit the following endpoints:

/images/search – Fetches a random cat image.
/images/:image_id – Fetches details for a specific cat image.
/favourites – Manages your favorite cat images.
/votes – Votes on images.
/breeds/search – Searches for cat breeds.
Postman scripts are used to verify the responses, including:

Validating response times.
Ensuring correct HTTP status codes.
Verifying the content of responses, such as image properties or breed data.
Environment Setup
The project uses a Postman environment file to handle variables like API keys and endpoints:

API Key: Required to access all features of The Cat API.
Endpoint: https://api.thecatapi.com/
Other environment variables include image_id, fav_Id, and vote_Id for dynamic requests​(TEST_ENV.postman_enviro…)​(Mohanad's API testing p…).
Run Results
The tests run successfully with:

Total Tests: 98
Passed Tests: 98
Failed Tests: 0
The run results show that all API tests, including performance tests (e.g., response time < 1500ms), validation of response structures, and functional checks like voting and uploading images, passed​(Mohanad's API testing p…).

Installation
Clone this repository or download the files.
Import the Postman collection and environment:
Collection: Mohanad's API testing project.postman_collection.json
Environment: TEST_ENV.postman_environment.json
Ensure you have a valid API key for The Cat API by signing up at The Cat API.
Usage
Open Postman and import the collection and environment.
Set your API key in the environment file.
Run the collection to execute all API requests and view test results.
Technologies Used
Postman: For API testing and collection management.
The Cat API: API for fetching, uploading, voting on, and favoriting cat images.
JavaScript: For scripting within Postman to validate API responses.
