# JupyterLab with Docker

## Introduction
This is a simple guide to run JupyterLab with Docker. This guide is intended for those who are new to Docker and want to run JupyterLab with Docker.

## About JupyterLab
JupyterLab is a web-based interactive development environment for Jupyter notebooks, code, and data. JupyterLab is flexible: configure and arrange the user interface to support a wide range of workflows in data science, scientific computing, and machine learning. JupyterLab is extensible and modular: write plugins that add new components and integrate with existing ones.

## Installation
1. Install Docker Desktop from [Docker Hub](https://hub.docker.com/).
2. `py3/Dockerfile` is a Dockerfile to build an image with Python 3. Dockerfile is timezone settings and python packages installation. You can modify the Dockerfile to install additional packages. If you want to use different Python version, you can change the base image in the Dockerfile.
3. `docker-compose.yml` is a docker-compose file to run JupyterLab with Docker. You can modify the docker-compose file to change the port number and volume settings.