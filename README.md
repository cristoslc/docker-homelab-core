# Docker Project

This project is designed to create a unified development and deployment environment specifically tailored for homelab setups. The core components are included in this repository, and additional components can be added as needed.

CORE services include:
 - nginx reverse proxy (TBD: swag / ngnix-proxy-manager)
 - portainer
 - guacamole
 - speedtest-tracker
 - autoheal
 - watchtower

## Project Standards
By adhering to the guidelines and standards detailed below, we can ensure an efficient and cooperative development process tailored to our homelab needs.

- **Utility Scripts**: All utility scripts utilized within this project should be written in Python. This is to ensure consistency and maintainability across our codebase. Please ensure that your Python scripts are compatible with Python 3.6 and above, properly documented, and include necessary requirements files if third-party libraries are used.

- **Code Style**: For Python scripts, adhere to [PEP 8](https://www.python.org/dev/peps/pep-0008/) style guidelines. Ensure your code is clean, well-commented, and follows the best practices.

- **Docker Practices**: Make use of multi-stage builds to minimize the size of your Docker images. Always tag your Docker images appropriately and strive for immutability. Use environment variables for configuration to ensure your Docker containers are environment agnostic.

- **Version Control**: We use Git for version control. Commit messages should be clear and follow best practices. Feature branches should be used for development and merged into the main branch through pull requests.

- **Documentation**: All components of the project should be properly documented. This includes Dockerfiles, Python scripts, and any other significant pieces of the project. Documentation should be clear, concise, and helpful to new team members.

## Getting Started

To get started with the project, ensure you have Docker and Python installed on your system. Clone the repository to your local machine and follow the setup instructions in the `SETUP.md` file.

## Contribution

We welcome contributions! Please read through the `CONTRIBUTING.md` document for guidelines on how to submit contributions to this project.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

Thank you for being part of our project. Happy coding!
