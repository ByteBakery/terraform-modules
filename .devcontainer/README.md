# Terraform Dev Container

This repository provides a development container for working with Terraform. The dev container is configured to be used by multiple users without including personal credentials.

## Features

- **Base Image**: Ubuntu
- **Docker-in-Docker**: Enabled - This allows Docker to run inside the container, enabling the use of Docker commands and Docker-based tools within the dev container.
- **VS Code Extensions**:
  - HashiCorp Terraform
  - Azure Tools for VS Code

## Getting Started

### Prerequisites

- [Docker](https://www.docker.com/get-started) installed on your machine
- [Visual Studio Code](https://code.visualstudio.com/) installed
- [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension installed in VS Code

### Setup

1. Clone this repository:

    ```bash
    git clone https://github.com/your-repo/terraform-modules.git
    cd terraform-modules
    ```

2. Open the repository in Visual Studio Code.

3. When prompted, reopen the repository in the dev container.

### Post-Setup Instructions

After the dev container is created, you need to set up your own Git credentials:

1. Open a terminal in VS Code.
2. Set your Git credentials:

    ```bash
    git config --global user.name "Your Name"
    git config --global user.email "your.email@example.com"
    ```

### Using the Dev Container

The dev container includes the necessary tools and extensions for working with Terraform. You can start using Terraform commands directly in the terminal.

### Customizing the Dev Container

If you need to customize the dev container, you can modify the [devcontainer.json](http://_vscodecontentref_/1) file. For example, you can add more VS Code extensions or change the base image.

## Contributing

If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.