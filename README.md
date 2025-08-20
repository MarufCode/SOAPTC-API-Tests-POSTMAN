# SOAPTC API Tests (Postman)

This repository contains Postman collections for testing SOAPTC APIs.

## Repository Structure

- **postman/**  
  - **collections/** → Postman collection JSON files  
  - **environments/** → Postman environment files (optional)  

## Running Tests Locally

1. **Install Newman (Postman CLI runner)**
bash
npm install -g newman

2.Run the collection
newman run postman/collections/SOAP\ Testcases\ Collection.postman_collection.json

3.Run with an environment (optional)
newman run postman/collections/SOAP\ Testcases\ Collection.postman_collection.json \--environment postman/environments/dev.postman_environment.json


