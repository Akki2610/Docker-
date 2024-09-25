# Docker-Cheat-Sheet
All the Most Essential Commands in One Place
Docker Architecture
Docker Commands Cheat Sheet
Build Commands
Clean Up Commands
Container Interaction Commands
Container Inspection Commands
Manage Images Commands
Run Commands
Registry Commands
Service Commands
Network Commands
Docker Architecture

Docker architecture consists of five main components: server, client, container, image, and registry.

**Docker Server**

A Docker server or Docker daemon is a program that runs in the background of your computer and manages Docker containers and images. When you use the Docker command line interface.

(CLI) to create, run, or manage containers, you interact with the Docker daemon.

The Docker daemon is an essential platform component that ensures containers can be started and stopped automatically when the system boots up.

**Docker Client**

The Docker client lets users interact with the Docker daemon with its command-line interface (CLI). In simple terms, it’s the main part of the Docker architecture for creating, managing, and running container applications.

When you use the Docker CLI to pass a command, the Docker client sends the command to the Docker daemon running on your computer, which then carries out the requested operation. The Docker client can be installed on any machine that needs to interact with the Docker daemon, including your local machine, a remote server, or a virtual server.

**Docker Container**

A Docker container is a package that contains all the required prerequisites to run an application.

Containers are designed to be highly portable, meaning that they can be easily moved from one environment to another, such as from a developer’s laptop to a testing environment or from a testing environment to a production environment.

**Docker Image**

A Docker image is a preconfigured template that specifies what should be included in a Docker container. Usually, images are downloaded from websites like Docker Hub. However, it’s also possible to create a custom image with the help of Dockerfile.

**Docker Registry**

The Docker registry is a central repository that stores and manages Docker images. It is a server-based system that lets users store and share Docker images with others, making it easy to distribute and deploy applications. The most notable Docker registry is Docker Hub.
