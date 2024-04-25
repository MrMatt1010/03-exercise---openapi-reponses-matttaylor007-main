# 03 Exercise - OpenAPI Definition File - Responses

## Brief

Your team is about to start working on a Todo application. As part of the API design process, your Tech Lead has asked to you to describe the responses for all operations of the Todos API in the OpenAPI definition file.

See [OpenAPI 3.0 - Describing Responses](https://swagger.io/docs/specification/describing-responses/)

## Getting Started

1. Open a Terminal in VS Code for this project
2. Type `npm install` to install npm dependencies
3. `Type npm start` to start the Express Server
4. Open `http://localhost:5001/` in your browser to view the [Swagger UI](https://swagger.io/tools/swagger-ui/) generated API docs. (You need to restart the server after you update the `apispec.yaml` file.)

## Instructions

Update the `apispec.yaml` file to include the responses for all operations.

**Acceptance Criteria:**

- [ ] The `apispec.yaml` file includes a response body for each HTTP status code.
- [ ] The global [`components` object](https://github.com/OAI/OpenAPI-Specification/blob/main/versions/3.0.3.md#componentsObject) is used to define `schemas` for the Todo [object](https://swagger.io/docs/specification/data-models/data-types/#object).
- [ ] If multiple operations return the same response (status code and data), the global [`components` object](https://github.com/OAI/OpenAPI-Specification/blob/main/versions/3.0.3.md#componentsObject) is used to define `responses`.
- [ ] Commits are pushed to GitHub
- [ ] Exercise has been submitted in Google Classroom
