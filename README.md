# Flask Docker Compose Example

This repository provides an example of how to build and deploy a Flask application using Docker Compose. It demonstrates the process of containerizing a Flask app and orchestrating multiple services with Docker Compose.

## Prerequisites

Make sure you have the following prerequisites installed on your machine:

- Docker: [Install Docker](https://docs.docker.com/get-docker/)
- Docker Compose: [Install Docker Compose](https://docs.docker.com/compose/install/)
- Git: [Install Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

## Getting Started

Follow the steps below to run the Flask application using Docker Compose:

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your-username/flask-docker-compose-example.git
    ```

2. Navigate to the project directory:

    ```bash
    cd flask-docker-compose-example
    ```

3. Build and run the Docker containers:

    ```bash
    docker-compose up
    ```

4. Access the Flask application in your web browser:

    ```
    http://localhost:5000
    ```

5. To stop the containers, press `Ctrl + C` in the terminal where Docker Compose is running.

## Project Structure

The project has the following structure:


- `app.py`: Contains the code for the Flask application.
- `docker-compose.yaml`: Specifies the services and their configurations for Docker Compose.
- `Dockerfile`: Specifies the instructions to build the Docker image for the Flask app.
- `requirements.txt`: Lists the Python packages required by the application.

## Contributing

Contributions are welcome! If you have any ideas or improvements, please submit a pull request. For major changes, please open an issue to discuss what you would like to change.

## License

This project is licensed under the [MIT License](LICENSE).
