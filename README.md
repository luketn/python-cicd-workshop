# Introduction to CI/CD Workshop

This repo hosts the codebase and tutorial for an Introductory CI/CD Workshop. The workshop is designed to demonstrate and explain how to implement a CI/CD pipeline into a codebase.

## Tutorial

The tutorial can be found in the `tutorial/` directory of this repo. The [icd_101_guide.md](tutorial/cicd_101_guide.md) file hosts the tutorial content for the hands on portion of this tutorial.

### Published to Docker
I've forked this, hooked it up to my personal CircleCI and published to my personal DockerHub:
```
docker run -p=5000:5000 luketn/python-cicd-workshop:0.1.4
``` 