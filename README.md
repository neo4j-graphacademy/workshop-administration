# Neo4j GraphAcademy Administration Workshop

This repository accompanies the [GraphAcademy Neo4j Administration Workshop](https://graphacademy.neo4j.com/courses/workshop-administration).

The repository includes docker configuration and related files required to complete the workshop.

## Requirements

- [Git](https://git-scm.com/downloads)
- [Docker Desktop](https://www.docker.com/products/docker-desktop/)

## Instructions

Before the workshop you should test that you can access the repository.

### Get the repository

Clone the repository:

```bash
git clone https://github.com/neo4j-graphacademy/workshop-administration
```

Open the directory

```bash
cd workshop-adminstration
```

### Start the Neo4j container

```bash
docker compose up -d
```

### Access the container

Open a terminal to the container:

```bash
docker exec -it neo4j-training bash
```

Exit the terminal:

```bash
exit
```

### Access Neo4j Browser

Open [http://localhost:7474](http://localhost:7474) and log in with:

- **Username:** `neo4j`
- **Password:** `neo4jpassword`

### Stop the container

```bash
docker compose down
```


