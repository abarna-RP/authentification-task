# Bearer Token Authentication and Authorization

This is a Node.js application implementing user authentication and authorization using Bearer tokens, following the MVC pattern.

## Tech Stack

-   Node.js
-   Express.js
-   Mongoose (MongoDB)
-   JWT



## API Endpoints

### Register User

-   **Endpoint:** `POST..api /user/register`
-   **Request Body:**

    ```json
    {
      "username": "subasri"

      "email": "suba@gmail.com",
      "password": "suba12!"
    }
    ```

-   **Response:**

    ```json
    {
      "message": "User registered successfully."
    }
    ```

### Login User

-   **Endpoint:** `POST..api /user/login`
-   **Request Body:**

    ```json
    {
      "username": "suba@gmail.com",
      "password": "suba12!"
    }
    ```

-   **Response:**

    ```json
    {
      "token": secret
    }
    ```

### Get User Info

-   **Endpoint:** `api /user/getuser`
-   **Headers:** Authorization: Bearer.
-   `
-   **Response:**

    json
    {
      "user": {
        "username": "subasri",
        "email": "suba@gmail.com",
        "_id": "67d8ffd192967a535a07bcfa"
      }
    }
    
    ![alt image](https://github.com/abarna-RP/authentification-task/blob/main/authentification%20task.png)
