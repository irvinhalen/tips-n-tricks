# 🍆 Tips & Tricks 🎃

> This one is for 🐳 *Docker*


## Getting Started

### Dockerfile

- Manually create Dockerfiles with the filename "Dockerfile" for each application (frontend and backend)


## Commands

### Frequently Used

- Build, Up & Down
    - Build the docker image using the docker compose.yaml file
    ```
    docker compose build
    ```
    - Build the docker image and run the container
    ```
    docker compose up --build
    ```
    - Runs the container
    ```
    docker compose up
    ```
    - Stops the container
    ```
    docker compose down
    ```

- Clean Up
    - Pruning specific parts of the system
    ```
    docker container prune
    docker image prune
    docker volume prune
    docker network prune
    ```
    - Pruning the whole system
    ```
    docker system prune --volumes
    ```

- Others
    - Executing commands from service (for example you installed an npm package on the frontend then you need to use the command below to npm install)
    ```
    docker compose exec nameOfService command
    ```
