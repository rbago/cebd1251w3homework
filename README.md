# CEBD 1251 week 3 homework

## Exercise 1
Completed steps:
1. Cloned git repository
2. build docker image
3. run docker through port 8080 using the image ID
4. play solitaire until all cards are stored away

## Exercise 2.1
https://hub.docker.com/repository/docker/rafaelbago/w3exercise2hw

Run the following command line:
`docker run -d -p 8000:8000 rafaelbago/w3exercise2hw`

### Exercise 2.2
#### Understanding cache in Docker
When a Docker image is being built each command is stored in the cache, allowing for speedier builds whenever a new build is process.

One important note about using cache in Docker, when adding a new command within the dockerfile, what follows from the line the cache will no longer be used. Meaning that anything after the new line, even though previously built, it will build and store a new cache layer.

## Exercise 3
See this repository for updloaded files

## Exercise 4
https://hub.docker.com/repository/docker/rafaelbago/w3exercise4hw

Run the following command line:
`docker run -d -p 8000:8000 -e NAME="INSERT_NAME" rafaelbago/w3exercise4hw`
