[![Docker Image CI](https://github.com/LoicSteve/hugging-face-docker/actions/workflows/docker-image.yml/badge.svg)](https://github.com/LoicSteve/hugging-face-docker/actions/workflows/docker-image.yml)

# MLOps packaging of HuggingFace to Docker Hub
Learn how to create a container and package it with GitHub Actions. This repository gives you a good starting point for a Dockerfile, GitHub Actions workflow, and Python code to package and push to Docker Hub

Depending on the type of model you need, you will need different workflow steps and most definitely a different `main.py` file. This example repository uses FastApi.
