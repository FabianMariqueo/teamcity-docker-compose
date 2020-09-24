FROM jetbrains/teamcity-agent:latest

USER root

ENV DEBIAN_FRONTEND noninteractive
ENV DEBCONF_NONINTERACTIVE_SEEN true

# Install Python stuff
RUN apt-get update && apt-get install -y \
    docker-compose
