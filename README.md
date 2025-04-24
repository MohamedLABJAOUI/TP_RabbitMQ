# TP_RabbitMQ
microservices-based application, likely using Docker for containerization. It's split into multiple services with frontend and backend components.

# TP:
ADD Service RabbitMQ to the microservices-based application


🔧 Key Components
1. Dockerized Environment
docker-compose.yml: Defines and orchestrates multiple services.

.gitignore: Standard Git file to exclude certain files from version control.

2. Frontend
Located in: frontend/

Uses Vite (vite.config.js) — a fast frontend build tool.

Code written in React (App.jsx, main.jsx).

Dockerfile and nginx.conf suggest it's served via NGINX in a Docker container.

3. Backend Services
There are two microservices:

Orders Service (orders-service/)

Node.js-based (server.js, package.json)

Has its own Dockerfile

Products Service (products-service/)

Also Node.js-based

Independent server.js and Dockerfile

