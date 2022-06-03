FROM ubuntu:20.04
RUN apt update
RUN apt upgrade -y
RUN apt -y install software-properties-common
ARG DEBIAN_FRONTEND=noninteractive
RUN add-apt-repository ppa:ondrej/php
RUN apt-get update
RUN apt -y install php7.4
RUN apt-get install -y php7.4-cli php7.4-json php7.4-common php7.4-sqlite3 php7.4-zip php7.4-gd php7.4-mbstring php7.4-curl php7.4-xml php7.4-bcmath