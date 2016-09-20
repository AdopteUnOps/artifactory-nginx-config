# artifactory-nginx-config

This container is inspired by other rancher images. It's a confd based container that will create nginx reverse proxy for artifactory configuration file.
This container is already configured (in the base image) to connect to the rancher api to get the metadata and do the templating of configuration file.
