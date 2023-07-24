# Steps to create a Redis cluster using Docker and connect to it using Redis Insights:

```sh
# Create a Docker network for the Redis cluster
$ docker network create redis-cluster


# Build the Docker image & Run the Docker Compose file
$ docker build -t my-redis .
$ docker-compose up -d

# Finally, Connect to Redis Insights by visiting http://localhost:8001 in your web browser.
```
