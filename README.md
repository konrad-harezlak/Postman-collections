# README - Cat APIs Postman Collection
## Overview
This combined Postman collection, featuring both the "goalsApi" and "publicApi," provides a comprehensive set of API requests for testing the functionalities of a Goals API and a public Cat Image API. The collection includes requests for managing goals, fetching cat images, analyzing images, voting on images, and managing votes.

## Goals API - "goalsApi"
### What is Tested?

### Add Goal

- Request Method: POST
- Endpoint: http://localhost:8000/goals
- Testing Purpose: Validate the ability to add a new goal to the system.

### Get Goal

- Request Method: GET
- Endpoint: http://localhost:8000/goals/1
- Testing Purpose: Confirm the retrieval of goal information for a specific goal with ID 1.

### Delete Goal

- Request Method: DELETE
- Endpoint: http://localhost:8000/goals/1
- Testing Purpose: Ensure the successful deletion of the goal with ID 1.

### Get Updated Goal

- Request Method: GET
- Endpoint: http://localhost:8000/goals/2
- Testing Purpose: Confirm the update of the goal with ID 1 and validate the retrieval of the updated information for a specific goal with ID 2.

### Update Goal

- Request Method: PUT
- Endpoint: http://localhost:8000/goals/1
- Testing Purpose: Validate the ability to update the information for a specific goal with ID 1.

## Public Cat API - "publicApi"

### What is Tested?

### Get Images

- Request Method: GET
- Endpoint: https://api.thecatapi.com/v1/images/search
- Testing Purpose: Verify the ability to retrieve cat images from the public Cat API.

### Get Image

- Request Method: GET
- Endpoint: https://api.thecatapi.com/v1/images/MTk1NTE4Ng
- Testing Purpose: Confirm the retrieval of a specific cat image by its ID.

### Post Image Analysis

- Request Method: POST
- Endpoint: https://api.thecatapi.com/v1/images/MTk1NTE4Ng/analysis
- Testing Purpose: Validate the ability to perform image analysis on a specific cat image.

### Post Vote

- Request Method: POST
- Endpoint: https://api.thecatapi.com/v1/votes
- Testing Purpose: Confirm the ability to submit a vote for a specific cat image.

### Delete Vote

- Request Method: DELETE
- Endpoint: https://api.thecatapi.com/v1/vote/1132217
- Testing Purpose: Ensure the successful deletion of a vote with a specific ID.

## Why Choose the Cat API ("publicApi")?
The choice to use the "publicApi" (Cat Image API) for testing is motivated by the following factors:

Rich Cat Content: The Cat API provides a diverse collection of cat images, allowing for comprehensive testing of image-related functionalities.

Community Support: The Cat API is widely used and maintained by the community, ensuring reliability and continuous updates.

Ease of Integration: The Cat API offers a straightforward and well-documented interface, simplifying the integration process into testing scenarios.

Real-world Application: Cat images are a popular and enjoyable subject, making the "publicApi" suitable for testing scenarios that involve user engagement and visual content.
