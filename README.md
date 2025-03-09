Docker Hello World

Overview

This project provides a simple Docker container that outputs Hello, World from Docker! when executed. It is designed as a lightweight example to demonstrate basic Docker functionality and containerization.

Project Structure

Dockerfile - Contains the instructions to build the Docker image.

hello-world.sh - A shell script that prints Hello, World from Docker!.

Requirements

Docker installed on your system (Download Docker).

Git installed for version control (Download Git).

How to Build and Run the Container

Step 1: Build the Docker Image

Run the following command in the terminal:

docker build -t my-hello-world .

Step 2: Run the Container

To execute the container and print the message, run:

docker run --rm my-hello-world

Uploading to GitHub

If you want to push your changes to GitHub, follow these steps:

Step 1: Initialize Git (if not already initialized)

git init

Step 2: Add and Commit Files

git add .
git commit -m "Initial commit - Docker Hello World"

Step 3: Connect to GitHub Repository

Replace YOUR_USERNAME with your GitHub username:

git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/DockerHelloWorld.git

Step 4: Push the Code to GitHub

git push -u origin main

Troubleshooting

Docker is Not Recognized

Ensure Docker is installed and running.

Restart your terminal or system after installation.

Run docker --version to check if Docker is properly installed.

Git is Not Recognized

Ensure Git is installed and added to your system's PATH.

Restart your terminal and try running git --version.

Permission Issues on Linux/Mac

If you encounter permission errors when running scripts, try:

chmod +x hello-world.sh

Push to GitHub Rejected

If you receive an error while pushing to GitHub, try pulling changes first:

git pull origin main --rebase
git push -u origin main

License

This project is released under the MIT License.

Contact

For questions or issues, open an issue on GitHub.
