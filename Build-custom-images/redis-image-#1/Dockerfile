# Base image
FROM alpine

# Download and install dependecies

RUN apk add --update redis

# Tell the images what to do when it starts as a container
CMD [ "redis-server" ]