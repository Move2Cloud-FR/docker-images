FROM node:22-slim

# Update OS packages to address reported vulnerabilities, then clean up
RUN apt-get update \
	&& apt-get upgrade -y \
	&& apt-get install --no-install-recommends -y ca-certificates \
	&& rm -rf /var/lib/apt/lists/*
