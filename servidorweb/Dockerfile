FROM nginx:latest

RUN apt update && apt install -y \
    iputils-ping \
    net-tools \
    nano \
    curl

CMD ["nginx", "-g", "daemon off;"]

