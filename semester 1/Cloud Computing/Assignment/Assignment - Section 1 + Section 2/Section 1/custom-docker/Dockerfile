# First Layer - from which Docker Image to start with
FROM ubuntu:latest
# Run indicates execute the commands inside the container
RUN mkdir /vim
RUN apt update
# -y is used to avoid prompt to install or not
RUN apt install vim -y
# WORKDIR informs which container working directory
WORKDIR /vim
# Which command to run in container - any executable as start point
ENTRYPOINT ["/bin/bash"]