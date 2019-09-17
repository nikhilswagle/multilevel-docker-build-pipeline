# multilevel-docker-build-pipeline
Builds cascaded docker image and pushes it to ECR.

Pipeline builds Jupiter Hub docker image and pushes it to ECR. This image is then used as the base image for a Python app to be deployed on Jupiter Hub.
