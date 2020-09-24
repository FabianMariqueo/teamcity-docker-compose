FROM jetbrains/teamcity-agent

USER root

ENV SERVER_URL=http://server:8111

# Install Python stuff
RUN apt-get update && apt-get install -y \
    docker-compose
