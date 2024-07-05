# Postman API Tests

![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white)
![Trello](https://img.shields.io/badge/Trello-%23026AA7.svg?style=for-the-badge&logo=Trello&logoColor=white)

## This is a test project for **Back-End Test Automation** March 2024 Course @ SoftUni

---

### Overview

This repository contains Postman collections and reports generated by Newman for the Postman collections. These reports provide detailed information about the test runs and can be useful for debugging and analysis.

### Prerequisites

- [Postman](https://www.postman.com/downloads/)
- [Newman](https://learning.postman.com/docs/collections/using-newman-cli/installing-running-newman/)
- [Trello](https://api.trello.com)

### Installation and Usage

#### Postman

Postman is a popular tool used to test APIs by making HTTP requests to various endpoints. To use Postman:

1. Download and install Postman from the [official website](https://www.postman.com/downloads/).
2. Open Postman and create a new request by selecting the HTTP method and entering the endpoint URL.
3. Add necessary headers, parameters, and body data.
4. Click on the "Send" button to make the request and view the response.

You can also import the provided Postman collections in this repository by selecting `Import` in Postman and uploading the collection file.

#### Newman

Newman is a command-line collection runner for Postman. It allows you to run and test Postman collections directly from the command line. To install and use Newman:

1. Install Node.js from the [official website](https://nodejs.org/).
2. Install Newman using npm:

   ```sh
   npm install -g newman
   ```
3. Run a Postman collection using Newman:

   ```sh
   newman run path/to/your/collection.json
   ```

- You can also generate HTML reports:

  ```sh
  newman run path/to/your/collection.json -r htmlextra
  ```

  
