FROM docker:dind

# Install necessary packages
RUN apk add --no-cache bash git openssh-client curl sudo

# Install Docker Compose
RUN apk add --no-cache docker-compose

ENV SANDBOX_RUNTIME_CONTAINER_IMAGE=docker.all-hands.dev/all-hands-ai/runtime:0.13-nikolaik
ENV LOG_ALL_EVENTS=true

# Add any additional configurations or installations if needed
