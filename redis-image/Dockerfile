#Use an existing docker image as Base Image
FROM alpine

#Download and install Dependencies
RUN apk add --update redis
RUN apk add --update gsoap

#Tell the imgae what to do when it starts as a container
CMD ["redis-server"]