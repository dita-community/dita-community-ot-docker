# dita-community-ot-docker

Configuration files for Docker containers for DITA Community-specific Open Toolkit

This project provides Docker configuration files (Dockerfile) for Docker containers
that provide DITA Open Toolkit images configured with DITA Community Open Toolkit
plugins. These Docker files extend the base ditaot/dita-ot-base Docker image.

The dita-ot-base container provides an extendable container that can be used to
create additional containers with additional plugins or other resources added.

The dita-ot container is a working container that provides the volumes needed
by other containers to work with the Open Toolkit or use the container with
files on the host machine.
