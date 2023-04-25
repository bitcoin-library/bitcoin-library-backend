# Bitcoin Library Backend

This is a backend for the Bitcoin Library project.
For now it only consists of a simple Dockerfile setting up Meilisearch to provide search functionality to the frontend.

## Usage

Copy the env file and set the master key.

    cp .env.example .env


Start the container.

    docker-compose up -d


