# dakshBadhoniya-djangoApp

## Overview

Docker is used to package the Django application along with its dependencies into a single, portable container. This ensures that the app runs consistently across development, testing, and production environments.

Key benefits include:
- **Isolation:** The application runs in its own container, avoiding conflicts with other software.
- **Consistency:** Containers provide the same runtime environment on any host.
- **Portability:** Easily move and deploy containers across different systems.
- **Scalability:** Containers can be scaled horizontally to handle increased load.

## How It Works

- **Dockerfile:** Located in the `sampleProject1` folder, it sets up a Python 3.9-slim environment, installs required dependencies, and copies the project files.
- **Jenkinsfile:** Automates the CI/CD pipeline to checkout the code, build the Docker image, and push it to Docker Hub.
- **Running the App:** Once the Docker image is built, the container can be run to serve the Django application on the specified port.

## Contact

For questions or support, please contact:
- **Name:** Daksh Badhoniya
- **Email:** [dakshbadhoniya1@gmail.com](mailto:dakshbadhoniya1@gmail.com)
