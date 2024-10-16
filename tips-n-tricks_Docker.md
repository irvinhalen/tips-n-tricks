# 🍆 Tips 'n' Tricks 🎃

This one is for 🐳 *Docker*


## Getting Started

### Dockerfile

- Manually create "Dockerfile" files for each application (frontend and backend)


## Commands

### Frequently Used

- Build, Up & Down
    - Build the docker image using the docker compose.yaml file
    ```sh
    docker compose build
    ```
    - Build the docker image and run the container
    ```sh
    docker compose up --build
    ```
    - Runs the container
    ```sh
    docker compose up
    ```
    - Stops the container
    ```sh
    docker compose down
    ```

- Clean Up
    - Pruning specific parts of the system
    ```sh
    docker container prune
    docker image prune
    docker volume prune
    docker network prune
    ```
    - Pruning the whole system
    ```sh
    docker system prune --volumes
    ```

- Docker Desktop
    - Docker Desktop uses docker-compose instead of docker compose

- Others
    - Executing commands from service (for example you installed an npm package on the frontend then you need to use the command below to npm install)
    ```sh
    docker compose exec nameOfService command
    ```
