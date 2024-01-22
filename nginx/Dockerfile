FROM nginx:latest

WORKDIR /app

RUN apt-get update
RUN apt-get install vim -y

ENTRYPOINT ["/docker-entrypoint.sh"]
CMD ["nginx", "-g", "daemon off;"]