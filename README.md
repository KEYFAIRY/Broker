# BROKER

This repository contains the necessary configuration to set up **Apache Kafka** (with Zookeeper) using Docker Compose.

## Requirements

* [Docker Desktop](https://www.docker.com/products/docker-desktop/) (Windows/Mac) or Docker Engine (Linux).
* `.env` file with environment variables.

## Project structure

```bash
├── 📁 BROKER/
│   └── docker-compose.yml # Docker Compose file to run Kafka and Zookeeper
```

## Steps to run the project

### Create .env file:

Rename .example.env file to .env and set your real variables

### Run the container for the broker

```bash
docker compose up --build -d
```

### Check running containers in Docker Desktop / Docker Engine

```bash
docker ps
```

### Stop the container

```bash
docker compose down
```