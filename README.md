# Trello API Testing

Manual API testing project for the Trello REST API using Postman.

## Project Overview

The purpose of this project is to practice and demonstrate manual API testing using the Trello REST API.

The project contains a Postman collection with requests covering basic operations on Trello boards, lists, and cards.

## Tools

- Postman
- Trello REST API
- Git
- GitHub

## Tested Areas

The current collection covers:

- Board creation
- Board verification
- List creation
- List verification
- Card creation
- Card verification
- Archiving a list
- Verification of archived list
- Unarchiving a list
- Verification of unarchived list
- Board deletion
- Verification of deleted board

## Project Structure

```text
trello-api-testing/
├── .gitignore
├── README.md
└── postman/
    └── Trello API.postman_collection.json
```

## How to Use

1. Clone or download the repository.
2. Open Postman.
3. Import the collection from:
   `postman/Trello API.postman_collection.json`
4. Configure the required environment variables in Postman.
5. Run the requests individually or as a collection.

## Notes

The collection uses variables for API credentials and dynamic Trello resource IDs.

Sensitive credentials are not included in the repository.

## Current Status

This is an ongoing learning and portfolio project.

The project will be expanded with additional test scenarios, validations, negative testing, assertions, documentation, and test evidence.
