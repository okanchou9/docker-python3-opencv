Docker image with python 3.9 and opencv 4.5.5

Usage:

    git clone
    cd 
    docker build -t $DOCKER_NAME . --no-cache
    docker run -it -d -v $SHARED_FOLDER:/opt/build opencv455
    docker exec -it $CONTAINER_ID bash
