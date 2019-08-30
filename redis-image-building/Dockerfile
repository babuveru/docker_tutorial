#Use an existing image as a base
FROM alpine

#download and install the dependency
RUN apk add --update redis

#Tell the image what to do when it starts as a container
CMD ["redis-server"]
