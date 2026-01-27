Dockerized Node.js Application with Volumes, Bind Mounts & Docker Hub

📌 Project Objective

Understand Docker-based application containerization

Learn container lifecycle behavior

Implement persistent storage mechanisms in Docker

Practice image distribution using Docker Hub

🛠️ Technolog:

Node.js – application layer

Docker – containerization platform

Docker Hub – image repository

Linux – execution environment

🐳 Dockerfile Implementation Details

Base image selected from official Node.js images

Dedicated working directory created inside container

Application dependencies installed in isolated environment

Source code copied into container filesystem

Application port exposed for external access

Node.js application executed within container runtime

⚙️ Application Containerization

Node.js application executed inside a Docker container

Application runs independently of host system configuration

Same container image works across multiple environments

Ensures consistent runtime behavior

🔗 Docker Volume Mount – Persistent Storage

Docker volume attached to container data directory

Files and folders created inside container runtime

Container stopped and removed during testing

Volume retained data independently of container

Data verified after container recreation

Demonstrates production-style data persistence

🔗 Bind Mount – Host & Container Synchronization

Host system directory bind-mounted to container directory

Files created inside container reflected on host system

Changes on host immediately visible inside container

Enables real-time file synchronization

Useful for development and debugging workflows

☁️ Docker Hub Image Publishing

Docker image tagged using repository naming conventions

Image pushed to Docker Hub registry

Image pulled and reused on different systems

Eliminates need for rebuilding image on every environment

Improves application portability and reuse

🔄 End-to-End Workflow Covered

Application development

Container image creation

Storage configuration (volume & bind mount)

Container lifecycle validation

Image publishing and reuse

✅ Final Outcome

Node.js application successfully containerized

Persistent data storage implemented using Docker volumes

File sharing achieved using bind mounts

Image distributed using Docker Hub

Complete Docker workflow executed

🎯 Key Learnings & Skills Gained

Writing and understanding Dockerfiles

Managing container lifecycle

Difference between volumes and bind mounts

Data persistence strategies in Docker

Docker image tagging and publishing

Real-world DevOps container workflow

📌 Real-World Use Case

Local development environments

Cloud-based application deployment

DevOps CI/CD pipelines

Container-based application distribution
