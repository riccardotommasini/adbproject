# README

Advanced databse streaming and graph project


```./
- graph: contains the scafold for the graph project
- stream: contains the scafold for the stream project
```

Both the projects require to compare MySQL with a data systems for advanced querying, i.e., continuous queries or graph queries.

To run the various projects ```docker-compose up -d```
The instruction are then available in the related notebook.

Both the projects require to compare a specific query, you are not required to implmenet a generic query system


## Requirements

You **only need [Docker](https://www.docker.com/)** to run this assignment and Py </br>
You don't need Java, Scala, or an IDE.

### Setting Up the Environment 

1. Clone this repo 
  ```bash
  git clone https://github.com/semlanghi/sql-training
  ```
2. In the cloned repo, run `docker-compose`
- Linux & MacOS
  ```bash
  docker-compose up -d
  ```
- Windows
  ```bash
  set COMPOSE_CONVERT_WINDOWS_PATHS=1
  docker-compose up -d
  ```

## Streaming extra steps

### Requirements

3. Start the sql-client 
  ```bash
  docker-compose exec sql-client ./sql-client.sh
  ```
5. It may happen that the sql-client container stops abruptly. If that happens, stops the docker compose with `docker-compose down`, and reset it with `docker-compose up -d`, and then again `docker-compose exec sql-client ./sql-client.sh`
6. To finally stop the docker compose
  ```bash 
  docker-compose down
  ```


## CleanUp

  
6. To finally stop the docker compose
  ```bash 
  docker-compose down
  ```

