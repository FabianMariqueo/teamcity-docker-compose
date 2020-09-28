FROM jetbrains/teamcity-minimal-agent

USER root

# Install Python stuff
RUN apt-get update && apt-get install -y \
    docker-compose \
    maven


##USER buildagent