# Use a specific version of Jenkins
FROM jenkins/jenkins:lts

USER root

# Install Docker
RUN apt-get update && \
    apt-get install -y docker.io && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*

USER jenkins
