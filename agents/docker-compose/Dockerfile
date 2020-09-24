FROM jetbrains/teamcity-agent

USER root

RUN echo "root:root" | chpasswd

# Install Python stuff
RUN apt-get update && apt-get install -y \
    docker-compose

USER buildagent