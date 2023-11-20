# flask-hello-world-application

This project is a simple Flask application that serves one route `/api/v1/hello-world-21` which returns a greeting "Hello World 21" with an HTTP status code of 200. It is meant as a basic demonstration of creating a web service with Flask.

## What is this project about?

This project is about setting up a basic Flask application. It is an example of how to create a web service that responds to HTTP requests and can be used as a starting point for more complex Flask applications.

## How to run this project on your machine?

To run this project, follow these steps:

1. Ensure you have Python 3.10 and `pipenv` installed on your system.
2. Clone the repository to your local machine.
3. Navigate to the cloned directory.
4. Set up a virtual environment with `pipenv`:
    ```bash
    pipenv --python 3.10
    ```
5. Install the project dependencies with `pipenv`:
    ```bash
    pipenv install
    ```
6. Activate the virtual environment:
    ```bash
    pipenv shell
    ```
7. Run the Flask application:
    ```bash
    flask run
    ```
8. Access the application in your web browser or using a tool like `curl` at:
    ```
    http://127.0.0.1:5000/api/v1/hello-world-21
    ```

## Examples of project work

When you run the Flask application and navigate to `http://127.0.0.1:5000/api/v1/hello-world-21`, you should see a page that displays the text "Hello World 21".
