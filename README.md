# Docker Camera Project

This repository is an exploration of using Docker to run a Python application that captures video from a camera using OpenCV.

## Project Structure

- `camera.py`: A simple Python script that captures video from the default camera and displays it in a window.
- `Dockerfile`: Defines the Docker image, including the necessary system dependencies and Python packages.
- `docker-compose.yaml`: Configuration for Docker Compose to run the application with the necessary permissions and environment settings.
- `pyproject.toml`: Project metadata and dependencies.
- `requirements.txt`: List of Python dependencies, generated from `pyproject.toml`.
- `.gitignore`: Specifies files and directories to be ignored by Git.
- `.python-version`: Specifies the Python version to be used.
- `uv.lock`: Lock file for dependencies.

## Getting Started

### Prerequisites

- Docker
- Docker Compose

### Running the Application

1. Build the Docker image:
    ```sh
    docker-compose build
    ```

2. Run the application:
    ```sh
    docker-compose up
    ```

3. The application will start capturing video from the default camera and display it in a window. Press `q` to quit the application.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [OpenCV](https://opencv.org/) for the computer vision library.
- [Docker](https://www.docker.com/) for containerization.
