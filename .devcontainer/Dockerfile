FROM docker:dind

# Install necessary packages
RUN apk add --no-cache bash git openssh-client

# Install Docker Compose
RUN apk add --no-cache docker-compose

# Install any other tools you might need

ENV SANDBOX_RUNTIME_CONTAINER_IMAGE=docker.all-hands.dev/all-hands-ai/runtime:0.13-nikolaik
ENV LOG_ALL_EVENTS=true

# Add any additional configurations or installations if needed
