# Jenkins Server (light)

The aim of this project is to create a functioning and preconfigured jenkins server with a single worker.

## Technologies used

- Docker
- Docker-compose
- Jenkins
- Jenkins Configuration as Code

## How to start

This project requires that your machine has Docker-compose installed.

1. Clone this repository to your machine
2. Navigate to the project directory
3. Start with
  ```sh
  docker-compose up
  ```

## Created resources

- A docker container for the jenkins server
- Another docker container for the worker

## Characteristics

The server can be accessed on 'http://localhost:9001/'.

It comes with all the recommended plugins preinstalled, and the node 'worker-1' created (The worker comes pre-equipped with docker).   

## Addendum

If the jenkins node seems to be not connected, wait a little, it might just not finished setting up yet.
If it remains disconnected restart its docker container.
