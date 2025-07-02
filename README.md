# networks-starting-setup

A simple Dockerized Node.js project designed to demonstrate basic container networking using Docker Compose. This setup is ideal for beginners exploring how services communicate within Docker containers.

## 📂 Project Structure

networks-starting-setup/
├── Dockerfile # Defines container image for the Node.js server
├── docker-compose.yml # Orchestrates container networking and services
├── package.json # Lists dependencies for the Express server
├── server.js # Basic Express server listening on port 80
└── README.md # Project documentation


## 🚀 Getting Started

### Prerequisites

- [Docker](https://www.docker.com/products/docker-desktop)  
- [Docker Compose](https://docs.docker.com/compose/)  
- [Node.js](https://nodejs.org/) (optional, for local testing)

### Steps

```bash
# 1. Clone the Repository
git clone https://github.com/ajitheaswari/networks-starting-setup.git
cd networks-starting-setup

# 2. Build and Run the Containers
docker-compose up --build

# 3. Access the App
# Open your browser and go to:
http://localhost

curl http://localhost
# Output:
Hello from inside the Docker container!


 Now everything is together in one cohesive markdown file — no breaks, no fragmentation. Just save this as your `README.md`. Let me know if you'd like to include Docker logs, environment variables, or CI setup next!
