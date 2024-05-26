# Use an official Node.js image as a base image
FROM mcr.microsoft.com/devcontainers/python:1-3.12-bullseye

# Set the working directory in the container
WORKDIR /workspaces/degrees-of-separation

RUN sudo apt-get update \
    && pip install check50 \
    && pip install style50

CMD ["bash"]
