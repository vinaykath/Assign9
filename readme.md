# Assignment 9
# QR Code REST API Assignment

This repository contains a FastAPI project for creating, retrieving, and deleting QR codes. The purpose of this assignment is to get you accustomed to running the project, understanding the steps it uses to process requests, and fixing errors in the code.

### Installation Instructions
Follow these steps to set up the project on your local machine:

1. clone the Repository
    ```sh
    git clone git@github.com:vinaykath/Assign9.git
    ```
2. Create and Activate a Virtual Environment
    ```sh
    python3 -m venv venv
    source venv/bin/activate
    ```
3. Install Requirements
    ```sh
    pip install -r requirements.txt
    ```
4. Create the qr_codes Directory
    ```sh
    mkdir qr_codes
    ```
5. Run Tests Locally
    ```sh
    pytest
    ```
6. Start Docker

7. Start the App with Docker Compose
    ```sh
    docker-compose up --build
    ```
8. View OpenAPI Spec Documentation
    ```sh
    Go to http://localhost/docs to view the OpenAPI specification documentation.
    ```
9. Authorize Click "Authorize" and input the following credentials:
- Username: admin
- Password: secret

10. Test the Endpoints
- Use the OpenAPI spec page to test making, retrieving, and deleting QR codes.

## Fixes Made
The following issues were identified and fixed in the assignment repository:

### 1. Spelling mistakes:
- Corrected spelling mistakes in various parts of the code such as password, secret, token, and qr_code.

### 2. Endpoint Modifications:
- Modified the GET and POST methods for getting a list of QR codes and making a QR code to avoid errors.

