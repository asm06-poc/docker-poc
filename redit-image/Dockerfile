#user exiting image as base
FROM alpine

#download dependacy
RUN apk add --update redis
RUN apk add --update gcc

# instructions 
CMD ["redis-server"]