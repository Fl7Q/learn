FROM nginx
RUN apt-get update && apt-get install -y nano
EXPOSE 80
ENTRYPOINT ["nginx", "-g", "daemon off;"]
